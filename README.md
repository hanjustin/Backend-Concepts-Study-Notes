# WIP. Study notes of backend development concepts.

* Learning concepts to get better at selecting the right tools for the job. There is no silver bullet

# Table of Contents
* [Communication](#communication)
    * Synchronous vs Asynchronous
    * [gRPC](#grpc)
    * [GraphQL](#graphql)
    * Message Broker
        * Kafka
        * RabbitMQ

* [Databases](#databases)
    * [SQL vs NoSQL](#sql-vs-nosql)
    * Relational
    * Non-relational
        * Key-value pair
        * Document-oriented
        * Column-oriented
        * Graph-based
        * Time series

* Architectural Patterns
    * Distributed System
        * [CAP theorem](#cap-theorem)
        * [PACELC theorem](#pacelc-theorem)
        * [Scaling Patterns](#scaling-patterns)
            * [Vertical vs Horizontal](#vertical-vs-horizontal)
            * Load Balancing
        * Consistency Patterns
    * Microservices
    * [Monolithic](#monolithic)
        * [Modular Monolith](#modular-monolith)
        * [Distributed Monolith](#distributed-monolith)
    * [Serverless](#serverless)

* [Design Patterns](#design-patterns)
    * Ambassador pattern
    * Anti-corruption Layer pattern
    * [Backends for Frontends](#backends-for-frontends)
    <!-- * [Gateway Routing](#gateway-routing) -->
    * Gatekeeper pattern
    * Sequential Convoy pattern
    * [Strangler Fig pattern](#strangler-fig-pattern)

* Tools
    * Microservices Orchestration
        * Kubernetes
            * vs Docker Swarm

* To-Do
    * Cloud
    * Authentication
        * JWT
        * OAuth
    * Server-side rendering
        * vs Client-side rendering
        * vs Single-page app
        * SEO
    * Monorepo vs Polyrepo Code Management

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

---

# Databases

## SQL vs NoSQL

## Relational

* ACID - Most relational DBMS are ACID compliant:
    * **Atomicity:** All transactions must succeed or fail completely as a unit. A transaction cannot be partially complete.
    * **Consistency:**
    * **Isolation:**
    * **Durability:**

## Non-relational

* A master-replica architecture

### Key-value pair
### Document-oriented
### Column-oriented
### Graph-based
### Time series

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

## Serverless

* Server management is abstracted away from app development as the cloud provider manages the server infrastructure. Automatically scale up and down as needed.
* Ideal for asynchronous, stateless apps that can be started instantaneously. Doesn’t cost anything when idle.
* Cloud provider limits the flexibility & customizability. 

  vs

  Increase developer productivity and reduce operational costs.

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