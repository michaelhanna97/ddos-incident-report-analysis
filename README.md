# 🌐 ICMP DDoS Incident Report Analysis – NIST Cybersecurity Framework

## 📌 Overview

This project analyzes a **Distributed Denial-of-Service (DDoS) attack** using a flood of ICMP packets that disrupted a company’s internal network. The incident is broken down and mapped to the **NIST Cybersecurity Framework (CSF)** functions: Identify, Protect, Detect, Respond, and Recover.

The goal of this analysis is to demonstrate how a real-world style incident can be documented, investigated, and aligned with industry-standard cybersecurity frameworks.

---

## 🗂️ Project File

- **ICMP-DDoS-Incident-Report-NIST-CSF.pdf**  
  A structured incident analysis that:
  - Summarizes the DDoS attack
  - Identifies root cause and weaknesses (unconfigured firewall)
  - Maps controls and responses to NIST CSF
  - Documents recovery steps and future prevention measures

---

## 🧠 Scenario Summary

- The company experienced a **DDoS attack** using a flood of **ICMP packets**
- Internal network services were unavailable for approximately **two hours**
- Normal internal traffic could not access network resources
- The security team:
  - Blocked incoming ICMP packets
  - Shut down non-critical services
  - Focused on restoring critical services first

The analysis then maps the organization’s actions to NIST CSF:

- **Identify** – Investigating the event and determining that an attacker exploited an **unconfigured firewall** to send ICMP floods  
- **Protect** – Implementing new **firewall rules**, **rate limiting**, and deploying **IDS/IPS**  
- **Detect** – Adding **source IP verification** and **network monitoring** for abnormal traffic patterns  
- **Respond** – Containing and isolating impacted systems, restoring critical services, reviewing logs, and reporting to management and authorities  
- **Recover** – Restoring normal operations, shutting down non-essential services during attack, and adjusting firewall rules to prevent future ICMP flood attempts  

---

## 🛠️ Skills & Concepts Demonstrated

- Understanding of **DDoS attacks** (ICMP flooding)
- Practical application of the **NIST Cybersecurity Framework (CSF)**
- Incident lifecycle thinking:
  - Identification
  - Protection strategies
  - Detection mechanisms
  - Response procedures
  - Recovery planning
- Use of core **network security controls**:
  - Firewalls and firewall rule configuration
  - IDS/IPS (Intrusion Detection/Prevention Systems)
  - Source IP verification
  - Network monitoring and traffic analysis
- **Incident documentation** and written analysis

---

## 📌 NIST CSF Mapping

### 🔎 Identify
- Investigated the event to determine that a malicious actor sent a flood of ICMP pings through an **unconfigured firewall**
- Recognized exposure due to missing firewall rules and lack of rate limiting

### 🛡 Protect
- Implemented a firewall rule to **limit incoming packet rates**
- Deployed **IDS/IPS** to filter ICMP traffic with suspicious characteristics

### 📡 Detect
- Configured **source IP verification** on the firewall to detect spoofed IP addresses
- Implemented **network monitoring software** to detect abnormal traffic patterns

### 🚨 Respond
- Isolated compromised or affected systems
- Prioritized restoration of **critical services**
- Reviewed network logs for unusual activity
- Documented the incident and reported it to management and, when appropriate, legal/regulatory bodies

### 🔁 Recover
- Restored network services to normal operation
- Temporarily shut down non-essential services to minimize load during recovery
- Updated firewall configurations to block or limit future ICMP flood attempts

---

## 📌 What This Project Shows Employers

This project demonstrates my ability to:

- Analyze and document a **DDoS (ICMP flood) incident**
- Apply the **NIST CSF** to a real-world style security event
- Understand and describe how **network controls** (firewalls, IDS/IPS, monitoring) mitigate attacks
- Think through the full **incident lifecycle**: identify, protect, detect, respond, recover
- Communicate technical security concepts in clear, structured written form

---

## 📌 Roles This Project Aligns With

The skills shown in this project are directly relevant to:

- **Cybersecurity Analyst (Entry Level)**
- **SOC Analyst – Tier 1**
- **Security Operations / Incident Response Trainee**
- **GRC Analyst (with focus on incident processes)**
- **IT Support / Help Desk with Security Focus**

---

## 📬 Contact

- **GitHub Portfolio:** *https://github.com/michaelhanna97*  
- **LinkedIn:** *your LinkedIn profile link here (optional)*

