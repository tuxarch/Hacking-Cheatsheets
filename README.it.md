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
  <b>📚 Una raccolta completa di cheatsheets di penetration testing per professionisti della sicurezza</b>
</p>

<p align="center">
  <a href="#-cheatsheets">Cheatsheets</a> •
  <a href="#-per-iniziare">Per iniziare</a> •
  <a href="#-contribuire">Contribuire</a> •
  <a href="#-licenza">Licenza</a>
</p>

---

## 🎯 Info sul progetto

**Hacking Cheatsheets** è una raccolta curata di guide di riferimento rapido per strumenti di penetration testing ed ethical hacking. Ogni cheatsheet fornisce:

- ✅ **Spiegazioni chiare** sulle funzionalità degli strumenti
- ✅ **Sintassi dei comandi** con esempi pratici
- ✅ **Scenari reali** e casi d'uso
- ✅ **Tabelle di riferimento rapido** per una consultazione veloce
- ✅ **Consigli & best practice** da pentester esperti

---

## 🎯 Metodologia d'attacco (Kill Chain)

> **NOVITÀ!** Guida completa passo-passo per il penetration testing basata sul framework MITRE ATT&CK.

| Fase | Descrizione | Guida |
|-------|-------------|-------|
| **1. Accesso iniziale** | Exploit, phishing, credenziali | [📄 Visualizza](./Attack-Methodology/01-Initial-Access.md) |
| **2. Enumerazione** | Discovery di sistemi e reti | [📄 Visualizza](./Attack-Methodology/02-Enumeration.md) |
| **3. Privilege Escalation** | Ottenere accesso root/SYSTEM | [📄 Visualizza](./Attack-Methodology/03-Privilege-Escalation.md) |
| **4. Movimento Laterale** | Muoversi attraverso la rete | [📄 Visualizza](./Attack-Methodology/04-Lateral-Movement.md) |
| **5. Persistenza** | Mantenere l'accesso | [📄 Visualizza](./Attack-Methodology/05-Persistence.md) |
| **6. Defense Evasion** | Bypassare AV/EDR/AMSI | [📄 Visualizza](./Attack-Methodology/06-Defense-Evasion.md) |
| **7. Azioni sugli obiettivi** | Data exfiltration e impatto | [📄 Visualizza](./Attack-Methodology/07-Actions-Objectives.md) |

👉 **[Panoramica completa della Kill Chain](./Attack-Methodology/README.md)**

---

## 🛡️ Blue Team (Defensive Security)

> **NOVITÀ!** Guide complete sulla sicurezza defensiva per analisti SOC e incident responder.

| Argomento | Descrizione | Guida |
|-------|-------------|-------|
| **Incident Response** | Ciclo di vita IR, contenimento, procedure | [📄 Visualizza](./Blue-Team/Incident-Response.md) |
| **Log Analysis** | Analisi log Windows/Linux & Event ID | [📄 Visualizza](./Blue-Team/Log-Analysis.md) |
| **SIEM Detection** | Query Splunk/ELK & dashboard | [📄 Visualizza](./Blue-Team/SIEM-Detection.md) |
| **Threat Hunting** | Tecniche di hunting proattivo | [📄 Visualizza](./Blue-Team/Threat-Hunting.md) |
| **Hardening** | Checklist di hardening Windows/Linux | [📄 Visualizza](./Blue-Team/Hardening.md) |
| **Sigma Rules** | Regole di detection platform-agnostic | [📄 Visualizza](./Blue-Team/Sigma-Rules.md) |
| **YARA Rules** | Pattern di detection malware & IOC | [📄 Visualizza](./Blue-Team/YARA-Rules.md) |

👉 **[Panoramica completa Blue Team](./Blue-Team/README.md)**

---

## ☁️ Cloud Security

> **NOVITÀ!** Guide al cloud pentesting per AWS, Azure e GCP.

