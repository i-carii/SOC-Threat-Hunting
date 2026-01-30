# SOC Analyst & Threat Hunting Lab 🛡️

## Objective
This project involved setting up a controlled lab environment to simulate real-world cyber attacks and practice detection, analysis, and response. The goal was to bridge the gap between theoretical security frameworks and hands-on incident response.

## Tools & Technologies Used
* **SIEM:** Splunk (Search Processing Language - SPL). 
* **Endpoint Monitoring:** Sysmon (System Monitor). 
* **Network Analysis:** Wireshark & Packet Captures (PCAP). 
* **Frameworks:** NIST 800-61 (Incident Response Lifecycle), MITRE ATT&CK. 
* **Environment:** Virtual Lab (TryHackMe / Home Lab).

---

## 🛠️ Skills Learned

* **Threat Detection & Analysis:** Proficiency in identifying indicators of compromise (IOCs) and recognizing attack patterns such as Brute-Force and process injection.
* **SIEM Mastery:** Expert use of Search Processing Language (SPL) to create complex queries for real-time monitoring and historical log analysis.
* **Network Forensics:** Ability to perform deep packet inspection (DPI) and analyze PCAP files to identify Command-and-Control (C2) traffic.
* **Incident Response:** Practical application of the NIST 800-61 lifecycle to manage security incidents from detection through recovery.
* **Security Frameworks:** Direct experience mapping adversary tactics and techniques using the MITRE ATT&CK and Cyber Kill Chain frameworks.
* **Data Visualization:** Enhanced security visibility by 40% through the creation of Sysmon-driven dashboards and reporting.
* 
---

## 🛠️ Phases of the Project

### 1. Threat Detection & Log Analysis
I utilized Splunk to monitor system logs and executed complex SPL queries to identify malicious patterns. 
* **Success:** Detected over 15 unauthorized access attempts and Brute-Force attacks. 
* **Example Query Logic:** Filtering for Event ID 4625 (Failed Logon) to identify account lockout patterns.

### 2. Endpoint Visibility with Sysmon
To gain deeper insight into the operating system, I deployed Sysmon. 
* **Result:** Identified malicious process injections that were hidden from standard Windows logs.
* **Impact:** Increased endpoint security visibility by 40%. 

### 3. Traffic & Protocol Analysis
I analyzed 50GB of packet captures to hunt for Command-and-Control (C2) signatures. 
* **Discovery:** Pinpointed C2 traffic by analyzing non-standard network protocol behaviors. 
* **Tool:** Wireshark was used for deep packet inspection and identifying threat vectors. 

### 4. Incident Response Methodology
Following the **NIST 800-61** lifecycle, I documented the response process for: 
1. **Preparation:** Configuring logging policies.
2. **Detection & Analysis:** Identifying Ransomware and Web Defacement signatures. 
3. **Containment, Eradication, & Recovery:** Implementing mitigations to stop the spread.
![alt](Screenshot%20(1).png)
![alt](Screenshot%20(2).png)

---

## Key Takeaways
* Developed proficiency in **Search Processing Language (SPL)** for rapid threat hunting. 
* Gained hands-on experience in identifying the **"Actions on Objectives"** phase of the Cyber Kill Chain. 
* Learned to translate raw log data into actionable security intelligence.

---
*Note: This project was completed To Prepeare for Tier1 SOC Analyst.* 
