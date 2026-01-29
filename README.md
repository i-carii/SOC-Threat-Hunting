# SOC Analyst & Threat Hunting Lab 🛡️

## Objective
This project involved setting up a controlled lab environment to simulate real-world cyber attacks and practice detection, analysis, and response. [cite_start]The goal was to bridge the gap between theoretical security frameworks and hands-on incident response. [cite: 5, 21, 30]

## Tools & Technologies Used
* [cite_start]**SIEM:** Splunk (Search Processing Language - SPL). [cite: 6, 31]
* [cite_start]**Endpoint Monitoring:** Sysmon (System Monitor). [cite: 32]
* [cite_start]**Network Analysis:** Wireshark & Packet Captures (PCAP). [cite: 6, 18, 33]
* [cite_start]**Frameworks:** NIST 800-61 (Incident Response Lifecycle), MITRE ATT&CK. [cite: 6, 20, 34]
* [cite_start]**Environment:** Virtual Lab (TryHackMe / Home Lab). [cite: 30]

---

## 🛠️ Phases of the Project

### 1. Threat Detection & Log Analysis
[cite_start]I utilized Splunk to monitor system logs and executed complex SPL queries to identify malicious patterns. [cite: 31]
* [cite_start]**Success:** Detected over 15 unauthorized access attempts and Brute-Force attacks. [cite: 31]
* **Example Query Logic:** Filtering for Event ID 4625 (Failed Logon) to identify account lockout patterns.

### 2. Endpoint Visibility with Sysmon
[cite_start]To gain deeper insight into the operating system, I deployed Sysmon. [cite: 32]
* [cite_start]**Result:** Identified malicious process injections that were hidden from standard Windows logs. [cite: 32]
* [cite_start]**Impact:** Increased endpoint security visibility by 40%. [cite: 32]

### 3. Traffic & Protocol Analysis
[cite_start]I analyzed 50GB of packet captures to hunt for Command-and-Control (C2) signatures. [cite: 33]
* [cite_start]**Discovery:** Pinpointed C2 traffic by analyzing non-standard network protocol behaviors. [cite: 33]
* [cite_start]**Tool:** Wireshark was used for deep packet inspection and identifying threat vectors. [cite: 24, 33]

### 4. Incident Response Methodology
[cite_start]Following the **NIST 800-61** lifecycle, I documented the response process for: [cite: 34]
1. **Preparation:** Configuring logging policies.
2. [cite_start]**Detection & Analysis:** Identifying Ransomware and Web Defacement signatures. [cite: 34]
3. **Containment, Eradication, & Recovery:** Implementing mitigations to stop the spread.

---

## Key Takeaways
* [cite_start]Developed proficiency in **Search Processing Language (SPL)** for rapid threat hunting. [cite: 6, 31]
* [cite_start]Gained hands-on experience in identifying the **"Actions on Objectives"** phase of the Cyber Kill Chain. [cite: 6, 20]
* [cite_start]Learned to translate raw log data into actionable security intelligence. [cite: 5, 17]

---
[cite_start]*Note: This project was completed as part of my ongoing B.S. in Cybersecurity & Information Assurance at WGU.* [cite: 4, 9]
