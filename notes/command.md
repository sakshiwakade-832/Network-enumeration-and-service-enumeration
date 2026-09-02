# Commands Used in Network Enumeration Lab

## 1. Nmap – Service Version Detection and FTP

nmap -sV <target-ip> , ftp <target-ip> --> Used to connect to an FTP service in the authorized lab environment.

## 2. Netstat – Network Connections

netstat -an --> Used to display active network connections and listening ports.

## 3. NBTScan – NetBIOS Enumeration

nbtscan <target-ip> --> Used to gather NetBIOS-related information from the target system.

## 4. SMBClient – SMB Enumeration

smbclient -L //<target-ip> --> Used to enumerate available SMB shares.

## 5. Telnet

telnet <target-ip> <port> --> Used to test connectivity to the Telnet service in the authorized lab environment.

## 6. SNMPWalk – SNMP Enumeration

snmpwalk -v 2c -c public <target-ip> --> Used to enumerate information exposed through SNMP.

## 7. Script

nmap --script <script-name> <target-ip> --> NSE scripts allow Nmap to perform more detailed checks than simple port scanning.
