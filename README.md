<!-- Banner -->
<p align="center">
  <img src="assets/github-banner.png" alt="Paul - Junior Linux & Security Engineer banner" />
</p>

---

### 👋 Hi, I’m Paul

**Junior Linux & Security Engineer** preparing for relocation to Tokyo in **April 2026** (Working Holiday → Work Visa).  
I focus on **internal IT**, **Linux system administration**, and **security incident handling**.

- 🖥️ Building hands-on labs for **Ubuntu Server**, SSH hardening, log auditing and enterprise-style troubleshooting  
- 🛡️ Interested in **Internal IT / System Administrator / IT Support Engineer / SOC Tier 1** roles  
- 🇯🇵 Currently learning Japanese (≈ JLPT N4) and planning my next move to Japan  
- 🎯 Goal: join a **Tokyo-based company** as a Junior Internal IT / Security Engineer

---

### 🔗 Where to find me

<p align="left">
  <a href="mailto:paulvigneron2@gmail.com">
    <img src="https://img.shields.io/badge/Email-paulvigneron2%40gmail.com-red?style=for-the-badge&logo=gmail" alt="Email">
  </a>
  <a href="https://www.linkedin.com/in/paul-vigneron-7946461b2/">
    <img src="https://img.shields.io/badge/LinkedIn-Paul%20Vigneron-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn">
  </a>
  <a href="https://tryhackme.com/r/p/HexGuardSec">
    <img src="https://img.shields.io/badge/TryHackMe-HexGuardSec-212C42?style=for-the-badge&logo=tryhackme" alt="TryHackMe">
  </a>
</p>

---

### 🧰 Tech focus

**Core domains**

- 🐧 Linux administration (Ubuntu Server)
- 🔐 SSH hardening (keys-only access, Fail2ban, firewall rules)
- 👥 User / group / sudo management
- 📁 File services (Samba, permissions, role-based access)
- 📊 Log analysis & incident response (auth logs, sudo, SSH, services)
- 🌐 Basic networking (NAT/Host-Only labs, ports, services, intrusion detection)

**Technologies & tools**

<p align="left">
  <img src="https://img.shields.io/badge/Linux-ubuntu-orange?style=for-the-badge&logo=ubuntu" />
  <img src="https://img.shields.io/badge/Shell-Bash-4EAA25?style=for-the-badge&logo=gnu-bash" />
  <img src="https://img.shields.io/badge/SSH-Security-333333?style=for-the-badge&logo=openssh" />
  <img src="https://img.shields.io/badge/VirtualBox-Lab-183A61?style=for-the-badge&logo=virtualbox" />
  <img src="https://img.shields.io/badge/GitHub-Labs-181717?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/TryHackMe-Blue%20Team-212C42?style=for-the-badge&logo=tryhackme" />
</p>

---

### 🔬 Featured Labs

#### 🛰️ Enterprise Audit Incident Response
**Repo:** [`enterprise-audit-incident-response`](https://github.com/HexGuardSec/enterprise-audit-incident-response)  

Full blown **enterprise-style incident response lab** on a Linux server:

- 🔑 `sudo-access-leak` – detect and remove unused privileged accounts  
- 🧿 `unknown-ssh-service` – identify and shut down rogue SSH services  
- ⏰ `crontab-abuse` – track down malicious or forgotten cron jobs  
- 📂 `permissions-misconfiguration` – fix dangerous file/directory permissions  
- 🔍 `unknown-port-listener` – find suspicious listening ports and kill the service  

<p>
  <img src="https://img.shields.io/badge/Linux-Security-blueviolet?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Incident%20Response-success?style=flat-square" />
  <img src="https://img.shields.io/badge/Scope-SSH%2C%20sudo%2C%20services-important?style=flat-square" />
</p>

---

#### 🛡️ Linux System Security Lab
**Repo:** [`linux-system-security-lab`](https://github.com/HexGuardSec/linux-system-security-lab)

Enterprise-level **Linux hardening & auditing** with multiple scenarios:

- `01-user-permissions` – review users, groups, and sudo access  
- `02-ssh-hardening-and-access` – secure SSH config, keys-only auth  
- `03-system-enumeration` – enumerate services, processes, SUID binaries  
- `04-log-analysis` – analyze SSH and auth logs  
- `05-intrusion-no-firewall` – intrusion detection without firewall  
- `06-fail2ban-ssh-protection` – brute-force protection with Fail2ban  
- `07-broken-sudoers` → `10-unknown-port-service` – critical misconfig & unknown service scenarios  

<p>
  <img src="https://img.shields.io/badge/Topic-Linux%20Hardening-informational?style=flat-square" />
  <img src="https://img.shields.io/badge/Includes-Fail2ban%2C%20UFW%2C%20SSH-blue?style=flat-square" />
</p>

---

#### 🔐 SSH Hardening Lab
**Repo:** [`ssh-hardening-lab`](https://github.com/HexGuardSec/ssh-hardening-lab)

Secure SSH configuration on Ubuntu Server:

- Keys-only authentication (ed25519)
- Custom port, restricted users, disabled password login
- Fail2ban protection for SSH brute-force attempts
- Clear docs & screenshots for each step

<p>
  <img src="https://img.shields.io/badge/SSH-Hardening-333333?style=flat-square&logo=openssh" />
  <img src="https://img.shields.io/badge/Focus-Access%20Control-success?style=flat-square" />
</p>

---

#### 🔍 Linux Access Troubleshooting Lab
**Repo:** [`linux-access-troubleshooting-lab`](https://github.com/HexGuardSec/linux-access-troubleshooting-lab)

Real-world SSH access problems and fixes:

- `01-invalid-shell` – user with `/bin/false` or wrong shell  
- `02-missing-home` – missing home directory & login issues  
- `03-bad-permissions` – wrong `.ssh` and `authorized_keys` permissions  

<p>
  <img src="https://img.shields.io/badge/Focus-Troubleshooting-yellow?style=flat-square" />
  <img src="https://img.shields.io/badge/Use%20case-Internal%20IT%20Support-blue?style=flat-square" />
</p>

---

#### 📁 Samba Enterprise Lab
**Repo:** [`samba-enterprise-lab`](https://github.com/HexGuardSec/samba-enterprise-lab)

Role-based file sharing for a small company:

- Manual & automated Samba setup  
- Users: accountant, developer, employee  
- Shares with proper group-based access  
- Automation script to provision new workstations  

<p>
  <img src="https://img.shields.io/badge/Samba-File%20Sharing-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Access%20Control-informational?style=flat-square" />
</p>

---

#### 🎓 TryHackMe Learnings
**Repo:** [`tryhackme-learnings`](https://github.com/HexGuardSec/tryhackme-learnings)

Notes & summaries from completed rooms:

- `Pre-Security` track (certificate)  
- `Linux Fundamentals`, `Windows Fundamentals`, `Cyber Security 101` modules  
- Wireshark / Nmap / basic cryptography notes (John the Ripper, hashing, etc.)

<p>
  <img src="https://img.shields.io/badge/TryHackMe-Notes-212C42?style=flat-square&logo=tryhackme" />
  <img src="https://img.shields.io/badge/Type-Study%20Log-lightgrey?style=flat-square" />
</p>

---

### 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=HexGuardSec&show_icons=true&theme=tokyonight&count_private=true" alt="Paul's GitHub stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=HexGuardSec&theme=tokyonight" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=HexGuardSec&layout=compact&theme=tokyonight" alt="Top Languages" />
</p>

---

### 💬 Languages

- 🇫🇷 **French** – Native  
- 🇬🇧 **English** – B2  
- 🇯🇵 **Japanese** – ~N4, continuing study