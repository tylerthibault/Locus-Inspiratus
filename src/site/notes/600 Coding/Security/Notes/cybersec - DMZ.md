---
{"tags":["CyberSecurity"],"template":"[[CyberSec Template]]","dg-publish":true,"permalink":"/600-coding/security/notes/cybersec-dmz/","dgPassFrontmatter":true}
---


# Notes
> [!definition] demilitarized zone
> 
> The DMZ acts as a network perimeter to the internal network.

![Pasted image 20240212122425.png](/img/user/104%20Attachments/Pasted%20image%2020240212122425.png)

This is where we set our <mark class="hltr-orange">publicly facing server in between two different firewalls</mark> and separate our company network behind the 2nd firewall. This <mark class="hltr-orange">isolates our companies network from the server (that is open on port 443) that is facing the open internet</mark>. What this does is if a threat actor gains access to our publicly accessible server they still get blocked by the second set of firewalls and therefore are not allowed to move laterally and infect other PC's on the system. While a company is able to do this with only one firewall, opening up port 443 to navigate to the publicly open server and blocking all other traffic, this might be considered less secure because if the threat actor finds a vulnerability in the first firewall then they will be able to access our companies system. However with the two firewall setup a vulnerability in the first firewall doesn't mean a vulnerability in the second firewall. Therefor making it more secure. 
