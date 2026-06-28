# Recon-Automation-Framework

An automated reconnaissance framework that streamlines the information gathering phase of penetration testing and bug bounty assessments by integrating multiple open-source security tools into a single, efficient workflow.

## 📌 Overview

Recon-Automation-Framework is a Python-based cybersecurity project designed to automate the reconnaissance process for penetration testers, ethical hackers, and security researchers. The framework performs subdomain enumeration, DNS resolution, live host detection, port scanning, technology fingerprinting, directory discovery, and report generation while minimizing manual effort.

The modular architecture allows users to add or remove reconnaissance modules easily, making it suitable for learning, research, and real-world security assessments.

## 🚀 Features

* Automated target reconnaissance
* Passive and active subdomain enumeration
* DNS information gathering
* Live host detection
* Port scanning using Nmap
* HTTP/HTTPS service discovery
* Technology fingerprinting
* Directory and endpoint enumeration
* WHOIS & IP information lookup
* Screenshot collection (optional)
* Organized output reports
* Logging and error handling
* Modular and scalable architecture
  
## 🛠 Technologies Used

* Python 3
* Bash
* Nmap
* Subfinder
* Amass
* Assetfinder
* HTTPX
* WhatWeb
* Dirsearch
* DNSX
* JSON
* Linux (Kali/Ubuntu)
  
## 📂 Project Structure

```text
Recon-Automation-Framework/
│
├── modules/
│   ├── subdomain.py
│   ├── portscan.py
│   ├── dns.py
│   ├── httpx_scan.py
│   ├── tech_detect.py
│   └── report.py
│
├── output/
│
├── logs/
│
├── config/
│
├── screenshots/
│
├── requirements.txt
├── recon.py
└── README.md
```

## ⚙ Installation

Clone the repository

```text
git clone https://github.com/yourusername/Recon-Automation-Framework.git
```

Move into the project directory

```text
cd Recon-Automation-Framework
```

Install Python dependencies

```text
pip install -r requirements.txt
```

Install required reconnaissance tools

```text
sudo apt install nmap

go install github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest

go install github.com/owasp-amass/amass/v4/...@master

go install github.com/projectdiscovery/httpx/cmd/httpx@latest

go install github.com/projectdiscovery/dnsx/cmd/dnsx@latest
```

Scan a single domain

```text
python3 recon.py -d example.com
```

Specify output directory

```text
python3 recon.py -d example.com -o results/
```

Run all reconnaissance modules

```text
python3 recon.py -d example.com --full
```

## 📊 Sample Workflow

```text
Target Domain
      │
      ▼
Subdomain Enumeration
      │
      ▼
DNS Resolution
      │
      ▼
Live Host Detection
      │
      ▼
Port Scanning
      │
      ▼
Technology Detection
      │
      ▼
Directory Enumeration
      │
      ▼
Generate Report
```

## 📈 Output

The framework generates organized reports including:

* Enumerated subdomains
* Live hosts
* Open ports
* Running services
* Technology stack
* HTTP response details
* DNS records
* Screenshots (optional)
* JSON and text reports
  
## 🎯 Use Cases

* Penetration Testing
* Bug Bounty Hunting
* Security Assessments
* Red Team Operations
* Asset Discovery
* Surface Mapping
* Cybersecurity Learning
* Research Projects
  
## 🔒 Disclaimer

This project is intended for educational purposes and authorized security testing only. Always obtain proper permission before scanning or testing any systems you do not own or have explicit authorization to assess.

## 🤝 Contributing

Contributions are welcome.

* Fork the repository
* Create a feature branch
* Commit your changes
* Push your branch
* Open a Pull Request
  
## 📜 License

This project is licensed under the MIT License.

## 👨‍💻 Author

### Sanjay

Cybersecurity Enthusiast | Ethical Hacker | Security Automation | Python Developer

## ⭐ Support

If you found this project useful, consider giving it a ⭐ Star on GitHub to support its development.

Meet Codex.
