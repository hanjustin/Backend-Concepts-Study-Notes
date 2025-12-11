
# WIP. <br>VERY basic study notes of backend concepts.

* Learning fundamental concepts & terminologies to get basic understanding of backend engineering to expedite the onboarding process.
* Not at the level to easily apply the concepts and evaluate the tradeoffs.

# Table of Contents
<!-- * Synchronous vs Asynchronous -->
<!-- * RabbitMQ -->
<ul>
    <li><b>Communication</b></li>
        <ul>
            <li><a href="#grpc">gRPC</a></li>
            <li><a href="#graphql">GraphQL</a></li>
            <li><details><summary>Kafka (Click)</summary>
                <ul>
                    <li><a href="#fundamentals-kafka"><b>Fundamentals</b></a></li>
                        <ul>
                            <li><b>Concepts</b></li>
                                <ul><ul><ul><ul>
                                    <li><a href="#partition-leader">Partition leader</a></li>
                                    <li><a href="#consumer-group">Consumer group</a></li>
                                    <li><a href="#cluster-coordinator---zookeeper-or-kraft">Cluster coordinator - Zookeeper or KRaft</a></li>
                                    <li><a href="#schema-registry">Schema registry</a></li>
                                    <li><a href="#data-retention-period">Data retention period</a></li>
                                </ul></ul></ul></ul>
                            <li><a href="#terminologies-kafka"><b>Terminologies</b></a></li>
                                <ul><ul><ul><ul>
                                    <li>
                                        <b><ins>P</ins></b>roducer,
                                        <b><ins>C</ins></b>onsumer,
                                        <b><ins>B</ins></b>roker,
                                        <b><ins>C</ins></b>luster,
                                        <b><ins>M</ins></b>essage,
                                        <b><ins>T</ins></b>opic,
                                        <b><ins>P</ins></b>artitions,
                                        <b><ins>O</ins></b>ffset,
                                        <b><ins>C</ins></b>onnectors
                                    </li>
                                </ul></ul></ul></ul>
                        </ul>
                </ul>
            </details>
            </li>
        </ul>
    <li><b>Tools</b></li>
        <ul>
            <li><a href="#postman">Postman</a></li>
            <li><details><summary>Kubernetes - WIP</summary>
                <ul>
                    <li><a href="#fundamentals-kubernetes"><b>Fundamentals</b></a></li>
                        <ul>
                            <li><a href="#key-features-kubernetes"><b>Key Features</b></a></li>
                                <ul><ul><ul><ul>
                                    <li>
                                        <b><ins>C</ins></b>ontainer orchestration,
                                        <b><ins>S</ins></b>ervice discovery,
                                        <b><ins>L</ins></b>oad balancing,
                                        <b><ins>S</ins></b>elf-healing
                                    </li>
                                </ul></ul></ul></ul>
                            <li><a href="#concepts-kubernetes"><b>Concepts</b></a></li>
                                <ul>
                                    <li><b>Architecture</b></li>
                                        <ul><ul><ul>
                                            <li><b>Master node</b></li>
                                                <ul>
                                                    <li>
                                                        <b><ins>e</ins></b>tcd,
                                                        <b><ins>A</ins></b>PI server,
                                                        <b><ins>S</ins></b>cheduler,
                                                        <b><ins>C</ins></b>ontroller manager
                                                    </li>
                                                </ul>
                                            <li><b>Worker node</b></li>
                                                <ul>
                                                    <li>
                                                        <b><ins>C</ins></b>ontainer runtime,
                                                        <b><ins>K</ins></b>ubelet,
                                                        <b><ins>K</ins></b>ube-proxy
                                                    </li>
                                                </ul>
                                        </ul></ul></ul>
                                    <li>Concept2 - WIP</li>
                                </ul>
                            <li><a href="#terminologies-kubernetes"><b>Terminologies</b></a></li>
                                <ul><ul><ul><ul>
                                    <li>
                                        WIP
                                    </li>
                                </ul></ul></ul></ul>
                        </ul>
                    <li><b>Tools</b></li>
                        <ul><ul><ul><ul><ul>
                            <li><b>m</b>inikube,
                            <b>k</b>ubectl,
                            <b>H</b>elm</li>
                        </ul></ul></ul></ul></ul>
                </ul>
            </details>
            </li>
        </ul>
    <li><b>Cloud</b></li>
        <ul>
            <li><details><summary>AWS</summary>
                <ul>
                    <li><a href="#fundamentals-aws"><b>Fundamentals</b></a></li>
                        <ul>
                            <li><b>Concepts</b></li>
                                <ul>
                                    <li><a href="#computing-models"><b>Computing Models</b></a></li>
                                            <ul><ul><ul>
                                                <li>
                                                    <b><ins>S</ins></b>erverless,
                                                    <b><ins>S</ins></b>aaS,
                                                    <b><ins>P</ins></b>aaS,
                                                    <b><ins>I</ins></b>aaS
                                                </li>
                                            </ul></ul></ul>
                                    <li><a href="#deployment-models"><b>Deployment Models</b></a></li>
                                            <ul><ul><ul>
                                                <li>
                                                    <b><ins>P</ins></b>rivate,
                                                    <b><ins>P</ins></b>ublic,
                                                    <b><ins>H</ins></b>ybrid,
                                                    <b><ins>M</ins></b>ulticloud
                                                </li>
                                            </ul></ul></ul>
                                    <li><a href="#global-infrastructure"><b>Global Infrastructure</b></a></li>
                                            <ul><ul><ul>
                                                <li>
                                                    <b><ins>R</ins></b>egions,
                                                    <b><ins>A</ins></b>vailability zones,
                                                    <b><ins>E</ins></b>dge locations
                                                </li>
                                            </ul></ul></ul>
                                    <li><a href="#best-practices-aws"><b>Cloud Best Practices Pillars - Well-Architected Framework</b></a></li>
                                            <ul><ul><ul>
                                                <li>
                                                    <b><ins>O</ins></b>perational excellence,
                                                    <b><ins>S</ins></b>ecurity,
                                                    <b><ins>R</ins></b>eliability,
                                                    <b><ins>P</ins></b>erformance efficiency,
                                                    <b><ins>C</ins></b>ost optimization
                                                </li>
                                            </ul></ul></ul>
                                </ul>
                            <li><a href="#terminologies-aws"><b>Terminologies</b></a></li>
                                <ul><ul><ul><ul>
                                    <li>
                                        <b><ins>F</ins></b>ault domain,
                                        <b><ins>A</ins></b>RNs,
                                        <b><ins>S</ins></b>ervice level agreement,
                                        <b><ins>S</ins></b>ervice level indicator,
                                        <b><ins>S</ins></b>ervice level objective,
                                        <b><ins>R</ins></b>ecovery point objective,
                                        <b><ins>R</ins></b>ecovery time objective
                                    </li>
                                </ul></ul></ul></ul>
                        </ul>
                    <li><b>Key Services</b></li>
                        <ul>
                            <li>
                                <a href="#iam-aws"><b>IAM</b></a> - 
                                <b><ins>U</ins></b>ser,
                                <b><ins>P</ins></b>olicy,
                                <b><ins>G</ins></b>roup,
                                <b><ins>R</ins></b>ole,
                                <b><ins>T</ins></b>rust Relationship
                            </li>
                            <li>
                                <a href="#vpc-aws"><b>VPC</b></a> - 
                                <b><ins>S</ins></b>ubnets,
                                <b><ins>S</ins></b>ecurity groups,
                                <b><ins>V</ins></b>PC endpoint
                            </li>
                            <li>
                                <a href="#ec2-aws"><b>EC2</b></a> - 
                                <b><ins>I</ins></b>nstance types,
                                <b><ins>S</ins></b>torage options (EBS & EFS),
                                <b><ins>A</ins></b>MI
                            </li>
                            <li>
                                <a href="#s3-aws"><b>S3</b></a> - 
                                <b><ins>B</ins></b>ucket,
                                <b><ins>O</ins></b>bject,
                                <b><ins>S</ins></b>torage classes,
                                <b><ins>L</ins></b>ifecycle automation
                            </li>
                            <li><a href="#lambda-aws"><b>Lambda</b></a> - 
                                <b><ins>F</ins></b>aaS,
                                <b><ins>T</ins></b>rigger,
                                <b><ins>E</ins></b>xecution environment
                            </li>
                            <li>
                                <a href="#cloudformation-aws"><b>CloudFormation</b></a> - 
                                <b><ins>I</ins></b>aC,
                                <b><ins>S</ins></b>tack,
                                <b><ins>C</ins></b>hangeSets
                            </li>
                        </ul>
                    <!-- <li><a href="#fundamentals-aws"><b>Other Services</b></a></li>
                        <ul>
                            <li>DynamoDB</b></a></li>
                        </ul> -->
                    <li><em>Key points from AWS certification preparation resources:</em></li>
                        <ul>
                            <li><b>CLF-C02</b> Cloud Practitioner - Foundational</li>
                            <li><b>SAA-C03</b> Solutions Architect - Associate</li>
                        </ul>
                </ul>
            </details>
            </li>
        </ul>
    <li><b>Databases</b></li>
        <ul>
            <li><details><summary>PostgreSQL</summary>
                <ul>
                    <li><a href="#fundamentals-postgresql"><b>Fundamentals</b></a></li>
                        <ul>
                            <li><a href="#concepts-postgresql"><b>Concepts</b></a></li>
                                <ul><ul><ul><ul>
                                    <li>Table Inheritance</li>
                                    <li>User-defined Data Types</li>
                                </ul></ul></ul></ul>
                            <li><a href="#terminologies-postgresql"><b>Terminologies</b></a></li>
                                <ul><ul><ul><ul>
                                    <li>
                                        <b><ins>P</ins></b>rimary key,
                                        <b><ins>C</ins></b>omposite primary key,
                                        <b><ins>F</ins></b>oreign key,
                                        <b><ins>V</ins></b>iew,
                                        <b><ins>M</ins></b>aterialized view,
                                        <b><ins>S</ins></b>tored procedure,
                                        <b><ins>A</ins></b>ggregate & window functions
                                    </li>
                                </ul></ul></ul></ul>
                        </ul>
                    <li><a href="#tools-postgresql"><b>Tools</b></a></li>
                        <ul><ul><ul><ul><ul>
                            <li><b>p</b>sql, <b>p</b>gAdmin</li>
                        </ul></ul></ul></ul></ul>
                    <li><a href="#sql-syntax"><b>SQL Syntax</b></a></li>
                                <ul><ul><ul><ul><ul>
                                    <li><b>Database Management</b></li>
                                        <ul>
                                            <li><code>CREATE</code>, <code>ALTER</code>, <code>TRUNCATE</code>, <code>DROP</code></li>
                                        </ul>
                                    <li><b>Data CRUD Operations</b></li>
                                        <ul>
                                            <li><code>INSERT INTO</code>, <code>SELECT</code>, <code>WHERE</code>, <code>UPDATE</code>, <code>DELETE</code></li>
                                        </ul>
                                    <li><b>Data Integrity Protection</b></li>
                                        <ul>
                                            <li><b>Constraint</b></li>
                                                <ul>
                                                    <li><code>PRIMARY KEY</code>, <code>REFERENCES</code>, <code>CHECK</code>, <code>UNIQUE</code>, <code>NOT NULL</code>, <code>ON DELETE</code></li>
                                                </ul>
                                            <li><b>Transaction Management</b></li>
                                                <ul>
                                                    <li><code>BEGIN</code>, <code>COMMIT</code>, <code>ROLLBACK</code>, <code>SAVEPOINT</code></li>
                                                </ul>
                                            <li><b>Trigger</b></li>
                                                <ul>
                                                    <li><code>CREATE TRIGGER</code>, <code>CREATE FUNCTION</code>, <code>BEFORE/AFTER event</code>, <code>$$string_constant$$</code></li>
                                                </ul>
                                        </ul>
                                    <li><b>Aggregate Queries</b></li>
                                        <ul>
                                            <li><code>MIN</code>, <code>SUM</code>, <code>AVG</code>, <code>COUNT</code>, <code>GROUP BY</code></li>
                                        </ul>
                                    <li><b>User Access Control</b></li>
                                        <ul>
                                            <li><code>ROLE</code>, <code>GRANT</code>, <code>REVOKE</code></li>
                                        </ul>
                                    <li><b>Join</b></li>
                                        <ul>
                                            <li><code>JOIN</code>, <code>LEFT JOIN</code>, <code>RIGHT JOIN</code>, <code>FULL JOIN</code></li>
                                        </ul>
                                </ul></ul></ul></ul></ul>
                </ul>
            </details>
            </li>
            <li><details><summary>Cassandra</summary>
                <ul>
                    <li><a href="#fundamentals-cassandra"><b>Fundamentals</b></a></li>
                        <ul>
                            <li><a href="#concepts-cassandra"><b>Concepts</b></a></li>
                                <ul><ul><ul><ul>
                                    <li>Masterless interconnected independent nodes</li>
                                    <li>Query oriented denormalized data format</li>
                                    <li>Per request tunable consistency</li>
                                    <li>Last write wins eventual consistency</li>
                                    <li>Rows with optional fields</li>
                                </ul></ul></ul></ul>
                            <li><a href="#terminologies-cassandra"><b>Terminologies</b></a></li>
                                <ul><ul><ul><ul>
                                        <b><ins>K</ins></b>eyspace,
                                        <b><ins>T</ins></b>able,
                                        <b><ins>P</ins></b>artition,
                                        <b><ins>R</ins></b>eplication factor,
                                        <b><ins>C</ins></b>onsistency levels,
                                        <b><ins>P</ins></b>rimary key,
                                        <b><ins>P</ins></b>artition key,
                                        <b><ins>C</ins></b>omposite partition key,
                                        <b><ins>C</ins></b>lustering key,
                                        <b><ins>C</ins></b>oordinator,
                                        <b><ins>P</ins></b>artitioner,
                                        <b><ins>G</ins></b>ossip protocol,
                                        <b><ins>L</ins></b>ightweight transactions
                                </ul></ul></ul></ul>
                        </ul>
                    <li><a href="#cql-syntax"><b>CQL Syntax</b></a></li>
                                <ul><ul><ul><ul><ul>
                                    <li><b>Keyspace Management</b></li>
                                        <ul>
                                            <li><code>CREATE</code>, <code>USE</code>, <code>DROP</code></li>
                                        </ul>
                                    <li><b>Table Management</b></li>
                                        <ul>
                                            <li><code>CREATE</code>, <code>ALTER</code>, <code>DELETE</code></li>
                                        </ul>
                                    <li><b>Data CRUD Operations</b></li>
                                        <ul>
                                            <li><code>INSERT INTO</code>, <code>SELECT</code>, <code>WHERE</code>, <code>UPDATE</code>, <code>USING TTL</code>, <code>DELETE</code></li>
                                        </ul>
                                    <li><b>Misc</b></li>
                                        <ul>
                                            <li><code>CREATE TYPE/INDEX</code>, <code>BEGIN/APPLY BATCH</code></li>
                                        </ul>
                                </ul></ul></ul></ul></ul>
                </ul>
            </details>
            </li>
            <li><details><summary>Redis</summary>
                <ul>
                    <li><a href="#fundamentals-redis"><b>Fundamentals</b></a></li>
                        <ul>
                            <li><a href="#key-features-redis"><b>Key Features</b></a></li>
                                <ul><ul><ul><ul>
                                    <li>RAM In-memory Datastore</li>
                                    <li>Data Structure Store</li>
                                    <li>Atomic Operations</li>
                                    <li>Pub/sub</li>
                                    <li>Optional Persistence</li>
                                </ul></ul></ul></ul>
                            <!-- <li><a href="#concepts-redis"><b>Concepts</b></a></li>
                                <ul><ul><ul><ul>
                                    <li>Eviction Policies</li>
                                </ul></ul></ul></ul> -->
                        </ul>
                    <li><a href="#use-cases-redis"><b>Use Cases</b></a></li>
                        <ul><ul><ul><ul><ul>
                            <li>Caching</li>
                            <li>Session Store</li>
                            <li>Rate Limiting</li>
                            <li>Real-Time Analytics</li>
                            <li>Event-Driven Message Queues</li>
                            <li>Location-Based Services</li>
                        </ul></ul></ul></ul></ul>
                </ul>
            </details>
            </li>
            <li><details><summary>MongoDB</summary>
                <ul>
                    <li><a href="#fundamentals-mongodb"><b>Fundamentals</b></a></li>
                        <ul>
                            <li><a href="#key-features-mongodb"><b>Key Features</b></a></li>
                                <ul><ul><ul><ul>
                                    <li>Optional Schema</li>
                                    <li>Aggregation Pipelines</li>
                                    <li>Relationship options: Embed vs. Reference</li>
                                </ul></ul></ul></ul>
                            <li><a href="#terminologies-mongodb"><b>Terminologies</b></a></li>
                                <ul><ul><ul><ul>
                                    <li>Collection, Document, BSON, mongosh</li>
                                </ul></ul></ul></ul>
                        </ul>
                </ul>
            </details>
            </li>
        </ul>
