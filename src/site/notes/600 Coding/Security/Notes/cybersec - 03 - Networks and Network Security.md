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

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-firewall-setup/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




1. _Username/password:_ modify the default password for a firewall device
2. _Remote administration:_ Disable the feature of the remote administration
3. _Port forwarding:_ Configure appropriate port forwarding for certain applications to work properly, such as a web server or FTP server
4. _DHCP server:_ Installing a firewall on a network with an existing DHCP server will cause conflict unless the firewall’s DHCP is disabled
5. _Logging:_ To troubleshoot firewall issues or potential attacks, ensure that logging is enabled and understand how to view logs
6. _Policies:_ You should have solid security policies in place and make sure that the firewall is configured to enforce those policies.

</div></div>


# Types of Firewalls

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-firewall-types/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




A firewall is a network security device that monitors traffic to and from your network. It either allows traffic or it blocks it based on a defined set of security rules. 
## Locations
### Hardware
A hardware firewall is a physical device that inspects each data packet before it's allowed to enter the network.  These tend to cost more than the software version. 
### Software
A software firewall is some software that inspects each data packet before it's allowed to enter the network. These cost less than the hardware version but they use up some of the processing of the device they are located on. 
### Cloud-based
Also known as FaaS or Firewall as a service. Cloud-based firewalls are software firewalls hosted by a cloud service provider. Organizations can configure the firewall rules on the cloud service provider's interface, and the firewall will perform security operations on all incoming traffic before it reaches the organization’s onsite network. 
## States
The terms "stateful" and "stateless" refer to how the firewall operates
### Stateless
Stateless refers to a class of firewall that operates based on predefined rules and does not keep track of information from data packets.
### Stateful
Stateful refers to a class of firewall that keeps track of information passing through it and proactively filters out threats. 

## NGFW Firewalls

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-ngfw/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> NGFW - Next Gen Firewall
> Not only does an NGFW provide stateful inspection of incoming and outgoing traffic, but it also performs more in-depth security functions like deep packet inspection and intrusion protection.






</div></div>


</div></div>


# Firewall Hardening
![[cybersec - firewall - hardening\|cybersec - firewall - hardening]]
# Memory Palace

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-firewall-memory/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




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

</div></div>



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
| Internet | IP, [[100 Fleeting Notes/cybersec - ARP\|cybersec - ARP]], [[600 Coding/Security/Notes/cybersec - ICMP\|cybersec - ICMP]] |
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
## Network Protocols

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-network-protocols/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> a set of rules used by two or more devices on a network to describe the order of delivery and the structure of data.
## Communication Protocols
- [[600 Coding/Security/Notes/cybersec - TCP\|cybersec - TCP]]
- [[100 Fleeting Notes/cybersec - UDP\|cybersec - UDP]]
- [[600 Coding/Security/Notes/cybersec - HTTP\|cybersec - HTTP]]
- [[600 Coding/Security/Notes/cybersec - DNS\|cybersec - DNS]]
## Management Protocols
- [[600 Coding/Security/Notes/cybersec - SNMP\|cybersec - SNMP]]
- [[600 Coding/Security/Notes/cybersec - ICMP\|cybersec - ICMP]]
## Security Protocols
- [[600 Coding/Security/Notes/cybersec - HTTPS\|cybersec - HTTPS]]
- [[600 Coding/Security/Notes/cybersec - SFTP\|cybersec - SFTP]]
## Side - Topics

Internet Assigned Numbers Authority ([[600 Coding/Security/Notes/cybersec - IANA\|IANA]])
Network Address Translation ([[600 Coding/Security/Notes/cybersec - NAT\|NAT]])
[[600 Coding/Security/Notes/cybersec - DHCP\|cybersec - DHCP]]
[[100 Fleeting Notes/cybersec - ARP\|cybersec - ARP]]
[[600 Coding/Security/Notes/cybersec - Telnet\|cybersec - Telnet]]

|**Protocol**|**Port**|
|---|---|
|DHCP|UDP port 67 (servers)<br><br>UDP port 68 (clients)|
|ARP|none|
|Telnet|TCP port 23|
|SSH|TCP port 22|
|POP3|TCP/UDP port 110 (unencrypted)<br><br>TCP/UDP port 995 (encrypted, SSL/TLS)|
|IMAP|TCP port 143 (unencrypted)<br><br>TCP port 993 (encrypted, SSL/TLS)|
|SMTP|TCP/UDP port 587 (encrypted, TLS)|

</div></div>
 

## IEEE 802.11

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-ieee-802-11/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> IEEE 802.11 is a set of standards that define communications for wireless LANs. IEEE stands for the Institute of Electrical and Electronics Engineers, which is an organization that maintains Wi-Fi standards, and 802.11 is a suite of protocols used in wireless communications. **IEEE 802.11 is commonly known as *WIFI***

Many people today refer to wireless internet as Wi-Fi. Wi-Fi refers to a set of standards that define communication for wireless LANs. Wi-Fi is a marketing term commissioned by the Wireless Ethernet Compatibility Alliance (WECA). WECA has since renamed their organization Wi-Fi Alliance. 

Wi-Fi standards and protocols are based on the 802.11 family of internet communication standards determined by the Institute of Electrical and Electronics Engineers (IEEE). So, as a security analyst, you might also see Wi-Fi referred to as IEEE 802.11.

Wi-Fi communications are secured by wireless networking protocols. Wireless security protocols have evolved over the years, helping to identify and resolve vulnerabilities with more advanced wireless technologies.

### Wi-Fi Protected Access

Wi-Fi Protected Access (WPA) was developed in 2003 to improve upon WEP, address the security issues that it presented, and replace it. WPA was always intended to be a transitional measure so backwards compatibility could be established with older hardware.

The flaws with WEP were in the protocol itself and how the encryption was used. WPA addressed this weakness by using a protocol called Temporal Key Integrity Protocol (TKIP). WPA encryption algorithm uses larger secret keys than WEPs, making it more difficult to guess the key by trial and error.

WPA also includes a message integrity check that includes a message authentication tag with each transmission. If a malicious actor attempts to alter the transmission in any way or resend at another time, WPA’s message integrity check will identify the attack and reject the transmission.

Despite the security improvements of WPA, it still has vulnerabilities. Malicious actors can use a key reinstallation attack (or KRACK attack) to decrypt transmissions using WPA. *Attackers can insert themselves in the WPA authentication handshake process and insert a new encryption key instead of the dynamic one assigned by WPA.* If they set the new key to all zeros, it is as if the transmission is not encrypted at all.

Because of this significant vulnerability, WPA was replaced with an updated version of the protocol called WPA2.

### WPA2 & WPA3

#### WPA2

The second version of Wi-Fi Protected Access—known as WPA2—was released in 2004. WPA2 improves upon WPA by using the Advanced Encryption Standard (AES). WPA2 also improves upon WPA’s use of TKIP. WPA2 uses the Counter Mode Cipher Block Chain Message Authentication Code Protocol (CCMP), which provides encapsulation and ensures message authentication and integrity. Because of the strength of WPA2, it is considered the security standard for all Wi-Fi transmissions today. WPA2, like its predecessor, is vulnerable to KRACK attacks. This led to the development of WPA3 in 2018. 

#### Personal

WPA2 personal mode is best suited for home networks for a variety of reasons. It is easy to implement, initial setup takes less time for personal than enterprise version. *The global passphrase for WPA2 personal version needs to be applied to each individual computer and access point in a network*. This makes it ideal for home networks, but unmanageable for organizations. 
#### Enterprise
WPA2 enterprise mode works best for business applications. It provides the necessary security for wireless networks in business settings. The initial setup is more complicated than WPA2 personal mode, but enterprise mode offers individualized and centralized control over the Wi-Fi access to a business network. This means that network administrators can grant or remove user access to a network at any time. *Users never have access to encryption keys*, this prevents potential attackers from recovering network keys on individual computers.

#### WPA3
WPA3 is a secure Wi-Fi protocol and is growing in usage as more WPA3 compatible devices are released. These are the key differences between WPA2 and WPA3:

- WPA3 addresses the authentication handshake vulnerability to KRACK attacks, which is present in WPA2. 
- WPA3 uses Simultaneous Authentication of Equals (SAE), a password-authenticated, cipher-key-sharing agreement. This prevents attackers from downloading data from wireless network connections to their systems to attempt to decode it.
- WPA3 has increased encryption to make passwords more secure  by using 128-bit encryption, with WPA3-Enterprise mode offering optional 192-bit encryption.

