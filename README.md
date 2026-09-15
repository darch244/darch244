# Mostafa Ibrahim Abdelaziz

### AI Red Team | Offensive Security Engineer | Penetration Tester

<p align="center">
  <a href="https://linkedin.com/in/mostafa-ibrahim-60b543341">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/darch244">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://hackerone.com/darch244">
    <img src="https://img.shields.io/badge/HackerOne-000000?style=flat-square&logo=hackerone&logoColor=white" alt="HackerOne">
  </a>
  <a href="https://bugcrowd.com/">
    <img src="https://img.shields.io/badge/Bugcrowd-F26822?style=flat-square&logo=bugcrowd&logoColor=white" alt="Bugcrowd">
  </a>
  <a href="https://tryhackme.com/p/Darch244">
    <img src="https://img.shields.io/badge/TryHackMe-3F3F3F?style=flat-square&logo=tryhackme&logoColor=red" alt="TryHackMe">
  </a>
</p>

---

## Professional Summary

Offensive Security Engineer specializing in AI Red Teaming, Web Application Security, Active Directory exploitation, and enterprise attack simulation[cite: 3]. Active Bug Bounty researcher with Hall of Fame acknowledgments from TU Delft and Mindtickle for responsible disclosure of critical access control vulnerabilities[cite: 3].

Develops offensive automation tooling, reconnaissance pipelines, and adversarial AI testing frameworks mapped to MITRE ATT&CK and MITRE ATLAS[cite: 3]. Currently expanding deep technical research into AI security aligned with OSAI principles, focusing on LLM jailbreaking, prompt injection, and agentic attack surfaces[cite: 3].

---

## Technical Skills

| Domain | Core Competencies & Tooling |
| :--- | :--- |
| **AI / LLM Security** | AI Red Teaming, Adversarial LLM Testing, Direct/Indirect Prompt Injection, Jailbreaking, RAG Corpus Poisoning, MITRE ATLAS, OWASP Top 10 for LLM[cite: 3] |
| **Penetration Testing** | PTES, OWASP Testing Guide, NIST SP 800-115, MITRE ATT&CK, Web/Network/AD Pentesting, Vulnerability Assessment, Red Team Operations[cite: 3] |
| **Web App Security** | OWASP Top 10, IDOR, SQLi, XSS, CSRF, SSRF, XXE, OAuth, Business Logic Flaws, API Security, White-Box Source Code Review[cite: 2, 3] |
| **Active Directory & Network** | Kerberoasting, AS-REP Roasting, NTLM Relay, Pass-the-Hash, GPO/ACL Abuse, BloodHound, Lateral Movement, Enterprise VLANs[cite: 3] |
| **Security Operations & Enterprise** | SIEM (Splunk, ELK), Log Analysis, Threat Detection, Digital Forensics, EDR/XDR, Incident Response, Azure AD / IAM[cite: 3] |
| **Security Tools** | Burp Suite, Nmap, Nuclei, Metasploit, CrackMapExec, NetExec, Impacket, Responder, Wireshark, ffuf, httpx, katana, Garak, PyRIT[cite: 3] |
| **Programming & Systems** | Python (Asyncio, Pydantic, Requests), Bash, PowerShell, C++, Java \| Kali Linux, Ubuntu, Windows Server / AD[cite: 3] |
| **Cloud & DevOps** | AWS (EC2, S3, IAM), Docker, CI/CD Security, CSPM, CloudTrail, Azure Monitor[cite: 3] |

---

## Featured Projects

### LLM & AI Red Teaming Lab (`llm-redteam-lab`)
Adversarial testing framework for LLM applications and agentic workflows.
* Engineered a 110-probe attack library mapped directly to MITRE ATLAS categories (Prompt Injection, Jailbreak, System Prompt Extraction, Data Leakage).
* Built executable multi-step attack scenarios: autonomous agent browsing injection and RAG vector corpus poisoning.
* Integrated pluggable target connectors (OpenAI, Anthropic, local Ollama, and offline mock) with an automated heuristic and LLM-as-judge scoring engine.
* Production-grade release with 68 automated unit tests, strict type-checking, and interactive HTML/JSON reporting.