</ul>

* **Databases - Fundamentals**
    * **Concepts**
        * **[Indexing](#indexing)**
        * **[Sharding](#sharding)**
        * **[Normalization](#normalization)**
            * 1NF, 2NF, 3NF
            * vs Denormalization
    * **Relational**
    <!-- * Non-relational
        * Key-value pair
        * Document-oriented
        * Column-oriented
        * Graph-based
        * Time series -->
    * **SQL vs NoSQL**
    * **[ACID vs BASE transaction](#acid-vs-base-transaction)**
        * **[ACID](#acid)**
            * **[Isolation Levels vs Read Phenomena](#isolation-levels-vs-read-phenomena)**
            * **[Compliance Strategies](#compliance-strategies)**
                * <b><ins>W</ins></b>rite-ahead logging,
                <b><ins>C</ins></b>heckpointing,
                <b><ins>S</ins></b>hadow paging,
                <b><ins>L</ins></b>ocking,
                <b><ins>M</ins></b>ulti-versioning
        * **[BASE](#base)**
    * **Terminologies**

<ul>
    <li><b>DevOps</b></li>
        <ul>
            <li><a href="#terminologies-devops"><b>Terminologies</b></a></li>
                <ul>
                    <li>
                        <b><ins>D</ins></b>evSecOps,
                        <b><ins>P</ins></b>latform engineering
                    </li>
                </ul>
        </ul>
  </li>
</ul>

* **Architectural Patterns**
    * **Distributed System**
        * [CAP theorem](#cap-theorem)
        * [PACELC theorem](#pacelc-theorem)
        * [Scaling Patterns](#scaling-patterns)
            * [Vertical vs Horizontal](#vertical-vs-horizontal)
            <!-- * Load Balancing -->
        <!-- * Consistency Patterns -->
    <!-- * Microservices -->
    * [Monolithic](#monolithic)
        * [Modular Monolith](#modular-monolith)
        * [Distributed Monolith](#distributed-monolith)

* **[Design Patterns](#design-patterns)**
    <!-- * Ambassador pattern
    * Anti-corruption Layer pattern -->
    * [Backends for Frontends](#backends-for-frontends)
    <!-- * [Gateway Routing](#gateway-routing) -->
    <!-- * Gatekeeper pattern
    * Sequential Convoy pattern -->
    * [Strangler Fig pattern](#strangler-fig-pattern)

<!-- * To-Do
    * Authentication
        * JWT
        * OAuth
    * Server-side rendering
        * vs Client-side rendering
        * vs Single-page app
        * SEO
    * Monorepo vs Polyrepo Code Management -->

---

# Other study notes
* [Artificial Intelligence](Artificial-Intelligence)

---

# Communication

## Synchronous vs Asynchronous

## gRPC

* Platform agnostic serialization protocol that is used to communicate between services.
* Protocol Buffer (Protobuf). `.proto` file format is commonly used to define messages sent between clients and servers for communication between two different languages. Generates code used for the client/server communication.

## GraphQL

* In client/server communication, clients can control the response data format. In REST, server controls the data format. Distinct clients (web, iOS, etc.) can have different data requirements.
* GraphQL schema file `*.graphqls` contains all information about what a client can potentially do with a GraphQL API.
* A single endpoint can be used to receive requests with GraphQL queries.
* As clients can request exact data wanted, could be used to avoid REST API's over-fetching & under-fetching problems.

## Kafka

<h3 id="fundamentals-kafka">Fundamentals</h3>

* Like a post office between a sender and receiver(s). Allows real-time data streaming and processing.
* Often used as a message broker, allowing different software systems to communicate by sending (producing) and receiving (consuming) messages.
* Can be used as a pub-sub and queue based messaging system.

#### Concepts
##### Partition leader
Every partition has exactly one partition leader which handles all the read/write requests of that partition. Every partition replica resides on a different broker. Every partition follower is reading messages from the partition leader (acts like a kind of consumer) and does not serve any consumers of that partition (only the partition leader serves read/writes). When a partition leader shuts down for any reason (e.g a broker shuts down), one of it's in-sync partition followers becomes the new leader.

##### Consumer group
Consumers within a group share responsibility for processing messages. One consumer can get many partitions, but no two consumers within a group will be subscribed to the same partition to prevent the two consumers receiving the same message.

##### Cluster coordinator - Zookeeper or KRaft
Centralized service for managing metadata and coordination of distributed systems.
Used to keep track of active brokers. Each Kafka partition has a leader broker and ZooKeeper facilates the election of the leader. Newer Kafka uses KRaft.

##### Schema registry
Data schema is needed for data serialization and deserialization. When the schema is expected to change, you must update the registry which resides in a cluster for consumers and producers to find out what schema a given message follows.

##### Data retention period
Other message queue programs delete messages after consumption. Kafka has a configurable messages retention period.

<h4 id="terminologies-kafka">Terminologies</h4>

* **Producer:** Services that publish/write to messages to Kafka
* **Consumer:** Susbscribe to read/process the messages sent to Kafka
* **Broker:** A single Kafka server that stores messages and manages distributing messages to cosumers.
* **Cluster:** A group of interconnected brokers that work together to manage the data streams entering and leaving a Kafka system.
* **Message:** Records the fact something happened. Also called "record" or "event". Read or write is done in the form of messages. It has a format of key/value pair & header data (meta data of topics & partitions).
* **Topic:** Categorization used to group messagess. Based on the requirements, define topics like schema for databases. Producers send to a topic, while consumers subscribe to topics.
* **Partitions:** For more throughput, topics are broken into several partitions, which is how a single topic can span across multiple brokers. Similar to RDBMS sharding for scaling.
* **Offset:** A unique integer identifier assigned to each message within a specific partition, representing its position within that partition's log, and is used to track the progress of consumers.
* **Connectors:** Used to connect to external systems such as databases, key-value stores, search indexes, and file systems to move data in/from Kafka.

---

# Tools
## Kubernetes
<h3 id="fundamentals-kubernetes">Fundamentals</h3>

Container orchestration tool to simplify managing containerized applications across multiple servers.

<h4 id="key-features-kubernetes">Key Features</h4>

* **Container Orchestration:** Automatically provision, deploy, scale and manage the lifecycle of containerized applications.
* **Service Discovery:** Applications in separate pods can communicate without knowing hard coded IP addresses.
* **Load Balancing:** Distribute traffic across the network to improve stability and performance.
* **Self-Healing:** Automatically replace failed containers.

<h4 id="concepts-kubernetes">Concepts</h4>

##### Architecture
* **Master node** controls cluster state & worker nodes. A cluster usually has multiple master nodes.
    * **etcd:** Cluster brain. Keeps current state of the cluster. Key value store of cluster changes for state restoration.
    * **API server:** Cluster gateway. Entry point into the cluster. Gatekeeper for authentication.
    * **Scheduler:** Decides which node will get the new Pod. Sends instruction to the node's kubelet to start the new pod.
    * **Controller manager:** Keeps overview of the cluster. Detects cluster state changes such as a pod crash.
* **Worker node** do the actual work. Each node can have multiple pods.
    * **Container runtime:** Docker or other container application
    * **Kubelet:** Interacts with both the container & node.
    * **Kubelet proxy:** Forwards requests from services to pods.

* Configuration:
    * Controller manager status checks by comparing declared desired state & current actual state. Self healing capability attempts to restore to the desired state `if current state != desired state`.
    * Configuration file has:
        * Metadata
        * Specification: Attributes specific to the `kind` of the configuration.
        * Status: Automatically generated by K8s that gets updated continuously. The current status information comes from `etcd`.

<!-- * Tools
    * Minikube
        * For testing cluster locally.
        * A cluster with one node with both master & worker processes.
    * Kubectl
        * CLI tool for K8s cluster -->

<h4 id="terminologies-kubernetes">Terminologies</h4>

* **Pod:** Smallest unit of K8s. A layer over a container to abstract away container technologies. Usually one container per pod. Each pod has an IP. New IP address on re-creation.
* **Service:** Static permanent IP address attached to Pod that doesn't change even when Pod gets re-created. Also acts as a load balancer.
* **Ingress:** Component to forward requests to Service.
* **ConfigMap:** External configuration for application. Making it easier to manage and update application settings without redeploying containers.
* **Secret:** ConfigMap to store sensitive secret data.
* **Volume:** Persistant storage for pods.
* **Deployment:** Abstract template/blueprint layer for creating pods with stateless apps.
* **StatefulSet:** Alternative of `Deployment` to replicate Stateful apps such as DBMS to manage data inconsistencies.
* **Virtual network:** Forms the cluster for master & worker nodes to interact.

## Postman

API testing tool. Unlike `cURL` which has a CLI, Postman has a GUI to simplify creating and managing API requests.

---

# Cloud
## AWS
<h3 id="fundamentals-aws">Fundamentals</h3>

Physical or virtual resources owned by Amazon that can be used and scaled on-demand over the internet. Allows businesses to save money on hardware, software, and IT maintenance costs.

<h4 id="concepts-aws">Concepts</h4>

##### Computing Models
* Different models offer varying level of control and responsibility.
* **Serverless:** <br> Allow developers to focus solely on writing code, often in the form of functions. Abstracts away the underlying infrastructure and server management completely. Ideal for asynchronous, stateless apps that can be started instantaneously. Doesn’t cost anything when idle. To consider when cold-starts are acceptable or you don't have lots of traffic demand.
* **SaaS - Software as a Service:** <br> Entire cloud-based application for customers. Completely managed by the service provider and come ready to use. <br> i.e. Gmail, Slack, Office 365
* **PaaS - Platform as a Service:** <br> Allow developers to develop and deploy applications without worrying about setting up the infrastructure. The environment to build and deploy is managed by the cloud service provider. <br> i.e. Heroku, Google App Engine
* **IaaS - Infrastructure as a Service:** <br> Provide cloud IT basic building blocks for high level of infrastructure flexibility. The cloud service provider hosts, manages and maintains the hardware and computing resources in its own data centers. <br> i.e. AWS, Azure, Google Cloud

##### Deployment models
* **Private:** Infrastructure resources used exclusively by one business or organization. Can be physically located at your organization’s on-site datacenter, or it can be hosted by a third-party service provider, but the services and infrastructure are solely dedicated to one organization.
* **Public:** Shared infrastructure resources. Public providers allow different companies or organizations to access hardware and software resources over the public internet and bill companies pay-per-usage.
* **Hybrid:** A mixture of public and private clouds.
* **Multicloud:** Using at least two cloud providers to run applications. A combination of two or more public clouds, two or more private clouds, or some combination of both.

##### Global Infrastructure
* Globally distributed hardware and datacenters that are physically networked together to act as one large resource for the end customer.
* **Regions:** Geographically distinct locations consisting of Availability Zone(s). Every region is physically isolated from and independent of every other region in terms of power for fault tolerance and stability. Each region usually has three Availability Zones. Not all AWS Services are available in all regions.
* **Availability Zone:** Physical location made up of datacenter(s). Within a region, AZs are connected through low-latency links. Common practice to run workloads in at least 3 AZs for high availability.
* **Edge Locations:** Datacenters with cached files that are used rather than the origin server to serve contents faster to users by reducing the delivery distance.

<h5 id="best-practices-aws">AWS Well-Architected Framework</h5>

Design principles and architectural best practices for designing and running workloads in the cloud. Aspects to consider:
* **Operational Excellence:** Apply software engineering principles to your cloud infrastructure. Make frequent, small, reversible changes while monitoring systems to perform post-mortems on system failures.
* **Security:** Apply security at all layers and follow security best practices to protect data and systems.
* **Reliability:** Scale horizontally to avoid a single point of failure and use automation to automatically recover from failure.
* **Performance Efficiency:** Structure and streamline allocation of IT and computing resources. Select resource types and sizes optimized for workload requirements.
* **Cost Optimization:** Minimize overspending by selecting resources of the right type and quantity.

<h4 id="terminologies-aws">Terminologies</h4>

* **Amazon Resource Names (ARNs):** Uniquely identify AWS resources.
* **Fault Domain:** A section of a network that is vulnerable to damage if a critical device or system fails. The domain is to limit the possible damage by limiting the damage cascade outside that domain when a failure occurs. The scope of a domain could be: specific servers in a rack, an entire rack/room in a datacenter, or the entire data center building.
* **Service Level Agreement (SLA):** A formal contract between a service provider and a customer that defines the level of service expected from the provider.
* **Service Level Indicator (SLI):** A metric/measurement that indicates what measure of performance a customer is receiving. i.e. uptime, performance, availability, throughput, latency, error rate, durability
* **Service Level Objective (SLO):** A measurable target that defines the desired level of service quality for a specific service. Represented as a specific target percentage over a period of time. i.e. Availability SLA of 99.99% in a period of 3 months
* **Recovery Point Objective (RPO):** The maximum acceptable amount of data loss after an unplanned data-loss incident.
* **Recovery Time Objective (RTO):** The maximum acceptable downtime of service.

<h3 id="key-services-aws">Key Services</h3>

<h4 id="iam-aws">IAM</h4>

Control access to resources/entities. Create **Users** who use credentials that gain access based on their **policy document**. **Policy** determines **Actions** that **Users** can perform.

* **Groups:** User types with default policy documents. i.e developer, tester
* **Roles:** Used to grant temporary access to resources.
* **Trust Relationships:** Used to access a resource under external accounts. The resource owner creates a role to allow external accounts to access the resource.

**Policy document to allow user to create Lambda functions**
```
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "CreateFunction",
            "Effect": "Allow"
            "Action": [
                "lambda: CreateFunction",
            ],
            "Resource": "*"
        }
    ]
}
```

<h4 id="vpc-aws">VPC</h4>

* Provides a secure isolated network environment for AWS resources to enhance security by preventing unauthorized access.
* Similar to your home network. Home devices are connected to your router, and this creates your private home network as routers have built-in firewalls. Your router also acts as a gateway between the private network and the public network.

* **Subnets:** VPC can be divided into smaller segments called subnets.
    * **Public subnet:** Allocation of resources to interact with the public internet directly through an internet gateway, which is a digital cloud modem similar to a home modem that allows AWS resources to connect to the internet.
    * **Private subnet:** Allocation of resources to NOT interact with the public internet directly. Will not have a route to an internet gateway and rely on mechanisms like NAT gateways to access the internet, so resources will be hidden from the outside world.
* **Security groups:** Control inbound and outbound traffic to associated resources using stateful rules based on IP addresses, ports, and protocols.
* **VPC endpoint:** Allows resources in your VPC to privately connect to AWS services outside of your VPC without using the internet. Enhances security and performance by keeping the traffic within the AWS network.

<h4 id="ec2-aws">EC2</h4>

Online virtual machine server service. Considered the backbone of AWS as the majority of AWS services are using EC2 as their underlying servers.

##### Instance types
Choosing the appropriate instance type for specific workloads. Factors to consider include CPU capacity, memory requirements, storage needs, network demands, and any specialized requirements such as GPUs accelerators.

* **General Purpose:** Balance of compute, memory and networking resources. Use-cases web servers and code repositories
* **Compute Optimized:** Ideal for compute bound applications that benefit from high performance processor. Use-cases scientific modeling, dedicated gaming servers and ad server engines
* **Memory Optimized:** Fast performance for workloads that process large data sets in memory. Use-cases in-memory caches, in-memory databases, real time big data analytics
* **Accelerated Optimized:** Hardware accelerators, or co-processors. Use-cases Machine learning, computational finance, seismic analysis, speech recognition
* **Storage Optimized:** High, sequential read and write access to very large data sets on local storage. Use-cases NoSQL, in-memory or transactional databases, data warehousing

##### Storage options
* **EBS:** Elastic Block Store for a low-latency block storage that can be attached to a single EC2 instance.
* **EFS:** Elastic File Storage for a shared file system that can be accessed by multiple EC2 instances concurrently.

##### AMI
The blueprint/snapshot used to create multiple EC2 instances with the same state. It contains the OS, pre-installed software, and configuration settings.

<h4 id="s3-aws">S3</h4>
S3 (Simple Storage Service) is an object storage is a data storage architecture that manages data as objects. Like Google Drive or Dropbox. No need to think about the underlying infrastructure.

##### Accessing Objects
* **By URL:** `http://s3.amazonaws.com/<BUCKET_NAME>/<OBJECT_NAME>`
* **Programmatically:**
```
sClient = boto3.client('s3')
myObject = sClient-get_object(Bucket='BUCKET_NAME', Key='OBJECT_NAME'
```
* **CLI:**

`aws s3 cp s3://<BUCKET_NAME>/<OBJECT_NAME> <local-destination-path>`

* **GUI:** The S3 Console provides an interface to upload and access your data.

##### S3 Bucket
A container of objects within a namespace. It is like a top-level folder that can also have nested folders.

##### S3 Object
Objects are like files. Resources that represent data

Object may consist of:
* **Etags:** Useful to programmatically detect content changes to objects without downloading
* **Checksums:** ensures the integrity of a files being uploaded or downloaded
* **Prefixes:** simulates file-system folders in a flat hierarchy
* **Metadata:** - To provide extra information of the contents of the data. Custom metadta must start with `x-amz-meta-`.
* **Tags:** - benefits resource tagging but at the object level
* **Locking:** - makes data files immutable
* **Versioning:** — have multiple versions of a data file

##### Storage Classes
Each tier has different pricing, retrieval time, availability.
* Tiers: Standard, Infrequent Access, Glacier

##### Lifecycle Automation
Bucket/Object Lifecycle rules automate the storage class optimization process to reduce cost.

<h4 id="lambda-aws">Lambda</h4>

* **FaaS:** Allow developers to only worry about writing code. Cloud compute service w/o the need of managing a server. Ideal for short, event driven workloads.
* **Trigger:** An event source that sends event data as a JSON file for your functions to process
* **Execution environment:** A secure isolated runtime environment for your lambda function.

<h4 id="cloudformation-aws">CloudFormation</h4>

**IaC:** Declarative Infrastructure as Code to automate provisioning of AWS resources with JSON or YAML template files.
* **Stack:** A collection of resources that you can manage as code within a template. When you deploy a template, it creates a stack.
* **ChangeSet:** Like `git diff`. Changing the running resources in a stack, requires updating the stack. Before making changes, generate a change set to see a summary of proposed changes to see how running resources will be impacted.

---

# Databases
## PostgreSQL
<h3 id="fundamentals-postgresql">Fundamentals</h3>

* Object-Relational Database Management System (ORDBMS) that combines traditional RDBMS with object-oriented concepts such as inheritance.
* Supports both relational (SQL) and non-relational (JSON) queries.

<h4 id="concepts-postgresql">Concepts</h4>

* **Table Inheritance:** Inherits all columns from parent table.
    * **Big limitation:** Constraints are **not** inherited. Indexes (including unique constraints) and foreign key constraints don't work with inheritance.
        * i.e. For tables Parent, Child (which inherits Parent), and Foo, and Foo having a foreign key on Parent.id, then adding a row to Child, and trying to insert a row into Foo, referencing Child's ID will fail, even though that ID is in the Parent table. The foreign keys only work on the direct table it references as it'll only find rows in that table exactly.
* **User-defined Data Types:** In addition to the native data types, custom data types can be created using `CREATE DOMAIN` or `CREATE TYPE`.

<h4 id="terminologies-postgresql">Terminologies</h4>

* **Primary key:** A column that uniquely identifies each row.
* **Composite primary key:** A combination of columns that uniquely identifies each row.
* **Foreign key:** Create relationship by referencing the primary key in another table.
* **View:** Assign an alias to a query for reuse of the query.
* **Materialized view:** View w/ cache. Precomputed query that periodically updates cached results for faster read.
* **Stored procedure:** Functions that can accept parameters.
* **Aggregate function:** Perform a calculation on a set of rows and return a single row.
* **Window function:** Perform a calculation on a set of rows and return multiple rows.

<h3 id="tools-postgresql">Tools</h3>

* **psql:** CLI tool to enter SQL queries or commands to PostgreSQL database. Commands start with backslash `\`.
* **pgAdmin:** GUI tool to manage PostgreSQL database.

<h3 id="sql-syntax">SQL Syntax</h3>

#### Database Management

```sql
CREATE TABLE my_table (
  my_column VARCHAR(255),
  my_number INT
);

ALTER TABLE my_table
ALTER COLUMN my_column TYPE VARCHAR(44);

ALTER TABLE my_table
ADD new_col VARCHAR(255);

TRUNCATE TABLE my_table;

DROP TABLE my_table;
```

#### Data CRUD Operations
```sql
-- Create
INSERT INTO my_table (col1, col2, col3)
VALUES('value1', 'value2', 'value3');

-- Read
SELECT * FROM my_table;

SELECT col1, col2, col3 AS new_col3_name
FROM my_table
WHERE col1 = 'My Condition';

-- Update
UPDATE my_table
SET col1 = 'New Value';
WHERE col1 = 'Old Value';

-- Delete
DELETE FROM my_table
WHERE col1 = 'My Condition';
```

#### Data Integrity Protection
##### Constraint
```sql
CREATE TABLE my_user (
  user_id SERIAL PRIMARY KEY,
  name TEXT NOT NULL,
  email TEXT UNIQUE,
  age INT DEFAULT -1,
  CONSTRAINT age_check CHECK (age BETWEEN 0 AND 100)
);

CREATE TABLE my_child (
  parent_id INT NOT NULL REFERENCES my_user(user_id) ON DELETE CASCADE
);
```

##### Transaction Management

```sql
-- Transaction inserting values 1 and 3, but not 2.
BEGIN;
  INSERT INTO my_table VALUES (1);

  SAVEPOINT my_savepoint;
  INSERT INTO my_table VALUES (2);
  ROLLBACK TO SAVEPOINT my_savepoint;

  INSERT INTO my_table VALUES (3);
COMMIT;
```

##### Trigger

```sql
CREATE TRIGGER my_trigger
  AFTER INSERT ON my_table
  FOR EACH ROW
  EXECUTE FUNCTION my_trigger_function();

-- Prevent negative values
CREATE OR REPLACE FUNCTION my_trigger_function()
RETURNS TRIGGER
AS
$$
BEGIN
  IF NEW.my_number < 0
  THEN
    RAISE EXCEPTION 'Number can''t be negative';
  END IF;
  RETURN NULL;
END;
$$
LANGUAGE plpgsql;

-- Return row count * argument value
-- Learned trigger function must be declared
-- no args and return type of trigger
CREATE OR REPLACE FUNCTION my_first_function(my_multiplier_param INT)
RETURNS INT
AS
$$
DECLARE
  my_int INT;
BEGIN
  SELECT COUNT(*) INTO my_int FROM my_table;
  RETURN my_int * my_multiplier_param;
END;
$$
LANGUAGE plpgsql;
```

#### Aggregate Queries

```sql
SELECT
  MIN(price),
  SUM(price),
  AVG(price),
  COUNT(DISTINCT price)
FROM my_products_table
GROUP BY category;
```

#### User Access Control
* Manage permissions & rights to control access to data

```sql
CREATE ROLE my_role
PASSWORD '1234';

GRANT SELECT, UPDATE ON my_table
TO my_role;

REVOKE UPDATE ON my_table
FROM my_role;
```

#### Misc

```sql
-- casting
`value::target_type`
```

* **Dollar-Quoted String Constants:** Can use `$Tag$It's working$Tag$` instead of `'It''s working'`. For better readability, dollar signs can be used to avoid double single quotes. The tag is optional, but can be used to provide additional context like `$uuid$ext_data$uuid$`. Nesting constants with different tags is also possible.

## Cassandra
<h3 id="fundamentals-cassandra">Fundamentals</h3>

* Distributed NoSQL no single point of failure database with denormalized data. Database to consider when needing a very high write throughput, prioritizing availability over consistency, and not needing advanced query patterns (such as `JOIN`) or adhoc aggregations.

<h4 id="concepts-cassandra">Concepts</h4>

* **Masterless interconnected independent nodes:** No single point of failure achieved by having each node performing the same functions and independently accepting read and write requests regardless of where the data is actually located in the cluster.
* **Query oriented denormalized data format:** A single table should fulfill a query, so all desired data in a denormalized form must be in a single table. UI & UX have a heavy influence on how data gets modeled. Unlike RDBMS, `JOIN` is not provided at the database level, so data merging should happen at the application level if needed.
* **Per request tunable consistency:** A client application can tune the consistency for individual read or write operation so that the data returned meets the consistency requirement. A tradeoff between operation latency and consistency.
* **Last write wins eventual consistency:** Every mutation is timestamped to resolve conflicting mutations.
* **Rows with optional fields:** Rows are identifiable with primary keys, and rows can omit columns as row data is stored in key/value pairs internally where `key = column name` & `value = cell data`.
* **Rows saved together by partition key:** For optimal data retrieval, all rows with the same partition key are stored in the same node.

<h4 id="terminologies-cassandra">Terminologies</h4>

* **Keyspace:** Contains tables like RDBMS database. Defines how a dataset is replicated, per datacenter. Replication is the number of copies saved per cluster, and it is controlled on a per-keyspace basis.
* **Table:** Defines the typed schema. Tables contain partitions, which contain rows, which contain columns. Can flexibly add new columns to tables with zero downtime.
* **Partition:** A group of rows saved together to a node that is also replicated to multiple nodes.
* **Replication factor:** Number of nodes in the cluster that will have copies of the same data.
* **Consistency levels:** Determines the number of replicas that need to acknowledge the read or write operation to return report to the client application. The write consistency level simply controls how many responses the coordinator waits before responding to the client, so all replicas will eventually get updated.
    * **One, Two, Three:** 1~3 replica(s) received the request.
    * **Quorum:** At least half of the replicas received the request.
* **Primary key:** Uniquely identifies a row. Consists of partition key(s) and optional clustering columns.
* **Partition key:** Group rows into the same node for optimal read/write and get hashed to distribute partitions across a cluster.
* **Composite partition key:** Uses two or more columns as partition keys to break the partition into smaller groups to improve data retrieval.
* **Clustering key:** Sorting columns used to order rows within a partition.
* **Coordinator:** A node that first receives a request that will act as a proxy between the client application and the nodes that own the data being requested.
* **Partitioner:** A hash function that derives a token from the primary key of a row. The token determines which nodes receive the replicas.
* **Gossip protocol:** Nodes periodically exchange state information about themselves and about other nodes they know about using the protocol.
* **Lightweight transactions:** Conditional update operations using `IF EXISTS` or `IF NOT EXISTS`

<h3 id="cql-syntax">CQL Syntax</h3>

* Primary key has partition key(s) first and then has optional clustering key(s).
* Columns used in the `where` clause should follow the same order as the columns defined in the primary key.
* All performant queries must include all partition key columns.

#### Keyspace Management
```sql
CREATE KEYSPACE my_keyspace
WITH replication = {'class': 'SimpleStrategy', 'replication_factor': '1'};

USE my_keyspace;
DESCRIBE KEYSPACES;
DROP KEYSPACE my_keyspace;
```

#### Table Management
```sql
CREATE TABLE my_table ( 
  partition_k1 text,
  partition_k2 text,
  clust_k int, 
  my_set set<int>,
  my_list list<int>,
  my_map map<int, text>,
  my_tuple tuple<int, int>,
  PRIMARY KEY ((partition_k1, partition_k2), clust_k)
) WITH CLUSTERING ORDER BY (clust_k DESC);

ALTER TABLE my_table ADD new_col int;
DELETE TABLE my_table;
```

#### Data CRUD Operations
```sql
-- Create
INSERT INTO my_table (partition_k1, partition_k2, clust_k)
VALUES ('par_k1', 'par_k2', 123);

-- Read
SELECT *
FROM my_table
WHERE partition_k1 = 'par_k1' AND partition_k2 = 'par_k2';

-- Update w/ TTL
UPDATE my_table
USING TTL 60
SET my_list = my_list + [1]
WHERE partition_k1 = 'par_k1' AND partition_k2 = 'par_k2' AND clust_k = 123;

-- Delete
DELETE my_list
FROM my_table
WHERE partition_k1 = 'par_k1' AND partition_k2 = 'par_k2' AND clust_k = 123;
```

#### Misc
```sql
CREATE TYPE full_name (
  first_name text,
  middle_name text,
  last_name text
);

-- Secondary index to search not using primary key
CREATE INDEX ON employee_by_id(name);

-- Timestamps
SELECT writetime(my_col) FROM my_table;

-- Execute multiple statements simultaneously
BEGIN BATCH  
-- Insert stmt;
-- Update stmt;
-- Delete stmt;
APPLY BATCH
```

<!-- <h3 id="cql-syntax">Data Modeling Examples</h3>

* expected queries to create table schema. a query-driven approach, in which specific queries are the key to organizing the data
* Consider understanding partition size limitations, cost of data consistency. partitions must be sized within certain limits. duplicate data in tables must be considered as well for resulting in performance latency during writes.
* The primary key is defined when the table is created and cannot be altered. The size of the partitions, the order of the data within partitions, the distribution of the partitions among the nodes of the cluster — you must consider all of these when selecting the table's primary key. -->

## Redis
<h3 id="fundamentals-redis">Fundamentals</h3>
Redis (REmote DIctionary Server) is a data structure server. It is a key-value in-memory store commonly used for caching as it leverages the speed of memory to complement other DBMS with data persistence, but Redis can persist data as well if needed.

<h4 id="key-features-redis">Key Features</h4>

* **RAM In-memory Datastore:** Fast data access speed for storing in RAM instead of storing on disk.
* **Data Structure Store:** Can use native data types to store data. i.e. `String`, `HashMap`, `List`, `Set`
* **Atomic Operations:** Supports transactions to execute and rollback a group of commands. Redis also uses single-threaded architecture.
* **Pub/sub:** A push-based model. Available messages are popped instantly to consumers. Does not guarantee ordered delivery.
* **Optional Persistence:** Compromise a bit on speed for disk-based durability. Use `Append-only file (AOF)` or `Snapshot` mode.

<!-- <h4 id="concepts-redis">Concepts</h4>

* **Eviction Policies:**
    * **TTL (Time-to-Live):** 
    * **LRU (Least Recently Used):** Removes the least recently accessed items.
    * **LFU (Least Frequently Used):** Removes items based on access frequency. -->

<h3 id="use-cases-redis">Use Cases</h3>

* **Caching:** Reducing database loads by storing frequently accessed data in memory.
* **Session Store:** Manage user sessions and authentication tokens, reducing overhead on DBMS.
* **Rate Limiting:** Use `EXPIRE` feature to limit number of requests to a particular service in a given time period.
* **Real-Time Analytics:** Fast read/write operations using in-memory data store.
* **Event-Driven Message Queues:** Act as a broker for real-time message delivery with its Pub/Sub features.
* **Location-Based Services:** Geospatial data structure can be used for storing and querying location data.

## MongoDB
<h3 id="fundamentals-mongodb">Fundamentals</h3>
NoSQL database storing data in a JSON-like format.

<h4 id="key-features-mongodb">Key Features</h4>

* **Optional Schema:** Often known as a schema-less db, but a schema can be added to a collection if needed.
* **Aggregation Pipelines:** Similar to SQL's `GROUP BY`. Select and process multiple documents to get computed results. Operations such as filtering, grouping, and sorting are used to create a data analysis pipeline.
* **Relationship options: Embed vs. Reference:**
    * **Embed:** Store related data in the same document (faster reads).
    * **Reference:** Store ObjectIDs to avoid redundancy (normalized like RDBMS).

<h4 id="terminologies-mongodb">Terminologies</h4>

* **Collection:** A group of documents. Similar to a table in RDBMS.
* **Document:** JSON-like basic unit of data. Will have a unique ID `_id`field and uses `BSON` format.
* **`BSON`:** The binary representation of JSON primarily used for data storage.
* **`mongosh`:** MongoDB Shell is a CLI to connect and interact with MongoDB databases.

---

# Databases - Fundamentals
## Indexing
Speeding up search queries by creating a search optimized data structure to avoid scanning the entire dataset, but will cost additional disk storage and slow down data inserts/updates/deletes.

* **Index Types**
    * **B-Tree:** Most common index using a self-balancing tree that maintains sorted data. Each node contains an ordered array of keys and pointers, structured to minimize disk reads.
    * **Geosptail index:** Location data search
    * **Hash index:** In-memory exact matching
    * **Inverted index:** Full text search

## Sharding
Splitting data into multiple servers to avoid exponential cost of vertical scaling of a single machine.

* **Sharding Types**
    * **Range-based sharding:** Using specifics data ranges or intervals to split rows, such as a range of dates, numeric values, or alphanumeric identifiers.
    * **Hash-based sharding:** Using a hash function to use the hash value as the identifier to allocate data to the appropriate shard.
    * **Directory-based sharding:** Using a lookup table to map sharding keys to shard locations.
    * **Geo-based sharding:** Using location or proximity to group data to a single shard. Essentially ranged sharding where the shard key contains geographic information and the shards themselves are geo-located.

## Normalization
Data organization to minimize data redundancy and improve data integrity by breaking down tables into smaller tables for easier database maintenance. Increasing normalization level improves data integrity, but it is not common to go above 3NF.

* **1NF - First normal form:**
    * Each row is uniquely identifiable with a primary key.
    * Each column represents unique characteristic or attribute type of the entity. i.e. For table `Product`, instead of having `Vendor1`, `Vendor2`, `Vendor3` and so on to list vendors for a product, only one `Vendor` column should be used.
    * Each cell holds a single, indivisible piece of data. i.e. Full name `John Doe` in `Name` column should be broken down into `John` and `Doe` to get saved in `First name` and `Last name` columns respectively.

* **2NF:**
Columns must be dependent on the entire primary key.

* **3NF:**
Columns must be **ONLY** dependent on the entire primary key, so columns should be independent of each other. Columns affected by a non-primary key column needs to be moved to a different table.

### vs Denormalization
In certain read-heavy applications, denormalization could be more suitable when performance and query speed are more critical than data integrity.

## Relational

* **Key:** What makes the row unique and separates from other rows. Key is a 'type of index'. Key should be:
    * Unique
    * Never changing
    * Never `Null`
    
* **Natural Key:** Unique identifier not artificially generated. i.e. email in User table. No need to have a separate col for keys.

#### Terminologies
* **Entity:** What we store. (Like object class)
* **Attribute:** Things about the entity (Like object property)
* **DBMS:** Database Management System. Allow Filter/search data using query



<!-- ## Non-relational

* A master-replica architecture

### Key-value pair
### Document-oriented
### Column-oriented
### Graph-based
### Time series -->

## SQL vs NoSQL

## ACID vs BASE transaction

* **Transaction:** A single unit of work. A sequence of one or more database operations treated as a single, indivisible unit. Must complete a transaction fully for the database to remain consistent.

|                  |       ACID        |        BASE        |
| ---------------- | ----------------- | ------------------ |
| **Priority**     | Consistency over availability | Availability & scalability over consistency |
| **Use cases**    | Financial & healthcare databases for high data integrity & data accuracy. | Social media platforms for high availability |

### ACID
* **Atomicity:** All transactions must succeed or fail completely as a unit. A transaction cannot be partially complete. Ensure data integrity and consistency by either committing all changes or rolling them back if an error occurs.
* **Consistency:** A transaction will keep data integrity by only making changes adhering to predefined constraints, rules, and relationships.
* **Isolation:** Each transaction is executed in isolation from other transactions, ensuring no interference.
* **Durability:** Changes from a committed transaction are permanent and won’t be lost.

#### Isolation Levels vs Read Phenomena
A trade-off of consistency vs performance. Higher isolation level reduces the number of concurrency effects, but increases the chances that one transaction will block another.

<table>
    <tr>
        <th>Read <ins>Phenomena→</ins><br>Isolation LVL↓</th>
        <th>Dirty read</th>
        <th>Non-repeatable read</th>
        <th>Phantom read</th>
    </tr>
    <tr>
        <td><b>Serializable</b></td>
        <td>No</td>
        <td>No</td>
        <td>No</td>
    </tr>
    <tr>
        <td><b>Repeatable read</b></td>
        <td>No</td>
        <td>No</td>
        <td>Yes</td>
    </tr>
    <tr>
        <td><b>Read committed</b></td>
        <td>No</td>
        <td>Yes</td>
        <td>Yes</td>
    </tr>
    <tr>
        <td><b>Read uncommitted</b></td>
        <td>Yes</td>
        <td>Yes</td>
        <td>Yes</td>
    </tr>
</table>

##### Read Phenomena
* <b>Dirty read: </b><br>Reading data not yet commited by another transaction.
* <b>Non-repeatable read: </b><br>Reading the same row twice returns different values because another transaction commited the row modification.
* <b>Phantom read: </b><br>Different results from the same two queries because another transaction commited a row insertion or deletion.

##### Isolation Levels
* <b>Read uncommitted: </b><br>Can read uncommited changes. The highest performance but the lowest isolation level.
* <b>Read committed: </b><br>Only allow commited data read.
* <b>Repeatable read: </b><br>Any data read during the transaction remains unchanged, even if other transactions commit changes to the data. Read and write locks acquired until the end of the transaction.
* <b>Serializable: </b><br>Execute the transaction as if it were the only transaction in the system. In addition to read and write locks, range locks acquired when using `WHERE` range clause to prevent a phantom read. The highest isolation level to prevent all anomalies.

#### Compliance Strategies

##### Write Ahead Logging
All modifications are written to a log before they are applied. Allow transactions to be reconstructed from the log in case of a crash.

##### Checkpointing
Process of saving changes in the buffer cache memory to the disk to create a checkpoint. Also uses transaction logs since the last checkpoint for a quick recovery in the event of a system crash.

##### Shadow paging
Creating a copy of the database’s page table and making all changes to the new page. Then, the new page table replaces the old one.

##### Locking
A transaction will mark the relevant data as locked, so other transactions will have to wait for the data access. This can create delays when other transactions need to access the affected data.

##### Multi-versioning
For writing, deleting, or updating transactions, creating multiple versions of the data for ACID compliance.

### BASE
* **Basically available:** High availability by distributing data across different nodes.
* **Soft state:** Intermediate states can exist before a consistent state. Data consistency handled by developers.
* **Eventually consistent:** Given enough time, all nodes will have the same data eventually.

---

# DevOps
<h2 id="terminologies-devops">Terminologies</h2>

* **DevSecOps:** Augmentation of DevOps to allow for security practices to be integrated into the DevOps approach. Making security a shared responsibility of development, security and IT operations teams, rather than the sole responsibility of a security silo.
* **Platform engineering:** A software engineering discipline focused on the development of self-service toolchains, services, and processes to create an internal developer platform (IDP).

---

# Architectural Patterns

## Distributed System

### CAP theorem
* A distributed system can prioritize only two of three desired characteristics — consistency, availability, and partition tolerance.
* The theorem really is about prioritizing consistency or availability. Partitions from a break in communication between nodes are inevitable. So can have CP and AP, but not CA.
* **Limitations:** Important to note that these properties are continuous spectrum and not strictly binary, so possible to have some levels of each property. The CAP theorem simplifies the complex trade-offs in distributed systems. 

    * **Consistency**

        **All nodes have the same data** at the same time. No divergence in the data observed by different nodes in the system.

    * **Availability**

        **Every request to the system receives a response** even if it is not the most recent data.

    * **Partition tolerance**

        **The system continues to operate from partitions** caused by break in communication between nodes.

### PACELC theorem

* Extension of CAP theorem. Theorem stating to consider Latency vs Consistency tradeoff when there is no partition.
* Acronym for: In the event of a Partition(**P**), choose Availability (**A**) or Consistency (**C**); Else (**E**) if no Partition, choose Latency (**L**) or Consistency (**C**)

### Scaling Patterns

#### Vertical vs Horizontal

|                  | Vertical Scaling  | Horizontal Scaling |
| ---------------- | ----------------- | ------------------ |
| **Description**  | Increase CPU, RAM. Scale up/down | Increase number of nodes. Scale in/out |
| **Cost**         | Low initial cost. Exponentially increasing cost | High initial cost. Optimal over time |
| **Complexity & Maintenance** | Lower  | Higher. Need to add load balancing and extra configuration.  |
| **Limitation**   | Bounded by capacity of one machine. | Bounded by time, expertise, and effort. |
| **Availability**  | Single point of failure  | Improved from increased number of nodes  |

#### Load Balancing

### Consistency Patterns

#### Strong Consistency
* All nodes have the same data at all times

#### Eventual Consistency
* Temporarily inconsistent across nodes but guarantees that all nodes will eventually converge to a consistent state


## Microservices

## Monolithic
* A traditional software development approach. A single codebase containing all the functionality that is deployed as a single unit.
* A good choice for a small team and application with little complexity. Consider refactoring into microservices if:
    * it becomes too complex.
    * performance is a problem even after scaling horizontally with load-balancing & database sharding.

### Modular Monolith

* **Improved cohesion:** Monolith divided into distinct modules with specific functionality. Each module will be independent and isolated so each module can be owned by a single team. This supports the separation of concerns, leading to a cleaner and organized codebase.

* **Middle ground of monolithic & microservices.** Provides some advantages of microservices without the complexity of distributed systems. Could serve as the foundation step of microservices. Each module could be an independent microservices candidate in the future.

* **Loose coupling:** A module is never completely independent, but dependencies with other modules should be minimal to enable teams to replace/modify modules without impacting others. To promote loose coupling, data isolation should be achieved by following options:

    - Separate table
    - Separate schema
    - Separate database
    - Different persistence

#### vs Microservices

* **Simple deployment, but no flexibility.** Deployment is the biggest difference. Modular monolith is deployed as a single unit whereas microservices allow independent deployments & scalability.
* **No tech stack flexibility.** Different technology stacks per service is possible for microservices.
* **Less latency between features:** Communication between modules occurs in-process, so no network latency or data serialization/deserialization overhead.

### Distributed Monolith
* **Antipattern.** Has the complexity of microservices without the benefits of microservices.
* Low coupling is crucial to get benefits of microservices. Not how small or how many services are there.
* Some signs of this problem:
    - Tightly coupled microservices.
    - The deployment of one service causes downtime for other services.
    - Services are overly chatty.

---

# Design Patterns

## Backends for Frontends

### Problem context
* Desktop & mobile clients can have different data requirements. One backend service being used for both desktop & mobile can become a bottleneck in the development process.

### Solution
* Create one backend per user interface. Fine-tune the behavior and performance of each backend to best match the needs of different clients.

### Benefits
* **Less Complexity -** The overall system could become less complex than a generic backend trying to satisfy all different types of clients.
* **Feature Selection Flexibility -** Each interface team has increased flexibility to prioritize features and autonomy to control their own backend.
* **Reliability Increase -** Malfunction of desktop backend service might not affect the availability of mobile backend service.
* **Performance optimization -** Custom optimization for a specific client's constraints and functionality.

### Issues and Considerations
* **Over-engineering -** Just a single backend will suffice if different clients mostly make the same requests. Building the new backends can create more technical debt.
* **Code Duplication -** Code duplication across services is highly likely without a proper planning. The new frontend-focused backend services should only contain client specific logics, and general business logics should be managed elsewhere.


<!-- ## Gateway Routing
### Problem context
* 

### Solution
* 

### Benefits
* 

### Issues and Considerations
* 

## Gatekeeper pattern
### Problem context
* 

### Solution
* 

### Benefits
* 

### Issues and Considerations
* 

## Anti-corruption Layer pattern
### Problem context
* 

### Solution
* 

### Benefits
* 

### Issues and Considerations
* 

## Sequential Convoy pattern
### Problem context
* 

### Solution
* 

### Benefits
* 

### Issues and Considerations
*  -->

## Strangler Fig pattern
### Problem context
* Migrating a monolithic application to microservices application in a single operation introduces transformation risk and business disruption. It is extremely hard or even impossible to add new features while the app is being refactored.

### Solution
* Incrementally migrate a monolithic application to a microservices architecture.

### Benefits
* **Minimal End Users Impact -** The features in the monolith are replaced by microservices gradually, and users are able to use the newly migrated features progressively. The monolithic application can be decommissioned safely when all features are moved out to the new system.

### Issues and Considerations
* **Request Interception -** The request needs to be interceptable. A proxy layer intercepts the requests that go to the monolithic application and routes them to either the legacy system or the new system.
* **Single Point of Failure -** The above proxy layer can become a single point of failure or a performance bottleneck.
* **Data synchronization -** Data consistency & redundancy issues can happen from the monolithic system having a data store and the new microservice having it's own data store as well. Sharing or updating data will likely require a synchronizing agent between the two stores for eventual consistency.
* **Complete refactoring -** For small applications, it might be more efficient to rewrite the whole application in microservices architecture instead of incrementally migrating it.

