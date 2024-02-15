---
{"dg-publish":true,"permalink":"/600-coding/security/notes/cybersec-01-foundations-of-cybersecurity/","tags":["CyberSecurity","moc"]}
---


# Notes
> [!definition] 
> 



# Links
---
Base: [[600 Coding/Security/Google CyberSec/00 -Google Cert Overview\|00 -Google Cert Overview]]
[[600 Coding/Security/Notes/cybersec - methods of attack\|cybersec - methods of attack]]
Terms and Definitions: [[600 Coding/Security/Notes/cybersec - terms mod 1\|cybersec - terms mod 1]]

---
# Memory Palace
[[Excalidraw/MindMap-MDHouse\|MindMap-MDHouse]]

# Module 1 Notes

> [!definition] What do Security Analysts do?
They are responsible for monitoring and protecting information and systems.

- Personally Identifiable Information (PII)
- Sensitive Personally Identifiable Information (SPII)

> [!memory] 
> A man with PlC on his Shirt Sitting at a desk at the top of the outside stairs in front of a bunch of monitors. He is also dressed in a knights suit of armor.


## Terminology
> [!definition] Playbook
> [[600 Coding/Security/Notes/CyberSec - Playbooks\|CyberSec - Playbooks]] are a list of how to go through a certain detection, and what the analyst needs to look at in order to investigate those incidents.

> [!definition] Compliance
**[[600 Coding/Security/Notes/cybersec - Compliance\|cybersec - Compliance]]** is the process of adhering to internal standards and external regulations and enables organizations to avoid fines and security breaches.

> [!definition] Security frameworks
**Security frameworks** are guidelines used for building plans to help mitigate risks and threats to data and privacy.

> [!definition] Security controls
**Security controls** are safeguards designed to reduce specific security risks. They are used with security frameworks to establish a strong security posture.

> [!definition] **Security posture**
**Security posture** is an organization’s ability to manage its defense of critical assets and data and react to change. A strong security posture leads to lower risk for the organization.

> [!definition] Threat Actor
A **threat actor**, or malicious attacker, is any person or group who presents a security risk. This risk can relate to computers, applications, networks, and data.

> [!definition] Internal Threat
An **internal threat** can be a current or former employee, an external vendor, or a trusted partner who poses a security risk. At times, an internal threat is accidental. For example, an employee who accidentally clicks on a malicious email link would be considered an accidental threat. Other times, the internal threat actor _intentionally_ engages in risky activities, such as unauthorized data access.

> [!definition] Network Security
**Network security** is the practice of keeping an organization's network infrastructure secure from unauthorized access. This includes data, services, systems, and devices that are stored in an organization’s network.

> [!definition] Cloud Security
**Cloud security** is the process of ensuring that assets stored in the cloud are properly configured, or set up correctly, and access to those assets is limited to authorized users. The cloud is a network made up of a collection of servers or computers that store resources and data in remote physical locations known as data centers that can be accessed via the internet. Cloud security is a growing subfield of cybersecurity that specifically focuses on the protection of data, applications, and infrastructure in the cloud.

> [!definition] Programming
**Programming** is a process that can be used to create a specific set of instructions for a computer to execute tasks. These tasks can include: 
- Automation of repetitive tasks (e.g., searching a list of malicious domains) 
- Reviewing web traffic 
- Alerting suspicious activity

## Skills
### Transferable skills
- **Communication:** As a cybersecurity analyst, you will need to communicate and collaborate with others. Understanding others’ questions or concerns and communicating information clearly to individuals with technical and non-technical knowledge will help you mitigate security issues quickly. 
    
- **Problem-solving:** One of your main tasks as a cybersecurity analyst will be to proactively identify and solve problems. You can do this by recognizing attack patterns, then determining the most efficient solution to minimize risk. Don't be afraid to take risks, and try new things. Also, understand that it's rare to find a perfect solution to a problem. You’ll likely need to compromise.
    
- **Time management:** Having a heightened sense of urgency and prioritizing tasks appropriately is essential in the cybersecurity field. So, effective time management will help you minimize potential damage and risk to critical assets and data. Additionally, it will be important to prioritize tasks and stay focused on the most urgent issue.
    
- **Growth mindset:** This is an evolving industry, so an important transferable skill is a willingness to learn. Technology moves fast, and that's a great thing! It doesn't mean you will need to learn it all, but it does mean that you’ll need to continue to learn throughout your career. Fortunately, you will be able to apply much of what you learn in this program to your ongoing professional development.
    