🔗 [Repository](https://github.com/darch244/llm-redteam-lab)

---

### Automated Reconnaissance Framework (`autorecon-framework`)
High-performance modular reconnaissance pipeline designed for asset discovery and attack-surface mapping[cite: 3].
* Engineered an asynchronous pipeline integrating `httpx`, `katana`, `nuclei`, and `waybackurls`[cite: 3].
* Automated end-to-end passive and active discovery, reducing manual reconnaissance time by 70%[cite: 3].
* Implemented zero-crash degradation logic with offline synthetic mock fallbacks for CI validation.
* Analyzed 500+ subdomains across production targets with structured JSON and Markdown triage reporting[cite: 3].

🔗 [Repository](https://github.com/darch244/autorecon-framework)

---

### Active Directory Threat Lab (`ad-threat-lab`)
Multi-VM enterprise Active Directory sandbox designed to simulate real-world attack paths[cite: 3].
* Simulated multi-stage adversary chains: Kerberoasting, AS-REP Roasting, NTLM Relay, Pass-the-Hash, and domain persistence[cite: 3].
* Executed privilege escalation via GPO misconfigurations and Active Directory ACL abuse[cite: 3].
* Documented end-to-end attack paths mapped against MITRE ATT&CK and validated defensive detection baselines[cite: 3].
* Identified and remediated 15+ security misconfigurations across domain controllers and joined workstations[cite: 3].

🔗 [Repository](https://github.com/darch244/ad-threat-lab)

---

## Vulnerability Disclosure & Bug Bounty Research

* **TU Delft Hall of Fame:** Recognized for responsible disclosure of a critical Broken Access Control vulnerability[cite: 3].
* **Mindtickle Hall of Fame:** Acknowledged for discovering and reporting 2 application security vulnerabilities[cite: 3].
* Active security researcher on HackerOne and Bugcrowd, reporting verified vulnerabilities to 3+ enterprise organizations[cite: 3].

---

## Technical Playbooks & Certification Syllabi Repositories

* **[OSWE — Web Expert Guide](https://github.com/darch244/OSWE-Offensive-Security-Web-Expert):** Complete OSWE study guide covering advanced web application security, exploitation, white-box source code review, and custom Python PoC development[cite: 2].
* **[OSEP — PEN-300 Guide](https://github.com/darch244/OSEP-Offensive-Security-Experienced-Penetration-Tester):** Advanced penetration testing, defense evasion, process injection, and breaching defenses preparation guide.
* **[OSCP — PEN-200 Methodology](https://github.com/darch244/OSCP-PEN200):** Hands-on penetration testing methodology, network exploitation notes, and privilege escalation workflows.
* **[CRTO — Red Team Operator Playbook](https://github.com/darch244/CRTO-Certified-Red-Team-Operator-study-notes):** Comprehensive adversary simulation notes, C2 infrastructure, Kerberos abuse, and post-exploitation tradecraft.
* **[CRTP — Active Directory Notes](https://github.com/darch244/CRTP-Professional):** Complete study guide and cheat sheets for enterprise Active Directory enumeration, domain privilege escalation, and trust abuse.
* **[Red Team Operator Playbook](https://github.com/darch244/Red-Team-Operator-Playbook):** Living Red Team methodology covering full attack chains from initial access to domain dominance based on OSCP, CRTP, and CRTO frameworks.

---

## Professional Experience

### Cybersecurity Content Creator & Instructor
**Hunters404 — Remote** | `Jan 2026 – Present`[cite: 3]
* Created and delivered practical networking, ethical hacking, and penetration testing curricula to a community of 2,000+ subscribers[cite: 3].
* Designed hands-on Active Directory exploitation and web vulnerability simulation labs[cite: 3].
* Developed offensive automation scripts reducing manual recon workflows by 70%[cite: 3].

### IT & Network Trainee
**Masrawy (ONA) — Giza, Egypt** | `May 2025 – Jul 2025`[cite: 3]
* Administered enterprise Windows Server and Active Directory environments: user management, GPOs, and authentication protocols[cite: 3].
* Managed enterprise TCP/IP networking, routing, switching, subnetting, and VLAN traffic isolation[cite: 3].
* Supported network monitoring, incident response, change management, and compliance documentation[cite: 3].

---

## Certifications

* **CompTIA Security+**[cite: 3]
* **Cisco CCNA**[cite: 3]
* **eJPTv2 & eJPTv1**[cite: 3]
* **Certified Cybersecurity Educator Professional (CCEP)**[cite: 3]
* **TCM External Pentest Playbook**[cite: 3]

---

## Advanced Security Training (In Preparation)

Hands-on lab preparation, adversary emulation, and self-study aligned with industry-standard syllabi[cite: 3]:

* **OSAI** — Offensive Security AI (Adversarial LLM testing & AI attack surfaces)[cite: 3]
* **CRTO** — Certified Red Team Operator (Adversary simulation, C2 operations, post-exploitation)[cite: 3]
* **CRTP** — Certified Red Team Professional (Active Directory exploitation & domain privilege escalation)[cite: 3]
* **OSWE (WEB-300)** — Advanced Web Application Security, white-box code review, custom Python PoC development[cite: 2, 3]
* **OSCP (PEN-200)** — Penetration Testing with Kali Linux[cite: 3]
* **OSEP (PEN-300)** — Evasion Techniques and Breaching Defenses[cite: 3]

---

## Education

**Bachelor of Computer Science — IT Department**  
*Faculty of Computing and AI, Cairo University, Giza, Egypt* | `Sep 2022 – Sep 2026`[cite: 3]

---

## Volunteering & Languages

* **Cybersecurity Trainer & CTF Organizer:** IEEE Cairo University Student Branch `(Sep 2025 – Jun 2026)`[cite: 3].
* **Languages:** Arabic (Native), English (Professional), French (Basic)[cite: 3].

---

## Contact

* **Email:** [himadarch@gmail.com](mailto:himadarch@gmail.com)[cite: 3]
* **LinkedIn:** [Mostafa Ibrahim](https://linkedin.com/in/mostafa-ibrahim-60b543341)[cite: 2]
* **GitHub:** [@darch244](https://github.com/darch244)
* **HackerOne:** [darch244](https://hackerone.com/darch244)[cite: 3]
* **TryHackMe:** [Darch244](https://tryhackme.com/p/Darch244)
