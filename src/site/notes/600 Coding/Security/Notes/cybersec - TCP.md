---
{"tags":["CyberSecurity"],"template":"[[CyberSec Template]]","dg-publish":true,"permalink":"/600-coding/security/notes/cybersec-tcp/","dgPassFrontmatter":true}
---

# Notes
> [!definition] 
>  **Transmission Control Protocol (TCP)** is a protocol of the Internet protocol suite that provides reliable data transfer services between different devices over network. It is a connection-oriented protocol that work sin tandem with the internet protocol (IP) to ensure that messages are exchanged between devices in a reliable manner. *TCP breaks down data into small bundles* and *reassembles them at the other end*, providing *error control, flow control, and congestion control*. In summary TCP is a protocol that helps in the exchange of message between different devices over network, ensuring reliable delivery of data and messages. 


Transmission Control Protocol (TCP) is an internet communication protocol that allows two devices to form a connection and stream data. TCP uses a *three-way handshake process*. 
1. First, the device sends a synchronize (SYN) request to a server. 
2. Then the server responds with a SYN/ACK packet to acknowledge receipt of the device's request. 
3. Once the server receives the final ACK packet from the device, a TCP connection is established. 
In the TCP/IP model, TCP occurs at the **transport layer**.

# Memory Palace
> [!memory] 
> Right as "[[100 Fleeting Notes/cybersec - UDP\|cybersec - UDP]]" goes to hit TCP, TCP contacts Scotty on the Enterprise and has him beam him up. TCP's particles gets broken down into small pieces and reassembled on the ship. 
