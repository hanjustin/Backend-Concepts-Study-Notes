# WIP. Study notes of backend development concepts.

* Learning concepts to get better at selecting the right tools for the job.

# Table of Contents
* [APIs](#apis)
    * [gRPC](#grpc)
    * [GraphQL](#graphql)

* [Design Patterns](#design-patterns)
    * Ambassador pattern
    * Anti-corruption Layer pattern
    * [Backends for Frontends](#backends-for-frontends)
    <!-- * [Gateway Routing](#gateway-routing) -->
    * Gatekeeper pattern
    * Sequential Convoy pattern
    * [Strangler Fig pattern](#strangler-fig-pattern)

* Architectural Patterns
    * [Monolithic](#monolithic)
    * Distributed System
        * CAP theorem
    * Distributed Monolith
    * Microservices
    * [Serverless](#serverless)

* [Databases](#databases)
    * [SQL vs NoSQL](#sql-vs-nosql)
    * Relational
        
    * Non-relational
        * Key-value pair
        * Document-oriented
        * Column-oriented
        * Graph-based
        * Time series

* Tools
    * Microservices Orchestration
        * Kubernetes
            * vs Docker Swarm
    * Message Queue Systems
        * Kafka
        * RabbitMQ

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

# APIs

## gRPC

* Platform agnostic serialization protocol that is used to communicate between services.
* Protocol Buffer (Protobuf). `.proto` file format is commonly used to define messages sent between clients and servers for communication between two different languages. Generates code used for the client/server communication.

## GraphQL

* In client/server communication, clients can control the response data format. In REST, server controls the data format. Distinct clients (web, iOS, etc.) can have different data requirements.
* GraphQL schema file `*.graphqls` contains all information about what a client can potentially do with a GraphQL API.
* A single endpoint can be used to receive requests with GraphQL queries.
* As clients can request exact data wanted, could be used to avoid REST API's over-fetching & under-fetching problems.

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


## Gateway Routing
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
* 

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

## Monolithic
* 

* Pros
    * 

* Cons
    * 

## Distributed System
### CAP theorem

## Distributed Monolith

## Microservices
* 

* Pros
    * 

* Cons
    * 

## Serverless

* Server management is abstracted away from app development as the cloud provider manages the server infrastructure. Automatically scale up and down as needed.
* Ideal for asynchronous, stateless apps that can be started instantaneously. Doesn’t cost anything when idle.
* Cloud provider limits the flexibility & customizability. 

  vs

  Increase developer productivity and reduce operational costs.
