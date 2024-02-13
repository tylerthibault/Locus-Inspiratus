---
{"dg-publish":true,"permalink":"/600-coding/security/notes/cybersec-syn-flood-attack/","tags":["CyberSecurity"]}
---

# Notes
 > [!definition] 
 > A SYN flood attack is a type of DoS attack that simulates the TCP connection and floods the server with SYN packets.
 
 By taking a closer look at the handshake process that is used to establish a TCP connection between a device and a server. The first step in the handshake is for the device to send a SYN, or synchronize, request to the server. Then, the server responds with a SYN/ACK packet to acknowledge the receipt of the device's request and leaves a port open for the final step of the handshake. Once the server receives the final ACK packet from the device, a TCP connection is established. Malicious actors can take advantage of the protocol by flooding a server with SYN packet requests for the first part of the handshake. But if the number of SYN requests is larger than the number of available ports on the server, then the server will be overwhelmed and become unable to function.

