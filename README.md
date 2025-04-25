
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
                    <li><b>Fundamentals</b></li>
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
                                    <li>Concept3 - WIP</li>
                                </ul></ul></ul></ul>
                            <li><a href="#terminologies-postgresql"><b>Terminologies</b></a></li>
                                <ul><ul><ul><ul>
                                    <li>
                                        <b><ins>P</ins></b>rimary key,
                                        <b><ins>C</ins></b>omposite primary key,
                                        <b><ins>F</ins></b>oreign key,
                                        <b><ins>V</ins></b>iew,
                                        <b><ins>M</ins></b>aterialized view,
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
            <!-- <li><details><summary>Cassandra</summary>
                <ul>
                    <li><a href="#fundamentals-cassandra"><b>Fundamentals</b></a></li>
                        <ul>
                            <li><a href="#concepts-cassandra"><b>Concepts</b></a></li>
                                <ul><ul><ul><ul>
                                    <li>TO DO - Empty</li>
                                    <li>TO DO - Empty</li>
                                </ul></ul></ul></ul>
                            <li><a href="#terminologies-cassandra"><b>Terminologies</b></a></li>
                                <ul><ul><ul><ul>
                                    <li>TO DO - Empty</li>
                                    <li>TO DO - Empty</li>
                                </ul></ul></ul></ul>
                        </ul>
                </ul>
            </details>
            </li> -->
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
    <!-- * **[Indexes](#indexes)** -->
    * **[Normalization](#normalization)**
        * 1NF, 2NF, 3NF, 4NF, 5NF
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

* Architectural Patterns
    * Distributed System
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
    * [Serverless](#serverless)

* [Design Patterns](#design-patterns)
    <!-- * Ambassador pattern
    * Anti-corruption Layer pattern -->
    * [Backends for Frontends](#backends-for-frontends)
    <!-- * [Gateway Routing](#gateway-routing) -->
    <!-- * Gatekeeper pattern
    * Sequential Convoy pattern -->
    * [Strangler Fig pattern](#strangler-fig-pattern)

* Tools
    <!-- * Microservices Orchestration
        * Kubernetes
            * vs Docker Swarm -->

<!-- * To-Do
    * Cloud
    * Authentication
        * JWT
        * OAuth
    * Server-side rendering
        * vs Client-side rendering
        * vs Single-page app
        * SEO
    * Monorepo vs Polyrepo Code Management -->

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
* Like a post office between a sender and receiver(s). Allows real-time data streaming and processing.
* Often used as a message broker, allowing different software systems to communicate by sending (producing) and receiving (consuming) messages.
* Can be used as a pub-sub and queue based messaging system.

### Fundamentals
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

* **Primary key:**
* **Composite primary key:**
* **Foreign key:** Create relationship by referencing the primary key in another table.
* **View:**
* **Materialized view:**
* **Aggregate function:** Perform a calculation on a set of rows and return a single row
* **Window function:** Perform a calculation on a set of rows and return multiple rows.

<h3 id="tools-postgresql">Tools</h3>

* **psql:** CLI tool to enter SQL queries or commands to PostgreSQL database. Commands start with backslash `\`.
* **pgAdmin:** GUI tool to manage PostgreSQL database.

<h3 id="sql-syntax">SQL Syntax</h3>

#### Database Management
* Define and modify database structure

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
* Retrieve and manage data

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

<h4 id="concepts-cassandra">Concepts</h4>

<h4 id="terminologies-cassandra">Terminologies</h4>

* **CQL:** SQL like query language for Cassandra.
* **Term2:** Term2

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

## Indexes
Speeds up data retrieval at the cost of additional storage, more RAM usage, and slower inserts/updates/deletes.

by creating a pointer to data.

They are created on columns that are frequently searched or used in queries.

## Normalization
Data organization to improve data integrity by breaking down tables into smaller ones to minimize data redundancy.


<h3>1NF - First normal form</h3>
Using row to convey information, not having primary key field, or mixing data types in a column violates 1NF.
Storing a repeating group of data items on a single row violates 1NF.

### 2NF
Each non-key attribute must depend on the entire primary key.

### 3NF
Every attribute in a table should depend on the key, the whole key, and nothing but the key.

### 4NF
### 5NF

### vs Denormalization

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