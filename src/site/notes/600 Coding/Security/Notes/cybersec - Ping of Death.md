---
{"dg-publish":true,"permalink":"/600-coding/security/notes/cybersec-ping-of-death/","tags":["CyberSecurity"]}
---

# Notes
> [!definition] 
> A ping of death attack is a type of DoS attack that is caused when a hacker pings a system by sending it an oversized ICMP packet that is bigger than 64 kilobytes, the maximum size for a correctly formed ICMP packet.

Pinging a vulnerable network server with an oversized ICMP packet will overload the system and cause it to crash. Think of this like dropping a rock on a small anthill. Each individual ant can carry a certain amount of weight while transporting food to and from the anthill. But if a large rock is dropped on the anthill, then many ants will be crushed, and the colony is unable to function until it rebuilds its operations elsewhere.

