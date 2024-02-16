---
{"tags":["CyberSecurity"],"template":"[[CyberSec Template]]","dg-publish":true,"permalink":"/600-coding/security/notes/cybersec-ip-spoofing/","dgPassFrontmatter":true}
---

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