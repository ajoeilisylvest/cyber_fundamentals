# Search Skills

## Passive Reconnaissance 

Gathering information without directly interacting with the target.

Examples:
- Searching Google
- Looking up domains
- Checking leaked data
- Using public databases

## OSINT (Open Source Intelligence)

Collecting information from publicly available sources.

That includes:
- Websites
- Search engines
- Social media
- Public databases
- Leaked breach data

## Google Search Operators

Search operators help refine search results and find more specific information during reconnaissance.

- `"exact phrase"`  
  Returns results containing the exact phrase.  
  Example: `"passive reconnaissance"`

- `site:`  
  Limits results to a specific domain.  
  Example: `site:tryhackme.com success stories`

- `-` (exclude keyword)  
  Removes unwanted terms from results.  
  Example: `pyramids -tourism`

- `filetype:`  
  Searches for specific file formats such as PDF, DOC, XLS or PPT.  
  Example: `filetype:ppt cyber security`

---

## Search Engines for Reconnaissance

### Shodan

Shodan is a search engine for devices connected to the internet.

It can be used to find:
- Servers  
- Networking equipment  
- Industrial control systems  
- IoT devices  

It is especially useful for identifying exposed services and systems.

---

### Censys

Censys focuses on internet-facing assets such as:
- Hosts  
- Websites  
- Certificates  

Common use cases:
- Enumerating domains  
- Auditing open ports and services  
- Discovering unknown or rogue assets  

---

## Threat Intelligence Tools

### VirusTotal

VirusTotal allows users to scan:
- Files  
- URLs  
- File hashes  

It uses multiple antivirus engines at once, making it useful for quickly checking if something is malicious.

---

### Have I Been Pwned (HIBP)

HIBP checks whether an email address has appeared in a known data breach.

Useful for:
- Identifying compromised accounts  
- Understanding exposure from past leaks  

---

## Vulnerabilities & Exploits

### Common Vulnerabilities and Exposures (CVE)

CVE is a standardized system for identifying vulnerabilities in software and hardware.

- Format: `CVE-YYYY-XXXX`  
- Example: `CVE-2024-29988`

Why this matters:
- Provides a universal reference for vulnerabilities  
- Ensures consistency across the cybersecurity community  

The CVE system is maintained by MITRE.

---

### National Vulnerability Database (NVD)

The NVD provides detailed information about CVEs, including:
- Technical details  
- Severity ratings  
- Impact analysis  

---

### Exploit Database

A public database of exploit code contributed by security researchers.

- Some exploits are verified  
- Useful for studying real-world exploitation techniques  

---

### GitHub

GitHub often contains:
- Security tools  
- Proof-of-concept (PoC) exploits  
- Scripts related to vulnerabilities  

---

## Technical Documentation

### Linux Manual Pages (man pages)

Manual pages are built-in documentation available on Linux and Unix-like systems.

They cover:
- Commands  
- System calls  
- Configuration files  

Usage: `man <command>`

---

### Official Documentation

Most software and tools provide official documentation, which is usually the most reliable source of information.

Examples include:
- Microsoft technical documentation  
- Snort documentation  
- Apache server documentation  
- Node.js documentation  

These resources explain how systems work and should be referenced when learning new tools.

---

## Key Takeaways

- Search operators make information gathering more efficient  
- OSINT tools help identify publicly exposed systems and data  
- CVEs provide a standardized way to track vulnerabilities  
- Exploit databases and GitHub are useful for practical research  
- Official documentation is one of the most reliable learning resources  
