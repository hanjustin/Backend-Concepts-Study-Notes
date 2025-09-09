
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
#### Loss Functions
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


## Approaches
### Unsupervised Learning

* **Clustering:** Group similar data points together.
* **Anomaly Detection:** Find unusual data points.
* **Dimensionality Reduction:** Compress data using fewer numbers.

Using unlabeled raw data to create models. Patterns (similarities, differences) or relationships are infered without any explicit guidance or instruction.

#### Use case
Useful for identifying previously undetected patterns in data and can help identify features useful for categorizing data
While the algorithm itself does not understand these patterns based on any previous information you provided, you can then go through the data groupings and attempt to classify them based on your understanding of the dataset.


### Supervised Learning

* **Regression:** Predicting a number. Infinitely many possible outputs.
* **Classification:** Predict categories. Small number of outputs.



Using labeled data to create models. The label is the "answer," or the value we want the model to predict. After seeing lots of data with the correct answers, models create patterns to make predictions.
* `cat` or `dog` labeled to images. Identify new photos with the correct animal.
* The sale price added to used cars. Assign accurate prices to other used cars.

#### 


### Semi-supervised Learning

### Reinforcement Learning
The model receives rewards or penalties based on actions. The algorithm modifies its strategy in order to achieve the highest reward.



## MLOps
DevOps for ML models.

### Steps
1. **Decision Process:** Estimating a pattern for given input data.
2. **Error Function:** Evaluates the prediction of the model. Assessing the accuracy of the model by comparing to known examples (if available).
3. **Model Optimization Process:** Iteratively improve the accuracy of a machine learning model by minimizing its loss function.

## Models
### Linear Regression
Using a line to summarize the relationship in the data. Just like a linear algebraic equation, a linear regression model equation is:
`y' = b + wx`
* `b`: The bias of the model. Same concept as the y-intercept for a line.
* `w`: The weight of the feature. Same concept as the slope for a line.


* Core concepts to study
    * Regularization
    * Train, Test, Validation set
    * Labels, Weights (Parameters), Hyperparameters
    * Validation and Cross Validation
    * Overfitting and Underfitting
    * IMPORTANT: bias and variance and the bias-variance tradeoff

## Problem Framing
Determine if ML is a good approach for a problem.






# Neural Network
* Subfield of ML.

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

**Data Preprocessing**
**Feature Engineering**
**Model Picking**
**Interpreting Model Results**


# Resources

* **Andrew Ng - Coursera**
    * [ML Specialization](https://www.coursera.org/specializations/machine-learning-introduction?utm_source=deeplearning-ai&utm_medium=institutions&utm_campaign=WebsiteCourses-MLS)