---
{"dg-publish":true,"permalink":"/600-coding/security/notes/cybersec-firewall/"}
---

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

