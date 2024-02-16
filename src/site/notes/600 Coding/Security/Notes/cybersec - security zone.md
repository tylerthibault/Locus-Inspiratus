---
{"tags":["CyberSecurity"],"template":"[[CyberSec Template]]","dg-publish":true,"permalink":"/600-coding/security/notes/cybersec-security-zone/","dgPassFrontmatter":true}
---


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


