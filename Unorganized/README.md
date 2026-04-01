
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

* **JWT (JSON Web Token):** 

---
# Proxy
Servers that sit between clients and servers to improve security, privacy and performance. Think of proxy server as a middleman that sits between a private network and the public internet. A Proxy acts on behalf of clients; a Reverse Proxy acts on behalf of servers.

* **Forward proxy:** Acts on behalf of clients. When you send a request, like opening a webpage, the proxy intercepts it, forwards it to the target server, and then relays the server’s response back to you.
    * a server that sits between user devices and the internet.
    * Used for:
        * Privacy and Anonymity: Proxy servers hide your IP address by using their own, so the destination server cannot know your real location or identity.
        * Access Control: Organizations use proxies to enforce content restrictions, monitor internet usage.
        * Security: Proxies can filter out malicious content and block suspicious sites, providing an additional layer of security.
        * Improved Performance: Proxies cache frequently accessed content, reducing latency and improving load times for websites.
    * Simplified steps:
        1. The proxy server intercepts request from the client.
        2. The proxy examines the request to decide if it should forward it, deny it, or serve a cached copy.
        3. If the proxy forwards the request, the server only sees the proxy server's IP address.
        4. The proxy receives the response from the server and relays it to the client.
* **Reverse Proxy:** Acts on behalf of servers. a server that accepts a request from the client, forwards the request to web servers, and returns the results to the client as if the proxy server had processed the request. It regulates traffic coming into a network.
    * Point of entry that filters and regulates incoming traffic all while keeping server IP addresses hidden.
    * Used for:
        * Enhanced Security: By acting as a protective layer, a reverse proxy hides backend servers from clients, reducing the risk of attacks directly targeting backend infrastructure.
        * Load Balancing: A reverse proxy can distribute incoming requests evenly across multiple backend servers, improving system reliability and preventing server overload.
        * Caching Static Content: Reverse proxies can cache static assets like images, CSS, and JavaScript, reducing the need to fetch these files from the backend repeatedly.
        * SSL Termination: Reverse proxies can handle SSL encryption, offloading this work from backend servers.
        * Web Application Firewall (WAF): Reverse proxies can inspect incoming requests, acting as a firewall to detect and block malicious traffic.
    * Simplified steps:
        1. The reverse proxy server receives the request and forwards it to the appropriate backend server.
        2. The backend server processes the request and sends a response back to the reverse proxy.
        3. The reverse proxy relays the response to the client, with the client never directly interacting with the backend servers.
    * Cloudflare:
        Cloudflare’s reverse proxy is widely used by global websites and applications to boost speed, security, and reliability.

        It’s Web Application Firewall (WAF) and DDoS protection blocks malicious traffic before it reaches the site’s servers, safeguarding against attacks and improving uptime.

        Cloudflare’s global content caching caches static and dynamic content at over 200 data centers around the world, storing frequently accessed files (like images, CSS, and JavaScript) closer to users. This significantly reduces load times and latency, as requests don’t always need to travel to the origin server.

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