| Provider | Descrizione | Guida |
|----------|-------------|-------|
| **AWS** | S3, IAM, Lambda, EC2, IMDS | [📄 Visualizza](./Cloud-Security/AWS-Pentesting.md) |
| **Azure** | Azure AD, Blob Storage, VM, Key Vault | [📄 Visualizza](./Cloud-Security/Azure-Pentesting.md) |
| **GCP** | GCS, IAM, Compute, Cloud Functions | [📄 Visualizza](./Cloud-Security/GCP-Pentesting.md) |

👉 **[Panoramica completa sulla Cloud Security](./Cloud-Security/README.md)**

---

## 📱 Mobile Security

> **NOVITÀ!** Guide al mobile app pentesting per Android e iOS.

| Piattaforma | Descrizione | Guida |
|----------|-------------|-------|
| **Android** | Analisi APK, Frida, bypass root detection | [📄 Visualizza](./Mobile-Security/Android-Pentesting.md) |
| **iOS** | Analisi IPA, jailbreak, Objection, keychain | [📄 Visualizza](./Mobile-Security/iOS-Pentesting.md) |

👉 **[Panoramica completa sulla Mobile Security](./Mobile-Security/README.md)**

---

## 🐳 Container Security

> **NOVITÀ!** Guide al pentesting di Docker & Kubernetes.

| Piattaforma | Descrizione | Guida |
|----------|-------------|-------|
| **Docker** | Container escape, analisi immagini, daemon exploitation | [📄 Visualizza](./Container-Security/Docker-Pentesting.md) |
| **Kubernetes** | Bypass RBAC, pod escape, secrets extraction | [📄 Visualizza](./Container-Security/Kubernetes-Pentesting.md) |

👉 **[Panoramica completa sulla Container Security](./Container-Security/README.md)**

---

## 🎭 Social Engineering

> **NOVITÀ!** Tecniche di social engineering, campagne di phishing e guide al pretexting.

| Argomento | Descrizione | Guida |
|-------|-------------|-------|
| **Phishing** | Email phishing, GoPhish, Evilginx2, vishing, smishing | [📄 Visualizza](./Social-Engineering/Phishing.md) |
| **Pretexting** | Personas, scenari, manipolazione psicologica | [📄 Visualizza](./Social-Engineering/Pretexting.md) |

👉 **[Panoramica completa sulla Social Engineering](./Social-Engineering/README.md)**

---

## 📝 Reporting Templates

> **NOVITÀ!** Template di report professionali per pentester e bug bounty hunter.

| Template | Descrizione | Guida |
|----------|-------------|-------|
| **Report di Pentest** | Struttura completa di un report di penetration test | [📄 Visualizza](./Reporting/Pentest-Report-Template.md) |
| **Report di Bug Bounty** | Template per l'invio di report su HackerOne/Bugcrowd | [📄 Visualizza](./Reporting/Bug-Bounty-Report-Template.md) |
| **Executive Summary** | Riassunto non tecnico per il management | [📄 Visualizza](./Reporting/Executive-Summary-Template.md) |

---

## 🔍 OSINT (Open Source Intelligence)

> **NOVITÀ!** Metodologia OSINT completa e guide agli strumenti.

| Argomento | Descrizione | Guida |
|-------|-------------|-------|
| **People Search** | Trovare individui online, ricerca telefono/indirizzo | [📄 Visualizza](./OSINT/People-Search.md) |
| **OSINT di Email** | Scoperta email,controllo dei data breach, verifica | [📄 Visualizza](./OSINT/Email-OSINT.md) |
| **Social Media** | Ricerca username, OSINT specifico per piattaforma | [📄 Visualizza](./OSINT/Social-Media-OSINT.md) |
| **Dominio & IP** | WHOIS, DNS, sottodomini, ricognizione IP | [📄 Visualizza](./OSINT/Domain-IP-OSINT.md) |
| **OSINT di Immagini** | Reverse image search, metadati EXIF | [📄 Visualizza](./OSINT/Image-OSINT.md) |

👉 **[Panoramica completa sulla OSINT](./OSINT/README.md)**

