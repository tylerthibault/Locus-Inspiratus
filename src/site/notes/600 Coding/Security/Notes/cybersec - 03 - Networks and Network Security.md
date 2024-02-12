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

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-firewall/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">

<div class="markdown-embed-title">

# Firewall

</div>



# Notes
> [!definition] 
*Monitors and/or restricts incoming or outgoing traffic based on a specific set of security rules.*

A Firewall is a network security system set on the boundaries of the system/network that monitors and controls network traffic. Firewalls are mainly used to protect the system/network from viruses, worms, malware, etc. Firewalls can also be to prevent remote access and content filtering.
## Steps to set up a firewall
- [x] Study (@2024-01-24)
1. _Username/password:_ modify the default password for a firewall device
2. _Remote administration:_ Disable the feature of the remote administration
3. _Port forwarding:_ Configure appropriate port forwarding for certain applications to work properly, such as a web server or FTP server
4. _DHCP server:_ Installing a firewall on a network with an existing DHCP server will cause conflict unless the firewall’s DHCP is disabled
5. _Logging:_ To troubleshoot firewall issues or potential attacks, ensure that logging is enabled and understand how to view logs
6. _Policies:_ You should have solid security policies in place and make sure that the firewall is configured to enforce those policies.


# Memory Palace
### Linking System
U             P          R              A           P          F        D               L           P
Unicorns Prance, Rainbows Appear, Playful Frogs Dance, Laughs Prevails

> [!memory] 
> **Position 5**
> The door leading into the kids room is made out of fire. I cannot go through it or see through it. It also has an ominous eyes looking at me, watching me. Once I give them it washes me with fire and hand sanitizer. Then allows me to look into the room. 
>
>When the fire subsides I see lots of unicorn horns lining the door way like a thorn lines the stem of a rose. 
>
#memory-palace #CyberSecurity 
> 


</div></div>


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

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/100-fleeting-notes/tcp-ip-internet-layer/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




# Notes
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

### What protocols fall under TCP/IP internet layer?
| **TCP/IP** | **TCP/IP Protocol Examples** |
| ---- | ---- |
| Application | NFS, NIS+, DNS, telnet, ftp, rlogin, rsh, rcp, RIP, RDISC, SNMP and others |
| Transport | TCP, UDP |
| Internet | IP, [[100 Fleeting Notes/ARP\|ARP]], [[600 Coding/Security/Notes/cybersec - ICMP\|cybersec - ICMP]] |
| Data Link | PPP, IEEE 802.2 |
| Physical Network | Ethernet (IEEE 802.3) Token ring, RS-232, others |

# Memory Palace
> [!memory] 
> 

</div></div>



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