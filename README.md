# Awesome Security [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Hi, this is Sarthak and I'm a lead maintainer of this project. For further questions or general security information catch me on Twitter at [smash8tap](https://twitter.com/smash8tap) or you can always find me in the chat during [Michael's](https://www.twitch.tv/mbcrump) twitch stream.
A collection of awesome ethical hacking security related content!

- [Awesome Security](#awesome-security)
  - [General Security](#general-security)
  - [Infrastructure Security](#infrastructure-security)
  - [Hardware Security and Binary Exploitation](#hardware-security-and-binary-exploitation)
  - [Communication Security](#communication-security)
  - [Wireless Security](#wireless-security)
  - [Web Security](#web-security)
  - [Cryptography](#cryptography)
  - [Operational Security](#operational-security)

### How to get most out of this Repo?

Each Section has a **Learning** and a **Test Your Knowledge** path, and if you follow the **learning** path in the order that is listed, then you shall be able to solve the challenges in the **Test your knowledge** path.

---

### General Security

(Work in Progress)

---

## Infrastructure Security <img src="https://img.icons8.com/color/20/000000/kali-linux.png"/>

##### Linux Basics <img src="https://img.icons8.com/nolan/16/linux--v2.png"/>

> Learning

- Linux Fundamentals series by [Tryhackme](https://tryhackme.com/)
  - [Part1](https://tryhackme.com/room/linux1) Learn basic linux commands (man, ls, cat, touch, su)
  - [Part2](https://tryhackme.com/room/linux2) Learn linux file permissions and file operations (&, $, |, ;, >, >>)
  - [Part3](https://tryhackme.com/room/linux3) Learn useful shell commands (cp, find, grep, sudo, apt)
- [Bash Scripting](https://ryanstutorials.net/bash-scripting-tutorial/) and [linux Basics](https://ryanstutorials.net/linuxtutorial/) Learn basic shell scripting and some more useful linux commands
- [Regular Expressions](https://tryhackme.com/room/catregex) Learn how to use regular expressoins
- [Linux Find Command](https://tryhackme.com/room/thefindcommand) Tryhackme room to learn linux find command
- [Nullbyte Linux Basics](https://null-byte.wonderhowto.com/how-to/linux-basics/) Learn linux-basics by reading these awesome articles which includes command-line basics to all the way over to linux boot process
- [Kali Linux Revealed](https://kali.training/lessons/introduction/) A free course by Offensive Security, which will teach you about kali and linux in general
  <br />

> Test your knowledge

- [Overthewire: Bandit](https://overthewire.org/wargames/bandit/) Test all that you have learnt so far by completing these Linux challenges

#### Networking Fundamentals

> Learning

- [Introductory Networking](https://tryhackme.com/room/introtonetworking) Room by Tryhackme, to learn about the basics of networking

#### Infrastructure Hacking

> Learning

(Linux Basics are required)

- [Nmap Basics](https://tryhackme.com/room/furthernmap) Learn how to do various types of scans and how to use nmap's scripting engine
- [Directory Enumeration](https://book.hacktricks.xyz/pentesting-web/web-tool-wfuzz) Learn how to perform web fuzzing with Wfuzz
- [Ffuf](https://www.youtube.com/watch?v=iLFkxAmwXF0&t=936s) Learn how to use Fuff for web directory enumeration
- [Metasploit](https://tryhackme.com/room/rpmetasploit) Learn how to launch an exploit and get a shell using metasploit
- [Metasploit Unleashed](https://www.offensive-security.com/metasploit-unleashed/) A free course developed by Offensive Security, which teaches you everything you need to know about metasploit.
- **Password Cracking**: Learn basics of password cracking
  - [Hydra](https://tryhackme.com/room/hydra) Learn a versatile logon cracker
  - [John and SSH](https://null-byte.wonderhowto.com/how-to/crack-ssh-private-key-passwords-with-john-ripper-0302810/) Crack Private SSH keys with Johntheripper
  - [Brute force SSH](https://null-byte.wonderhowto.com/how-to/gain-ssh-access-servers-by-brute-forcing-credentials-0194263/) Learn how to brute force ssh credentials with nmap, hydra and metasploit
- [INE Starter Pass](https://checkout.ine.com/starter-pass) Learn basics of Penetration testing with Elearn-Security's Junior Penetration testing path for free.

> Test Your Knowledge

- Tryhackme Rooms
  - [Tryhackme: Crackthehash](https://tryhackme.com/room/crackthehash) Use your password-cracking skills to crack various hash types like md5, sha-512 etc
  - [Tryhackme: Blue](https://tryhackme.com/room/blue) A walkthrough based room, where you hack into a vulnerable windows machine using metasploit
  - [Tryhackme: Vulnversity](https://tryhackme.com/room/vulnversity) Use your recon and privilege escalation skill to hack into this machine
  - [Tryhackme: Basic Pentesting](https://tryhackme.com/room/basicpentestingjt) Perform a basic Pentest in a lab environment and sharpen your skills learnt so far

---

### Hardware Security And Binary Exploitation

> Learning

- [Pwn college](https://pwn.college/) An in-depth and thorough lecture series by Arizona State University
- [Nightmare's Binary Exploitation](https://guyinatuxedo.github.io/) An in-depth guide to learn the basics of reverse engineering and binary exploitation along with various tools like gdb, Ghidra, etc.
- [Malware Unicorn](https://malwareunicorn.org/#/) Learn basics of reverse engineering with hands-on workshop
  - [Reverse Engineering 101](https://malwareunicorn.org/workshops/re101.html#0) Learn basics of Windows PE program, x86 assembly language and some reverse engineering tools
  * [Reverse Engineering 102](https://malwareunicorn.org/workshops/re102.html#0) Learn Anti Reverse Engineering techniques including encrytion, VM evasion and Packing.
- [Liveoverflow Binary Exploitation](https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN) An awesome Youtube playlist describing about Binary Exploitation and Memory Corruption.
- [Radare2book](https://radare.gitbooks.io/radare2book/content/) Learn everything about the reverse engineering framework tool Radare2
- [Nightmare Binary Exploitation Course](https://github.com/guyinatuxedo/nightmare) Learn basics of Binary exploitation and reverse engineering
- [Bartosz Wójcik](https://www.pelock.com) Reverse engineering, antidebugging, polymorphic encryption, assembly programming, malware analysis
  - [Reverse engineering tools review](https://www.pelock.com/articles/reverse-engineering-tools-review) Advantages and disadvantages, alternative solutions.
  - [Windows Hot Patching Mechanism Explained](https://dev.to/pelock/windows-hot-patching-mechanism-explained-2m1f) Low-level technical analysis of Windows hot-patching feature.
  - [Assembly code size optimization tricks](https://dev.to/pelock/assembly-code-size-optimization-tricks-2abd) How to make you shellcodes smaller?
  - [How to write a CrackMe for a CTF competition](https://www.pelock.com/articles/how-to-write-a-crackme-for-a-ctf-competition) A tutorial of how to write a CTF crackme in C++.
  - [Polymorphic Encryption Algorithms](https://www.pelock.com/articles/polymorphic-encryption-algorithms) A tutorial of how to write a polymorphic engine in C++ & assembly.
  - [Anti reverse engineering. Malware vs Antivirus Software](https://www.pelock.com/articles/anti-reverse-engineering-malware-vs-antivirus-software) Techniques that make it difficult to reverse-engineer malware (malicious software).
  - [DLL Libraries API Hooking](https://www.pelock.com/articles/intercepting-dll-libraries-calls-api-hooking-in-practice) Intercepting DLL libraries calls. API hooking in practice.
  - [Assembly programming basics](https://www.pelock.com/articles/when-and-how-to-use-an-assembler-assembly-programming-basics) When and how to use an x86 assembler
  - [Anti-cracking protections for programmers](https://www.pelock.com/articles/how-to-make-crackers-life-harder-anti-piracy-protections-for-programmers) How to make cracker's life harder.
- [Linux System Call Table](http://blog.rchapman.org/posts/Linux_System_Call_Table_for_x86_64/) Useful when you are trying to write a shell code
- [x86 Assembly Guide](https://www.cs.virginia.edu/~evans/cs216/guides/x86.html) Learn the basics of 32-bit x86 Assembly programming.

  > Test You Knowledge

- [Pwn College](https://cse466.pwn.college/) CTF by Arizona State University
- [Micro Corruption CTF](https://microcorruption.com/login) Solve various challenges exploiting the code on MSP430 chip
- [Exploit Education: Nebula](https://exploit.education/nebula/) Exploit common weaknesses like SUID files permissions, buffer overflows, $PATH weaknesses
- [ROP Emporium](https://ropemporium.com/) Learn return-oriented programming through a series of challenges
- [Cyberdefenders RE101](https://cyberdefenders.org/labs/36) Binary Analysis challenges

---

### Communication Security

(Work in Progress)

### Wireless Security

(Work in Progress)

### Web Security

(Work in Progress)

### Cryptography

(Work in Progress)

### Operational Security

(Work in Progress)