---

## 🌐 Pentesting di rete

> **NOVITÀ!** Guide complete al penetration testing di rete.

| Argomento | Descrizione | Guida |
|-------|-------------|-------|
| **Scansione delle porte** | Nmap, Masscan, RustScan | [📄 Visualizza](./Network-Pentesting/Port-Scanning.md) |
| **Enumerazione della rete** | SMB, SNMP, NFS, LDAP, DNS | [📄 Visualizza](./Network-Pentesting/Network-Enumeration.md) |
| **Attacchi MITM** | ARP spoofing, DNS spoofing, SSL strip | [📄 Visualizza](./Network-Pentesting/MITM-Attacks.md) |
| **Exploitation di Servizi** | FTP, SSH, SMB, RDP, database | [📄 Visualizza](./Network-Pentesting/Service-Exploitation.md) |

👉 **[Panoramica completa sul Pentesting di rete](./Network-Pentesting/README.md)**

---

## 🏁 Cheatsheets su CTF

> **NOVITÀ!** Guide complete per competizioni CTF su HackTheBox, TryHackMe, PicoCTF.

| Categoria | Descrizione | Guida |
|----------|-------------|-------|
| **Web** | SQLi, XSS, SSTI, LFI, Auth bypass | [📄 Visualizza](./CTF/Web-CTF.md) |
| **Crypto** | RSA, AES, hash, encoding, XOR | [📄 Visualizza](./CTF/Crypto-CTF.md) |
| **Ingegneria inversa** | Ghidra, IDA, GDB, patching | [📄 Visualizza](./CTF/Reverse-Engineering-CTF.md) |
| **Forensics** | Steganografia, memoria, disco, PCAP | [📄 Visualizza](./CTF/Forensics-CTF.md) |
| **Pwn/Binary** | Buffer overflow, ROP, shellcode | [📄 Visualizza](./CTF/Pwn-CTF.md) |

👉 **[Panoramica completa sui CTF](./CTF/README.md)**

---

## 📡 Hacking di dispositivi IoT

> **NOVITÀ!** Hacking di dispositivi IoT, firmware analysis e guide all'hardware hacking.

| Argomento | Descrizione | Guida |
|-------|-------------|-------|
| **Analisi del Firmware** | Binwalk, estrazione, RE, secrets | [📄 Visualizza](./IoT-Hacking/Firmware-Analysis.md) |
| **Hardware Hacking** | UART, JTAG, SPI, I2C, porte di debug | [📄 Visualizza](./IoT-Hacking/Hardware-Hacking.md) |

