# 🔴 Hacking Cheatsheets

```
    ██╗  ██╗ █████╗  ██████╗██╗  ██╗██╗███╗   ██╗ ██████╗ 
    ██║  ██║██╔══██╗██╔════╝██║ ██╔╝██║████╗  ██║██╔════╝ 
    ███████║███████║██║     █████╔╝ ██║██╔██╗ ██║██║  ███╗
    ██╔══██║██╔══██║██║     ██╔═██╗ ██║██║╚██╗██║██║   ██║
    ██║  ██║██║  ██║╚██████╗██║  ██╗██║██║ ╚████║╚██████╔╝
    ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝╚═╝╚═╝  ╚═══╝ ╚═════╝ 
     ██████╗██╗  ██╗███████╗ █████╗ ████████╗███████╗██╗  ██╗███████╗███████╗████████╗███████╗
    ██╔════╝██║  ██║██╔════╝██╔══██╗╚══██╔══╝██╔════╝██║  ██║██╔════╝██╔════╝╚══██╔══╝██╔════╝
    ██║     ███████║█████╗  ███████║   ██║   ███████╗███████║█████╗  █████╗     ██║   ███████╗
    ██║     ██╔══██║██╔══╝  ██╔══██║   ██║   ╚════██║██╔══██║██╔══╝  ██╔══╝     ██║   ╚════██║
    ╚██████╗██║  ██║███████╗██║  ██║   ██║   ███████║██║  ██║███████╗███████╗   ██║   ███████║
     ╚═════╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝   ╚═╝   ╚══════╝╚═╝  ╚═╝╚══════╝╚══════╝   ╚═╝   ╚══════╝
```

<p align="center">
  <img src="https://img.shields.io/badge/Penetration-Testing-red?style=for-the-badge" alt="Penetration Testing">
  <img src="https://img.shields.io/badge/Ethical-Hacking-orange?style=for-the-badge" alt="Ethical Hacking">
  <img src="https://img.shields.io/badge/Cybersecurity-blue?style=for-the-badge" alt="Cybersecurity">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
</p>

<p align="center">
  <b>📚 A comprehensive collection of penetration testing cheatsheets for security professionals</b>
</p>

<p align="center">
  <a href="#-cheatsheets">Cheatsheets</a> •
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-contributing">Contributing</a> •
  <a href="#-license">License</a>
</p>

---

## 🎯 About

**Hacking Cheatsheets** is a curated collection of quick reference guides for penetration testing and ethical hacking tools. Each cheatsheet provides:

- ✅ **Clear explanations** of tool functionality
- ✅ **Command syntax** with practical examples
- ✅ **Real-world scenarios** and use cases
- ✅ **Quick reference tables** for rapid lookup
- ✅ **Tips & best practices** from experienced pentesters

---

## 📖 Cheatsheets

### 🔴 Exploitation Framework

| Tool | Description | Cheatsheet |
|------|-------------|------------|
| **Metasploit Framework** | The world's most used penetration testing framework | [📄 View](./Metasploit/README.md) |
| **Meterpreter** | Advanced post-exploitation payload | [📄 View](./Metasploit/Meterpreter.md) |

### 🔍 Reconnaissance & Scanning
*Coming Soon...*

| Tool | Description | Status |
|------|-------------|--------|
| Nmap | Network discovery and security auditing | 🔜 Planned |
| Gobuster | Directory/DNS/VHost brute-forcing | 🔜 Planned |
| Nikto | Web server scanner | 🔜 Planned |

### 🌐 Web Application Testing

| Tool | Description | Cheatsheet |
|------|-------------|------------|
| **SQLMap** | SQL injection automation tool | [📄 View](./SQLMap/README.md) |
| Burp Suite | Web vulnerability scanner | 🔜 Planned |
| OWASP ZAP | Web app security scanner | 🔜 Planned |

### 🔓 Password Cracking
*Coming Soon...*

| Tool | Description | Status |
|------|-------------|--------|
| Hydra | Network login cracker | 🔜 Planned |
| John the Ripper | Password cracker | 🔜 Planned |
| Hashcat | Advanced password recovery | 🔜 Planned |

### 📡 Network Analysis
*Coming Soon...*

| Tool | Description | Status |
|------|-------------|--------|
| Wireshark | Network protocol analyzer | 🔜 Planned |
| tcpdump | Command-line packet analyzer | 🔜 Planned |

### 🔝 Privilege Escalation
*Coming Soon...*

| Topic | Description | Status |
|-------|-------------|--------|
| Linux PrivEsc | Linux privilege escalation techniques | 🔜 Planned |
| Windows PrivEsc | Windows privilege escalation techniques | 🔜 Planned |

---

## 🚀 Quick Start

### Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Hacking-Cheatsheets.git
cd Hacking-Cheatsheets
```

### Browse Cheatsheets

Navigate to any tool folder and open the README.md file:

```bash
# View Metasploit cheatsheet
cat Metasploit/README.md

# Or open in your favorite editor
code Metasploit/
```

### Offline Access

All cheatsheets are in Markdown format, making them:
- 📱 **Mobile-friendly** - Read on any device
- 🔌 **Offline accessible** - No internet required
- 🖨️ **Printable** - Create physical copies
- 🔍 **Searchable** - Use grep or your editor's search

---

## 📂 Repository Structure

```
Hacking-Cheatsheets/
│
├── README.md              # This file - Main index
├── LICENSE                # MIT License
├── CONTRIBUTING.md        # Contribution guidelines
├── .gitignore             # Git ignore rules
│
├── Metasploit/            # Metasploit Framework
│   ├── README.md          # Complete msfconsole guide
│   └── Meterpreter.md     # Meterpreter cheatsheet
│
├── SQLMap/                # SQL Injection Tool
│   └── README.md          # Complete SQLMap guide
│
├── Nmap/                  # (Coming Soon)
├── Burp-Suite/            # (Coming Soon)
└── ...
```

---

## 🤝 Contributing

Contributions are welcome! Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting a pull request.

### Ways to Contribute

- 📝 **Add new cheatsheets** for tools not yet covered
- 🔧 **Improve existing cheatsheets** with better examples
- 🐛 **Report issues** or suggest improvements
- 🌐 **Translate** cheatsheets to other languages
- ⭐ **Star this repo** to show your support!

---

## ⚠️ Legal Disclaimer

> **IMPORTANT:** These cheatsheets are intended for **educational purposes** and **authorized security testing only**. 
> 
> - ✅ Use on systems you own
> - ✅ Use with explicit written permission
> - ✅ Use in legal penetration testing engagements
> - ❌ Never use for unauthorized access
> - ❌ Never use for malicious purposes
> 
> **Unauthorized access to computer systems is illegal.** The authors are not responsible for any misuse of this information.

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🌟 Show Your Support

If you find these cheatsheets useful, please consider:

- ⭐ **Starring** this repository
- 🍴 **Forking** to contribute
- 📢 **Sharing** with fellow security professionals
- 💬 **Providing feedback** for improvements

---

## 📬 Contact

- **GitHub Issues** - For bug reports and feature requests
- **Pull Requests** - For contributions

---

<p align="center">
  <b>Happy Hacking! 🔴</b><br>
  <i>Remember: Hack responsibly, hack ethically!</i>
</p>

---

<p align="center">
  Made with ❤️ for the cybersecurity community
</p>
