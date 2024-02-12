---
{"dg-publish":true,"permalink":"/600-coding/security/notes/cybersec-proxy-severs/","tags":["CyberSecurity"]}
---


# Notes
> [!definition] 
> proxy server is a server that fulfills the request of a client by forwarding them on to other servers. 
> 

The proxy server is a dedicated server that sits between the internet and the rest of the network.

![Pasted image 20240212123624.png](/img/user/104%20Attachments/Pasted%20image%2020240212123624.png)

A proxy server uses temporary memory to store data that's regularly requested by external servers. This way, it doesn't have to fetch data from an organization's internal servers every time. This enhances security by reducing contact with the internal server.

## Type of Proxy Servers
### Forward proxy server
A forward proxy server regulates and restricts a person with access to the internet. The goal is to hide a user's IP address and approve all outgoing requests. In the context of an organization, a forward proxy server receives outgoing traffic from an employee, approves it, and then forwards it on to the destination on the internet.

### Reverse  proxy server
A reverse proxy server regulates and restricts the internet access to an internal server. The goal is to accept traffic from external parties, approve it, and forward it to the internal servers. This setup is useful for protecting internal web servers containing confidential data from exposing their IP address to external parties.

### Email proxy server
An email proxy server is another valuable security tool. It filters spam email by verifying whether a sender's address was forged. This reduces the risk of phishing attacks that impersonate people known to the organization.