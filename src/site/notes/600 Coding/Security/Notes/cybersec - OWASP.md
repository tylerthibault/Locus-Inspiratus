---
{"tags":["CyberSecurity"],"template":"[[CyberSec Template]]","dg-publish":true,"permalink":"/600-coding/security/notes/cybersec-owasp/","dgPassFrontmatter":true}
---


# Notes
> [!definition] 
> Open Web Application Security Project
> 
> Minimize the attack surface area

## Terminology
- Attack Surface - All the potential vulnerabilities that a threat actor could exploit
	- Phishing Emails
	- Weak passwords

## Principal 1 - Minimize the attack surface area

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-owasp-minimize-the-attack-surface-area/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> An attack surface refers to all the potential vulnerabilities that a threat actor could exploit, like attack vectors, which are pathways attackers use to penetrate security defenses.




</div></div>


## Principal 2 - Least Privilege

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-principle-of-least-privilege/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> [The principle of least privilege (PoLP) is a **security concept that limits the access and permissions of users, programs, or processes to only what is necessary for their legitimate purpose**](https://www.bing.com/ck/a?!&&p=af3d6e1554d792deJmltdHM9MTcwNjE0MDgwMCZpZ3VpZD0xMTk2NmUwMi1mNTQzLTZlMTgtM2EwOS03ZGZmZjQ4NDZmNjAmaW5zaWQ9NjA3Ng&ptn=3&ver=2&hsh=3&fclid=11966e02-f543-6e18-3a09-7dfff4846f60&psq=Principle+Least+privilege&u=a1aHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvUHJpbmNpcGxlX29mX2xlYXN0X3ByaXZpbGVnZQ&ntb=1)[1](https://www.bing.com/ck/a?!&&p=6bdb210eb3e41387JmltdHM9MTcwNjE0MDgwMCZpZ3VpZD0xMTk2NmUwMi1mNTQzLTZlMTgtM2EwOS03ZGZmZjQ4NDZmNjAmaW5zaWQ9NjA3Nw&ptn=3&ver=2&hsh=3&fclid=11966e02-f543-6e18-3a09-7dfff4846f60&psq=Principle+Least+privilege&u=a1aHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvUHJpbmNpcGxlX29mX2xlYXN0X3ByaXZpbGVnZQ&ntb=1)[2](https://www.bing.com/ck/a?!&&p=3a2bfdc63a1b339dJmltdHM9MTcwNjE0MDgwMCZpZ3VpZD0xMTk2NmUwMi1mNTQzLTZlMTgtM2EwOS03ZGZmZjQ4NDZmNjAmaW5zaWQ9NjA3OA&ptn=3&ver=2&hsh=3&fclid=11966e02-f543-6e18-3a09-7dfff4846f60&psq=Principle+Least+privilege&u=a1aHR0cHM6Ly93d3cuY3liZXJhcmsuY29tL3doYXQtaXMvbGVhc3QtcHJpdmlsZWdlLw&ntb=1). [It is a way of minimizing the risk of unauthorized or malicious actions, data breaches, or system compromises. PoLP is also known as the principle of minimal privilege (PoMP) or the principle of least authority (PoLA)](https://www.bing.com/ck/a?!&&p=23a7019471ecc7ffJmltdHM9MTcwNjE0MDgwMCZpZ3VpZD0xMTk2NmUwMi1mNTQzLTZlMTgtM2EwOS03ZGZmZjQ4NDZmNjAmaW5zaWQ9NjA3OQ&ptn=3&ver=2&hsh=3&fclid=11966e02-f543-6e18-3a09-7dfff4846f60&psq=Principle+Least+privilege&u=a1aHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvUHJpbmNpcGxlX29mX2xlYXN0X3ByaXZpbGVnZQ&ntb=1)[1](https://www.bing.com/ck/a?!&&p=48dd204e4d190417JmltdHM9MTcwNjE0MDgwMCZpZ3VpZD0xMTk2NmUwMi1mNTQzLTZlMTgtM2EwOS03ZGZmZjQ4NDZmNjAmaW5zaWQ9NjA4MA&ptn=3&ver=2&hsh=3&fclid=11966e02-f543-6e18-3a09-7dfff4846f60&psq=Principle+Least+privilege&u=a1aHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvUHJpbmNpcGxlX29mX2xlYXN0X3ByaXZpbGVnZQ&ntb=1). 

Making sure that users have the least amount of access required to perform their everyday tasks


</div></div>


## Principal 3 - Defense in Depth

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-owasp-defense-in-depth/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">

<div class="markdown-embed-title">

# Defense in depth

</div>




# Notes
> [!definition] 
> An organization should have multiple security controls that address risks and threats in different ways. 






</div></div>



## Principal 4 - Separation of Duties

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-owasp-separation-of-duties/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> No one should be given so many privileges that they can misuse the system.




</div></div>

## Principal 5 - Keep security simple

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-owasp-keep-security-simple/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> When implementing security controls, unnecessarily complicated solutions should be avoided because they can become unmanageable. The more complex the security controls are, the harder it is for people to work collaboratively. 




</div></div>


## Principal 6 - Fix security issues correctly

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/notes/cybersec-owasp-fix-security-issues-correctly/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





# Notes
> [!definition] 
> When a security incident occurs, security professionals are expected to identify the root cause quickl. From there, it's important to correct any identified vulnerabilities and conduct tests to ensure that repairs are successful. 




</div></div>



