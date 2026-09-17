<p align="center"><img src="banner.svg" alt="Ebrahim Mohamed — SOC Analyst · Detection Engineer · Cybersecurity Instructor" width="100%"></p>

<p align="center">
  <a href="https://linkedin.com/in/EbrahimMohamed"><img src="https://img.shields.io/badge/LinkedIn-EbrahimMohamed-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:EbrahimMohamed9299@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://cybertalents.com/members/Ebrahim9299"><img src="https://img.shields.io/badge/CyberTalents-Ebrahim9299-1F2937?style=flat-square" alt="CyberTalents"></a>
  <a href="https://tryhackme.com"><img src="https://img.shields.io/badge/TryHackMe-SOC%20L1%20%7C%20SOC%20L2%20%7C%20Red%20Teaming-212C42?style=flat-square&logo=tryhackme&logoColor=white" alt="TryHackMe"></a>
</p>

---

I work on both sides of the SOC: during the day I triage alerts, write and tune detection rules, and hunt threats on production Wazuh estates; the rest of the time I build and teach diploma-level cybersecurity programs. Every course I publish is built from the same detections, incidents and lab work I run myself.

## What I do

| Blue team (SOC) | Training & course design |
|---|---|
| Alert triage, incident reporting and threat hunting on a multi-tenant Wazuh SIEM | Lead Cybersecurity Instructor — SOC, CEH, eCIR and eCDFP diploma tracks |
| Detection engineering: PCRE2 rules, decoders, sibling/level tuning, rule-ID architecture across environments | Full session packages: instructor guide, student guide, guided lab, quiz, homework |
| SOAR enrichment and response (Shuffle, VirusTotal, AbuseIPDB) | Static-HTML course sites that run offline in a classroom |
| Log sources: Cloudflare, Nginx, Google Workspace, Azure, Windows, Linux, FIM | Investigation challenges and CTF-style capstones mapped to MITRE ATT&CK |

## Featured work

| Repository | What it is | Stack |
|---|---|---|
| [ecdfp-diploma](https://github.com/Ebrahim-Qareen/ecdfp-diploma) | Windows digital forensics diploma (INE eCDFP) — 6 sessions, one carry-through investigation, verified-evidence policy, render/density gates | HTML · Python · PowerShell |
| [ecir-diploma](https://github.com/Ebrahim-Qareen/ecir-diploma) | Enterprise incident response diploma (INE eCIR) — 10 sessions, SOC lab, investigation challenges, cheat sheets | HTML · Wazuh |
| [ceh-diploma](https://github.com/Ebrahim-Qareen/ceh-diploma) | CEH diploma — session pages, topic map, lab topology, practice-platform index | HTML · Python |
| [Wazuh-SIEM-Integration](https://github.com/Ebrahim-Qareen/Wazuh-SIEM-Integration) | Multi-OS Wazuh lab: agents, FIM, VirusTotal integration, Suricata IDS, DVWA attack traffic and custom rules | Wazuh · Suricata · Linux · Windows |
| [Network-Attack-Simulation-Lab](https://github.com/Ebrahim-Qareen/Network-Attack-Simulation-Lab) | pfSense + Snort lab detecting DoS, DNS abuse, ARP spoofing and malware C2 traffic | pfSense · Snort · Kali |

Live course sites: [eCDFP](https://ebrahim-qareen.github.io/ecdfp-diploma/) · [eCIR](https://ebrahim-qareen.github.io/ecir-diploma/) · [CEH](https://ebrahim-qareen.github.io/ceh-diploma/)

## Tooling

**SIEM / detection** — Wazuh · Splunk (SPL) · Microsoft Sentinel (KQL) · IBM QRadar · Elastic · Sigma · YARA · PCRE2
**Response / SOAR** — Shuffle · TheHive · VirusTotal · AbuseIPDB · Cloudflare WAF
**Network** — Suricata · Snort · pfSense · Sophos XG · Wireshark · Nmap
**Forensics** — Volatility · FTK Imager · Autopsy · Registry & event-log analysis · FlareVM · REMnux · CyberChef
**Offensive (for detection validation)** — Kali · Metasploit · Burp Suite · Nessus · Active Directory attack paths
**Scripting** — Python · Bash · PowerShell
**Frameworks** — MITRE ATT&CK · Cyber Kill Chain · NIST IR lifecycle · OWASP Top 10

## Home lab — "Cybersecurity Corp"

VMware environment used to develop and validate everything above: Sophos XG perimeter, Windows Server 2025 domain controller, Wazuh manager, domain-joined Windows 11/10/7 and Ubuntu endpoints with agents, Kali Purple as the attacker host, DVWA as the web target. An IAM/PAM extension (PowerShell identity lifecycle, Keycloak SSO + MFA, Windows LAPS, tiered admin model) is in progress.

## Currently

- Rebuilding a unified multi-environment Wazuh ruleset (per-environment rule files, readable ID scheme, no cross-tenant firing)
- Building the eCDFP and CEH diploma packages session by session
- Preparing for INE eTHP (Threat Hunting)

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Ebrahim-Qareen&show_icons=true&theme=github_dark&hide_border=true&hide_title=true" alt="GitHub stats" height="150">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ebrahim-Qareen&layout=compact&theme=github_dark&hide_border=true" alt="Top languages" height="150">
</p>

<p align="center"><i>Turn attacks into detections, and detections into knowledge.</i></p>
