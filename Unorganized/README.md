TCP 3-Way Handshake

-----
* **DNS:** The phonebook of the internet translating human-readable domain names (e.g., example.com) into machine-readable IP addresses (e.g., 192.0.2.1).
* **Routing:** Finding the best physical path for the data to reach its destination.

* **MAC (Media Access Control) address:**

* **TCP** is commonly used where all data must be intact (e.g. file share), whereas UDP is used when retaining all packets is less critical (e.g. video streaming). Transmission Control Protocol (TCP), a near-lossless connection-based protocol, and the User Datagram Protocol (UDP), a lossy connectionless protocol
-----

WAN vs LAN
IPv4, IPv6

1. Network Types
Local Area Network (LAN)
Wide Area Network (WAN)
Metropolitan Area Network (MAN)
Wireless Networks (Wi-Fi)
2. IP Addressing
IPv4 Addresses
IPv6 Addresses
Public vs. Private Addresses
Static vs. Dynamic IP Addressing
3. Network Protocols
TCP/IP Protocol Suite
UDP (User Datagram Protocol)
HTTP/HTTPS (HyperText Transfer Protocol/Secure)
FTP (File Transfer Protocol)
DNS (Domain Name System)
4. Hardware Components
Routers
Switches
Hubs
Access Points
5. Data Transmission
Packet Switching
Circuit Switching
Bandwidth and Latency
Data Encoding

8. Network Topologies
Star Topology
Bus Topology
Ring Topology
Mesh Topology

## Transport Layer
* TCP (Transmission Control Protocol): A communication protocol that ensures reliable, connection-oriented transmission of data by dividing it into smaller packets, numbering them, and reassembling them at the receiving end. Splits data into packets and correctly reassembles them at the destination.
    * 3-way handshake
* UDP (User Datagram Protocol): Faster than TCP, but doesn't guarantee delivery or order of packets.

## Application Layer
* HTTP: Built on TCP/IP
* WebSockets: Real time updates two way communication channel. a communication protocol that provides full-duplex, real-time, and bidirectional communication between a client and a server over a single, long-lived connection.WebSockets can be used in applications such as chat systems or real-time collaboration tools, where instant and continuous data exchange between clients and servers is required.

## Email related protocols
* SMTP: Email transmission across the internet.
* IMAP (Internet Message Access Protocol): Used to retrieve emails from a server.
* POP3: Used for downloading emails from a server. Typically when emails are accessed by only one device.

ACID: a set of properties that ensure reliability and integrity in database transactions, guaranteeing that they are executed reliably, consistently, and without interference.

* FTP: For transfering files over the internet.

## Real-time communication
* **WebRTC:** Enables browser-to-browser applications for voice calling, video chat, and file sharing.
* **MQTT (Message Queuing Telemetry Transport):** Lightweight messaging protocol. For devices w/ low processing power.
* **AMQP (Advanced Message Queuing Protocol):** Protocol for message-oriented middleware. For enterprise level communication with robust security.
* **RPC (Remote Procedure Call):** Invoking function on another server as if. Abstracts network communication to allow developers to interact code on a remote server as if it were local.


<!-- * To-Do
    * Authentication
        * JWT
        * OAuth
    * Server-side rendering
        * vs Client-side rendering
        * vs Single-page app
        * SEO
    * Monorepo vs Polyrepo Code Management -->

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

<!-- * Synchronous vs Asynchronous -->
<!-- * RabbitMQ -->

---

Tools:
* **Postman:** API testing tool. Unlike `cURL` which has a CLI, Postman has a GUI to simplify creating and managing API requests.