# WIP. Study notes of backend development concepts.

# Table of Contents
* [APIs](#apis)
    * [gRPC](#grpc)
    * [GraphQL](#graphql)
* [Design Patterns](#design-patterns)
    * [Backends for Frontends](#backends-for-frontends)
    <!-- * [Gateway Routing](#gateway-routing) -->
    * Gatekeeper pattern
    * Anti-corruption Layer pattern
    * Sequential Convoy pattern
    * [Strangler Fig pattern](#strangler-fig-pattern)

* Architectural Patterns
    * Monolithic
    * Microservices
    * [Serverless](#serverless)
* [Databases - SQL vs NoSQL](#databases---sql-vs-nosql)
    * Relational
    * Non-relational
        * Key-value pair
        * Document-oriented
        * Column-oriented
        * Graph-based
        * Time series
* Authentication
    * JWT
    * OAuth
* MISC
    * Distributed & CAP

## APIs

### gRPC

* Platform agnostic serialization protocol that is used to communicate between services.
* Protocol Buffer (Protobuf). `.proto` file format is commonly used to define messages sent between clients and servers for communication between two different languages. Generates code used for the client/server communication.

### GraphQL

* In client/server communication, clients can control the response data format. In REST, server controls the data format. Distinct clients (web, iOS, etc.) can have different data requirements.
* GraphQL schema file `*.graphqls` contains all information about what a client can potentially do with a GraphQL API.
* A single endpoint can be used to receive requests with GraphQL queries.
* As clients can request exact data wanted, could be used to avoid REST API's over-fetching & under-fetching problems.

## Design Patterns

### Backends for Frontends

#### Problem context
* Desktop & mobile clients can have different data requirements. One backend service being used for both desktop & mobile can become a bottleneck in the development process.

#### Solution
* Create one backend per user interface. Fine-tune the behavior and performance of each backend to best match the needs of different clients.

#### Benefits
* The overall system could become less complex than a generic backend trying to satisfy all different types of clients.
* Each interface team has increased flexibility to prioritize features and autonomy to control their own backend.
* Potentially increase reliability. Malfunction of desktop backend service might not affect the availability of mobile backend service.
* Can optimize performance for a specific client's constraints and functionality.

#### Issues and Considerations
* Code duplication across services is highly likely.
* If different clients mostly make the same requests, building the new backends can create more technical debt, so just a single backend will suffice.
* The new frontend-focused backend services should only contain client specific logics, and general business logics should be managed elsewhere.


### Gateway Routing
#### Problem context
* 

#### Solution
* 

#### Benefits
* 

#### Issues and Considerations
* 

### Gatekeeper pattern
#### Problem context
* 

#### Solution
* 

#### Benefits
* 

#### Issues and Considerations
* 

### Anti-corruption Layer pattern
#### Problem context
* 

#### Solution
* 

#### Benefits
* 

#### Issues and Considerations
* 

### Sequential Convoy pattern
#### Problem context
* 

#### Solution
* 

#### Benefits
* 

#### Issues and Considerations
* 

### Strangler Fig pattern
#### Problem context
* Migrating a monolithic application to microservices application in a single operation introduces transformation risk and business disruption. It is extremely hard or even impossible to add new features while the app is being refactored.

#### Solution
* Migrate a monolithic application to a microservices architecture incrementally

#### Benefits
* The features in the monolith are replaced by microservices gradually, and users are able to use the newly migrated features progressively. End users are minimally impacted during the transformation.
* The monolithic application can be decommissioned safely when all features are moved out to the new system.

#### Issues and Considerations
* 

## Databases - SQL vs NoSQL

### Relational

* ACID - Atomicity, Consistency, Isolation, and Durability.
    * Most relational DBMS are ACID compliant

### Non-relational

#### Key-value pair
#### Document-oriented
#### Column-oriented
#### Graph-based
#### Time series


## Architectural Patterns

### Monolithic

### Microservices

### Serverless

* Server management is abstracted away from app development as the cloud provider manages the server infrastructure. Automatically scale up and down as needed.
* Ideal for asynchronous, stateless apps that can be started instantaneously. Doesn’t cost anything when idle.
* Cloud provider limits the flexibility & customizability. 

  vs

  Increase developer productivity and reduce operational costs.
