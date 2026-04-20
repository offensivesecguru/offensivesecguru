# Hi, I'm Marlone Michaud 👋

Cybersecurity student graduating July 2026, focused on **SOC analysis and blue team operations**. I build hands-on labs to develop real-world skills in threat detection, log analysis, network defense, and penetration testing. Currently holding **CompTIA Security+** and pursuing my **CEH**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-marlone--michaud-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/marlone-michaud)

---

## 🔧 Skills & Tools

`Kali Linux` `Splunk` `Metasploit` `Burp Suite` `Wireshark` `Nmap` `pfSense`  
`grep` `awk` `Linux CLI` `OWASP Top 10` `MITRE ATT&CK` `VirtualBox / VMware`

---

## 🎓 Certifications

- ✅ CompTIA Security+
- 🔄 CEH *(in progress)*

---

## 📁 Projects

### 🔴 [Pentest-Lab](https://github.com/offensivesecguru/Pentest-Lab)
Full penetration test against Metasploitable 2 and OWASP Juice Shop in an isolated home lab.  
Covers the full attack lifecycle: recon → exploitation → post-exploitation → documentation.

- Exploited **vsftpd 2.3.4** (CVE-2011-2523) and **Samba usermap_script** (CVE-2007-2447) for root shells
- Identified SQL injection, XSS, broken auth, and misconfigurations in Juice Shop
- Mapped findings to **MITRE ATT&CK** and **OWASP Top 10**
- Tools: Nmap, Metasploit, Burp Suite, Kali Linux

---

### 🟡 [Network-Security-Lab](https://github.com/offensivesecguru/network-security-lab)
Home lab focused on firewall configuration, network segmentation, and traffic analysis.

- Deployed and configured **pfSense** with rule-based access control across WAN/LAN/Lab segments
- Captured and analyzed traffic in **Wireshark**: SYN scans, cleartext credentials (Telnet), ARP anomalies
- Mapped findings to **MITRE ATT&CK** (T1040, T1046, T1557)
- Tools: pfSense, Wireshark, Nmap, Kali Linux, Metasploitable 2

---

### 🔵 [SOC-Alert-Investigation](https://github.com/offensivesecguru/soc-alert-investigation)
SOC log analysis simulating a real-world brute force SSH attack investigation.

- Analyzed authentication logs to identify repeated failed login attempts
- Identified source IP and frequency using `grep`, `awk`, `sort`, `uniq`
- Mapped to **MITRE ATT&CK T1110** (Brute Force)
- Recommended: account lockout, MFA, continuous log monitoring

---

## 📊 GitHub Stats

![offensivesecguru's GitHub stats](https://github-readme-stats.vercel.app/api?username=offensivesecguru&show_icons=true&theme=dark&hide_border=true)

---

*All lab work conducted in isolated environments. No production systems were targeted.*
