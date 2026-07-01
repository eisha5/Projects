# Eisha Khan

**Cybersecurity & AI Security Analyst**

Recent Cyber Operations graduate specializing in security operations, threat detection, and the emerging field of AI/LLM security. This repository is a portfolio of hands-on projects spanning defensive security, offensive security, malware analysis, and vulnerability research.

---

## About Me

I'm a Cybersecurity Analyst and 2025 Cyber Operations graduate (B.S., Dakota State University) with hands-on experience across SOC operations, threat detection, incident response, malware analysis, and reverse engineering — and a growing specialization in securing AI and large language model (LLM) systems.

I'm currently seeking an **entry-level role in AI Security, SOC operations, or Cyber Threat Intelligence**. The projects in this repository show how I approach real security problems end to end: building and defending enterprise networks, hunting threats across enterprise telemetry, reverse-engineering malware, testing systems from an attacker's perspective, and researching hardware-level vulnerabilities.

## Background

I earned my **B.S. in Cyber Operations from Dakota State University in 2025**, a program grounded in both offensive and defensive security, digital forensics, and secure systems. My academic and independent work covers the full defensive stack — designing and hardening enterprise networks, and hunting threats across SIEM, endpoint, and network telemetry — as well as offensive security through penetration testing and binary reverse engineering.

More recently, I've focused on the **security of AI systems**: applying the OWASP Top 10 for LLMs, the NIST AI Risk Management Framework, and ISO/IEC 42001 concepts, and studying agentic AI threat modeling and secure-AI-lifecycle practices. I've reinforced this through independent development — building an autonomous LLM-powered agent integrated with the Anthropic Claude API — which gave me practical exposure to prompt handling, structured API integration, and the security considerations of real-world LLM applications.

## Technical Skills

**AI & LLM Security** OWASP Top 10 for LLMs · Prompt Injection & Jailbreak Detection · LLM Output Validation & Guardrails · MITRE ATLAS · AI Threat Modeling · NIST AI RMF · ISO/IEC 42001 Concepts · Secure AI Lifecycle · RAG & AI Agent Security

**Security Operations & Investigation** SIEM Monitoring · Threat Hunting · Incident Response · Alert Triage & Validation · Log & Packet Analysis · Endpoint Forensics · Cross-Platform Log Correlation · MITRE ATT&CK

**Reverse Engineering & Malware Analysis** Ghidra · Static & Dynamic Analysis · Sandbox Analysis · Network Behavior Analysis · Assembly Fundamentals

**Offensive Security** Nmap · Metasploit · NetExec · SearchSploit · Enumeration · Vulnerability Analysis · Privilege Escalation

**Tools & Platforms** Splunk · Security Onion · Velociraptor · Wazuh · Arkime · Wireshark · Palo Alto NGFW · Sysmon

**Programming & Automation** Python · Bash · PowerShell · SQL

**Networking & Systems** TCP/IP · DNS · NAT · Layer 3 Routing · Network Segmentation · IDS/IPS · Firewalls · Windows · Linux (Ubuntu, Kali)

## Projects

### [AI Security Assessment & Threat Model — Autonomous LLM Agent](AI_Security_Assessment_LLM_Agent.pdf)

A source-level security assessment and threat model of an autonomous, LLM-driven decision agent built on the Anthropic Claude API. Maps the agent's attack surface to the OWASP Top 10 for LLMs — identifying indirect prompt injection through untrusted feeds as the primary risk — documents the existing safe-default controls (typed output validation, fail-closed defaults, data/instruction separation), rates findings by severity, and defines a prioritized hardening roadmap.

### [InvisibleFerret Malware Analysis](InvisibleFerret_Malware_Analysis.pdf)

Static and dynamic analysis of a Python-based information stealer linked to the North Korean "Contagious Interview" campaign. Examines the malware's modular class architecture, Base64-obfuscated C2 communication, cross-browser credential theft, and filesystem exfiltration, with runtime network behavior captured in a sandbox.

### [Enterprise Network Security Implementation](Enterprise_Network_Security_Implementation.pdf)

An enterprise network built and secured from scratch on a Palo Alto next-generation firewall — segmented LAN/DMZ/WAN zones, least-privilege security policies, inline malware inspection, Wazuh HIDS across a multi-host Windows domain, Sysmon telemetry, and Windows Defender hardening.

### [Threat Hunting & Incident Response](Threat_Hunting_Incident_Response.pdf)

A threat hunt and incident investigation across a 9-host Active Directory environment with no prior documentation, correlating Splunk, Security Onion, Velociraptor, and Arkime to profile hosts, validate alerts, and distinguish malicious activity from benign endpoint-protection behavior.

### [Internal Penetration Test](Internal_Penetration_Test_Report.pdf)

An assumed-breach penetration test of an internal /24 network — full methodology from discovery through exploitation and privilege escalation. Three hosts were compromised (a vsftpd backdoor, MS08-067, and an SSH-key + SUID escalation chain), with findings documented alongside CVSS scoring and remediation guidance.

### [GoFetch Vulnerability Research](GoFetch_Vulnerability_Research.pdf)

A research analysis of the GoFetch side-channel attack on Apple M-series processors — how the data memory-dependent prefetcher (DMP) breaks constant-time cryptography, the chosen-input key-extraction technique, the affected classical and post-quantum algorithms, and available software mitigations.

## Certifications

- Google Cybersecurity Professional Certificate — Coursera
- Securing Generative AI — Pearson / Coursera
- Building AI Products: Security Essentials — LinkedIn
- Microsoft Security Essentials Professional Certificate
- Microsoft Azure AI Essentials Professional Certificate
- Ubuntu Linux Professional Certificate — Canonical

## Contact

Open to entry-level opportunities in AI Security, SOC operations, and Cyber Threat Intelligence.

- **LinkedIn:** [linkedin.com/in/eisha-khan](https://www.linkedin.com/in/eisha-khan-8857a6287/)