- **Diverse perspectives:** The only way to go far is together. By having respect for each other and encouraging diverse perspectives and mutual respect, you’ll undoubtedly find multiple and better solutions to security problems.

### Tech skills
- **Programming languages:** By understanding how to use programming languages, cybersecurity analysts can automate tasks that would otherwise be very time consuming. Examples of tasks that programming can be used for include searching data to identify potential threats or organizing and analyzing information to identify patterns related to security issues. 
    
- **Security information and event management (SIEM) tools:** SIEM tools collect and analyze log data, or records of events such as unusual login behavior, and support analysts’ ability to monitor critical activities in an organization. This helps cybersecurity professionals identify and analyze potential security threats, risks, and vulnerabilities more efficiently.
    
- **Intrusion detection systems (IDSs):** Cybersecurity analysts use IDSs to monitor system activity and alerts for possible intrusions. It’s important to become familiar with IDSs because they’re a key tool that every organization uses to protect assets and data. For example, you might use an IDS to monitor networks for signs of malicious activity, like unauthorized access to a network.
    
- **Threat landscape knowledge:** Being aware of current trends related to threat actors, malware, or threat methodologies is vital. This knowledge allows security teams to build stronger defenses against threat actor tactics and techniques. By staying up to date on attack trends and patterns, security professionals are better able to recognize when new types of threats emerge such as a new ransomware variant. 
    
- **Incident response:** Cybersecurity analysts need to be able to follow established policies and procedures to respond to incidents appropriately. For example, a security analyst might receive an alert about a possible malware attack, then follow the organization’s outlined procedures to start the incident response process. This could involve conducting an investigation to identify the root issue and establishing ways to remediate it.





# Module 2 Notes
## Virus
- [[600 Coding/Security/Notes/cybersec - brain virus\|cybersec - brain virus]]
- [[100 Fleeting Notes/Morris Worm\|Morris Worm]]
- [[600 Coding/Security/Notes/cybersec - love letter\|cybersec - love letter]] Malware 


## Common attacks and their effectiveness
### Phishing

<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">




# Type 1

> [!definition] 
Phishing is a cyberattack method where attackers impersonate trustworthy entities, often through emails or websites, to deceive individuals into revealing sensitive information like usernames, passwords, or financial details.

## Phishing attacks today include:
- **Business Email Compromise (BEC):** A threat actor sends an email message that seems to be from a known source to make a seemingly legitimate request for information, in order to obtain a financial advantage.
    
- **Spear phishing:** A malicious email attack that targets a specific user or group of users. The email seems to originate from a trusted source.
    
- **Whaling:** A form of spear phishing. Threat actors target company executives to gain access to sensitive data.
    
- **Vishing:** The exploitation of electronic voice communication to obtain sensitive information or to impersonate a known source.
    
- **Smishing:** The use of text messages to trick users, in order to obtain sensitive information or to impersonate a known source.

## Prevention
- Don’t enter sensitive information in the webpages that you don’t trust
- Verify the site’s security
- Use Firewalls
- Use AntiVirus Software that has Internet Security
- Use Anti-Phishing Toolbar



</div></div>


### Malware

<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">






> [!definition] 
Malware, short for malicious software, is any software specifically designed to harm, exploit, or gain unauthorized access to computer systems or data. Common types of malware include viruses, worms, Trojans, and ransomware.

## Malware attacks today include: 

- **Viruses:** Malicious code written to interfere with computer operations and cause damage to data and software. A virus needs to be initiated by a user (i.e., a threat actor), who transmits the virus via a malicious attachment or file download. When someone opens the malicious attachment or download, the virus hides itself in other files in the now infected system. When the infected files are opened, it allows the virus to insert its own code to damage and/or destroy data in the system.
    
- **Worms:** Malware that can duplicate and spread itself across systems on its own. In contrast to a virus, a worm does not need to be downloaded by a user. Instead, it self-replicates and spreads from an already infected computer to other devices on the same network.
    
- **Ransomware:** A malicious attack where threat actors encrypt an organization's data and demand payment to restore access. 
    
- **Spyware:** Malware that’s used to gather and sell information without consent. Spyware can be used to access devices. This allows threat actors to collect personal data, such as private emails, texts, voice and image recordings, and locations.
## Sources of Malware
1. Email Attachments
2. Fake Websites
3. Software Downloads
4. Torrents
5. Removable Media
6. Insider Threats
7. Unpatched Software

</div></div>

Equifax Breach


### Social Engineering

<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">




