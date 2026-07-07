# 🔐 Security Write-ups

A collection of my hands-on security work, split into two categories:

- **[`CTFs/`](./CTFs)** — Offensive security exercises: enumeration, exploitation, privilege escalation, and post-exploitation analysis on intentionally vulnerable machines (HackMyVM, VulnHub, TryHackMe).
- **[`Forensic-Analysis/`](./Forensic-Analysis)** — Digital forensics and incident response reports: evidence handling, chain of custody, timeline reconstruction, and root cause analysis.

Each write-up follows a consistent structure so findings are easy to compare and evidence-based conclusions are clearly separated from analysis.

---

## 🚩 CTFs

| Platform | Machine | Focus |
|---|---|---|
| HackMyVM | [Soc1](./CTFs/HackMyVM/Soc1) | *(short tag, e.g. web exploitation → priv esc)* |
| HackMyVM | [gift](./CTFs/HackMyVM/gift) | |
| HackMyVM | [Hunter](./CTFs/HackMyVM/Hunter) | |
| VulnHub | [LazySysAdmin](./CTFs/VulnHub/LazySysAdmin) | |
| VulnHub | [Thales](./CTFs/VulnHub/Thales) | |

## 🕵️ Forensic Analysis

| Case | Type | Summary |
|---|---|---|
| [CF-2026-002](./Forensic-Analysis/Case-CF-2026-002) | Memory & disk forensics | Samba persistence + web shell + local privilege escalation (Dirty COW, PwnKit) |
| [CF-2026-003](./Forensic-Analysis/Case-CF-2026-003) | Full incident response | Multi-stage domain compromise: SSH brute-force → SQLi → PwnKit → HiveNightmare → Zerologon |
| [CF-2026-004](./Forensic-Analysis/Case-CF-2026-004) | Memory, disk & network forensics | vsftpd 2.3.4 backdoor exploitation (CVE-2011-2523), full session reconstructed from PCAP |
| [Linux Incident 3](./Forensic-Analysis/Case-2025-12-SSH-Bruteforce) | Disk & log forensics | SSH brute-force, credential exfiltration, memory capture via `avml` |

---

## ⚠️ Note on Confidentiality

All content in this repository is based on lab exercises, CTF platforms, or synthetic/anonymized scenarios. No real client, employer, or production data, logs, or identifiable information is included in any report.
