---
{"tags":["CyberSecurity","cybersec-profm","cybersec-sec-plus"],"template":"[[CyberSec Template]]","dg-publish":true,"Summary":"The ability to verify that the information really came from the sender.","YouTube_Link":"https://www.youtube.com/watch?v=XxnCxPEllMg&list=PLG49S3nxzAnl4QDVqK-hOnoqcSKEIDDuv&index=6","db-show":true,"memory_palace":null,"permalink":"/600-coding/security/notes/cybersec-non-repudiation/","dgPassFrontmatter":true}
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