</div></div>


## Firewalls

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-firewall/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




# Notes
> [!definition] 
*Monitors and/or restricts incoming or outgoing traffic based on a specific set of security rules.*

A Firewall is a network security system set on the boundaries of the system/network that monitors and controls network traffic. Firewalls are mainly used to protect the system/network from viruses, worms, malware, etc. Firewalls can also be to prevent remote access and content filtering.
## Steps to set up a firewall

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-firewall-setup/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




1. _Username/password:_ modify the default password for a firewall device
2. _Remote administration:_ Disable the feature of the remote administration
3. _Port forwarding:_ Configure appropriate port forwarding for certain applications to work properly, such as a web server or FTP server
4. _DHCP server:_ Installing a firewall on a network with an existing DHCP server will cause conflict unless the firewall’s DHCP is disabled
5. _Logging:_ To troubleshoot firewall issues or potential attacks, ensure that logging is enabled and understand how to view logs
6. _Policies:_ You should have solid security policies in place and make sure that the firewall is configured to enforce those policies.

</div></div>


# Types of Firewalls

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-firewall-types/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




A firewall is a network security device that monitors traffic to and from your network. It either allows traffic or it blocks it based on a defined set of security rules. 
## Locations
### Hardware
A hardware firewall is a physical device that inspects each data packet before it's allowed to enter the network.  These tend to cost more than the software version. 
### Software
A software firewall is some software that inspects each data packet before it's allowed to enter the network. These cost less than the hardware version but they use up some of the processing of the device they are located on. 
### Cloud-based
Also known as FaaS or Firewall as a service. Cloud-based firewalls are software firewalls hosted by a cloud service provider. Organizations can configure the firewall rules on the cloud service provider's interface, and the firewall will perform security operations on all incoming traffic before it reaches the organization’s onsite network. 
## States
The terms "stateful" and "stateless" refer to how the firewall operates
### Stateless
Stateless refers to a class of firewall that operates based on predefined rules and does not keep track of information from data packets.
### Stateful
Stateful refers to a class of firewall that keeps track of information passing through it and proactively filters out threats. 

## NGFW Firewalls

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-ngfw/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> NGFW - Next Gen Firewall
> Not only does an NGFW provide stateful inspection of incoming and outgoing traffic, but it also performs more in-depth security functions like deep packet inspection and intrusion protection.






</div></div>


</div></div>


# Firewall Hardening
![[cybersec - firewall - hardening\|cybersec - firewall - hardening]]
# Memory Palace

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-firewall-memory/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




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

</div></div>



</div></div>


## VPN

<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">






> [!definition] 
> Almost all Cybersecurity Interview Questions will have this question included. **VPN** stands for **Virtual Private Network**. It is *used to create a safe and encrypted connection*. When you use a VPN, 
> 1. the data from the client is sent to a point in the VPN where it is encrypted and then sent through the internet to another point. 
> 2. At this point, the data is decrypted and sent to the server. 
> 3. When the server sends a response, the response is sent to a point in the VPN where it is encrypted and this encrypted data is sent to another point in the VPN where it is decrypted. 
> 4. And finally, the decrypted data is sent to the client. The whole point of using a VPN is to ensure encrypted data transfer.


