---
{"dg-publish":true,"permalink":"/600-coding/security/notes/cybersec-firewall-types/","tags":["CyberSecurity"]}
---

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
