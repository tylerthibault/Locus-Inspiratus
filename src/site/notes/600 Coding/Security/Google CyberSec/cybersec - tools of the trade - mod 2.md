---
{"dg-publish":true,"permalink":"/600-coding/security/google-cyber-sec/cybersec-tools-of-the-trade-mod-2/","tags":["CyberSecurity"]}
---

# Components of Linux
- [User](#User)
- [Applications](#Applications)
- [Shell](#Shell)
- [Filesystem Hierarchy Standard](#Filesystem-Hierarchy-Standard)
- [Kernal](#Kernal)
## User
 > [!definition] 
 > The user is the person interacting with the computer
 
The **user** is the person interacting with a computer. They initiate and manage computer tasks. Linux is a multi-user system, which means that multiple users can use the same resources at the same time.
## Applications
> [!definition] 
> A program that performs a specific task

An **application** is a program that performs a specific task. There are many different applications on your computer. Some applications typically come pre-installed on your computer, such as calculators or calendars. Other applications might have to be installed, such as some web browsers or email clients. In Linux, you'll often use a package manager to install applications. A **package manager** is a tool that helps users install, manage, and remove packages or applications. A **package** is a piece of software that can be combined with other packages to form an application.
## Shell
> [!definition] 
> The command-line interpreter (CLI)

The **shell** is the command-line interpreter. Everything entered into the shell is text based. The shell allows users to give commands to the kernel and receive responses from it. You can think of the shell as a translator between you and your computer. The shell translates the commands you enter so that the computer can perform the tasks you want.
## Filesystem Hierarchy Standard
> [!definition] 
>  FHS is the component of the Linux OS that organizes data. You can think about it as a filing cabinet of data. 

The **Filesystem Hierarchy Standard (FHS)** is the component of the Linux OS that organizes data. It specifies the location where data is stored in the operating system. 

A **directory** is a file that organizes where other files are stored. Directories are sometimes called “folders,” and they can contain files or other directories. The FHS defines how directories, directory contents, and other storage is organized so the operating system knows where to find specific data.
## Kernel
> [!definition] 
> The component of the Linux OS that manages processes and memory

The **kernel** is the component of the Linux OS that manages processes and memory. It communicates with the applications to route commands. The Linux kernel is unique to the Linux OS and is critical for allocating resources in the system. The kernel controls all major functions of the hardware, which can help get tasks expedited more efficiently.



# Kali Linux
KALI LINUX™ is a trademark of Offensive Security and is Debian derived. This open-source distro was made specifically with penetration testing and digital forensics in mind. There are many tools pre-installed into KALI LINUX™. 

It's important to note that KALI LINUX™ should be used on a virtual machine. This prevents damage to your system in the event its tools are used improperly. An additional benefit is that using a virtual machine gives you the ability to revert to a previous state.

## Pen Testing
### Tools for Pen Testing
- Metasploit
	  Look for and exploit vulnerabilities on machines
- Burp Suite
	  A tool that helps to test for weaknesses
- John the Ripper
	  Is a tool used to guess passwords

## Digital Forensics

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/600-coding/security/google-cyber-sec/cybersec-digital-forensics/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




# Notes
> [!definition] 
> Digital forensics is the process of collecting and analyzing data to determine what has happened after an attack.




</div></div>


### Tools for Digital Forensics
- tcpdump
	  tcpdump is a command-line packet analyzer. It's used to capture network traffic.
- Wireshark
	  It has a graphical user interface that can be used to analyze live and capture network traffic.
- Autopsy
	  Is a forensic tool used to analyze hard drives and smartphones. 


# Shells
## Types of Shells
The many different types of Linux shells include the following:

- Bourne-Again Shell (bash)
	    
- C Shell (csh)
    
- Korn Shell (ksh)
    
- Enhanced C shell (tcsh)
    
- Z Shell (zsh)
### Bash
Bash is the default shell in most Linux distributions. It’s considered a user-friendly shell. You can use bash for basic Linux commands as well as larger projects.

Bash is also the most popular shell in the cybersecurity profession. You’ll use bash throughout this course as you learn and practice Linux commands.
