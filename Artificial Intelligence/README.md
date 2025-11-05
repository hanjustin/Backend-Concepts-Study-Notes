
# Study Goal

Improve technology literacy by reading AI fundamentals.

# Table of Contents

<ul>
        <li><b>Artificial Intelligence</b></li>
        <ul>
            <li><details><summary>Fundamentals</summary>
                <ul>
                    <li><b>Concepts</b></li>
                        <ul><ul><ul><ul>
                            <li><a href="#">Concept1</a></li>
                        </ul></ul></ul></ul>
                    <li><a href="#"><b>Terminologies</b></a></li>
                        <ul><ul><ul><ul>
                            <li>
                                <b><ins>T</ins></b>erm1,
                                <b><ins>T</ins></b>erm2,
                            </li>
                        </ul></ul></ul></ul>
                </ul>
            </details>
            </li>
        </ul>
    <li><b>Machine Learning</b></li>
        <ul>
            <li><details><summary>Fundamentals</summary>
                <ul>
                    <li><b>Concepts</b></li>
                        <ul>
                            <li><a href="#"><b>Learning Approaches</b></a></li>
                                    <ul><ul><ul>
                                        <li>
                                            <b><ins>S</ins></b>upervised,
                                            <b><ins>U</ins></b>n-supervised,
                                            <b><ins>S</ins></b>emi-supervised,
                                            <b><ins>R</ins></b>einforcement
                                        </li>
                                    </ul></ul></ul>
                            <li><a href="#"><b>Deployment Models</b></a></li>
                                    <ul><ul><ul>
                                        <li>
                                            <b><ins>P</ins></b>rivate,
                                            <b><ins>P</ins></b>ublic,
                                            <b><ins>H</ins></b>ybrid,
                                            <b><ins>M</ins></b>ulticloud
                                        </li>
                                    </ul></ul></ul>
                        </ul>
                    <li><a href="#"><b>Terminologies</b></a></li>
                        <ul><ul><ul><ul>
                            <li>
                                <b><ins>T</ins></b>erm1,
                                <b><ins>T</ins></b>erm2,
                            </li>
                        </ul></ul></ul></ul>
                </ul>
            </details>
            </li>
            <li><details><summary>MLOps</summary>
                <ul>
                    <li><a href="#"><b>Fundamentals</b></a></li>
                        <ul>
                            <li><b>Concepts</b></li>
                                <ul><ul><ul><ul>
                                    <li><a href="#">Concept1</a></li>
                                </ul></ul></ul></ul>
                            <li><a href="#"><b>Terminologies</b></a></li>
                                <ul><ul><ul><ul>
                                    <li>
                                        <b><ins>T</ins></b>erm1,
                                        <b><ins>T</ins></b>erm2,
                                    </li>
                                </ul></ul></ul></ul>
                        </ul>
                </ul>
            </details>
            </li>
        </ul>
</ul>

---

# Artificial Intelligence

An umbrella term encompassing a broad range of technologies that mimic human intelligence. Enabling a machine or system to sense, reason, act, or adapt like a human.

# Machine Learning

* **Definition** <br> Formally, a subset of AI that automatically uses statistical algorithms to analyze large amounts of data, learn from the insights, and then make informed decisions. Enables a machine or system to learn and improve from experience. The terms AI & ML are used interchangeably.
* **Process** <br> Training a piece of software, called a model, to make useful predictions from data. Primarily based on mathematics and statistics for establishing or discovering patterns.

## Fundamentals
### Concepts
#### Learning Approaches
##### Unsupervised Learning
Using unlabeled raw data to create models. Patterns (similarities, differences) or relationships are infered without any explicit guidance or instruction.

* **Clustering:** Group similar data points together.
* **Anomaly Detection:** Find unusual data points.
* **Dimensionality Reduction:** Compress data using fewer numbers.



###### Use case
Useful for identifying previously undetected patterns in data and can help identify features useful for categorizing data
While the algorithm itself does not understand these patterns based on any previous information you provided, you can then go through the data groupings and attempt to classify them based on your understanding of the dataset.


##### Supervised Learning

