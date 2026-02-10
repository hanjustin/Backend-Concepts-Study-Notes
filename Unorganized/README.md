

<!-- * Synchronous vs Asynchronous -->
<!-- * RabbitMQ -->

## Transport Layer
* TCP (Transmission Control Protocol): A communication protocol that ensures reliable, connection-oriented transmission of data by dividing it into smaller packets, numbering them, and reassembling them at the receiving end.
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