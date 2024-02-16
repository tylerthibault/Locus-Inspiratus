---
{"dg-publish":true,"db-show":true,"memory_palace":null,"tags":["CyberSecurity","cybersec-profm","cybersec-sec-plus"],"template":"[[CyberSec Template]]","Summary":"The AAA framework is the process we use to get someone logged into the system and track where and what data packets are being moved around.","YouTube_Link":"https://www.youtube.com/watch?v=AhaZtj5P2a8&list=PLG49S3nxzAnl4QDVqK-hOnoqcSKEIDDuv&index=5","permalink":"/600-coding/security/notes/cybersec-aaa-framework/","dgPassFrontmatter":true}
---

# Authentication, Authorization and Accounting

> [!summary] 
> The AAA framework is the process we use to get someone logged into the system and track where and what data packets are being moved around. 


> [!definition] 
> 

![Pasted image 20240215132255.png](/img/user/104%20Attachments/Pasted%20image%2020240215132255.png)
## Identification
> [!definition] 
> This is a person stating to be someone and identifying as that person. This is usually done through a username or email
## Authentication
> [!definition] 
> This is when a person proves that they are that person. This is done through passwords and other authentication methods ([[600 Coding/Security/Notes/cybersec - 2FA\|cybersec - 2FA]])

When it comes to hardware that we can't see the question is how do we authenticate a device?
ANS: 
1. We put a digitally signed certificate on the device
2. We log the digitally signed certificate on our servers as being an approved device

In order to do this we must have a [[cybersec - Certificate Authority (CA)\|Certificate Authority (CA)]] 
## Authorization
> [!definition] 
> This is the level of access you have based off of who you are logged in as. 

### Authorization Model
In order to make this scale we put an authorization model in the middle before the user access the database. 

![Pasted image 20240215133438.png](/img/user/104%20Attachments/Pasted%20image%2020240215133438.png)
## Accounting
> [!definition] 
> This is what resources you used while you were logged in and the data on those resources. This could be anything from login times, data sent and received, data viewed, etc.