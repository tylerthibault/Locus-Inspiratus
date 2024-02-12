---
{"dg-publish":true,"permalink":"/600-coding/security/notes/cybersec-03-networks-and-network-security/","tags":["CyberSecurity"]}
---


# Module 1
- [ ] #task #memory-work  Add network components
## Network Components
### Hubs and Switches
Both direct traffic on a local network. 
#### Hub
*A network device that broadcasts information to every device on the network*
IE: a radio tower broadcasting a signal
#### Switch
*A device that makes connections between specific devices on a network by sending and receiving data between them*
### Router
> [!definition] 
*A network device that connects multiple networks together*
### Modem
> [!definition] 
*A device that connects your router to the internet and brings internet access to the LAN*

Modems receive transmissions from the internet and translate them into digital signals that can be understood by the devices on the network
![Pasted image 20240206230338.png](/img/user/104%20Attachments/Pasted%20image%2020240206230338.png)
### Firewalls
> [!definition] 
*Monitors and/or restricts incoming or outgoing traffic based on a specific set of security rules.*
### Servers 
> [!definition] 
*Provide services for other devices on the network.* 

client-server model
![Pasted image 20240206230052.png](/img/user/104%20Attachments/Pasted%20image%2020240206230052.png)

### Wireless access point
> [!definition] 
*A wireless access point sends and receives digital signals over radio waves creating a wireless network.*

![Pasted image 20240206230418.png](/img/user/104%20Attachments/Pasted%20image%2020240206230418.png)

## Cloud Computing
> [!definition] 
> The practice of using remote servers, applications, and network services that are hosted on the internet instead of on local physical devices. 


## Cloud Network
> [!definition] 
> A collection of servers of computers that stores resources and data in remote data centers that can be accessed via the internet. 




## TCP/IP
> [!definition] 
> Transmission Control Protocol
> An internet communication protocol that allows two devices to form a connection and stream data

TCP/IP has 4 layers
1. Network access layer
	Hubs, modems, cables and wiring are all considered part of this layer. ARP is part of this layer as well. 
2. Internet layer
	Is responsible for ensuring the delivery to the destination host, which potentially resides on a different network.
3. Transport Layer
	   The transport layer is responsible for delivering data between two systems
4. Application Layer
	   The application layer is responsible for making network requests or responding to requests. Similar to the OSI model. Some common protocols used on this layer are: 
	- Hypertext transfer protocol (HTTP)
	- Simple mail transfer protocol (SMTP)
	- Secure shell (SSH)
	- File transfer protocol (FTP)
	- Domain name system (DNS)

![Pasted image 20240207090157.png](/img/user/104%20Attachments/Pasted%20image%2020240207090157.png)


### IP
> [!definition] 
> Internet Protocol
> A set of standards used for routing and addressing data packets as they travel between devices on a network

Two versions
IPV4
IPV6

#### Headers
headers contain more than just the address of the destination. It also includes information such as the source IP address, the size of the packet, and which protocol will be used for the data portion of the packet. 

### Port 
> [!definition] 
> a software-based location that organizes the sending and receiving of data between devices on a network

common port numbers 
- 25 email
- 443 https
- 20 large file transfer

# Module 2
### TCP 