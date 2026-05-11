# Network Intrusion Detection System Using Suricata

##  Objective
This project demonstrates a basic Network Intrusion Detection System (NIDS) using Suricata on Kali Linux.

##  Tools Used
- Kali Linux
- Suricata
- Nmap

##  Features
- Real-time network monitoring
- Intrusion detection
- Alert generation
- Traffic analysis

##  Installation

```bash
sudo apt update
sudo apt install suricata -y
```

##  Running Suricata

```bash
sudo suricata -i wlan0
```

##  Testing Detection

```bash
nmap localhost
```

##  Project Structure

Network-IDS/
│
├── screenshots/
├── rules/
├── report/
└── README.md

##  Screenshots
Screenshots are available inside the screenshots folder.

##  Conclusion
Successfully implemented a basic Network IDS using Suricata and detected suspicious network activity.
