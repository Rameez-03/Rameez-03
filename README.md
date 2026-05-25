<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1F3A,100:1F4E8C&height=140&section=header" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=30&duration=2400&pause=900&color=4F8CFF&center=true&vCenter=true&width=800&lines=Rameez+Ahmed;SOC+Analyst+%7C+Blue+Team+Operations;Threat+Detection+%7C+Incident+Response;Security+Monitoring+%7C+Automation+Focused" />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1F4E8C,100:0B1F3A&height=2&section=footer"/>


**BSc Computer Science · King's College London · Year Abroad @ University of Toronto**

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0072b1?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rameez-ahmed-a0802a190/)
[![Email](https://img.shields.io/badge/-rameez.r%40hotmail.co.uk-0078D4?style=flat-square&logo=microsoft-outlook&logoColor=white)](mailto:rameez.r@hotmail.co.uk)
[![GitHub](https://img.shields.io/badge/-Rameez--03-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Rameez-03)


---

## Skills
| Category | Skill | Project |
|---|---|---|
| 🟢 SOC | SIEM log ingestion, correlation and alert triage | [SOC and Systems Operation Lab](https://github.com/Rameez-03/SOC-Lab) |
| 🟢 SOC | Active Directory domain administration and endpoint management | [SOC and Systems Operation Lab](https://github.com/Rameez-03/IT-Infrastructure) |
| 🤖 AI/Automation | LLM-powered autonomous alert triage and response | [SOC AI Agent](https://github.com/Rameez-03/SOC-AI-Agent) |
| 🤖 AI/Automation | REST API integration and pluggable connector architecture | [SOC AI Agent](https://github.com/Rameez-03/SOC-AI-Agent) |
| 🟡 Detection Eng | Detection rule authoring and MITRE ATT&CK mapping | [SIEM Rule Validator](https://github.com/Rameez-03/SIEM-Rule-Validator) |
| 🟡 Detection Eng | Automated rule testing with CI/CD audit trail | [SIEM Rule Validator](https://github.com/Rameez-03/SIEM-Rule-Validator) |
| 🔵 CTF | Web exploitation - SQLi, XSS, IDOR, broken auth | [CTF Write-Ups](https://github.com/Rameez-03/CTF-Writeups) |
| 🔵 CTF | Network forensics and PCAP analysis | [CTF Write-Ups](https://github.com/Rameez-03/CTF-Writeups) |
| 🟣 Research | Post-quantum cryptographic standards implementation | [Dissertation (1st Class)](https://github.com/Rameez-03/IP-PQC-KEM) |
| 🟣 Research | Structured benchmarking and evidence-based technical reporting | [Dissertation (1st Class)](https://github.com/Rameez-03/IP-PQC-KEM) |
| 🟠 SecDev | OWASP Top 10, PCI DSS, GDPR compliance and audit | [Secure Bank App](https://github.com/Rameez-03/Secure-Bank) |
| 🟠 SecDev | DevSecOps pipeline - CI/CD, SAST, CVE scanning, cloud deployment | [Secure Bank App](https://github.com/Rameez-03/Secure-Bank) |

---

## Projects

### ◈ &nbsp;[Post-Quantum Cryptographic Systems — University Dissertation](https://github.com/Rameez-03/IP-PQC-KEM) &nbsp;`First-Class`
> Quantum-safe KEM aligned to NIST FIPS 203. Implemented in Python from mathematical first principles including NTT-based polynomial arithmetic, key generation, encapsulation, and decapsulation. Validated against all NIST KAT vectors across ML-KEM-512, ML-KEM-768, and ML-KEM-1024. Benchmarked across all security parameter sets with formal documented findings.

`NIST FIPS 203` &nbsp; `Python` &nbsp; `AES-GCM` &nbsp; `Key Exchange` &nbsp; `Benchmarking`

---

### ◉ &nbsp;[SOC and Systems Operation Lab](https://github.com/Rameez-03/SOC-Lab) &nbsp;`SOC | Infrastructure`
> Full enterprise IT architecture built from scratch: Windows Active Directory domain controller with users, OUs, group policies, and multiple vulnerable endpoints replicating a realistic corporate network. Wazuh SIEM/XDR + Shuffle SOAR + TheHive deployed as the security operations layer — full Tier 1 pipeline from alert ingestion to case closure. Custom detection rules for Mimikatz (MITRE T1003), brute-force, C2 beaconing, and lateral movement. Automated VirusTotal and AbuseIPDB enrichment.

`Wazuh` &nbsp; `Shuffle SOAR` &nbsp; `TheHive` &nbsp; `Active Directory` &nbsp; `VirusTotal` &nbsp; `AbuseIPDB` &nbsp; `Windows Server`

Repos: [IT-Infrastructure](https://github.com/Rameez-03/IT-Infrastructure) &nbsp;|&nbsp; [SOC-Lab](https://github.com/Rameez-03/SOC-Lab)

---

### ⚙ &nbsp;[SOC AI Agent](https://github.com/Rameez-03/SOC-AI-Agent) &nbsp;`AI/Automation | SOC`
> Fully autonomous AI-powered security analyst built in Python. Polls TheHive for open cases, triages true/false positives via a locally hosted LLM (Ollama/Qwen2.5), enriches IOCs through VirusTotal and Cortex APIs, executes MITRE ATT&CK mapped response playbooks, updates case records, and notifies analysts in real time. Pluggable connector architecture. Fully containerised with Docker Compose and FastAPI.

`Python` &nbsp; `FastAPI` &nbsp; `Docker` &nbsp; `Ollama` &nbsp; `LLM` &nbsp; `REST API`

---

### 🛡 &nbsp;[SIEM Rule Validator](https://github.com/Rameez-03/SIEM-Rule-Validator) &nbsp;`Detection Engineering`
> Standalone Python tool for testing Wazuh detection rules against synthetic log events without requiring a live SIEM instance. Implements a full detect, suppress, and correlate pipeline including sliding-window frequency analysis for brute-force and recon chain detection. GitHub Actions CI runs the full test suite on every rule change, providing an automated, auditable detection engineering workflow. Reduces rule iteration time from minutes to under one second.

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
  <img src="https://img.shields.io/badge/hashcat-000000?style=for-the-badge" />
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