Using labeled data to create models. The label is the "answer," or the value we want the model to predict. After seeing lots of data with the correct answers, models create patterns to make predictions.
* `cat` or `dog` labeled to images. Identify new photos with the correct animal.
* The sale price added to used cars. Assign accurate prices to other used cars.

* **Regression:** Predicting a number. Infinitely many possible outputs.
* **Classification:** Predict categories. Small number of outputs.


##### Semi-supervised Learning

##### Reinforcement Learning
The model receives rewards or penalties based on actions. The algorithm modifies its strategy in order to achieve the highest reward.



#### Loss/Error/Cost Functions
Describes how wrong a model's predictions are. Measures the distance between the model's predictions and the actual labels. Focuses on the distance between the values by using the absolute value or square of the distance. The goal of training a model is to minimize the loss.

* **MSE (Mean squared error):** The model is closer to the outliers but further away from most of the other data points. `Sum(Distance^2) / N`

* **MAE (Mean absolute error):** The model is further away from the outliers but closer to most of the other data points. `Sum(Abs(Distance)) / N`

#### Gradient Descent
An iterative mathematical process that finds the weights and bias that produce the model with the lowest loss.

* **Repeat the following steps until the loss can't be reduced any further.**
    * Calculate the loss with the current weight and bias.
    * Determine the direction to move the weights and bias that reduce loss.
    * Move the weight and bias values a small amount (`gradient`*`learning rate`) in the direction that reduces loss. The learning rate determines the magnitude of the change.

#### Learning Rate
Number that influences how quickly the model converges. If too low, take a long time to converge. If too high, the model never converges, but instead bounces around the weights and bias that minimize the loss. The goal is to pick a learning rate that's not too high nor too low so that the model converges quickly.

### Terminologies
* **Parameter:** The weights and biases that a model learns during training.
* **Hyperparameters:** The values that you adjust during successive runs of training a model.
* **Convergence:** A state reached when additional training won't improve the model as loss values change very little or not at all.

## Algorithms
### Linear Regression
Using a line to summarize the relationship in the data. Just like a linear algebraic equation, a linear regression model equation is:
`y' = b + wx`
* `b`: The bias of the model. Same concept as the y-intercept for a line.
* `w`: The weight of the feature. Same concept as the slope for a line.

### Logistic Regression
Used for binary classification tasks, such as identifying whether spam or not spam.

* **Sigmoid/logistic function:** S-shaped curve function that is used to calculate a probability between 0 and 1.
* **Log loss cost function:** Used to penalize confident wrong predictions more and to ensure a convex cost function to guarantee a global minimum for optimization with gradient descent.

* Core concepts to study
    * Regularization
    * Train, Test, Validation set
    * Labels, Weights (Parameters), Hyperparameters
    * Validation and Cross Validation
    * Overfitting and Underfitting
    * IMPORTANT: bias and variance and the bias-variance tradeoff

## Problem Framing
Determine if ML is a good approach for a problem.

## To be organized
* **Underfitting:** High bias. Doesn't fit the training set well.
* **Overfitting:** High variance. Fits the training set TOO well, so the cost function is close to zero, and the model will not generalize to new examples well.
    * **Addressing overfitting:**
        * Collecting more training examples.
        * Feature selection. Include/exclude features.
        * Regularization. Reducing the size of parameters to reduce the effect. Regularization steps:
            * Modify the cost function by adding a regularization term, which significantly increases the cost when a parameter's value is high.
            * Regulariazation paremeter: Used to control the balance of fitting to the data and keeping the parameters small. Underfitting will happen for a large value and overfitting will happen for a small value.

## MLOps
DevOps for ML models.

### Steps
1. **Decision Process:** Estimating a pattern for given input data.
2. **Error Function:** Evaluates the prediction of the model. Assessing the accuracy of the model by comparing to known examples (if available).
3. **Model Optimization Process:** Iteratively improve the accuracy of a machine learning model by minimizing its loss function.

# Neural Network
* Subfield of ML.

* **Neuron:** The most fundamental unit of processing that receives inputs and generates an output.
* **Hidden (Activation) layers:** Layers between input layer & output layer. Created from feature engineering automation. Neurons per layer & the number of hidden layers need to be decided when building a neural network.
* **Forward propagation:** Activation of layers from left to right.

