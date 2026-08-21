# Blueteam-Journey
# 🔵 Blue Team Journey

## About Me
I am an aspiring Security Operations Center (SOC) Analyst passionate about threat detection, incident response, and vulnerability management. This repository documents my hands-on homelab projects, detection rules, and incident reports.

---

## 🛠️ Skills & Tools

| Category | Tools |
| :--- | :--- |
| **SIEM** | Splunk, Wazuh |
| **Vulnerability Assessment** | Nessus Essentials |
| **Network Analysis** | Wireshark |
| **Operating Systems** | Linux (Ubuntu, Kali), Windows |
| **Scripting** | Bash, PowerShell (learning) |

---

## 📁 Projects

### 1. Metasploitable Vulnerability Assessment
**Objective:** Identify and remediate critical vulnerabilities on an intentionally vulnerable Linux system.

**Tools:** Nessus Essentials, Metasploitable 2

**Findings:**
- **Critical:** VNC Server default password (`password`) – **Remediated**
- **Critical:** UnrealIRCd backdoor – **Remediated**
- **High:** vsftpd anonymous login enabled – **Remediated**

**Screenshots:**
![Before its fixe
<img width="1190" height="780" alt="image" src="https://github.com/user-attachments/assets/53ccbd1e-d379-456d-bd6b-73a29cad7eab" />

![After - VNC Fixed](screenshots/vnc-after.png)

**Lesson Learned:** Default credentials are a massive security risk. Always disable unnecessary services.

---

### 2. Simulated Brute-Force Attack Detection
**Objective:** Simulate a brute-force attack and detect it using Wazuh SIEM.

**Tools:** Kali Linux (attacker), Metasploitable 2 (victim), Wazuh (detection)

**Attack:** Used Hydra to perform SSH brute-force against Metasploitable.

**Detection:**
- Wazuh alerted on "Multiple SSH authentication failures"
- Alert triggered within 30 seconds of attack start

**Screenshots:**
![Hydra Attack](screenshots/hydra-attack.png)
![Wazuh Alert](screenshots/wazuh-alert.png)

**Lesson Learned:** SIEM tools can detect brute-force attacks in real-time through log analysis.

---

## 🎯 Current Learning Goals

- [ ] Complete BTL1 (Blue Team Level 1) – *Free alternative: BTLO challenges*
- [ ] Build a full Active Directory lab environment
- [ ] Create custom Wazuh rules for threat detection
- [ ] Write a full Incident Response playbook

---

## 📚 Resources I'm Using

- [TryHackMe - Cyber Defense Path](https://tryhackme.com)
- [Blue Team Labs Online](https://blueteamlabs.online)
- [The DFIR Report](https://thedfirreport.com)
- [Malware Traffic Analysis](https://malware-traffic-analysis.net)

---

## 📫 Connect With Me

- **LinkedIn:** [Your LinkedIn URL]
- **GitHub:** [Your GitHub URL]
- **Email:** [Your Email]

---

*"Every expert was once a beginner."*
