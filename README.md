# 🛡️ hackNos-2.1 - Penetration Testing Narrative

## 📄 Summary
This document outlines the penetration testing process conducted against the **hackNos-2.1** virtual machine. The methodology follows a structured approach across key phases: **scoping, information gathering, discovery, enumeration, exploitation**, and **post-exploitation**.

---

## 1️⃣ Target Scoping

### 1.1 Gathering Client Requirements
- Description of what was required from the client, including testing goals and boundaries.

### 1.2 Preparing the Test Plan
- Plan for the testing procedure, including the tools and methods to be used.

### 1.3 Profiling Test Boundaries
- Outlining the systems and resources that were included or excluded from the test.

### 1.4 Defining Business Objectives
- Understanding the business context and objectives behind the penetration test.

---

## 2️⃣ Information Gathering

### 2.1 Identifying the Target Machine's IP Address
- Finding the IP address of the target machine, either manually or via network scanning.

### 2.2 Collecting Basic Information About the Target
- Gathering information about the system, services, and applications running on the target machine.

---

## 3️⃣ Target Discovery

### 3.1 Checking Machine Availability (e.g., ping)
- Verifying if the target machine is reachable on the network.

### 3.2 OS Fingerprinting Techniques
- Using tools to identify the operating system running on the target machine.

---

## 4️⃣ Enumeration & Port Scanning

### 4.1 Nmap & SSH Service Analysis

#### 4.1.1 Investigating SSH Service
- Analyzing the SSH service for version information and vulnerabilities.

#### 4.1.2 Running Nmap Scans
- Using Nmap to scan the target for open ports and potential vulnerabilities.

---

## 5️⃣ Vulnerability Mapping

### 5.1 Manual Vulnerability Scanning
- Performing manual checks for known vulnerabilities and misconfigurations.

### 5.2 Automated Vulnerability Scanning Tools
- Using automated tools (e.g., Nessus, OpenVAS) to detect vulnerabilities.

### 5.3 Web Application Analysis (if applicable)
- Assessing any web applications on the target for security flaws.

---

## 6️⃣ Target Exploitation

### 6.1 Exploiting Local File Inclusion (LFI) Vulnerability
- Steps to exploit an LFI vulnerability to gain access to sensitive files.

---

## 7️⃣ Post Exploitation

### 7.1 Password Cracking

#### 7.1.1 Identifying Hash Format
- Identifying the hash format used for storing passwords (e.g., MD5, SHA1).

#### 7.1.2 Cracking with John the Ripper
- Using tools like **John the Ripper** to crack password hashes.

#### 7.1.3 Leveraging SSH Access
- Using SSH keys or credentials obtained during the exploit phase.

### 7.2 Vertical Privilege Escalation

#### 7.2.1 Obtaining User Flag
- Escalating privileges to the user level and obtaining flags.

### 7.3 Horizontal Privilege Escalation

#### 7.3.1 Obtaining Root Flag
- Further escalation to obtain root/admin access and complete the test by getting the root flag.

