# İKÜ CİS — Cybersecurity Cheat Sheets

> **İstanbul Kültür Üniversitesi · Cryptography & Information Security Club**  
> A growing collection of reference sheets for members studying ethical hacking, network security, and CTF competitions.

---

## 📂 Sheets in This Repo

| File | Module | Domain | Level |
|------|--------|--------|-------|
| [`cheatsheet_networking.html`](cheatsheet_networking.html) | 01 | Networking | Essential |
| [`cheatsheet_footprinting.html`](cheatsheet_footprinting.html) | 02 | Reconnaissance | Essential |
| [`cheatsheet_nmap.html`](cheatsheet_nmap.html) | 03 | Enumeration | Essential |

---

## 📋 Contents at a Glance

### Module 01 — Networking Basics
Foundation concepts every security practitioner needs before touching a target.

- OSI Model — all 7 layers with roles
- TCP vs UDP comparison
- Essential ports reference
- Subnetting quick-reference table
- TCP 3-Way Handshake breakdown
- DNS record types (A, AAAA, MX, CNAME, TXT, PTR…)
- Key protocols & concepts (ARP, ICMP, NAT, DHCP…)

---

### Module 02 — Footprinting
Passive and active reconnaissance — mapping the attack surface before scanning.

- Footprinting methodology (6-step flow: OSINT → Infrastructure → DNS → Web → Employee → Report)
- WHOIS / DNS commands
- OSINT tools reference
- Google Dork operators
- Service footprinting commands
- Web footprinting techniques
- Passive vs Active recon distinction
- Information targets — what to collect

---

### Module 03 — Nmap Enumeration
*(Source: Hack The Box Academy)*  
Everything needed to enumerate hosts, services, and vulnerabilities with Nmap.

- Core scan types: SYN (stealth), TCP Connect, UDP, Version Detection, OS Detection, Ping Scan
- Essential flags & options
- Port specification, timing & speed controls, output options
- Port states explained
- NSE script categories
- HTB enumeration workflow (5-step recommended sequence)
- Firewall / IDS evasion techniques
- Service-specific NSE scripts
- Reading Nmap output + output file formats
- Useful one-liners

---

## 🚀 Usage

All sheets are standalone HTML files — just open them in any browser, no server required.

```bash
# Clone the repo
git clone https://github.com/<your-org>/cis-cheatsheets.git
cd cis-cheatsheets

# Open any sheet directly
open cheatsheet_nmap.html          # macOS
xdg-open cheatsheet_networking.html  # Linux
start cheatsheet_footprinting.html   # Windows
```

They're also print-friendly — use `Ctrl+P` / `Cmd+P` for a clean PDF export.

---

## 🗺️ Roadmap

Planned modules to add:

- [ ] Module 04 — Service Enumeration (FTP, SSH, SMB, SNMP, IMAP/POP3)
- [ ] Module 05 — Web Application Enumeration (Gobuster, ffuf, Burp basics)
- [ ] Module 06 — Password Attacks (Hydra, Hashcat, John)
- [ ] Module 07 — Privilege Escalation (Linux & Windows)

---

## 🤝 Contributing

Members are welcome to contribute corrections, additions, or new modules.

1. Fork the repo and create a branch (`feat/module-04-service-enum`)
2. Keep the existing HTML template and dark cyberpunk styling
3. Open a pull request with a short description of what you added

---

## ⚠️ Disclaimer

These materials are intended **solely for educational purposes** within the İKÜ CİS club — for CTF practice, lab environments, and ethical security research. Never use these techniques against systems you do not own or have explicit written permission to test.

---

*İKÜ CİS · v1.0 · Maintained by club members*