## Tensorflow Code snippet

* Simple neural network example

```python
x = np.array([[200.0, 17.0]])  # Input array
layer_1 = Dense(units=3, activation='sigmoid')  # Hidden layer
a1 = layer_1(x)   # Output of layer1

layer_2 = Dense(units=1, activation='sigmoid')  # Output layer
a2 = layer_2(a1)

layer_1 = Dense(units=3, activation='sigmoid')
layer_2 = Dense(units=1, activation='sigmoid')
model = Sequential([layer_1, layer_2])

# Train the model
model.compile(...)
model.fit(input_data, targets)

# Use the model
model.predict(new_input_data)
```


# Deep Learning
* Scalable version of ML. Subfield of neural networks that eliminates some of the human intervention of supervised learning by automatically determining the set of features to categorize unstructured data.

# Generative AI
* Subfield of Deep Learning for generating new contents; often natural language dialogs, but also images, video, code, and other formats.
* The ability to generate content is based on a language model. There are large language models (LLMs) and small language models (SLMs) - the difference is based on the volume of data and the number of variables in the model. LLMs are very powerful and generalize well, but can be more costly to train and use. SLMs tend to work well when focused on specific topic areas, and usually cost less.
* The models "know" how words relate to one another as semantic relationships between language elements are encapsulated. This enables them to generate a meaningful sequence of text.

# Speech
* **Speech recognition** Speech-to-text. "Hear" and interpret speech by transcribing speech audio signal into text.
* **Speech synthesis:** Text-to-speech. Information in text format is converted into an audible signal to vocalize words as spoken language.

# Computer Vision

* **Image classification:** Identifying the subject of the image.
* **Object detection:** Trained to identify the location of specific objects in an image.
* **Semantic segmentation:** Advanced object detection where individual pixels in the image that belong to a particular object are identified.

# NLP

# Statistics

# Terminologies
* **Standard Deviation:** Measure of how spreadout numbers are / how far typical data points are from the average. Square root of variance, which is the average of the squared differences between each data point and the mean.
* **Z-score:** How many standard deviations away from the mean.
* **Residual:** Synonymous to the loss value in ML. `Actual - Model Expected`. Residual plots help to determine whether a linear model is appropriate in modeling the given data. There should not be a visible pattern of residual plots.
* **Correlation coefficient (r):** Measure of the strength of a linear relationship between two variables. Between `-1` and `1`. The closer `r` is to zero, the weaker the linear relationship.
* **Coefficient of determination (R-squared):** Measure of how well a statistical model predicts an outcome. Shows how much of the change in one thing can be explained by changes in another. How much of the change in the outcome (dependent variable) can be explained by the things we’re using to predict it (independent variable(s)). Between `0` and `1`. Closer to 1 mean a better fit.

* Core concepts to study
    * Probability Distributions
    * Different types of Plots
    * Populations and Samples & Law of Large Numbers
    * Expected Values


    * Random Variables
    * Variance & Covariance, Correlation
    * Central Limit Theorem & Normal Distribution
    * Standard Deviation, Statistical Significance, Z-scores and Hypothesis Testing
    * Specificity, Sensitivity & Confusion Matrices
    * Multiple Comparisons Problem & solutions (e.g. Bonferroni correction)
    * Conditional Probability and Bayes Theorem

# Data Science

* **Dataset**
    * **Label:** The "answer," or the value we want the model to predict.
    * **Features:** The values that a supervised model uses to predict the label.

* **Data Preprocessing**
    * **Feature Scaling:** Bringing all features to a similar scale using normalization or standardization. To ensure that all features contribute equally to the model and to prevent being biased toward certain features simply because of their magnitudes.

    * **Feature Engineering:**
Using intuition to design new features, by transforming or combining original features.


**Model Picking**
**Interpreting Model Results**


# Resources

* **Andrew Ng - Coursera**
    * [ML Specialization](https://www.coursera.org/specializations/machine-learning-introduction?utm_source=deeplearning-ai&utm_medium=institutions&utm_campaign=WebsiteCourses-MLS)