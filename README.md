<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:0a192f,100:0d1117&height=160&section=header&text=Sagar%20Bidari&fontSize=40&fontColor=e6f1ff&fontAlignY=40&fontFamily=Space+Grotesk&desc=Cybersecurity%20Professional%20%E2%80%94%20Melbourne%2C%20AU&descSize=14&descAlignY=62&descColor=8892b0" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=400&size=18&duration=3000&pause=800&color=64FFDA&center=true&vCenter=true&width=600&lines=CompTIA+Security%2B+Certified+%F0%9F%94%90;SOC+Analyst+%26+Blue+Teamer;Attack-to-Detection+Homelab+Projects;Melbourne%2C+AU+%F0%9F%87%A6%F0%9F%87%BA)](https://git.io/typing-svg)

*"Security is not a product, but a process."* — Bruce Schneier

</div>

---

## 👾 About Me

Hey — I'm **Sagar**, a cybersecurity professional based in **Melbourne, Australia 🇦🇺**, transitioning into **threat detection, incident response, and blue team operations**. I hold **CompTIA Security+ CE** and completed the **Monash University Cybersecurity Bootcamp** (in partnership with edX).

My homelab work follows one pattern: **attack something on purpose, then prove — with real telemetry — the difference between an attempt that failed and one that would have succeeded.** That's the thread running through the projects below.

- 🔭 **Currently building:** full attack-and-detect labs (Wazuh, Splunk, Windows/Linux telemetry)
- 🌱 **Currently learning:** Microsoft Sentinel, detection engineering, SOC workflows & MITRE ATT&CK
- 🛡️ **Goal:** Land a SOC Analyst / Help Desk / Systems Administrator role in Melbourne
- 🏃 **Outside the terminal:** Cricket, the gym, and more AI automation than is strictly necessary
- 💡 **Background:** pivoted from hospitality/care into cybersecurity — zero regrets

---

## 🛡️ Certifications & Education

| Credential | Issuer | Status |
|---|---|---|
| 🏅 CompTIA Security+ CE | CompTIA | ✅ Certified |
| 🎓 Cybersecurity Bootcamp | Monash University × edX | ✅ Completed |
| 📚 SOC Analyst Path | TryHackMe / HTB | 🔄 In progress |

---

## 🧰 Tech Stack & Tools

<div align="center">

**Security & Detection**

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-3253DC?style=for-the-badge&logo=wazuh&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-214478?style=for-the-badge&logo=nmap&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)

**Operating Systems & Virtualisation**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=for-the-badge&logo=virtualbox&logoColor=white)

**Scripting & Dev**

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

**Frameworks & Standards**

![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-FF0000?style=for-the-badge&logo=target&logoColor=white)
![NIST](https://img.shields.io/badge/NIST_CSF-003087?style=for-the-badge&logo=nist&logoColor=white)
![Sigma](https://img.shields.io/badge/Sigma_Rules-2E8B57?style=for-the-badge&logo=yaml&logoColor=white)

</div>

---

## 🛡️ Featured Projects — Attack & Detect

Each one follows the same contract: **real attack → real telemetry → real detection logic**, with screenshots and a documented limitations/lessons-learned section — not just a write-up of what was supposed to happen.

| Project | What it proves | Stack |
|---|---|---|
| 🔑 [**RDP Brute-Force → Splunk Detection**](https://github.com/sagarbid/rdp-bruteforce-splunk-detection) | Ran a real Hydra brute-force against a Windows RDP target with two outcomes — one account locked out, one compromised — then built the Splunk SPL + Sigma detection logic to tell the difference, including fixing a correlation query that initially overstated what it proved | `Splunk` `Hydra` `Sigma` `MITRE ATT&CK` `Windows Event Logs` |
| 🖥️ [**Wazuh SOC Homelab**](https://github.com/sagarbid/wazuh-homelab-soc) | Deployed a full Wazuh manager + agent stack across VMware, simulated port scans / SSH brute-force / file-integrity events, and documented every command with screenshots end-to-end | `Wazuh` `VMware` `Kali` `Ubuntu` `MITRE ATT&CK` |
| 📊 [**Splunk SIEM — Vandalay Industries**](https://github.com/sagarbid/Splunk-SIEM-Monitoring-Vandalay-Industries) | Built Splunk dashboards and threshold alerts to detect DDoS, brute-force, and vulnerability-scan activity, correlating Nessus findings with Apache logs | `Splunk Enterprise` `SIEM` `Nessus` `Log Correlation` |
| 🔓 [**Password Cracking with Hashcat**](https://github.com/sagarbid/Password-Cracking-Hashcat) | Benchmarked MD5/SHA-1/bcrypt crack rates with dictionary and brute-force attacks — presented at the Monash Bootcamp conference on weak-password-policy risk | `Hashcat` `Python` `Bash` |
| 🔍 [**Automated Nmap Scanner**](https://github.com/sagarbid/Automated-Nmap-Network-Scanner) | Python CLI wrapping Nmap for structured network recon — target scanning, open-port ID, JSON/CSV export for downstream analysis | `Python` `Nmap` `CLI` |
| 🧪 [**VirtualBox Cybersecurity Lab**](https://github.com/sagarbid/VirtualBox-Cybersecurity-Lab) | The underlying lab environment — Kali, Ubuntu, and Windows VMs networked together as the base every other project runs on | `VirtualBox` `Networking` `Linux/Windows` |

> 📌 Pin these six on the profile (Settings → “Customize your pins”) so they're what a recruiter sees first — not the automation/tooling repos.

<!--
⚠️ Need links or to drop — tell me which:
- Mobile Device Forensics (simulated iPhone theft/fraud case)
- SOC Analysis — Virtual Space Industries
-->

---

## 📊 GitHub Stats

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=sagarbid&theme=tokyonight&hide_border=true&show_icons=true&count_private=true"/>
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sagarbid&theme=tokyonight&hide_border=true&layout=compact"/>

<img width="70%" src="https://github-readme-streak-stats-eight.vercel.app?user=sagarbid&theme=tokyonight&hide_border=true"/>

</div>

---

## 🌐 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sagarbidari)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sagarbid)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cybersecure@bidarisagar.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://www.bidarisagar.com)

</div>

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:0a192f,100:0d1117&height=120&section=footer&text=Let%27s%20Connect&fontSize=22&fontColor=64ffda&fontAlignY=50&fontFamily=Space+Grotesk&desc=Open%20to%20Cybersecurity%20Roles%20%7C%20bidarisagar.com&descSize=12&descAlignY=72&descColor=8892b0" />
