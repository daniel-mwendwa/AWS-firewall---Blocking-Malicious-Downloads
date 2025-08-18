# 🔒 Blocking Malicious Downloads with AWS Network Firewall

This project demonstrates how to **block malicious downloads** using **AWS Network Firewall** integrated with **Suricata rules**.  
It highlights a proactive approach to network security, ensuring that employees are protected from accessing malware-hosting domains.

---

## 📌 Problem Statement
A common cybersecurity concern is employees unknowingly downloading malicious software from unauthorized sites.  
Attackers disguise malware as legitimate applications, leading to:
- Data breaches  
- System corruption  
- Financial losses  

**Objective:** Prevent employees from accessing risky sites before any damage occurs.

---

## ⚙️ Approach
To mitigate this risk:
1. **Initial Testing** – Attempted access to a test malicious site on a sandbox (confirmed reachable).  
2. **Deploying AWS Network Firewall** – Configured Suricata rules to identify and block traffic to malicious domains.  
3. **Verification** – Retested access, which was successfully blocked by the firewall.  

---

## 🚀 Implementation Overview
- **AWS VPC** for network segmentation.  
- **AWS Network Firewall** deployed for filtering malicious traffic.  
- **Suricata Rules** configured to block known malware-hosting domains.  
- **Testing** confirmed that malicious sites were no longer accessible.

---

## ✅ Results
- Successfully blocked access to malicious websites.  
- Reduced risk of malware infections within the organization.  
- Strengthened proactive security posture.  

---

## 📈 Conclusion
By using AWS Network Firewall with Suricata rules, organizations can:
- Prevent employees from downloading malware.  
- Maintain operational efficiency with minimal disruptions.  
- Expand firewall rules to cover broader threats in the future.  

---

## 📚 Author
**Daniel Mwithui**  
Cybersecurity Analyst / Cloud Security

---
[LinkedIn](https://www.linkedin.com/in/daniel-mwendwa-mwithui/) | [GitHub](https://github.com/daniel-mwendwa)
