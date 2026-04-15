# Information Security and Privacy Repository
A Brief explination of what is in this repository, why, and what each entity contains.
## Overview
The documents contained in this repository are PDF renders of lab excercises I completed as part of my coursework. Each lab was
formatted with Microsoft Word to clearly and accuratly answer questions, give information, and display images of the tools and information being used.

The labs contained in this repository display hands on practice with computer and network security principles as well as incident prevention and management. This includes aspects such as availability, integrity, authentication, confidentiality and non-repudiation to ensure secure transmission, storage and processing of information.

## Table of Contents
* Linux Core Commands
* Password Cracking
* Authentication Access Control
* Deciphering Classical Ciphers
* Using Public Key Algorithms
* Reconnaissance and Scanning
* Exploitation
* Wireless Exploitation
* Firewalls and Interusion Detection Systems
* Final Details

## [Linux Core Commands](https://github.com/DustinZCrawford/Information-Security-and-Privacy/blob/main/LinuxCoreCommands.pdf)
Focused on using the terminal in Ubuntu Linux to practice core commands for traversing a directory and creating, editing, and moving files. This lab includes a second [document](https://github.com/DustinZCrawford/Information-Security-and-Privacy/blob/main/SS.pdf) (found in the files of this repository) with images that display the processes used.

#### Applications and Tools:
* Ubuntu Linux
* Command Line

## [Password Cracking](https://github.com/DustinZCrawford/Information-Security-and-Privacy/blob/main/PasswdCracking.pdf)
Practiced password cracking via Kali Linux inside a virtual machine set up by me. Inside Kali I used the password cracking tool John the Ripper to discover passwords for other users.

#### Applications and Tools:
* Ubuntu Linux
* Kali Linux
* VMware
* Command Line
* [John the Ripper](https://www.kali.org/tools/john/) password cracking software

## [Authentication Access Control](https://github.com/DustinZCrawford/Information-Security-and-Privacy/blob/main/AuthAccessControl.pdf)
Used administrative permissions in Ubuntu Linux to display authentication, different levels of authorization, and access control through the terminal. This involved giving different user profiles unique passwords, and various levels of permission to view, access, edit and execute files on the machine.

#### Applications and Tools:
* Ubuntu Linux
* Command Line

## [Deciphering Classical Ciphers](https://github.com/DustinZCrawford/Information-Security-and-Privacy/blob/main/DecipheringClassicalCiphers.pdf)
Focused on deciphering messages from both a shift cipher (also known as a caesar cipher) and a substitution cipher. Methods I used were brute force and pattern recognition such as frequency analysis and statistics like most common letters and letter combinations.

#### Applications and Tools:
* Windows 10
* Google Chrome
* [CrypTool 1](https://www.cryptool.org/en/ct1/downloads/) for frequency analysis
* [practicalcryptography.com](http://practicalcryptography.com/cryptanalysis/text-characterisation/monogram-bigram-and-trigram-frequency-counts/) for frequency analysis

## [Using Public Key Algorithms](https://github.com/DustinZCrawford/Information-Security-and-Privacy/blob/main/UsingPublicKeyAlgorithms.pdf)
Practiced applications for public key algorithms by using Kleopatra along with integrity verification. I used Kleopatra to send and recive a message to a partner through encryption and decription with our public and private keys. This was hands on practice for authentication, authorization, access, and decryption. To verify the integrity of a download I compared the expected hash value of the download with the one in the download to see if the file had been tampered with.

#### Applications and Tools:
* Windows 11
* Kleopatra
* [Hash value calculator](https://md5file.com/calculator)
* [Verification test file](https://www.openoffice.org/download/index.html)

## [Reconnaissance and Scanning](https://github.com/DustinZCrawford/Information-Security-and-Privacy/blob/main/ReconnaissanceAndScanning.pdf)
This lab taught us how to gather information about people and systems using openly available
tools and how to scan network services using Kali Linux. We looked to see what kind of sensitive info can be found just by searching the web. Also, we used Kali and ran Nmap against a Metasploitable VM to find hosts and ports, and tried WHOIS lookups with Nmap scripts on various sites. The goal was to learn both how attackers do reconnaissance and how defenders can spot and close those information leaks. This lab was completed with a partner.

#### Applications and Tools:
* Ubuntu Linux
* VMware
* Kali Linux
* Command Line
* Google Chrome
* [Netcraft](https://sitereport.netcraft.com/)
* [The Wayback Machine](https://web.archive.org/)
* [Exploit DB](https://www.exploit-db.com/google-hacking-database)
* [CVE Listings](https://www.cvedetails.com/)
* [IP Geolocation sites](https://www.ipvoid.com/ip-to-google-maps/)
* Nmap
* Metasploit

## [Exploitation](https://github.com/DustinZCrawford/Information-Security-and-Privacy/blob/main/Exploitation.pdf)
The purpose of this lab was to perform vulnerability discovery and exploitation against a
Metasploitable 2 target from a Kali Linux virtual machine attacker, using both Metasploit and Armitage to exploit identified backdoors. This lap was completed with a partner.

#### Applications and Tools:
* Ubuntu Linux
* Ubuntu Metasploitable 2
* Metasploit
* Kali Linux
* VMware
* Command Line

## [Wireless Exploitation](https://github.com/DustinZCrawford/Information-Security-and-Privacy/blob/main/WirelessExploitation.pdf)
This lab focused on cracking wireless security protocols in an attempt to gain access to a local network using Wireshark to catpure network commmunication and Aircrack to obtain the necessary passwords. In this case, we had a personal Asus router to operate in a controlled network environment. This lab was completed with a partner.

#### Applications and Tools:
* Windows 10
* VirtualBox
* Kali Linux
* Command Line
* Asus access point
* Wireshark
* Aircrack

## [Firewalls and Interusion Detection Systems](https://github.com/DustinZCrawford/Information-Security-and-Privacy/blob/main/FirewallsAndIntrusionDetectionSystems.pdf)
This lab was ussed to learning how intrusion detection systems work. We used a Kali Linux virtual machine to target an Ubuntu Linux virtual machine. This sets up a virtual environment to simulate different intrusion systems where we could observe and learn real behaivors without risking damaging a real system. This lab was completed with a partner.

#### Applications and Tools:
* Ubuntu Linux
* Kali Linux
* VMware
* Command Line

## Final Details
Each one of these reports was a lab assignment given during a guided college course. There was a rubrik and instructions on what needed to be completed, but the work and results are original and from my own trial and error. Each lab took between 3-8 hours of total work time to be completed.