## Social Engineering 

**Social engineering** is a manipulation technique that exploits human error to gain private information, access, or valuables. Human error is usually a result of trusting someone without question. It’s the mission of a threat actor, acting as a social engineer, to create an environment of false trust and lies to exploit as many people as possible. 

- [ ] #task #memory-work  #CyberSecurity Social Engineering Examples
Some of the most common types of social engineering attacks today include:

- **Social media phishing:** A threat actor collects detailed information about their target from social media sites. Then, they initiate an attack.
    
- **Watering hole attack:** A threat actor attacks a website frequently visited by a specific group of users.
    
- **USB baiting:** A threat actor strategically leaves a malware USB stick for an employee to find and install, to unknowingly infect a network. 
    
- **Physical social engineering:** A threat actor impersonates an employee, customer, or vendor to obtain unauthorized access to a physical location.
    

### Social engineering principles 

Social engineering is incredibly effective. This is because people are generally trusting and conditioned to respect authority. The number of social engineering attacks is increasing with every new social media application that allows public access to people's data. Although sharing personal data—such as your location or photos—can be convenient, it’s also a risk.

- [ ] #task #memory-work  #CyberSecurity why social attacks are effective
Reasons why social engineering attacks are effective include:

- **Authority:** Threat actors impersonate individuals with power. This is because people, in general, have been conditioned to respect and follow authority figures. 
    
- **Intimidation:** Threat actors use bullying tactics. This includes persuading and intimidating victims into doing what they’re told. 
    
- **Consensus/Social proof:** Because people sometimes do things that they believe many others are doing, threat actors use others’ trust to pretend they are legitimate. For example, a threat actor might try to gain access to private data by telling an employee that other people at the company have given them access to that data in the past. 
    
- **Scarcity:** A tactic used to imply that goods or services are in limited supply. 
    
- **Familiarity:** Threat actors establish a fake emotional connection with users that can be exploited.  
    
- **Trust:** Threat actors establish an emotional relationship with users that can be exploited _over time_. They use this relationship to develop trust and gain personal information.
    
- **Urgency:** A threat actor persuades others to respond quickly and without questioning.



</div></div>




## [[600 Coding/Security/Notes/cybersec - CISSP\|cybersec - CISSP]]
[[Excalidraw/MindMap-Our Apt\|MindMap-Our Apt]]

There are 8 [[600 Coding/Security/Notes/cybersec - security domains\|cybersec - security domains]] in CISSP

<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">





# Notes
> [!definition] 
> 




</div></div>

## Threat actor types
- [[600 Coding/Security/Notes/cybersec - APT\|Advanced persistent threats]]
- [[600 Coding/Security/Notes/cybersec - insider threats\|cybersec - insider threats]]
- [[600 Coding/Security/Notes/cybersec - Hacktivists\|cybersec - Hacktivists]]
## Hacker Types
A **hacker** is any person who uses computers to gain access to computer systems, networks, or data. They can be beginner or advanced technology professionals who use their skills for a variety of reasons.

- Authorized hackers are also called ethical hackers. They follow a code of ethics and adhere to the law to conduct organizational risk evaluations. They are motivated to safeguard people and organizations from malicious threat actors.
    
- Semi-authorized hackers are considered researchers. They search for vulnerabilities but don’t take advantage of the vulnerabilities they find.
    
- Unauthorized hackers are also called unethical hackers. They are malicious threat actors who do not follow or respect the law. Their goal is to collect and sell confidential data for financial gain.




# Module 3 Notes
## Security Frameworks


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">




> [!definition] 
> Guidelines used for building plans to help mitigate risk and threats to data and privacy
> 
> Security frameworks are used to establish guidelines for building security plans that enable security professionals to help mitigate risk. Biometrics are unique physical characteristics that can be used to verify a person’s identity.
### Purpose
- protecting PII
- Securing financial information
- Identifying security weaknesses
- managing organizational risks
- aligning security with business goals

### Four Core Components
1. Identifying and documenting security goals 
2. Setting guidelines to achieve security goals
3. Implementing strong security processes
4. Monitoring and communicating results


### Examples of Framewords
- [[600 Coding/Security/Notes/cybersec - CIA triad\|cybersec - CIA triad]]
- [[600 Coding/Security/Notes/cybersec - NIST Cybersecurity Framework\|cybersec - NIST Cybersecurity Framework]] (CSF)

</div></div>


## Security Controls

<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">





# Notes
> [!definition] 
> Safeguards designed to reduce specific security risks

