# 🛡️ CyberShield Corp – Linux & SQL Security Audit

## 📘 Project Overview

**CyberShield Corp** is a fictional cybersecurity firm specializing in providing secure IT solutions to small and medium-sized enterprises. As part of their internal security enhancement initiative, a comprehensive audit of Linux systems and SQL databases was conducted to identify vulnerabilities, assess current security measures, and recommend improvements.

---

## 🎯 Objectives

- Evaluate the security posture of Linux servers and SQL databases.
- Identify misconfigurations, outdated packages, and potential vulnerabilities.
- Assess user access controls and permissions.
- Provide actionable recommendations to strengthen system and database security.

---

## 🛠️ Tools and Technologies

- **Linux (Ubuntu 20.04 LTS)** – Primary operating system for servers.
- **MySQL 8.0** – Relational database management system in use.
- **Lynis** – Security auditing tool for Unix-based systems.
- **chkrootkit** – Tool to locally check for signs of a rootkit.
- **ufw (Uncomplicated Firewall)** – Interface to manage firewall rules.
- **Fail2Ban** – Intrusion prevention software framework.
- **SQLMap** – Automated tool for SQL injection and database takeover.
- **Bash Scripting** – Automation of routine security checks.

---

## 🧪 Methodology

1. **System Information Gathering**: Collected data on installed packages, running services, and open ports using native Linux commands and tools.

2. **Security Auditing**: Employed Lynis to perform in-depth security scans of the Linux systems, identifying areas of concern.

3. **Rootkit Detection**: Utilized chkrootkit to scan for known rootkits and malware signatures.

4. **Firewall Assessment**: Reviewed and configured ufw to ensure only necessary ports and services were accessible.

5. **Intrusion Prevention**: Implemented and configured Fail2Ban to monitor log files and ban IPs showing malicious signs.

6. **Database Security Evaluation**: Analyzed MySQL configurations, user privileges, and potential vulnerabilities using SQLMap and manual inspection.

7. **Automation**: Developed Bash scripts to automate regular security checks and generate reports.

---

## 📊 Findings

- **Outdated Packages**: Several critical packages were outdated, lacking recent security patches.

- **Excessive User Privileges**: Some users had unnecessary sudo privileges, increasing the risk of privilege escalation.

- **Open Ports**: Unused services were running, exposing unnecessary ports to potential attackers.

- **Weak Firewall Rules**: The firewall was not configured to restrict access effectively.

- **MySQL Vulnerabilities**: Default configurations were in place, and some users had excessive privileges without proper justification.

---

## ✅ Recommendations

- **Regular Updates**: Implement a routine schedule for updating system packages and applying security patches.

- **User Privilege Review**: Conduct periodic reviews of user accounts and adjust privileges based on the principle of least privilege.

- **Service Management**: Disable or remove unused services to minimize the attack surface.

- **Firewall Configuration**: Strengthen ufw rules to allow only necessary traffic and monitor for unauthorized access attempts.

- **Database Hardening**: Secure MySQL by changing default settings, enforcing strong passwords, and limiting user privileges.

- **Automation**: Utilize the developed Bash scripts to perform regular security audits and maintain system integrity.

---

## 📁 Project Structure