👉 **[Panoramica completa sull'IoT Hacking](./IoT-Hacking/README.md)**

---

## 📖 Cheatsheets Programmate

### 🔴 Framework di Exploitation

| Strumento | Descrizione | Cheatsheet |
|------|-------------|------------|
| **Metasploit** | Il framework di penetration testing più usato al mondo | [📄 Visualizza](./Metasploit/README.md) |
| **Meterpreter** | Payload avanzato di post-exploitation | [📄 Visualizza](./Metasploit/Meterpreter.md) |
| **Mimikatz** | Strumento per l'estrazione di credenziali Windows | [📄 Visualizza](./Mimikatz/README.md) |
| **PowerShell** | Scripting Windows per il pentesting | [📄 Visualizza](./PowerShell/README.md) |
| **Comandi di Linux** | Linux & Bash per il pentesting | [📄 Visualizza](./Linux-Commands/README.md) |

### 🔍 Reconnaissance e scansione

| Strumento | Descrizione | Cheatsheet |
|------|-------------|------------|
| **Nmap** | Network discovery e security auditing | [📄 Visualizza](./Nmap/README.md) |
| **Gobuster** | Brute-forcing di Directory/DNS/VHost | [📄 Visualizza](./Gobuster/README.md) |
| **Nikto** | SCanner di web server | [📄 Visualizza](./Nikto/README.md) |

### 🌐 Testing delle Applicazioni Web

| Strumento | Descrizione | Cheatsheet |
|------|-------------|------------|
| **SQLMap** | Strumento di automazione per la SQL injection | [📄 Visualizza](./SQLMap/README.md) |
| **Burp Suite** | Piattaforma di test per la sicurezza delle applicazioni web application | [📄 Visualizza](./Burp-Suite/README.md) |
| **OWASP ZAP** | Scanner di sicurezza web app gratuito | [📄 Visualizza](./OWASP-ZAP/README.md) |

### 🔓 Password Cracking

| Strumento | Descrizione | Cheatsheet |
|------|-------------|------------|
| **Hydra** | Veloce network login cracker | [📄 Visualizza](./Hydra/README.md) |
| **John the Ripper** | Leggendario password cracker | [📄 Visualizza](./John-The-Ripper/README.md) |
| **Hashcat** | Il GPU password cracker più veloce al mondo | [📄 Visualizza](./Hashcat/README.md) |

### 📡 Analisi di rete

| Strumento | Descrizione | Cheatsheet |
|------|-------------|------------|
| **Wireshark** | Analizzatore di protocolli di rete | [📄 Visualizza](./Wireshark/README.md) |
| **tcpdump** | Analizzatore di pacchetti da riga di comando | [📄 Visualizza](./tcpdump/README.md) |

### 🐛 Bug Bounty

| Strumento | Descrizione | Cheatsheet |
|------|-------------|------------|
| **⭐ BB Methodology** | Guida completa al bug bounty hunting | [📄 Visualizza](./Bug-Bounty-Methodology/README.md) |
| **Nuclei** | Vulnerability scanner basato su template | [📄 Visualizza](./Nuclei/README.md) |
| **ffuf** | Veloce web fuzzer | [📄 Visualizza](./ffuf/README.md) |
| **Subfinder** | Discovery di sottodomini | [📄 Visualizza](./Subfinder/README.md) |
| **httpx** | HTTP probe & toolkit | [📄 Visualizza](./httpx/README.md) |
| **Amass** | Mapping approfondito della superficie di attacco | [📄 Visualizza](./Amass/translations/README.it.md) |
| **GAU** | Prendi tutti gli URL dagli archivi | [📄 Visualizza](./GAU/README.md) |
| **Katana** | Web crawler di nuova generazione | [📄 Visualizza](./Katana/README.md) |
| **Arjun** | Discovery di parametri nascosti | [📄 Visualizza](./Arjun/translations/README.it.md) |
| **Dalfox** | Scanner di vulnerabilità XSS | [📄 Visualizza](./Dalfox/README.md) |

### 💉 Collezione di Payloads

| Vulnerabilità | Descrizione | Cheatsheet |
|---------------|-------------|------------|
| **XSS** | Payload per Cross-Site Scripting | [📄 Visualizza](./Payloads/XSS.md) |
| **SQLi** | Payload per SQL Injection | [📄 Visualizza](./Payloads/SQLi.md) |
| **LFI** | Payload per Local File Inclusion | [📄 Visualizza](./Payloads/LFI.md) |
| **SSTI** | Server-Side Template Injection | [📄 Visualizza](./Payloads/SSTI.md) |
| **Command Injection** | Payload per OS command injection | [📄 Visualizza](./Payloads/Command-Injection.md) |
| **NoSQL Injection** | Payload per MongoDB, CouchDB, Redis | [📄 Visualizza](./Payloads/NoSQL-Injection.md) |
| **Deserialization** | Payload per Java, PHP, Python, .NET | [📄 Visualizza](./Payloads/Deserialization.md) |
| **Attacchi WebSocket** | CSWSH, injection, hijacking | [📄 Visualizza](./Payloads/WebSocket-Attacks.md) |
| **GraphQL Injection** | Introspection, IDOR, injection | [📄 Visualizza](./Payloads/GraphQL-Injection.md) |

### 🔴 Vulnerabilità Web

| Vulnerabilità | Descrizione | Cheatsheet |
|---------------|-------------|------------|
| **Sicurezza delle API** | Guida al testing di REST/GraphQL/JWT | [📄 Visualizza](./API-Security/translations/README.it.md) |
| **IDOR** | Insecure Direct Object Reference | [📄 Visualizza](./IDOR/README.md) |
| **SSRF** | Server-Side Request Forgery | [📄 Visualizza](./SSRF/README.md) |
| **XXE** | XML External Entity Injection | [📄 Visualizza](./XXE/README.md) |
| **Race Conditions** | Attacchi di timing & concorrenza | [📄 Visualizza](./Race-Conditions/README.md) |
| **Auth Bypass** | Tecniche di bypass dell'autenticazione | [📄 Visualizza](./Auth-Bypass/README.md) |
| **CORS** | Misconfigurazioni Cross-Origin | [📄 Visualizza](./CORS/README.md) |
| **Open Redirect** | Vulnerabilità redirect URL | [📄 Visualizza](./Open-Redirect/README.md) |

### 🛡️ Tecniche Avanzate di Attacco

| Argomento | Descrizione | Cheatsheet |
|-------|-------------|------------|
| **WAF Bypass** | Discovery IP di origine & evasione WAF | [📄 Visualizza](./WAF-Bypass/README.md) |
| **Cloudflare Bypass** | Trovare l'IP di origine dietro Cloudflare | [📄 Visualizza](./Cloudflare-Bypass/README.md) |
| **Subdomain Takeover** | Exploitation di CNAME dangling | [📄 Visualizza](./Subdomain-Takeover/README.md) |
| **Cache Poisoning** | Web cache poisoning & deception | [📄 Visualizza](./Cache-Poisoning/README.md) |
| **HTTP Smuggling** | Request smuggling (CL.TE/TE.CL) | [📄 Visualizza](./HTTP-Request-Smuggling/README.md) |
| **Prototype Pollution** | Attacchi JavaScript prototype | [📄 Visualizza](./Prototype-Pollution/README.md) |

### 🔎 Dorking & OSINT

| Strumento | Descrizione | Cheatsheet |
|------|-------------|------------|
| **Google Dorking** | Tecniche di ricerca avanzata su Google | [📄 Visualizza](./Google-Dorking/README.md) |
| **Shodan** | Motore di ricerca per IoT e dispositivi | [📄 Visualizza](./Shodan/README.md) |
| **GitHub Dorking** | Ricerca di informazioni sensibili nei repository | [📄 Visualizza](./GitHub-Dorking/README.md) |

### 🔝 Privilege Escalation

| Argomento | Descrizione | Cheatsheet |
|-------|-------------|------------|
| **Linux PrivEsc** | Tecniche di privilege escalation su Linux | [📄 Visualizza](./Linux-PrivEsc/README.md) |
| **Windows PrivEsc** | Tecniche di privilege escalation su Windows | [📄 Visualizza](./Windows-PrivEsc/README.md) |

### 🔬 Digital Forensics

| Strumento | Descrizione | Cheatsheet |
|------|-------------|------------|
| **Volatility** | Framework di memory forensics | [📄 Visualizza](./Volatility/README.md) |
| **Autopsy** | Piattaforma di digital forensics (GUI) | [📄 Visualizza](./Autopsy/README.md) |
| **ExifTool** | Estrazione e analisi di metadati | [📄 Visualizza](./ExifTool/README.md) |
| **Binwalk** | Analisi ed estrazione di firmware | [📄 Visualizza](./Binwalk/README.md) |

### 🔄 Ingegneria Inversa

| Strumento | Descrizione | Cheatsheet |
|------|-------------|------------|
| **Ghidra** | Suite di reverse engineering della NSA | [📄 Visualizza](./Ghidra/README.md) |
| **GDB** | Debugger GNU (debugging Linux) | [📄 Visualizza](./GDB/README.md) |
| **x64dbg** | Debugger Windows x64/x32 | [📄 Visualizza](./x64dbg/README.md) |

### 📶 WiFi Hacking

| Strumento | Descrizione | Cheatsheet |
|------|-------------|------------|
| **Aircrack-ng** | Suite per WiFi hacking (WPA/WPA2) | [📄 Visualizza](./Aircrack-ng/translations/README.it.md) |
| **Wifite** | Auditor WiFi automatizzato | [📄 Visualizza](./Wifite/README.md) |
| **Bettercap** | Framework per attacchi di rete (MITM/WiFi) | [📄 Visualizza](./Bettercap/README.md) |

### 🏢 Active Directory

| Strumento | Descrizione | Cheatsheet |
|------|-------------|------------|
| **⭐ AD Methodology** | Guida all'attacco passo-passo | [📄 Visualizza](./AD-Attack-Methodology/translations/README.it.md) |
| **BloodHound** | Visualizzazione dei percorsi di attacco AD | [📄 Visualizza](./BloodHound/README.md) |
| **Impacket** | Toolkit di attacco AD in Python | [📄 Visualizza](./Impacket/README.md) |
| **CrackMapExec** | Il coltellino svizzero per AD | [📄 Visualizza](./CrackMapExec/README.md) |
| **Rubeus** | Toolkit per l'abuso di Kerberos | [📄 Visualizza](./Rubeus/README.md) |
| **PowerView** | Enumerazione AD via PowerShell | [📄 Visualizza](./PowerView/README.md) |
| **Responder** | Avvelenamento LLMNR/NBT-NS | [📄 Visualizza](./Responder/README.md) |
| **Evil-WinRM** | Shell WinRM per pentester | [📄 Visualizza](./Evil-WinRM/README.md) |
| **Kerbrute** | Enum utenti e spraying Kerberos | [📄 Visualizza](./Kerbrute/README.md) |

### 📚 Risorse

| Risorsa | Descrizione | Cheatsheet |
|----------|-------------|------------|
| **Wordlists** | Guida di riferimento completa alle wordlist | [📄 Visualizza](./Wordlists/README.md) |
| **Kali Linux Tools** | Oltre 600 strumenti divisi per categoria | [📄 Visualizza](./Kali-Linux-Tools/README.md) |

---

## 🚀 Per iniziare

### Clonare il Repository

```bash
git clone [https://github.com/Ilias1988/Hacking-Cheatsheets.git](https://github.com/Ilias1988/Hacking-Cheatsheets.git)
cd Hacking-Cheatsheets

```

### Sfogliare le Cheatsheets

Naviga in qualsiasi cartella degli strumenti e apri il file README.md:

```bash
# Visualizza la cheatsheet di Metasploit
cat Metasploit/README.md

# Oppure aprila nel tuo editor preferito
code Metasploit/

```

### Accesso Offline

Tutte le cheatsheet sono in formato Markdown, il che le rende:

* 📱 **Mobile-friendly** - Leggibili su qualsiasi dispositivo
* 🔌 **Accessibili offline** - Nessuna connessione internet richiesta
* 🖨️ **Stampabili** - Per creare copie fisiche
* 🔍 **Ricercabili** - Usa grep o lo strumento di ricerca del tuo editor

---

## 📂 Struttura del Repoitory

```
Hacking-Cheatsheets/
│
├── README.md                # Versione originale (ENG) - Indice principale
├── README.it.md             # Questo file - Indice principale
├── LICENSE                  # Licenza MIT
├── CONTRIBUTING.md          # Linee guida per contribuire
├── CONTRIBUTING.it.md       # Linee guida per contribuire (Italiano)
├── .gitignore               # Regole Git ignore
│
├── Metasploit/              # Metasploit Framework
│   ├── README.md            # Guida completa msfconsole
│   └── Meterpreter.md       # Cheatsheet Meterpreter
│
├── Nmap/                    # Network Scanner
│   └── README.md            # Guida completa Nmap
│
├── Gobuster/                # Enumerazione Directory/DNS
│   └── README.md            # Guida completa Gobuster
│
├── Nikto/                   # Web Server Scanner
│   └── README.md            # Guida completa Nikto
│
├── SQLMap/                  # Tool SQL Injection
│   └── README.md            # Guida completa SQLMap
│
├── Burp-Suite/              # Web Application Testing
│   └── README.md            # Guida completa Burp Suite
│
├── OWASP-ZAP/               # OWASP Zed Attack Proxy
│   └── README.md            # Guida completa ZAP
│
├── Hydra/                   # Network Login Cracker
│   └── README.md            # Guida completa Hydra
│
├── John-The-Ripper/         # Password Cracker
│   └── README.md            # Guida completa John
│
├── Hashcat/                 # GPU Password Cracker
│   └── README.md            # Guida completa Hashcat
│
├── Wireshark/               # Network Protocol Analyzer
│   └── README.md            # Guida completa Wireshark
│
├── tcpdump/                 # Analizzatore di pacchetti da riga di comando
│   └── README.md            # Guida completa tcpdump
│
├── Nuclei/                  # Bug Bounty Scanner
│   └── README.md            # Guida completa Nuclei
│
├── ffuf/                    # Web Fuzzer
│   └── README.md            # Guida completa ffuf
│
├── Subfinder/               # Discovery Sottodomini
│   └── README.md            # Guida completa Subfinder
│
├── httpx/                   # HTTP Probe & Toolkit
│   └── README.md            # Guida completa httpx
│
├── Google-Dorking/          # Google Search Hacking
│   └── README.md            # Guida completa Google Dorking
│
├── Shodan/                  # Motore di ricerca IoT
│   └── README.md            # Guida completa Shodan
│
├── GitHub-Dorking/          # Secret Hunting
│   └── README.md            # Guida completa GitHub Dorking
│
└── ...
```

---

## 🤝 Contribuire

I contributi sono benvenuti! Si prega di leggere le nostre [Linee guida per i contributi](CONTRIBUTING.it.md) prima di inviare una pull request.

### Modi per contribuire

* 📝 **Aggiungi nuove cheatsheet** per strumenti non ancora trattati
* 🔧 **Migliora le cheatsheet esistenti** con esempi migliori
* 🐛 **Segnala problemi** o suggerisci miglioramenti
* 🌐 **Traduci** le cheatsheet in altre lingue
* ⭐ **Metti una stella a questo repo** per mostrare il tuo supporto!

---

## ⚠️ Legal Disclaimer

> **IMPORTANTE:** Queste cheatsheet sono destinate esclusivamente a **scopo educativo** e per **test di sicurezza autorizzati**.
> * ✅ Utilizzale su sistemi di tua proprietà
> * ✅ Utilizzale con esplicito permesso scritto
> * ✅ Utilizzale in incarichi legali di penetration testing
> * ❌ Non utilizzarle mai per accessi non autorizzati
> * ❌ Non utilizzarle mai per scopi malevoli
> 
> 
> **L'accesso non autorizzato ai sistemi informatici è illegale.** Gli autori non sono responsabili per qualsiasi uso improprio di queste informazioni.

---

## 📜 Licenza

Questo progetto è rilasciato sotto la Licenza MIT - consulta il file [LICENZA](LICENSE.it.md) per i dettagli.

---

## 🌟 Mostra il tuo supporto

Se trovi utili queste cheatsheet, considera di:

* ⭐ **Mettere una stella** a questo repository
* 🍴 **Fare il fork** per contribuire
* 📢 **Condividerlo** con altri professionisti della sicurezza
* 💬 **Fornire feedback** per miglioramenti

---

## 📬 Contatti

* **GitHub Issues** - Per bug report e richieste di funzionalità
* **Pull Requests** - Per i contributi

---

<p align="center">
<b>Buon Hacking! 🔴</b>




<i>Ricorda: Hackera responsabilmente, hackera eticamente!</i>
</p>

---

<p align="center">
Fatto con il ❤️ per la community della cybersicurezza
</p>
