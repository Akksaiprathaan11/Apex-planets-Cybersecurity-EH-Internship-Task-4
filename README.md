Project Overview

This project demonstrates a controlled penetration testing and system hardening exercise performed in a safe lab environment using Kali Linux and Metasploitable 2.

The objective of this project is to understand:

How vulnerabilities are identified

How weak configurations can be exploited

How to apply security hardening techniques

⚠️ All activities were performed in an isolated lab environment for educational purposes only.

🎯 Objectives

Perform network and service enumeration

Identify vulnerable services

Conduct controlled password testing

Apply firewall-based system hardening

Document findings and mitigation strategies

🧰 Tools & Technologies Used
Category	Tools
OS	Kali Linux, Metasploitable 2
Scanning	Nmap
Password Testing	Hydra
Exploitation Framework	Metasploit
Firewall	UFW (Uncomplicated Firewall)
Environment	VirtualBox / VMware
🧪 Lab Environment Setup

Attacker Machine: Kali Linux

Target Machine: Metasploitable 2

Network Type: Host-only / Internal Network

This ensures:

No internet exposure

No impact on real systems

🔍 Phase 1: Reconnaissance & Enumeration

Performed service discovery to identify open ports and running services.

Identified Services:

FTP (vsftpd)

SSH

Telnet

HTTP (Apache)

SMB (Samba)

MySQL

IRC

Tomcat

This helped in understanding the attack surface.

🔐 Phase 2: Vulnerability Assessment

Identified vulnerabilities such as:

Weak authentication mechanisms

Outdated software versions

Unnecessary open services

Each vulnerability was categorized based on:

Risk level

Impact

Exploitability

🔑 Phase 3: Password Security Testing

A controlled password audit was conducted to test authentication strength.

✔ Weak credentials were detected
✔ Demonstrated risks of poor password policies

No unauthorized access or data modification was performed.

🛡️ Phase 4: System Hardening (Firewall Setup)

To reduce attack surface, firewall rules were applied using UFW:

Actions taken:

Allowed only essential services

Blocked unused and insecure ports

Enabled logging for monitoring

This significantly improved system security.

📊 Results Summary
Category	Status
Vulnerability Detection	✅ Completed
Password Testing	✅ Completed
Firewall Hardening	✅ Implemented
Risk Mitigation	✅ Applied
🛠️ Security Recommendations

Disable unused services

Use strong and unique passwords

Apply regular security updates

Implement firewall rules

Monitor logs continuously

📸 Screenshots

📁 Screenshots included:

Service enumeration

Password testing output

Firewall configuration

(Screenshots attached in repository)

📄 Learning Outcomes

Gained hands-on experience in penetration testing

Understood real-world attack vectors

Learned defensive security techniques

Improved system security awareness
