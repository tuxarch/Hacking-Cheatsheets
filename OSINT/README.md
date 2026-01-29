# 🔍 OSINT (Open Source Intelligence) Cheatsheet

```
 ██████╗ ███████╗██╗███╗   ██╗████████╗
██╔═══██╗██╔════╝██║████╗  ██║╚══██╔══╝
██║   ██║███████╗██║██╔██╗ ██║   ██║   
██║   ██║╚════██║██║██║╚██╗██║   ██║   
╚██████╔╝███████║██║██║ ╚████║   ██║   
 ╚═════╝ ╚══════╝╚═╝╚═╝  ╚═══╝   ╚═╝   
```

> **Open Source Intelligence** - Collecting and analyzing publicly available information.

---

## 📑 Table of Contents

| Topic | Description | Guide |
|-------|-------------|-------|
| **People Search** | Find information about individuals | [📄 View](./People-Search.md) |
| **Email OSINT** | Email reconnaissance & verification | [📄 View](./Email-OSINT.md) |
| **Social Media** | Social media investigation | [📄 View](./Social-Media-OSINT.md) |
| **Domain & IP** | Domain/IP reconnaissance | [📄 View](./Domain-IP-OSINT.md) |
| **Image OSINT** | Reverse image search & analysis | [📄 View](./Image-OSINT.md) |

---

## 🎯 OSINT Methodology

```
┌─────────────────────────────────────────────────────────────┐
│                    OSINT LIFECYCLE                           │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  1. REQUIREMENTS    →  Define intelligence needs            │
│         ↓                                                   │
│  2. COLLECTION      →  Gather raw data from sources         │
│         ↓                                                   │
│  3. PROCESSING      →  Convert data to usable format        │
│         ↓                                                   │
│  4. ANALYSIS        →  Evaluate and correlate findings      │
│         ↓                                                   │
│  5. DISSEMINATION   →  Report and present intelligence      │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 🛠️ Essential OSINT Tools

### Search Engines
| Tool | URL | Purpose |
|------|-----|---------|
| **Google** | google.com | General search |
| **Bing** | bing.com | Alternative search |
| **DuckDuckGo** | duckduckgo.com | Privacy-focused |
| **Yandex** | yandex.com | Russian search (good for images) |
| **Baidu** | baidu.com | Chinese search |

### People Search
| Tool | URL | Purpose |
|------|-----|---------|
| **Pipl** | pipl.com | Deep people search |
| **Spokeo** | spokeo.com | US people search |
| **WhitePages** | whitepages.com | Phone/Address lookup |
| **ThatsThem** | thatsthem.com | Free people search |
| **BeenVerified** | beenverified.com | Background checks |

### Email Tools
| Tool | URL | Purpose |
|------|-----|---------|
| **Hunter.io** | hunter.io | Find company emails |
| **Have I Been Pwned** | haveibeenpwned.com | Breach checking |
| **EmailRep** | emailrep.io | Email reputation |
| **Phonebook.cz** | phonebook.cz | Email/domain search |
| **h8mail** | GitHub | Breach credential search |

### Social Media
| Tool | URL | Purpose |
|------|-----|---------|
| **Sherlock** | GitHub | Username search |
| **Social Searcher** | social-searcher.com | Social media search |
| **Namechk** | namechk.com | Username availability |
| **KnowEm** | knowem.com | Username check |

### Domain/IP Tools
| Tool | URL | Purpose |
|------|-----|---------|
| **Shodan** | shodan.io | Device search |
| **Censys** | censys.io | Internet scanning |
| **SecurityTrails** | securitytrails.com | DNS history |
| **ViewDNS** | viewdns.info | DNS tools |
| **BuiltWith** | builtwith.com | Technology profiler |

---

## 🔥 Quick Reference Commands

### theHarvester
```bash
# Email & subdomain gathering
theHarvester -d target.com -l 500 -b all

# Specific sources
theHarvester -d target.com -b google,linkedin,twitter

# Save to file
theHarvester -d target.com -b all -f results.html
```

### Sherlock (Username Search)
```bash
# Search all platforms
python3 sherlock.py username

# Specific sites
python3 sherlock.py username --site twitter instagram facebook

# Output to file
python3 sherlock.py username --output results.txt
```

### Maltego
```
# Transform types:
- Person to Email
- Email to Domain
- Domain to IP
- IP to Location
- Social Media profiles
```

### Recon-ng
```bash
# Start recon-ng
recon-ng

# Create workspace
workspaces create target_name

# Load modules
modules load recon/domains-hosts/hackertarget
modules load recon/contacts-credentials/hibp_breach

# Set target
options set SOURCE target.com

# Run module
run
```

---

## 📊 OSINT Categories

### Passive OSINT
```
No direct interaction with target:
- Search engines
- Social media
- Public records
- Archive.org
- WHOIS data
```

### Active OSINT
```
Some interaction with target:
- Port scanning
- DNS queries
- Web crawling
- Email verification
```

---

## 🔒 Operational Security (OPSEC)

### Best Practices
```
✓ Use VPN/Tor
✓ Create sock puppet accounts
✓ Use virtual machines
✓ Don't use personal accounts
✓ Clear cookies/cache regularly
✓ Use separate browser profiles
✓ Document everything
```

### Sock Puppet Accounts
```
- Use generated identities
- Consistent persona across platforms
- Aged accounts (more trusted)
- Believable profile details
- Don't link to real identity
```

---

## 📋 OSINT Checklist

```markdown
## Target: [Name/Company/Domain]

### People
□ Full name variations
□ Phone numbers
□ Email addresses
□ Physical addresses
□ Social media profiles
□ Professional history
□ Education history
□ Photos/Images

### Company
□ Domain registration (WHOIS)
□ Technology stack
□ Employee list
□ Email format
□ Social media presence
□ News/Press releases
□ Financial information
□ Physical locations

### Technical
□ IP addresses
□ Subdomains
□ Open ports/services
□ DNS records
□ SSL certificates
□ Historical data
```

---

## 🔗 OSINT Frameworks

### OSINT Framework
```
https://osintframework.com/
- Organized by category
- Links to hundreds of tools
- Visual tree structure
```

### IntelTechniques
```
https://inteltechniques.com/tools/
- Michael Bazzell's tools
- Custom search tools
- Investigation workflows
```

---

## 📚 Related Guides in This Repo

- [Google Dorking](../Google-Dorking/README.md)
- [GitHub Dorking](../GitHub-Dorking/README.md)
- [Shodan](../Shodan/README.md)
- [Amass](../Amass/README.md)
- [Subfinder](../Subfinder/README.md)

---

**Back to Main:** [🔴 Hacking Cheatsheets](../README.md)
