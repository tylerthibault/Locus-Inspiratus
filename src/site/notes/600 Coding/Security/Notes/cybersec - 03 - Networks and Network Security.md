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

# Types of Firewalls
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
- [x] Study (@2024-01-24)
1. _Username/password:_ modify the default password for a firewall device
2. _Remote administration:_ Disable the feature of the remote administration
3. _Port forwarding:_ Configure appropriate port forwarding for certain applications to work properly, such as a web server or FTP server
4. _DHCP server:_ Installing a firewall on a network with an existing DHCP server will cause conflict unless the firewall’s DHCP is disabled
5. _Logging:_ To troubleshoot firewall issues or potential attacks, ensure that logging is enabled and understand how to view logs
6. _Policies:_ You should have solid security policies in place and make sure that the firewall is configured to enforce those policies.

# Types of Firewalls
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





