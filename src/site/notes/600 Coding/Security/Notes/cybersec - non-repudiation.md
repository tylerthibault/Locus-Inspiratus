---
{"dg-publish":true,"permalink":"/600-coding/security/notes/cybersec-non-repudiation/","tags":["CyberSecurity","cybersec-profm","cybersec-sec-plus"]}
---

> [!summary] 
> The ability to verify that the information really came from the sender.  

# Proof of Integrity
> [!definition] 
> Any data that we receive is the same data that was sent.

We can accomplish this by using a hash. You can hash the content of that data and then when the receiver gets the content they can hash it and compare the hashes together. **This allows us to have proof of Integrity**

# Proof of Origin
> [!definition] 
> We sign the transaction with a private key, which is only known to the person who is sending the data. To verify we compare it with a public key. 


