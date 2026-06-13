<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1F3A,100:1F4E8C&height=140&section=header" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=30&duration=2400&pause=900&color=4F8CFF&center=true&vCenter=true&width=800&lines=Rameez+Ahmed;SOC+Analyst+%7C+Blue+Team+Operations;Threat+Detection+%7C+Incident+Response;Security+Monitoring+%7C+Automation+Focused" />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1F4E8C,100:0B1F3A&height=2&section=footer"/>


**BSc Computer Science · King's College London · Year Abroad @ University of Toronto**

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rameez-ahmed-a0802a190/)
[![Email](https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:rameez.r@hotmail.co.uk)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rameez-03)
[![Portfolio](https://img.shields.io/badge/Portfolio-00d4ff?style=for-the-badge&logo=vercel&logoColor=black)](https://rameez-03.github.io)

</div>

---

## 🎓 Certifications

<div align="center">

[![Security+](https://img.shields.io/badge/CompTIA_Security%2B-FF0000?style=for-the-badge&logo=comptia&logoColor=white)](https://github.com/Rameez-03/Certifications/blob/main/Security%2B.png)
[![Network+](https://img.shields.io/badge/CompTIA_Network%2B-FF0000?style=for-the-badge&logo=comptia&logoColor=white)](https://github.com/Rameez-03/Certifications/blob/main/Network%2B.png)
[![Google](https://img.shields.io/badge/Google_Cybersecurity-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://github.com/Rameez-03/Certifications/blob/main/GoogleCyber.png)
[![TryHackMe](https://img.shields.io/badge/TryHackMe_SOC_L1-1DB954?style=for-the-badge&logo=tryhackme&logoColor=white)](https://github.com/Rameez-03/Certifications/blob/main/SOC1.png)

</div>


---

## Projects

### ◈ &nbsp;[Post-Quantum Cryptographic Systems — University Dissertation](https://github.com/Rameez-03/IP-PQC-KEM) &nbsp;`First-Class`
> Quantum-safe KEM aligned to NIST FIPS 203. Implemented in Python from Mathematical first principles including NTT-based Polynomial Arithmetic, Key Generation, Encapsulation, and Decapsulation. Validated against all NIST KAT vectors across ML-KEM-512, ML-KEM-768, and ML-KEM-1024. Benchmarked across all Security Parameter Sets with Formal Documented Findings.

`NIST FIPS 203` &nbsp; `Python` &nbsp; `AES-GCM` &nbsp; `Key Exchange` &nbsp; `Benchmarking`

---

### ◉ &nbsp;[SOC and Systems Operation Lab](https://github.com/Rameez-03/SOC-Lab) &nbsp;`SOC | Infrastructure`
> Full Enterprise IT Architecture built from scratch: Windows Active Directory Domain Controller with users, OUs, Group Policies, and multiple Vulnerable Endpoints replicating a realistic corporate Network. Wazuh SIEM/XDR + Shuffle SOAR + TheHive deployed as the Security Operations Layer — full Tier 1 Pipeline from Alert Ingestion to Case Closure. Custom Detection Rules for Mimikatz (MITRE T1003), Brute-Force, C2 Beaconing, and Lateral Movement. Automated VirusTotal and AbuseIPDB Enrichment.

`Wazuh` &nbsp; `Shuffle SOAR` &nbsp; `TheHive` &nbsp; `Active Directory` &nbsp; `VirusTotal` &nbsp; `AbuseIPDB` &nbsp; `Windows Server`

Repos: [IT-Infrastructure](https://github.com/Rameez-03/IT-Infrastructure) &nbsp;|&nbsp; [SOC-Lab](https://github.com/Rameez-03/SOC-Lab)

---

### ⚙ &nbsp;[SOC AI Agent](https://github.com/Rameez-03/SOC-AI-Agent) &nbsp;`AI/Automation | SOC`
> Fully Autonomous AI-powered Security Analyst built in Python. Polls TheHive for open cases, Triages true/false positives via a locally hosted LLM (Ollama/Qwen2.5), Enriches IOCs through VirusTotal and Cortex APIs, Executes MITRE ATT&CK mapped response playbooks, Updates case records, and Notifies analysts in real time. Pluggable connector architecture. Fully containerised with Docker Compose and FastAPI.

`Python` &nbsp; `FastAPI` &nbsp; `Docker` &nbsp; `Ollama` &nbsp; `LLM` &nbsp; `REST API`

---

### 🛡 &nbsp;[SIEM Rule Validator](https://github.com/Rameez-03/SIEM-Rule-Validator) &nbsp;`Detection Engineering`
> Standalone Python tool for Testing Wazuh Detection Rules against Synthetic Log Events without requiring a live SIEM instance. Implements a full detect, suppress, and correlate pipeline including sliding-window frequency analysis for brute-force and recon chain detection. GitHub Actions CI runs the full test suite on every rule change, providing an automated, auditable detection engineering workflow. Reduces rule iteration time from minutes to under one second.

`Python` &nbsp; `Wazuh` &nbsp; `GitHub Actions` &nbsp; `CI/CD` &nbsp; `Detection Engineering` &nbsp; `MITRE ATT&CK`

---

### ⚑ &nbsp;[CTF Write-Ups](https://github.com/Rameez-03/CTF-Writeups) &nbsp;`CTF`
> TryHackMe and HackTheBox — web exploitation (Burp Suite, sqlmap), Linux privesc (linPEAS, GTFOBins), network forensics (Wireshark PCAP, C2 detection, credential recovery), DFIR investigations correlating Sysmon logs and PCAPs to reconstruct full attack timelines.

`Burp Suite` &nbsp; `sqlmap` &nbsp; `linPEAS` &nbsp; `Wireshark` &nbsp; `Sysmon` &nbsp; `DFIR`

---

### ▣ &nbsp;[Secure Bank Application](https://github.com/Rameez-03/Secure-Bank) &nbsp;`SecDev + GRC`
> OWASP Top 10 mitigations — bcrypt, CSRF tokens, secure sessions. Full DevSecOps pipeline with GitHub Actions CI/CD, Jest automated testing (38 tests), Trivy CVE scanning, and Arko SAST reducing hackable score from 59% to 48%. Deployed to AWS EC2 with Docker Compose, nginx, and CloudWatch monitoring. Full GRC audit: STRIDE threat model, GDPR compliance (ROPA, DPIA, Breach Register), PCI DSS cardholder data protection.

`OWASP` &nbsp; `GDPR` &nbsp; `bcrypt` &nbsp; `Docker` &nbsp; `AWS EC2` &nbsp; `GitHub Actions` &nbsp; `STRIDE`

---

## Tools

<p align="center">
  <img src="https://img.shields.io/badge/Wazuh-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white" />
  <img src="https://img.shields.io/badge/Elastic-000000?style=for-the-badge&logo=elastic&logoColor=white" />
  <img src="https://img.shields.io/badge/Wireshark-000000?style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Burp_Suite-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Nmap-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/sqlmap-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/CyberChef-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Shuffle_SOAR-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/TheHive-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Microsoft_Defender-000000?style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/VirusTotal-000000?style=for-the-badge&logo=virustotal&logoColor=white" />
  <img src="https://img.shields.io/badge/AbuseIPDB-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-000000?style=for-the-badge&logo=javascript&logoColor=white" />
</p>

---

## Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Rameez-03&theme=github-compact&hide_border=true" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Rameez-03&theme=github-dark&hide_border=true" />
</p>