## 3 Different Types of Controls
1. Encryption
	1. The process of converting data from a readable format to an encoded format.
2. Authentication
	1. The process of verifying who someone or something is
3. Authorization
	1. The concept of granting access to specific resources within a system







</div></div>



## Given Notes
### Controls, frameworks, and compliance

Previously, you were introduced to security frameworks and how they provide a structured approach to implementing a security lifecycle. As a reminder, a security lifecycle is a constantly evolving set of policies and standards. In this reading, you will learn more about how security frameworks, controls, and compliance regulations—or laws—are used together to manage security and make sure everyone does their part to minimize risk.

#### How controls, frameworks, and compliance are related

The **confidentiality, integrity, and availability (CIA) triad** is a model that helps inform how organizations consider risk when setting up systems and security policies. 

![A triangle representing the CIA (confidentiality, integrity, availability) triad](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/tRYBVP2USbGPopkOfhzPpw_6ab653e71a614420b313c9e7675893f1_PULBC_YPYaRtzxvZUx-luk79t2pB_kZEoF2XeW17w6D2BekL7XaIUhCIAf65kNzAZU-WXYJ6IwhMr_jwiPhYMd2kWk5TyfeNFUy4ax3hyj_fJbtGSEw4UB0bzaA-E-gKD5tG8yud6Q2kmQFomLoF4CGW-0cCnhAyOvriAcCqrRKDlJMkaNOReSToFqs5I_cjfFOVTU9cmwiYyFETx2_4Gbf80z4rpW3ioqxBAw?expiry=1706140800000&hmac=YUViBKMg-325TXtagfhs-mq_8vWt455DCPK54RGEO24)

CIA are the three foundational principles used by cybersecurity professionals to establish appropriate controls that mitigate threats, risks, and vulnerabilities.

As you may recall, **security** **controls** are safeguards designed to reduce specific security risks. So they are used alongside frameworks to ensure that security goals and processes are implemented correctly and that organizations meet regulatory compliance requirements.

**Security frameworks** are guidelines used for building plans to help mitigate risks and threats to data and privacy. They have four core components:

1. Identifying and documenting security goals 
    
2. Setting guidelines to achieve security goals 
    
3. Implementing strong security processes
    
4. Monitoring and communicating results
    

**Compliance** is the process of adhering to internal standards and external regulations.

#### Specific controls, frameworks, and compliance

The National Institute of Standards and Technology (NIST) is a U.S.-based agency that develops multiple voluntary compliance frameworks that organizations worldwide can use to help manage risk. The more aligned an organization is with compliance, the lower the risk.

Examples of frameworks include the NIST Cybersecurity Framework (CSF) and the NIST Risk Management Framework (RMF). 

**Note:** Specifications and guidelines can change depending on the type of organization you work for.

