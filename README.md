# parocyber-final-capstone-penetration-testing
Final capstone Ethical hacker
# Overview
This repository documents the completion of the ParoCyber final capstone activity, a hands-on ethical hacking and penetration testing project with Cisco Networking Academy.
The objective of this course was to conduct a full penetration testing engagement like
         Reconnaissance
         Vulnerability discovery
         Exploitation
         Flag capturing
         Recommendations or Remediations
# Scope & Objectives
        Perform SQL injection attacks to retrieve sensitive information
        Exploit web server  misconfigurations 
        Enumerate and exploit open SMB shares
        Analyze packet capture or PCAP files 
        Propose mitigation strategies or remediations
# Target networks
        10.5.5.0/24
        192.168.0.0/24
# Challenge 1: SQL Injection
        Identified vulnerable input fields
        Extracted database credentials using SQL injection payloads
        Cracked password hashes
        Accessed a protected system using compromised credentials 
        Retrieved the Flag 
# Challenge 2: Web Server Vulnerabilities
         Conducted directory enumeration
         Identified directory listing misconfigurations
         Navigated exposed subdirectories
         Retrieved flag file via URL manipulation
Skills learned: Web reconnaissance, directory enumeration
# Challenge 3: SMB Share Exploitation
         Scanned the network for SMB services
         Enumerated anonymous shares 
         Accessed unsecured SMB directories
         Downloaded and analyzed flags
Key skills: SMB enumeration, lateral access
# Challenge 4: PCAP Analysis
         Analysed captured network traffic using Wireshark
         Identified sensitive data transmitted in clear text
         Extracted URLs, IP addresses, and exposed file contents
         Retrieved final challenge flag
Skills learned: Network traffic Analysis, Data exposure detection
# Tools Used
         DVWA
         Kali Linux
         NMAP
         SMBclient
         Web Browser Development Tools
         Wireshark
# Remediation 
Each challenge includes remediation guidance covering:
         Input validation and prepared statements
         SMB access control and hardening
         Encryption of data in transit (HTTPS, SMB signing)
         Secure web server configuration
# Disclaimer
This project was completed and designed for strictly educational purposes in a controlled laboratory environment. Unauthorised testing against live systems is illegal and prohibited.
# Author
Omara Isaac Lucky | Uopeople University | SOC Analyst L1 | Cybersecurity
