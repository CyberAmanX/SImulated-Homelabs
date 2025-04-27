## 🚀 SecureLab: Building a Detection-Focused Security Homelab

(Screenshots/homelab.png)  


### Welcome to my personal cybersecurity project where I built a real-world, attack-and-detect focused Security Homelab from scratch!

This lab covers **Active Directory**, **Windows & Linux Clients**, **Security Monitoring Servers** with **Wazuh**, **Sysmon**, and **Real Attack Simulations** — from initial setup to active threat detection and analysis!

---

## 🛠️ Project Goals

- Build a mini enterprise-like environment in a home network.
- Simulate real-world attacks and persistence techniques.
- Detect threats using **Sysmon** and **Wazuh**.
- Analyze incidents like a SOC Analyst or Threat Hunter.
- Sharpen blue-team and red-team skills.

---

## 🔥 What's Inside?

| Phase | Description |
|:---|:---|
| **1. Network Design** | Designed a secured lab topology with routers, VMs, and isolated networks. |
| **2. Environment Setup** | Installed Windows Server 2022, Windows 11, Ubuntu Linux, configured Active Directory, DNS, DHCP. |
| **3. Security Monitoring** | Deployed Wazuh Server and installed Sysmon on all endpoints. |
| **4. Attack Simulations** | Simulated real-world attacks (malware, persistence, privilege escalation). |
| **5. Detection and Response** | Tuned Wazuh rules, analyzed Sysmon logs, documented detection workflows. |

---

## ⚙️ Technologies Used

- **VMWare** & **VirtualBox** for virtualization
- **Windows Server 2022** and **Windows 11**
- **Ubuntu Linux**
- **Active Directory Services** (AD DS)
- **DNS / DHCP** Servers
- **Wazuh SIEM**
- **Sysmon** for endpoint telemetry
- **MITRE ATT&CK Framework** as reference
- **Attack simulation tools** and custom payloads


## 🧠 Attack Simulations & Detection Highlights

| Attack | Method | Detection |
|:---|:---|:---|
| **Payload Execution** | Dropped `payload.exe` on client | Detected via Sysmon Event ID 1, Wazuh alert |
| **Scheduled Task Persistence** | Created hidden task with schtasks | Detected Sysmon Event 106 |
| **Reverse Shell** | Using msfvenom payload | Outbound network connection detected |
| **Privilege Escalation** | Exploited service misconfiguration | Wazuh high severity alert triggered |

> Detailed detection logs and analysis screenshots available in the documentation!

---

## 📚 Resources

- [Download ISO Files](https://ln5.sync.com/dl/831828380#cbtjtrs7-yhmjd4ad-yaxm6hka-x97b3ug7)
- [Grant Collins Security Lab Guide](https://projectsecurity.teachable.com/courses/2721940/lectures/59518536)
- [Wazuh Installation Docs](https://documentation.wazuh.com/current/installation-guide/index.html)
- [Sysmon Official Guide](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon)

---

## ✨ Inspiration

This project was inspired by real-world incident response workflows, SOC analyst practices, and the continuous need to think like both **attacker** and **defender**.

---

## 🚧 Future Work

- Add Email Server to simulate phishing detection.
- Deploy Honeypots (Canary tokens) inside the network.
- Configure Wazuh Rules for advanced custom detection.
- Simulate ransomware and DCSync attacks.
- Build an Automated Incident Response playbook.

---

## 📥 Download Full Report

> 📄 [**Download the full PDF Documentation here**](docs/full_report.pdf)


---

## 🧑‍💻 About Me

I’m a cybersecurity enthusiast passionate about blue teaming, SOC operations, and learning by building and breaking things!  
Always exploring the next frontier of security engineering.

**🔗 Let's Connect on LinkedIn** → [Your LinkedIn Profile]

---

## 🌟 If you liked this project, please ⭐ star it on GitHub!  
## 📢 Contributions, suggestions, or collaborations are welcome!

---

# Footer:

> **Disclaimer:** This project is strictly for educational purposes.  
> **Please do not use any knowledge gained here for illegal activities.**

---

# 🚀 Let's Hunt Threats Like Pros!