In addition to the [NIST CSF](https://www.nist.gov/cyberframework) and [NIST RMF](https://csrc.nist.gov/projects/risk-management/about-rmf), there are several other controls, frameworks, and compliance standards that it is important for security professionals to be familiar with to help keep organizations and the people they serve safe.

##### **The Federal Energy Regulatory Commission - North American Electric Reliability Corporation (FERC-NERC)**

FERC-NERC is a regulation that applies to organizations that work with electricity or that are involved with the U.S. and North American power grid. These types of organizations have an obligation to prepare for, mitigate, and report any potential security incident that can negatively affect the power grid. They are also legally required to adhere to the Critical Infrastructure Protection (CIP) Reliability Standards defined by the FERC. 

### **The Federal Risk and Authorization Management Program (FedRAMP®)**

FedRAMP is a U.S. federal government program that standardizes security assessment, authorization, monitoring, and handling of cloud services and product offerings. Its purpose is to provide consistency across the government sector and third-party cloud providers. 

### **Center for Internet Security (CIS®)**

CIS is a nonprofit with multiple areas of emphasis. It provides a set of controls that can be used to safeguard systems and networks against attacks. Its purpose is to help organizations establish a better plan of defense. CIS also provides actionable controls that security professionals may follow if a security incident occurs. 

### **General Data Protection Regulation (GDPR)**

GDPR is a European Union (E.U.) general data regulation that protects the processing of E.U. residents’ data and their right to privacy in and out of E.U. territory. For example, if an organization is not being transparent about the data they are holding about an E.U. citizen and why they are holding that data, this is an infringement that can result in a fine to the organization. Additionally, if a breach occurs and an E.U. citizen’s data is compromised, they must be informed. The affected organization has 72 hours to notify the E.U. citizen about the breach.

### **Payment Card Industry Data Security Standard (PCI DSS)**

PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment. The objective of this compliance standard is to reduce credit card fraud. 

### **The Health Insurance Portability and Accountability Act (HIPAA)**

HIPAA is a U.S. federal law established in 1996 to protect patients' health information. This law prohibits patient information from being shared without their consent. It is governed by three rules: 

1. Privacy
    
2. Security 
    
3. Breach notification 
    

Organizations that store patient data have a legal obligation to inform patients of a breach because if patients' **Protected Health Information** (PHI) is exposed, it can lead to identity theft and insurance fraud. PHI relates to the past, present, or future physical or mental health or condition of an individual, whether it’s a plan of care or payments for care. Along with understanding HIPAA as a law, security professionals also need to be familiar with the Health Information Trust Alliance (HITRUST®), which is a security framework and assurance program that helps institutions meet HIPAA compliance.

### **International Organization for Standardization (ISO)** 

ISO was created to establish international standards related to technology, manufacturing, and management across borders. It helps organizations improve their processes and procedures for staff retention, planning, waste, and services. 

### **System and Organizations Controls (SOC type 1, SOC type 2)**

The American Institute of Certified Public Accountants® (AICPA) auditing standards board developed this standard. The SOC1 and SOC2 are a series of reports that focus on an organization's user access policies at different organizational levels such as: 

- Associate
    
- Supervisor
    
- Manager
    
- Executive
    
- Vendor
    
- Others 
    

They are used to assess an organization’s financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud.

**Pro tip**: There are a number of regulations that are frequently revised. You are encouraged to keep up-to-date with changes and explore more frameworks, controls, and compliance. Two suggestions to research: the Gramm-Leach-Bliley Act and the Sarbanes-Oxley Act.

### United States Presidential Executive Order 14028

On May 12, 2021, President Joe Biden released an executive order related to improving the nation’s cybersecurity to remediate the increase in threat actor activity. Remediation efforts are directed toward federal agencies and third parties with ties to U.S. [critical infrastructure](https://csrc.nist.gov/glossary/term/critical_infrastructure#:~:text=Definition(s)%3A,any%20combination%20of%20those%20matters.). For additional information, review the [Executive Order on Improving the Nation’s Cybersecurity](https://www.whitehouse.gov/briefing-room/presidential-actions/2021/05/12/executive-order-on-improving-the-nations-cybersecurity/).

### Key takeaways

In this reading you learned more about controls, frameworks, and compliance. You also learned how they work together to help organizations maintain a low level of risk.

As a security analyst, it’s important to stay up-to-date on common frameworks, controls, and compliance regulations and be aware of changes to the cybersecurity landscape to help ensure the safety of both organizations and people.


## Ethics in Cybersecurity
### Security Ethics

<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">





# Notes
> [!definition] 
> Guidelines for making appropriate decisions as a security professional


## Principles
- Confidentiality
- Privacy protections
- Laws




</div></div>



# Module 4 Notes
## [[600 Coding/Security/Notes/cybersec - SIEM\|cybersec - SIEM]] Tools 
**Security Information and Event Management** - (SIM or SEAM)
### Tools 
- Splunk
- Chronicle
- [[600 Coding/Security/Notes/CyberSec - Playbooks\|CyberSec - Playbooks]]
- [[600 Coding/Security/Notes/cybersec - Network Protocol Analyzers\|cybersec - Network Protocol Analyzers]] (packet sniffer)

[[600 Coding/Security/Notes/cybersec - portfolio\|cybersec - portfolio]]


## Terminology of module 4
**Antivirus software:** A software program used to prevent, detect, and eliminate malware and viruses

**Database:** An organized collection of information or data

**Data point:** A specific piece of information

**Intrusion detection system (IDS):** An application that monitors system activity and alerts on possible intrusions

**Linux:** An open-source operating system

**Log:** A record of events that occur within an organization’s systems 

**Network protocol analyzer (packet sniffer):** A tool designed to capture and analyze data traffic within a network

**Order of volatility:** A sequence outlining the order of data that must be preserved from first to last

**Programming:** A process that can be used to create a specific set of instructions for a computer to execute tasks

**Protecting and preserving evidence:** The process of properly working with fragile and volatile digital evidence

**Security information and event management (SIEM)**: An application that collects and analyzes log data to monitor critical activities in an organization

**SQL (Structured Query Language):** A programming language used to create, interact with, and request information from a database