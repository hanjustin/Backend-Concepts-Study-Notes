
Subnet
netmask

* Network packet
    * Routing header
        * Source & destination IP address.
    * data payload

---
# AuthN

* **Factor:** Element used to verify a user’s identity.
* **2FA (Two-Factor Authentication):**
* **MFA (Multi-Factor Authentication):**


---
# Proxy
Servers that sit between clients and servers to improve security, privacy and performance. Think of proxy server as a middleman that sits between a private network and the public internet.
* **Forward proxy:** Acts on behalf of clients. When you send a request, like opening a webpage, the proxy intercepts it, forwards it to the target server, and then relays the server’s response back to you.
    * a server that sits between user devices and the internet.
    * Used for:
        * Protect clients
        * Avoid browsing restrictions
        * Block access to certain content
* **Reverse Proxy:** Acts on behalf of servers. a server that accepts a request from the client, forwards the request to web servers, and returns the results to the client as if the proxy server had processed the request.
    * Used for:
        * Protect servers
        * Load balancing
        * Cache static contents
        * Encrypt and decrypt SSL communications

---
# IP

* **IP masking:** hiding true IP address and replacing it with a different one.

---
* Databases
    * Migrations
    * N + 1 problem
    * Federation
    * SQL Tuning

* Security
    * Authorization
    * Authentication
        * JWT
        * OAuth
* Server-side rendering
    * vs Client-side rendering
    * vs Single-page app
    * SEO
* System Design
    * Availability Patterns
        * Replication - Master & Slave
        * Fail-Over - Active & Passive
    * Scale problems mitigation strategies
        * Graceful Degradation
        * Throttling
        * Backpressure
        * Loadshifting
        * Circuit Breaker
    * CDN
        * Pull CDNs
        * Push CDNs
    * Load Balancer
        * LB vs Reverse Proxy
        * Algorithms
        * Layer 7 & Layer 4 LB
    * Service Discovery
    * Caching
        * Refresh Ahead
        * Write-behind
        * Write-through
        * Cache Aside
    * Asynchronism
        * Back Pressure
        * Task Queues
        * Message Queues
    * Performance Antipatterns
    * Cloud Design Patterns
        * Data Management
        * Messaging
    * Reliability Patterns
        * Resiliency
        * Availability
        * Security
            * Federated Identity
            * Gatekeeper
            * Valet Key


---

Tools:
* **Postman:** API testing tool. Unlike `cURL` which has a CLI, Postman has a GUI to simplify creating and managing API requests.