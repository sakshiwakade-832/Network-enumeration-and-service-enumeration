# 🔐 Network Enumeration & Service Enumeration Lab

## 📌 Project Overview

This project documents a hands-on cybersecurity lab focused on network reconnaissance and service enumeration.

The practical exercises involved identifying network services, analyzing open ports, investigating network connections, and enumerating services such as SMB and SNMP.

All activities were performed in an authorized laboratory environment for educational purposes.

## 🎯 Objectives

- Perform network reconnaissance
- Identify open ports and services
- Detect service versions
- Analyze active network connections
- Perform NetBIOS enumeration
- Enumerate SMB shares
- Investigate FTP and Telnet services
- Perform SNMP enumeration
- Practice command-line cybersecurity tools
- Document practical findings

## 🛠️ Tools Used

- Nmap
- FTP
- Telnet
- Netstat
- NBTScan
- SMBClient
- SNMPWalk
- Linux / Kali Linux

## 🔎 Practical Exercises

### 1. Nmap Service Version Detection

Command:

nmap -sV <target-ip>

(screenshots/01-nmap-service-version.jpeg.jpeg)

The `-sV` option was used to identify services and their versions running on the target system.

### 2. FTP

Command:

ftp <target-ip>

(screenshots/01-nmap-service-version.jpeg.jpeg)

FTP was investigated to understand the identification and connection of an FTP service in the lab environment.

### 3. Telnet

Command:

telnet <target-ip>

(screenshots/02-telnet.jpeg.jpeg)

Telnet was used to understand remote service connectivity and investigate an identified Telnet service.

### 4. Netstat

Command:

netstat -an

Used to view active network connections and listening ports.

### 5. NBTScan

NBTScan was used to gather NetBIOS-related information from the target system.

### 6. SMBClient

Command:

smbclient -L //<target-ip>

Used to enumerate available SMB shares.

### 7. Script

A script was used during the practical to assist with network information gathering and enumeration.

### 8. SNMPWalk

SNMPWalk was used to enumerate information exposed through the SNMP service in the authorized lab environment.

## 📚 Key Learning Outcomes

Through this lab, I gained practical experience in:

- Network reconnaissance
- Port scanning
- Service enumeration
- Service version detection
- Network connection analysis
- NetBIOS enumeration
- SMB enumeration
- SNMP enumeration
- Linux command-line tools
- Basic cybersecurity assessment methodology

## 🔐 Security Disclaimer

All activities documented in this repository were performed in an authorized laboratory environment for educational purposes.

These techniques should only be used against systems for which explicit authorization has been obtained.

## 👩‍💻 Author

### Sakshi Wakade

Cybersecurity Learner | Computer Engineering Graduate

**Skills:**  
`Cybersecurity` `Networking` `Nmap` `Linux` `SMB` `SNMP` `Reconnaissance` `Enumeration`