<style> .container {font-family: sans-serif; text-align: center;} .button-wrapper button {z-index: 1;height: 40px; width: 100px; margin: 10px;padding: 5px;} .excalidraw .App-menu_top .buttonList { display: flex;} .excalidraw-wrapper { height: 800px; margin: 50px; position: relative;} :root[dir="ltr"] .excalidraw .layer-ui__wrapper .zen-mode-transition.App-menu_bottom--transition-left {transform: none;} </style><script src="https://cdn.jsdelivr.net/npm/react@17/umd/react.production.min.js"></script><script src="https://cdn.jsdelivr.net/npm/react-dom@17/umd/react-dom.production.min.js"></script><script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@excalidraw/excalidraw@0/dist/excalidraw.production.min.js"></script><div id="Drawing_2024-01-21_1036.11.excalidraw.md1"></div><script>(function(){const InitialData={"type":"excalidraw","version":2,"source":"https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/1.9.28","elements":[{"type":"rectangle","version":171,"versionNonce":762104420,"isDeleted":false,"id":"alV_sSzkhK1axLo0GHkNv","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-665.323754010124,"y":30.915457637327563,"strokeColor":"#1e1e1e","backgroundColor":"#96f2d7","width":323.1578947368419,"height":196.84210526315783,"seed":1809723492,"groupIds":[],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858576580,"link":null,"locked":false},{"type":"text","version":104,"versionNonce":2041437668,"isDeleted":false,"id":"DRPkXM2p","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-646.3265808056124,"y":70.5996681636434,"strokeColor":"#1e1e1e","backgroundColor":"#96f2d7","width":108.25993347167969,"height":25,"seed":1895990244,"groupIds":[],"frameId":null,"roundness":null,"boundElements":[{"id":"6BWE-GNqctIVsna_N7nN8","type":"arrow"}],"updated":1705858576580,"link":null,"locked":false,"fontSize":20,"fontFamily":1,"text":"User Data","rawText":"User Data","textAlign":"left","verticalAlign":"top","containerId":null,"originalText":"User Data","lineHeight":1.25,"baseline":18},{"type":"text","version":78,"versionNonce":842183908,"isDeleted":false,"id":"1OhWbM0p","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-657.0634229108755,"y":-0.6634897310932502,"strokeColor":"#1e1e1e","backgroundColor":"#96f2d7","width":143.35986328125,"height":25,"seed":89155428,"groupIds":[],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858576580,"link":null,"locked":false,"fontSize":20,"fontFamily":1,"text":"User Computer","rawText":"User Computer","textAlign":"left","verticalAlign":"top","containerId":null,"originalText":"User Computer","lineHeight":1.25,"baseline":18},{"type":"text","version":284,"versionNonce":1934784612,"isDeleted":false,"id":"2w37kR0u","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-500.22131764771757,"y":117.7586326714819,"strokeColor":"#1e1e1e","backgroundColor":"#96f2d7","width":125.84602355957031,"height":26.087912066977374,"seed":756407012,"groupIds":[],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858576580,"link":null,"locked":false,"fontSize":20.870329653581898,"fontFamily":1,"text":"VPN program","rawText":"VPN program","textAlign":"left","verticalAlign":"top","containerId":null,"originalText":"VPN program","lineHeight":1.25,"baseline":18},{"type":"arrow","version":190,"versionNonce":1040577116,"isDeleted":false,"id":"6BWE-GNqctIVsna_N7nN8","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-529.6950018582438,"y":82.4944050057486,"strokeColor":"#1e1e1e","backgroundColor":"#96f2d7","width":170.5263157894736,"height":72.63157894736844,"seed":853597796,"groupIds":[],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858576620,"link":null,"locked":false,"startBinding":{"elementId":"DRPkXM2p","focus":0.427544154437022,"gap":8.371645475688865},"endBinding":null,"lastCommittedPoint":null,"startArrowhead":null,"endArrowhead":"arrow","points":[[0,0],[90.52631578947364,-13.684210526315837],[-79.99999999999997,55.78947368421052],[11.57894736842104,58.9473684210526]]},{"type":"arrow","version":429,"versionNonce":1269014500,"isDeleted":false,"id":"0s9nhQnCDWYlJnPW73qsv","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-308.37857752118884,"y":32.80312631065135,"strokeColor":"#1e1e1e","backgroundColor":"#96f2d7","width":129.03445285592733,"height":49.8525809540256,"seed":1602187748,"groupIds":[],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858588577,"link":null,"locked":false,"startBinding":{"elementId":"EONaciGJZ1Ax7nwRS624o","focus":0.06250023671291878,"gap":17.95762611619068},"endBinding":{"elementId":"uH6dRps4IT4rdaki95Qz8","focus":0.6632218716671767,"gap":14.044753116646291},"lastCommittedPoint":null,"startArrowhead":null,"endArrowhead":"arrow","points":[[0,0],[129.03445285592733,-49.8525809540256]]},{"type":"arrow","version":334,"versionNonce":637346396,"isDeleted":false,"id":"Ipw_1fYR01C6uH5F5oRFE","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":199.89251453475245,"y":-18.513934744955918,"strokeColor":"#1e1e1e","backgroundColor":"#96f2d7","width":142.11782515139808,"height":40.479374441963046,"seed":397363428,"groupIds":[],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858585573,"link":null,"locked":false,"startBinding":{"elementId":"uH6dRps4IT4rdaki95Qz8","focus":-0.6485599927905719,"gap":20.91460808918879},"endBinding":null,"lastCommittedPoint":null,"startArrowhead":null,"endArrowhead":"arrow","points":[[0,0],[142.11782515139808,40.479374441963046]]},{"type":"rectangle","version":214,"versionNonce":1296480740,"isDeleted":false,"id":"Dd0oLlE8ZDB4Ons903HQX","fillStyle":"solid","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":392.2741159812279,"y":19.482066189247007,"strokeColor":"#1e1e1e","backgroundColor":"transparent","width":102.91666666666652,"height":144.08333333333323,"seed":605850724,"groupIds":["_n5BL8sR6fXH4ntAMR24O"],"frameId":null,"roundness":{"type":3},"boundElements":[],"updated":1705858576580,"link":null,"locked":false},{"type":"line","version":260,"versionNonce":2006834532,"isDeleted":false,"id":"vt1h7z87t9A84_mALJuVV","fillStyle":"solid","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":396.01654022365204,"y":62.51994497712576,"strokeColor":"#1e1e1e","backgroundColor":"transparent","width":91.68939393939388,"height":11.227272727272723,"seed":1226137572,"groupIds":["_n5BL8sR6fXH4ntAMR24O"],"frameId":null,"roundness":{"type":2},"boundElements":[],"updated":1705858576580,"link":null,"locked":false,"startBinding":null,"endBinding":null,"lastCommittedPoint":null,"startArrowhead":null,"endArrowhead":null,"points":[[0,0],[46.78030303030299,11.227272727272723],[91.68939393939388,0]]},{"type":"line","version":280,"versionNonce":574918884,"isDeleted":false,"id":"XhAEBnV76qtQU58yiH4vn","fillStyle":"solid","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":396.01654022365204,"y":84.03888437106536,"strokeColor":"#1e1e1e","backgroundColor":"transparent","width":91.68939393939388,"height":11.227272727272723,"seed":245875556,"groupIds":["_n5BL8sR6fXH4ntAMR24O"],"frameId":null,"roundness":{"type":2},"boundElements":[],"updated":1705858576580,"link":null,"locked":false,"startBinding":null,"endBinding":null,"lastCommittedPoint":null,"startArrowhead":null,"endArrowhead":null,"points":[[0,0],[46.78030303030299,11.227272727272723],[91.68939393939388,0]]},{"type":"line","version":270,"versionNonce":1019794532,"isDeleted":false,"id":"7WhYBMY7RtsaLc5PKxgDE","fillStyle":"solid","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":396.01654022365204,"y":101.81539952258049,"strokeColor":"#1e1e1e","backgroundColor":"transparent","width":91.68939393939388,"height":11.227272727272723,"seed":1260500708,"groupIds":["_n5BL8sR6fXH4ntAMR24O"],"frameId":null,"roundness":{"type":2},"boundElements":[],"updated":1705858576580,"link":null,"locked":false,"startBinding":null,"endBinding":null,"lastCommittedPoint":null,"startArrowhead":null,"endArrowhead":null,"points":[[0,0],[46.78030303030299,11.227272727272723],[91.68939393939388,0]]},{"type":"line","version":287,"versionNonce":351840228,"isDeleted":false,"id":"GfHM4N_fAJ1GAswyDwCgR","fillStyle":"solid","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":396.01654022365204,"y":122.39873285591386,"strokeColor":"#1e1e1e","backgroundColor":"transparent","width":91.68939393939388,"height":11.227272727272723,"seed":1527855716,"groupIds":["_n5BL8sR6fXH4ntAMR24O"],"frameId":null,"roundness":{"type":2},"boundElements":[],"updated":1705858576580,"link":null,"locked":false,"startBinding":null,"endBinding":null,"lastCommittedPoint":null,"startArrowhead":null,"endArrowhead":null,"points":[[0,0],[46.78030303030299,11.227272727272723],[91.68939393939388,0]]},{"type":"line","version":310,"versionNonce":249695076,"isDeleted":false,"id":"LfaA7B8m7hV_falX-Spya","fillStyle":"solid","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":396.01654022365204,"y":138.30403588621687,"strokeColor":"#1e1e1e","backgroundColor":"transparent","width":91.68939393939388,"height":11.227272727272723,"seed":1497648612,"groupIds":["_n5BL8sR6fXH4ntAMR24O"],"frameId":null,"roundness":{"type":2},"boundElements":[],"updated":1705858576580,"link":null,"locked":false,"startBinding":null,"endBinding":null,"lastCommittedPoint":null,"startArrowhead":null,"endArrowhead":null,"points":[[0,0],[46.78030303030299,11.227272727272723],[91.68939393939388,0]]},{"type":"line","version":271,"versionNonce":1557331684,"isDeleted":false,"id":"zVt5REZA3ut6_qw9yaLTa","fillStyle":"solid","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":396.01654022365204,"y":43.80782376500474,"strokeColor":"#1e1e1e","backgroundColor":"transparent","width":91.68939393939388,"height":11.227272727272723,"seed":1456009572,"groupIds":["_n5BL8sR6fXH4ntAMR24O"],"frameId":null,"roundness":{"type":2},"boundElements":[],"updated":1705858576580,"link":null,"locked":false,"startBinding":null,"endBinding":null,"lastCommittedPoint":null,"startArrowhead":null,"endArrowhead":null,"points":[[0,0],[46.78030303030299,11.227272727272723],[91.68939393939388,0]]},{"type":"text","version":354,"versionNonce":928612964,"isDeleted":false,"id":"8lrkpum6","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":514.9713980530928,"y":39.89051838378123,"strokeColor":"#1e1e1e","backgroundColor":"#96f2d7","width":193.85235595703125,"height":100.52631578947356,"seed":317531364,"groupIds":["Uf8Jibjc7zenP_mfgWLzv"],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858576580,"link":null,"locked":false,"fontSize":40.21052631578942,"fontFamily":1,"text":"Internet \nWebserver","rawText":"Internet \nWebserver","textAlign":"left","verticalAlign":"top","containerId":null,"originalText":"Internet \nWebserver","lineHeight":1.25,"baseline":85},{"type":"arrow","version":198,"versionNonce":2041134556,"isDeleted":false,"id":"W_cpTAf-RhwFG3mjNf5S6","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":343.39966735676245,"y":112.02846803788054,"strokeColor":"#1e1e1e","backgroundColor":"transparent","width":157.2015771097432,"height":84.79008978831223,"seed":859760740,"groupIds":[],"frameId":null,"roundness":{"type":2},"boundElements":[],"updated":1705858585573,"link":null,"locked":false,"startBinding":null,"endBinding":{"elementId":"uH6dRps4IT4rdaki95Qz8","focus":0.630747221997994,"gap":7.220183801455562},"lastCommittedPoint":null,"startArrowhead":null,"endArrowhead":"arrow","points":[[0,0],[-157.2015771097432,84.79008978831223]]},{"type":"arrow","version":313,"versionNonce":442841948,"isDeleted":false,"id":"hjegvG8mCv6w18NE7w4qc","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-185.5260627830885,"y":203.19200089795794,"strokeColor":"#1e1e1e","backgroundColor":"transparent","width":141.8235981353182,"height":0.12368794686926776,"seed":1533880804,"groupIds":[],"frameId":null,"roundness":{"type":2},"boundElements":[],"updated":1705858585573,"link":null,"locked":false,"startBinding":{"elementId":"uH6dRps4IT4rdaki95Qz8","focus":-0.48306152824977894,"gap":20.226691234473265},"endBinding":{"elementId":"WW654fOAvxkJNcvrhI9m6","focus":-0.31719850262923494,"gap":22.575090279936717},"lastCommittedPoint":null,"startArrowhead":null,"endArrowhead":"arrow","points":[[0,0],[-141.8235981353182,0.12368794686926776]]},{"type":"rectangle","version":156,"versionNonce":1350228708,"isDeleted":false,"id":"WW654fOAvxkJNcvrhI9m6","fillStyle":"solid","strokeWidth":0.5,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-474.7921577247296,"y":166.56274894716114,"strokeColor":"#1e1e1e","backgroundColor":"#a5d8ff","width":124.86740652638616,"height":107.92111564066226,"seed":1467370852,"groupIds":["lZ3r42A6ufypMUrg9a_kR"],"frameId":null,"roundness":null,"boundElements":[{"id":"hjegvG8mCv6w18NE7w4qc","type":"arrow"}],"updated":1705858576580,"link":null,"locked":false},{"type":"text","version":629,"versionNonce":765751780,"isDeleted":false,"id":"6A0yPJPY","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-465.7323389069586,"y":198.5985750996491,"strokeColor":"#1e1e1e","backgroundColor":"#96f2d7","width":112.77345275878906,"height":77.63157894736848,"seed":1301217508,"groupIds":["lZ3r42A6ufypMUrg9a_kR"],"frameId":null,"roundness":null,"boundElements":[{"id":"hjegvG8mCv6w18NE7w4qc","type":"arrow"}],"updated":1705858576580,"link":null,"locked":false,"fontSize":12.421052631578958,"fontFamily":1,"text":"Gets the \nEncrypted package\nand decrypts it \nso the client can\nsee it","rawText":"Gets the \nEncrypted package\nand decrypts it \nso the client can\nsee it","textAlign":"left","verticalAlign":"top","containerId":null,"originalText":"Gets the \nEncrypted package\nand decrypts it \nso the client can\nsee it","lineHeight":1.25,"baseline":72},{"type":"text","version":558,"versionNonce":1938068836,"isDeleted":false,"id":"3hf4QlZa","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-462.8821098152803,"y":165.6632697979395,"strokeColor":"#1e1e1e","backgroundColor":"#96f2d7","width":77.75993347167969,"height":25,"seed":1967473764,"groupIds":["lZ3r42A6ufypMUrg9a_kR"],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858576580,"link":null,"locked":false,"fontSize":20,"fontFamily":1,"text":"Incoming","rawText":"Incoming","textAlign":"left","verticalAlign":"top","containerId":null,"originalText":"Incoming","lineHeight":1.25,"baseline":18},{"type":"rectangle","version":525,"versionNonce":1620330724,"isDeleted":false,"id":"EONaciGJZ1Ax7nwRS624o","fillStyle":"solid","strokeWidth":0.5,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-421.36123512461904,"y":11.164236948888629,"strokeColor":"#1e1e1e","backgroundColor":"#a5d8ff","width":95.02503148723952,"height":86.18549367447301,"seed":1684477924,"groupIds":["18dXtI_oFxo7qtQbUYXq_"],"frameId":null,"roundness":null,"boundElements":[{"id":"0s9nhQnCDWYlJnPW73qsv","type":"arrow"}],"updated":1705858576580,"link":null,"locked":false},{"type":"text","version":545,"versionNonce":1555718116,"isDeleted":false,"id":"OiX4JaiK","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-415.2117168634029,"y":36.90225721716979,"strokeColor":"#1e1e1e","backgroundColor":"#96f2d7","width":83.82244873046875,"height":62.10526315789479,"seed":1191344996,"groupIds":["18dXtI_oFxo7qtQbUYXq_"],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858576580,"link":null,"locked":false,"fontSize":12.421052631578958,"fontFamily":1,"text":"Encrypts the \ncontent and \nthe address \nlocation","rawText":"Encrypts the \ncontent and \nthe address \nlocation","textAlign":"left","verticalAlign":"top","containerId":null,"originalText":"Encrypts the \ncontent and \nthe address \nlocation","lineHeight":1.25,"baseline":57},{"type":"text","version":563,"versionNonce":1705821028,"isDeleted":false,"id":"djZs3cHQ","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-415.2117168634029,"y":12.276455033182174,"strokeColor":"#1e1e1e","backgroundColor":"#96f2d7","width":82.01991271972656,"height":25,"seed":392523492,"groupIds":["18dXtI_oFxo7qtQbUYXq_"],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858576580,"link":null,"locked":false,"fontSize":20,"fontFamily":1,"text":"Outgoing","rawText":"Outgoing","textAlign":"left","verticalAlign":"top","containerId":null,"originalText":"Outgoing","lineHeight":1.25,"baseline":18},{"type":"rectangle","version":121,"versionNonce":233166180,"isDeleted":false,"id":"uH6dRps4IT4rdaki95Qz8","fillStyle":"solid","strokeWidth":0.5,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-165.29937154861523,"y":-117.71452904701755,"strokeColor":"#1e1e1e","backgroundColor":"#b2f2bb","width":344.2772779941789,"height":432.5763726092662,"seed":2144693476,"groupIds":["lf4x0-8fYU2bE3EhRkBKm"],"frameId":null,"roundness":null,"boundElements":[{"id":"W_cpTAf-RhwFG3mjNf5S6","type":"arrow"},{"id":"Ipw_1fYR01C6uH5F5oRFE","type":"arrow"},{"id":"hjegvG8mCv6w18NE7w4qc","type":"arrow"},{"id":"0s9nhQnCDWYlJnPW73qsv","type":"arrow"}],"updated":1705858588216,"link":null,"locked":false},{"type":"text","version":530,"versionNonce":425553884,"isDeleted":false,"id":"Vi4DrElW","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-92.47570361262984,"y":-25.102086222321986,"strokeColor":"#1e1e1e","backgroundColor":"#96f2d7","width":181.41867065429688,"height":46.57894736842109,"seed":838833508,"groupIds":["pnUkVtYdqWCyAhvNzeSuH","lf4x0-8fYU2bE3EhRkBKm"],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858585573,"link":null,"locked":false,"fontSize":12.421052631578958,"fontFamily":1,"text":"Decrypts the information so \nthat it knows where to send \nthe data","rawText":"Decrypts the information so \nthat it knows where to send \nthe data","textAlign":"left","verticalAlign":"top","containerId":null,"originalText":"Decrypts the information so \nthat it knows where to send \nthe data","lineHeight":1.25,"baseline":41},{"type":"text","version":193,"versionNonce":1683690588,"isDeleted":false,"id":"pzjU92Vp","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-98.5971415972096,"y":71.02486806493698,"strokeColor":"#1e1e1e","backgroundColor":"#96f2d7","width":217.4154052734375,"height":50.26315789473678,"seed":2072787940,"groupIds":["1OrN-sN7ssiZQNT9DSpQw","lf4x0-8fYU2bE3EhRkBKm"],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858585573,"link":null,"locked":false,"fontSize":40.21052631578942,"fontFamily":1,"text":"VPN Server","rawText":"VPN Server","textAlign":"left","verticalAlign":"top","containerId":null,"originalText":"VPN Server","lineHeight":1.25,"baseline":35},{"type":"text","version":92,"versionNonce":959457500,"isDeleted":false,"id":"caIz6oSP","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-147.5519097529807,"y":-64.19501326739669,"strokeColor":"#1e1e1e","backgroundColor":"transparent","width":59.67994689941406,"height":25,"seed":98770788,"groupIds":["lf4x0-8fYU2bE3EhRkBKm"],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858585573,"link":null,"locked":false,"fontSize":20,"fontFamily":1,"text":"Step 1","rawText":"Step 1","textAlign":"left","verticalAlign":"top","containerId":null,"originalText":"Step 1","lineHeight":1.25,"baseline":18},{"type":"text","version":132,"versionNonce":1265544540,"isDeleted":false,"id":"zozHjm8w","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":94.94809024701925,"y":165.8049867326033,"strokeColor":"#1e1e1e","backgroundColor":"transparent","width":68.49993896484375,"height":25,"seed":2056360676,"groupIds":["lf4x0-8fYU2bE3EhRkBKm"],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858585573,"link":null,"locked":false,"fontSize":20,"fontFamily":1,"text":"Step 2","rawText":"Step 2","textAlign":"left","verticalAlign":"top","containerId":null,"originalText":"Step 2","lineHeight":1.25,"baseline":18},{"type":"text","version":617,"versionNonce":208183772,"isDeleted":false,"id":"iC8XeUX0","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-92.47570361262984,"y":199.897913777678,"strokeColor":"#1e1e1e","backgroundColor":"#96f2d7","width":256.8327941894531,"height":31.052631578947395,"seed":1210422884,"groupIds":["sbfcqCr1OZHlnsCyMGm_e","lf4x0-8fYU2bE3EhRkBKm"],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858585573,"link":null,"locked":false,"fontSize":12.421052631578958,"fontFamily":1,"text":"Encrypts the information before sending it\nback to the host computer","rawText":"Encrypts the information before sending it\nback to the host computer","textAlign":"left","verticalAlign":"top","containerId":null,"originalText":"Encrypts the information before sending it\nback to the host computer","lineHeight":1.25,"baseline":26},{"type":"line","version":95,"versionNonce":1932527196,"isDeleted":false,"id":"f6RIM6ajrLaMu_d6YBnDi","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":-153.70454094259367,"y":91.88433190798764,"strokeColor":"#1e1e1e","backgroundColor":"#b2f2bb","width":48.16314251732035,"height":0,"seed":1444803172,"groupIds":["lf4x0-8fYU2bE3EhRkBKm"],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858585573,"link":null,"locked":false,"startBinding":null,"endBinding":null,"lastCommittedPoint":null,"startArrowhead":null,"endArrowhead":null,"points":[[0,0],[48.16314251732035,0]]},{"type":"line","version":113,"versionNonce":1150737116,"isDeleted":false,"id":"22paKmsuowQEnUNBsQfQD","fillStyle":"solid","strokeWidth":4,"strokeStyle":"solid","roughness":1,"opacity":100,"angle":0,"x":125.46330364854106,"y":96.34388214107298,"strokeColor":"#1e1e1e","backgroundColor":"#b2f2bb","width":40.1359520977669,"height":0.891910046617113,"seed":1106904548,"groupIds":["lf4x0-8fYU2bE3EhRkBKm"],"frameId":null,"roundness":null,"boundElements":[],"updated":1705858585573,"link":null,"locked":false,"startBinding":null,"endBinding":null,"lastCommittedPoint":null,"startArrowhead":null,"endArrowhead":null,"points":[[0,0],[40.1359520977669,-0.891910046617113]]}],"appState":{"theme":"light","viewBackgroundColor":"#ffffff","currentItemStrokeColor":"#1e1e1e","currentItemBackgroundColor":"transparent","currentItemFillStyle":"solid","currentItemStrokeWidth":2,"currentItemStrokeStyle":"solid","currentItemRoughness":1,"currentItemOpacity":100,"currentItemFontFamily":1,"currentItemFontSize":20,"currentItemTextAlign":"left","currentItemStartArrowhead":null,"currentItemEndArrowhead":"arrow","scrollX":822.25,"scrollY":400.2578125,"zoom":{"value":1},"currentItemRoundness":"round","gridSize":null,"gridColor":{"Bold":"#C9C9C9FF","Regular":"#EDEDEDFF"},"currentStrokeOptions":null,"previousGridSize":null,"frameRendering":{"enabled":true,"clip":true,"name":true,"outline":true}},"files":{}};InitialData.scrollToContent=true;App=()=>{const e=React.useRef(null),t=React.useRef(null),[n,i]=React.useState({width:void 0,height:void 0});return React.useEffect(()=>{i({width:t.current.getBoundingClientRect().width,height:t.current.getBoundingClientRect().height});const e=()=>{i({width:t.current.getBoundingClientRect().width,height:t.current.getBoundingClientRect().height})};return window.addEventListener("resize",e),()=>window.removeEventListener("resize",e)},[t]),React.createElement(React.Fragment,null,React.createElement("div",{className:"excalidraw-wrapper",ref:t},React.createElement(ExcalidrawLib.Excalidraw,{ref:e,width:n.width,height:n.height,initialData:InitialData,viewModeEnabled:!0,zenModeEnabled:!0,gridModeEnabled:!1})))},excalidrawWrapper=document.getElementById("Drawing_2024-01-21_1036.11.excalidraw.md1");ReactDOM.render(React.createElement(App),excalidrawWrapper);})();</script>


VPN uses Encapsulation
**VPN Encapsulation**: A process performed by a VPN service that protects your data by wrapping sensitive data in other data packets.
# Port
Port 500


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-vpn-protocols/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> 




</div></div>


</div></div>


## Security Zone

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-security-zone/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> Security zones are a segment of a network that protects the internal network from the internet. They are a part of a security technique called network segmentation that divides the network into segments. Each network segment has its own access permissions and security rules. Security zones control who can access different segments of a network. Security zones act as a barrier to internal networks, maintain privacy within corporate groups, and prevent issues from spreading to the whole network.


## Types of Security Zones
### Uncontrolled Zone
<mark class="hltr-yellow">Any network outside of the organization's control</mark>

### Controlled Zone
<mark class="hltr-yellow">A subnet that protects the internal network from the uncontrolled zone</mark>

![Pasted image 20240212122641.png](/img/user/104%20Attachments/Pasted%20image%2020240212122641.png)
#### DMZ
On the outer layer is the demilitarized zone, or [[600 Coding/Security/Notes/cybersec - DMZ\|DMZ]], which contains public-facing services that can access the internet. This includes web servers, proxy servers that host websites for the public, and DNS servers that provide IP addresses for internet users.

#### Restricted Zone
The restricted zone protects highly confidential information that is only accessible to employees with certain privileges.




</div></div>


## Subnetting 

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-subnetting/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> **Subnetting** is the subdivision of a network into logical groups called subnets. It works like a network inside a network.

Subnetting divides up a network address range into smaller subnets within the network. These smaller subnets form based on the IP addresses and network mask of the devices on the network. Subnetting creates a network of devices to function as their own network. This makes the network more efficient and can also be used to create security zones. If devices on the same subnet communicate with each other, the switch changes the transmissions to stay on the same subnet, improving speed and efficiency of the communications.

</div></div>

## Proxy Servers

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-proxy-severs/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





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

</div></div>




## VPN protocols

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-vpn-protocols/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> 




</div></div>



# Module 3
<mark class="hltr-yellow">Network Intrusion Tactics</mark>

## Network Interception Attacks

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-network-interception-attacks/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> Network interception attacks work by intercepting network traffic and stealing valuable information or interfering with the transmission in some way.

Malicious actors can use hardware or software tools to capture and inspect data in transit. This is referred to as [[600 Coding/Security/Notes/cybersec - packet sniffing\|packet sniffing]]. In addition to seeing information that they are not entitled to, malicious actors can also intercept network traffic and alter it. These attacks can cause damage to an organization’s network by inserting malicious code modifications or altering the message and interrupting network operations. For example, an attacker can intercept a bank transfer and change the account receiving the funds to one that the attacker controls.


</div></div>


## Backdoor Attacks

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-backdoor-attacks/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> backdoors are weaknesses intentionally left by programmers or system and network administrators that bypass normal access control mechanisms

A **backdoor attack** is another type of attack you will need to be aware of as a security analyst. An organization may have a lot of security measures in place, including cameras, biometric scans and access codes to keep employees from entering and exiting without being seen. However, an employee might work around the security measures by finding a backdoor to the building that is not as heavily monitored, allowing them to sneak out for the afternoon without being seen. 

In cybersecurity, backdoors are weaknesses intentionally left by programmers or system and network administrators that bypass normal access control mechanisms. <mark class="hltr-orange">Backdoors are intended to help programmers conduct troubleshooting or administrative tasks.</mark> However, backdoors can also be installed by attackers after they’ve compromised an organization to ensure they have persistent access.

Once the hacker has entered an insecure network through a backdoor, they can cause extensive damage: installing malware, performing a denial of service (DoS) attack, stealing private information or changing other security settings that leaves the system vulnerable to other attacks. A **DoS attack** is an attack that targets a network or server and floods it with network traffic.

</div></div>


## Possible impacts on an organization

As you’ve learned already, network attacks can have a significant negative impact on an organization. Let’s examine some potential consequences.

- **Financial**: When a system is taken offline with a DoS attack, or business operations are halted or slowed down by some other tactic, they prevent a company from performing the tasks that generate revenue. Depending on the size of an organization, interrupted operations can cost millions of dollars. In addition, if a malicious actor gets access to the personal information of the company’s clients or customers, the company may face heavy litigation and settlement costs if customers seek legal recourse.
    
- **Reputation**: Attacks can also have a negative impact on the reputation of an organization. If it becomes public knowledge that a company has experienced a cyber attack, the public may become concerned about the security practices of the organization. They may stop trusting the company with their personal information and choose a competitor to fulfill their needs.
    
- **Public safety**: If an attack occurs on a government network, this can potentially impact the safety and welfare of the citizens of a country. In recent years, defense agencies across the globe are investing heavily in combating cyber warfare tactics. If a malicious actor gained access to a power grid, a public water system, or even a military defense communication system, the public could face physical harm due to a network intrusion attack.
    

## Key takeaways

Malicious actors are constantly looking for ways to exploit systems. They learn about new vulnerabilities as they arise and attempt to exploit every vulnerability in a system. Attackers leverage backdoor attack methods and network interception attacks to gain sensitive information they can use to exploit an organization or cause serious damage. These types of attacks can impact an organization financially, damage its reputation, and potentially put the public in danger.  It is important that security analysts stay educated in order to maintain network safety and reduce the likelihood and impact of these types of attacks. Securing networks has never been more important.


## The Thee C's
1. Command
2. Control 
3. Communication
## DDOS Attack

<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">






> [!definition] 
DDoS stands for Distributed Denial of Service. It's a type of cyberattack in which multiple compromised computers or devices are used to flood a target system with a massive volume of traffic, causing it to become unavailable or slow down significantly.

A type of denial of service attack that uses multiple devices or servers in different locations to flood the target network with unwanted traffic. #google-cyber 

# Network Level Dos Attacks
## SYN Flood Attack

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-syn-flood-attack/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




# Notes
 > [!definition] 
 > A SYN flood attack is a type of DoS attack that simulates the TCP connection and floods the server with SYN packets.
 
 By taking a closer look at the handshake process that is used to establish a TCP connection between a device and a server. The first step in the handshake is for the device to send a SYN, or synchronize, request to the server. Then, the server responds with a SYN/ACK packet to acknowledge the receipt of the device's request and leaves a port open for the final step of the handshake. Once the server receives the final ACK packet from the device, a TCP connection is established. Malicious actors can take advantage of the protocol by flooding a server with SYN packet requests for the first part of the handshake. But if the number of SYN requests is larger than the number of available ports on the server, then the server will be overwhelmed and become unable to function.



</div></div>

 

## ICMP Flood Attack
This attack takes advantage of the protocol [[600 Coding/Security/Notes/cybersec - ICMP\|ICMP]]. 


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-icmp-flood-attack/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> Type of DoS attack performed by an attacker repeatedly sending ICMP packets to a network server.

An ICMP flood attack is a type of DoS attack performed by an attacker repeatedly sending ICMP packets to a network server. This forces the server to send an ICMP packet. This eventually uses up all the bandwidth for incoming and outgoing traffic and causes the server to crash. 

</div></div>



Both of the attacks, SYN flood and ICMP flood, take advantage of communication protocols by sending an overwhelming number of requests. 

## Ping of Death

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-ping-of-death/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




# Notes
> [!definition] 
> A ping of death attack is a type of DoS attack that is caused when a hacker pings a system by sending it an oversized ICMP packet that is bigger than 64 kilobytes, the maximum size for a correctly formed ICMP packet.

Pinging a vulnerable network server with an oversized ICMP packet will overload the system and cause it to crash. Think of this like dropping a rock on a small anthill. Each individual ant can carry a certain amount of weight while transporting food to and from the anthill. But if a large rock is dropped on the anthill, then many ants will be crushed, and the colony is unable to function until it rebuilds its operations elsewhere.



</div></div>



</div></div>


## Read tcpdump Logs

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-tcpdump/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




# Notes
> [!definition] 
> **tcpdump** is a command-line network protocol analyzer.

## tcpdump
**tcpdump** is a command-line network protocol analyzer. It is popular, lightweight–meaning it uses little memory and has a low CPU usage–and uses the open-source libpcap library. tcpdump is text based, meaning all commands in tcpdump are executed in the terminal. It can also be installed on other Unix-based operating systems, such as macOS®. It is preinstalled on many Linux distributions.

tcpdump provides a brief packet analysis and converts key information about network traffic into formats easily read by humans. It prints information about each packet directly into your terminal. tcpdump also displays the source IP address, destination IP addresses, and the port numbers being used in the communications.
## Interpreting output

tcpdump prints the output of the command as the sniffed packets in the command line, and optionally to a log file, after a command is executed. The output of a packet capture contains many pieces of important information about the network traffic.

![Pasted image 20240212152526.png](/img/user/104%20Attachments/Pasted%20image%2020240212152526.png)
Some information you receive from a packet capture includes: 

- **Timestamp**: The output begins with the timestamp, formatted as hours, minutes, seconds, and fractions of a second.  
- **Source IP**: The packet’s origin is provided by its source IP address.
- **Source port**: This port number is where the packet originated.
- **Destination IP**: The destination IP address is where the packet is being transmitted to.
- **Destination port**: This port number is where the packet is being transmitted to.

**Note:** By default, tcpdump will attempt to resolve host addresses to hostnames. It'll also replace port numbers with commonly associated services that use these ports.
## Common uses

tcpdump and other network protocol analyzers are commonly used to capture and view network communications and to collect statistics about the network, such as troubleshooting network performance issues. They can also be used to:

- Establish a baseline for network traffic patterns and network utilization metrics.
- Detect and identify malicious traffic
- Create customized alerts to send the right notifications when network issues or security threats arise.
- Locate unauthorized instant messaging (IM), traffic, or wireless access points.

However, attackers can also use network protocol analyzers maliciously to gain information about a specific network. For example, attackers can capture data packets that contain sensitive information, such as account usernames and passwords. As a cybersecurity analyst, It’s important to understand the purpose and uses of network protocol analyzers.

</div></div>


## Assignment
[Cybersecurity incident report network traffic analysis - Google Docs](https://docs.google.com/document/d/1az18kzjRsD9M95sifZydxS5sneyhLZ4lNRwVsO4wZZc/edit#heading=h.rkogpw759h9x)
Answers: [The Exemplar Explained - Cybersecurity Incident Report: Network Traffic Analysis - Google Docs](https://docs.google.com/document/d/19kE466MVHdIRk86EOkUFvbepahRIMMIu5lDDgCBkg0E/template/preview#heading=h.rkogpw759h9x)

## Packet Sniffing

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-packet-sniffing/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> Packet sniffing is the practice of using software tools to observe data as it moves across a network. Malicious actors can use hardware or software tools to capture and inspect data in transit

Malicious packet sniffing can be prevented. Let's look at a few ways the network security professional can prevent these attacks. 
1. One way to protect against malicious packet sniffing is to <mark class="hltr-yellow">use a VPN</mark> to encrypt and protect data as it travels across the network. If you don't remember how VPNs work, you can revisit the video about this topic in the previous section of the program. When you use a VPN, hackers might interfere with your traffic, but they won't be able to decode it to read it and read your private information. 
2. Another way to add a layer of protection against packet sniffing is to <mark class="hltr-yellow">make sure that websites you have use HTTPS</mark> at the beginning of the domain address. Previously, we discussed how HTTPS uses SSL/TLS to encrypt data and prevent eavesdropping when malicious actors spy on network transmissions. 
3. One final way to help protect yourself against malicious packet sniffing is to <mark class="hltr-yellow">avoid using unprotected WiFi</mark>. You usually find unprotected WiFi in public places like coffee shops, restaurants, or airports. These networks don't use encryption. This means that anyone on the network can access all of the data traveling to and from your device. One precaution you can take is avoiding free public WiFi unless you have a VPN service already installed on your device.


</div></div>



## IP Spoofing

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-ip-spoofing/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




# Notes
> [!definition] 
> IP spoofing is a network attack performed when an attacker changes the source IP of a data packet to impersonate an authorized system and gain access to a network.

In this kind of attack, the hacker is pretending to be someone they are not so they can communicate over the network with the target computer and get past firewall rules that may prevent outside traffic.

## On-path Attacks
<mark class="hltr-yellow">An on-path attack is an attack where the malicious actor places themselves in the middle of an authorized connection and intercepts or alters the data in transit.</mark> On-path attackers gain access to the network and put themselves between two devices, like a web browser and a web server. Then they sniff the packet information to learn the IP and MAC addresses to devices that are communicating with each other. After they have this information, they can pretend to be either of these devices.
## Replay Attacks
<mark class="hltr-yellow">A replay attack is a network attack performed when a malicious actor intercepts a data packet in transit and delays it or repeats it at another time</mark>. A delayed packet can cause connection issues between target computers, or a malicious actor may take a network transmission that was sent by an authorized user and repeat it at a later time to impersonate the authorized user.

## Smurf Attacks
<mark class="hltr-yellow">A smurf attack is a combination of a DDoS attack and an IP spoofing attack. The attacker sniffs an authorized user's IP address and floods it with packets.</mark> This overwhelms the target computer and can bring down a server or the entire network.

## How To Protect
IP spoofing makes it seem like the malicious actor is an authorized user by changing the sender's address of the data packet to match the target network's address. <mark class="hltr-blue">So if a firewall receives a data packet from the internet where the sender's IP address is the same as the private network</mark>, then the firewall will deny the transmission since all the devices with that IP address should already be on the local network. You can make sure that your firewalls configure correctly by creating a rule to reject all incoming traffic that has the same IP address as the local network.

</div></div>


# Module 4
## Security Hardening

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-security-hardening/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




# Notes
> [!definition] 
> Security hardening is the process of strengthening a system to reduce its vulnerability and attack surface.

As part of security hardening, security analysts perform regular maintenance procedures to keep network devices and systems functioning securely and optimally. Security hardening can be conducted on any device or system that can be compromised, such as <mark class="hltr-yellow">hardware, operating systems, applications, computer networks, and databases</mark>. Physical security is also a part of security hardening. This may include securing a physical space with security cameras and security guards.

Some common types of hardening procedures include <mark class="hltr-yellow">software updates</mark>, also called patches, and <mark class="hltr-yellow">device application configuration changes</mark>. These updates and changes are done to increase security and fix security vulnerabilities on a network. <mark class="hltr-orange">An example of a security configuration change would be requiring longer passwords or more frequent password changes.</mark> This makes it harder for a malicious actor to gain login credentials. An example of a configuration check is updating the encryption standards for data that is stored in a database. Keeping encryption up to date makes it harder for malicious actors to access the database.

Other examples of security hardening include <mark class="hltr-yellow">removing or disabling unused applications and services</mark>, <mark class="hltr-yellow">disabling unused ports, and reducing access permissions across devices and network</mark>. <mark class="hltr-blue">Minimizing the number of applications, devices, ports, and access permissions makes network and device monitoring more efficient and reduces the overall attack surface</mark>, which is one of the best ways to secure an organization.

Another important strategy for security hardening is to <mark class="hltr-yellow">conduct regular penetration testing</mark>. A penetration test, also called a pen test, is a simulated attack that helps identify vulnerabilities in a system, network, website, application, and process. Penetration testers document their findings in a report. Depending on where the test fails, security teams can determine the type of security vulnerabilities that require fixing. Organizations can then review these vulnerabilities and come up with a plan to fix them.

</div></div>


## OS Hardening

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-os-hardening/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




# Notes
The operating system is the interface between computer hardware and the user. The OS is the first program loaded when a computer turns on. The OS acts as an intermediary between software applications and the computer hardware. It's important to secure the OS in each system because one insecure OS can lead to a whole network being compromised. There are many types of operating systems, and they all share similar security hardening practices. Let's talk about some of those security hardening practices that are recommended to secure an OS.

Some OS hardening tasks are performed at regular intervals, like <mark class="hltr-yellow">updates, backups, and keeping an up-to-date list of devices and authorized users</mark>. Other tasks are performed only once as part of preliminary safety measures. One example would be configuring a device setting to fit a secure encryption standard. Let's begin with OS hardening tasks that are performed at a regular interval, such as patch installation, also known as patch updates.

--- 

Another hardening task performed regularly is hardware and software disposal. This ensures that all old hardware is properly wiped and disposed of. It's also a good idea to delete any unused software applications since some popular programming languages have known vulnerabilities. Removing unused software makes sure that there aren't any unnecessary vulnerabilities connected with the programs that the software uses.

---
The final OS hardening technique that we'll discuss is implementing a strong password policy. Strong password policies require that passwords follow specific rules. For example, an organization may set a password policy that requires a minimum of eight characters, a capital letter, a number, and a symbol. To discourage malicious actors, a password policy usually states that a user will lose access to the network after entering the wrong password a certain number of times in a row. Some systems also require multi-factor authentication, or MFA. MFA is a security measure which requires a user to verify their identity in two or more ways to access a system or network. Ways of identifying yourself include **something you know**, like a password, **something you have** like an ID card, or **something unique about you**, like your fingerprint.
## Patch Update
> [!definition] 
> A patch update is a software and operating system, or OS, update that addresses security vulnerabilities within a program or product.






</div></div>


### Reading
#### Brute force attacks and OS hardening

In this reading, you’ll learn about brute force attacks. You’ll consider how vulnerabilities can be assessed using virtual machines and sandboxes, and learn ways to prevent brute force attacks using a combination of authentication measures. Implementing various OS hardening tasks can help prevent brute force attacks. An attacker can use a brute force attack to gain access and compromise a network.

<mark class="hltr-yellow">Usernames and passwords are among the most common and important security controls in place today.</mark> They are used and enforced on everything that stores or accesses sensitive or private information, like personal phones, computers, and restricted applications within an organization. However, a major issue with relying on login credentials as a critical line of defense is that they’re vulnerable to being stolen and guessed by malicious actors.

##### Brute force attacks

A **brute force attack** is a trial-and-error process of discovering private information. There are different types of brute force attacks that malicious actors use to guess passwords, including: 

- _Simple brute force attacks._ When attackers try to guess a user's login credentials, it’s considered a simple brute force attack. They might do this by entering any combination of usernames and passwords that they can think of until they find the one that works.
    
- _Dictionary attacks_ use a similar technique. In dictionary attacks, attackers use a list of commonly used passwords and stolen credentials from previous breaches to access a system. These are called “dictionary” attacks because attackers originally used a list of words from the dictionary to guess the passwords, before complex password rules became a common security practice. 
    

Using brute force to access a system can be a tedious and time consuming process, especially when it’s done manually. There are a range of tools attackers use to conduct their attacks.

##### Assessing vulnerabilities

Before a brute force attack or other cybersecurity incident occurs, companies can run a series of tests on their network or web applications to assess vulnerabilities. Analysts can use virtual machines and sandboxes to test suspicious files, check for vulnerabilities before an event occurs, or to simulate a cybersecurity incident.

###### Virtual machines (VMs)

Virtual machines (VMs) are software versions of physical computers. VMs provide an additional layer of security for an organization because they can be used to run code in an isolated environment, preventing malicious code from affecting the rest of the computer or system. VMs can also be deleted and replaced by a pristine image after testing malware. 

VMs are useful when investigating potentially infected machines or running malware in a constrained environment. Using a VM may prevent damage to your system in the event its tools are used improperly. VMs also give you the ability to revert to a previous state. However, there are still some risks involved with VMs. There’s still a small risk that a malicious program can escape virtualization and access the host machine. 

You can test and explore applications easily with VMs, and it’s easy to switch between different VMs from your computer. This can also help in streamlining many security tasks.

###### Sandbox environments

A sandbox is a type of testing environment that allows you to execute software or programs separate from your network. They are commonly used for testing patches, identifying and addressing bugs, or detecting cybersecurity vulnerabilities. Sandboxes can also be used to evaluate suspicious software, evaluate files containing malicious code, and simulate attack scenarios. 

Sandboxes can be stand-alone physical computers that are not connected to a network; however, it is often more time- and cost-effective to use software or cloud-based virtual machines as sandbox environments. Note that some malware authors know how to write code to detect if the malware is executed in a VM or sandbox environment. <mark class="hltr-blue">Attackers can program their malware to behave as harmless software when run inside these types of  testing environments</mark>.

##### Prevention measures

Some common measures organizations use to prevent brute force attacks and similar attacks from occurring include: 

- **Salting and hashing:** Hashing converts information into a unique value that can then be used to determine its integrity. It is a one-way function, meaning it is impossible to decrypt and obtain the original text. Salting adds random characters to hashed passwords. This increases the length and complexity of hash values, making them more secure.
    
- **Multi-factor authentication (MFA) and two-factor authentication (2FA):** MFA is a security measure which requires a user to verify their identity in two or more ways to access a system or network. This verification happens using a combination of authentication factors: a username and password, fingerprints, facial recognition, or a one-time password (OTP) sent to a phone number or email. 2FA is similar to MFA, except it uses only two forms of verification.
    
- **CAPTCHA and reCAPTCHA:** CAPTCHA stands for Completely Automated Public Turing test to tell Computers and Humans Apart. It asks users to complete a simple test that proves they are human. This helps prevent software from trying to brute force a password. reCAPTCHA is a free CAPTCHA service from Google that helps protect websites from bots and malicious software.
    
- **Password policies:** Organizations use password policies to standardize good password practices throughout the business. Policies can include guidelines on how complex a password should be, how often users need to update passwords, and if there are limits to how many times a user can attempt to log in before their account is suspended.
##### Key takeaways

Brute force attacks are a trial-and-error process of guessing passwords. Attacks can be launched manually or through software tools. Methods include simple brute force attacks and dictionary attacks. To protect against brute force attacks, cybersecurity analysts can use sandboxes to test suspicious files, check for vulnerabilities, or to simulate real attacks and virtual machines to conduct vulnerability tests. Some common measures to prevent brute force attacks include: hashing and salting, MFA and/or 2FA, CAPTCHA and reCAPTCHA, and password policies.


## Network Hardening
Layers of security to a network is referred to as **defense in depth**. We can Harden our network by adding things like
- [[600 Coding/Security/Notes/cybersec - IDS\|IDS]]
- [[600 Coding/Security/Notes/cybersec - Firewall\|Firewall]]
- [[600 Coding/Security/Notes/cybersec - IPS\|IPS]]
- [[600 Coding/Security/Notes/cybersec - full packet capture devices\|Full Packet Capture Devices]]
- [[600 Coding/Security/Notes/cybersec - SIEM\|SIEM Tools]]

### Table of Network Hardening
| Security hardening task | Description | Common uses |
| ---- | ---- | ---- |
| Baseline configurations | A documented set of specifications within a system that is used as a basis for future builds, releases, and updates. | To restore a system to a previous baseline after a network outage, or unauthorized changes on a baseline. |
| Configuration checks | Updating the encryption standards for data that is stored in databases. | To see if there are any unauthorized changes to the system. |
| Disabling unused ports | Ports can be blocked on firewalls, routers, servers, and more to prevent potentially dangerous network traffic from passing through. | Before an incident occurs, to prevent malicious actors from entering the network through the open port. Can be used after an incident to prevent future attacks from happening through unused open ports. |
| Encryption using the latest standards | Rules or methods used to conceal outgoing data and uncover or decrypt the incoming data. | Can be implemented regularly to assess if the current encryption standards are secure and effective for your organization. The encryption standards can also be updated after a data breach. |
| Firewall maintenance | Firewall maintenance entails checking and updating security configurations regularly to stay ahead of potential threats. | This can happen regularly. Firewall rules can be updated in response to an event that allows abnormal network traffic into the network. This measure can be used to protect against various DDoS attacks. |
| Hardware & software disposal | Ensures that all old hardware is properly wiped of all data and disposed of. | Prevent the network from various threats by removing outdated or unused software or hardware that do not have the latest security patches or updates. Unpatched devices can allow malicious actors to easily access the network. |
| Multifactor authentication (MFA) | A security measure which requires a user to verify their identity in two or more ways to access a system or network. MFA options include a password, pin number, badge, one-time password (OTP) sent to a cell phone, fingerprint, and more. | Can help protect against brute force attacks and similar security events. MFA can be implemented at any time, and is mostly a technique that is set up once then maintained. |
| Network access privileges | Network access privileges involves permitting, limiting, and/or blocking access privileges to network assets for people, roles, groups, IP addresses, MAC addresses, etc. | Reduces the risk of unauthorized users and outside traffic from accessing the internal network. This can be implemented once, or revisited depending on the likelihood of social engineering or brute force attacks. |
| Network log analysis | The process of examining network logs to identify events of interest. | Can be configured to alert the security team when there is abnormal traffic on the network. This can be used either before an incident occurs, during to track network traffic, and can be configured in the response of a cybersecurity attack. A common tool used for analyzing network logs is a SIEM. |
| Password policies | The National Institute of Standards and Technology's (NIST) latest recommendations for password policies focuses on using methods to salt and hash passwords, rather than requiring overly complex passwords or enforcing frequent changes to passwords. | Password policies are used to prevent attackers from easily guessing user passwords, either manually or by using a script to attempt thousands of stolen passwords (commonly called a brute force attack). |
| Patch updates | A software and operating system (OS) update that addresses security vulnerabilities within a program or product. | Patch updates often contain fixes to security problems. It is important to keep systems up to date with the latest security patches because attackers will be alerted to the security vulnerability when patches are released. They will be more likely to target that vulnerability before people eventually apply the patches. |
| Penetration test (pen test) | A simulated attack that helps identify vulnerabilities in systems, networks, websites, applications, and processes. | Pen tests are used to protect and prevent against potential attacks. |
| Port filtering | A firewall function that blocks or allows certain port numbers to limit unwanted communication. | Port filtering is used to control network traffic and can prevent potential attackers from entering a private network. |
| Removing or disabling unused applications and services | Unused applications and services can become a point of vulnerability because they are less likely to be maintained or updated with new security features. | This procedure is used to reduce potential vulnerabilities within a network. |
| Server and data storage backups | Server and data storage backups help protect data assets from being lost. Backups can be recorded and stored in a physical location or uploaded/synced to a cloud repository. | Backups are used to restore lost data from attacks, human error, equipment failures, and other unplanned losses. |

### Questions 
- What is the basic principle of port filtering
	- A basic principle of port filtering is to allow ports that are used by normal network operations. Any port that is not being used by the normal network operations should be disallowed to protect against vulnerabilities.

## Cloud Hardening
Cloud Hardening includes using the following

[[600 Coding/Security/Notes/cybersec - Identity and Access Management (IAM)\|cybersec - Identity and Access Management (IAM)]]
[[600 Coding/Security/Notes/cybersec - Hypervisors\|cybersec - Hypervisors]]
[[600 Coding/Security/Notes/cybersec -Baselining\|cybersec -Baselining]]

### Cloud security considerations
#### Identity access management
Identity access management (IAM) is a collection of processes and technologies that helps organizations manage digital identities in their environment. This service also authorizes how users can use different cloud resources. A common problem that organizations face when using the cloud is the <mark class="hltr-red">loose configuration of cloud user roles</mark>. An improperly configured user role increases risk by allowing unauthorized users to have access to critical cloud operations. 

#### Configuration
The number of available cloud services adds complexity to the network. Each service must be carefully configured to meet security and compliance requirements. This presents a particular challenge when organizations perform an initial migration into the cloud. When this change occurs on their network, they must ensure that every process moved into the cloud has been configured correctly. If network administrators and architects are not meticulous in correctly configuring the organization’s cloud services, they could leave the network open to compromise. Misconfigured cloud services are a common source of cloud security issues. 

#### Attack surface 
**Cloud service providers** (CSPs) offer numerous applications and services for organizations at a low cost. 

Every service or application on a network carries its own set of risks and vulnerabilities and increases an organization’s overall attack surface. An increased attack surface must be compensated for with increased security measures.

Cloud networks that utilize many services introduce lots of entry points into an organization’s network. However, if the network is designed correctly, utilizing several services does not introduce more entry points into an organization’s network design. These entry points can be used to introduce malware onto the network and pose other security vulnerabilities. It is important to note that CSPs often defer to more secure options, and have undergone more scrutiny than a traditional on-premises network. 

#### Zero-day attacks
Zero-day attacks are an important security consideration for organizations using cloud or traditional on-premise network solutions. A zero day attack is an exploit that was previously unknown. CSPs are more likely to know about a zero day attack occurring before a traditional IT organization does. CSPs have ways of patching hypervisors and migrating workloads to other virtual machines. These methods ensure the customers are not impacted by the attack. There are also several tools available for patching at the operating system level that organizations can use.

#### Visibility and tracking 
Network administrators have access to every data packet crossing the network with both on-premise and cloud networks. They can sniff and inspect data packets to learn about network performance or to check for possible threats and attacks.

This kind of visibility is also offered in the cloud through flow logs and tools, such as packet mirroring. CSPs take responsibility for security in the cloud, but they do not allow the organizations that use their infrastructure to monitor traffic on the CSP’s servers. Many CSPs offer strong security measures to protect their infrastructure. Still, this situation might be a concern for organizations that are accustomed to having full access to their network and operations. CSPs pay for third-party audits to verify how secure a cloud network is and identify potential vulnerabilities. The audits can help organizations identify whether any vulnerabilities originate from on-premise infrastructure and if there are any compliance lapses from their CSP. 

#### Things change fast in the cloud
CSPs are large organizations that work hard to stay up-to-date with technology advancements. For organizations that are used to being in control of any adjustments made to their network, this can be a potential challenge to keep up with. Cloud service updates can affect security considerations for the organizations using them. For example, connection configurations might need to be changed based on the CSP’s updates. 

Organizations that use CSPs usually have to update their IT processes. It is possible for organizations to continue following established best practices for changes, configurations, and other security considerations. However, an organization might have to adopt a different approach in a way that aligns with changes made by the CSP. 

Cloud networking offers various options that might appear attractive to a small company—options that they could never afford to build on their own premises. However, it is important to consider that each service adds complexity to the security profile of the organization, and they will need security personnel to monitor all of the cloud services. 



