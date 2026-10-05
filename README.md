# GP2: Dual-Channel Network Security Monitoring Laboratory

**Course:** NET 496 - Graduation Project 2  
**Academic Year:** 2025–2026  
**Institution:** King Saud University - College of Applied Studies and Community Services  
**Department:** Computer Science and Engineering (Network Track)  
**Supervisor:** Dr. Ahmad Ali Awwad Alzubi 
**Google Drive(URL):** https://drive.google.com/drive/folders/1itbMt8Iw2z6txtT1Jx2jHxoFjxKt-Zl2?usp=sharing

---

## 📌 Project Overview
This project provides an empirical, side-by-side comparative analysis between **manual packet-level inspection (Wireshark)** and an **automated SIEM intrusion detection pipeline (Suricata + ELK Stack)**. Both channels operate concurrently over mirrored live traffic (SPAN session) within a controlled 14-node corporate network emulated on GNS3.

---

## 🗂️ Repository Structure

```text
├── configs/
│   ├── gns3/                 # Cisco IOU startup configurations and topology specs
│   ├── suricata/             # suricata.yaml configuration and Emerging Threats rulesets
│   └── elk/                  # Filebeat (filebeat.yml) and Logstash (logstash.conf) pipelines
├── scripts/
│   ├── attacks/              # Attack execution scripts (Hydra, Nmap, Metasploit, etc.)
│   └── analysis/             # Scripts for metrics parsing, detection latency, and comparison
├── results/
│   ├── kibana_csv/           # Exported alert records from Kibana Security Solution
│   └── metrics/              # Empirical benchmarking datasets and comparison matrices
├── filters/
│   └── wireshark/            # Standardized display filters mapped per attack scenario
<<<<<<< HEAD
└── README.md                 # Project documentation and setup guide
=======
└── README.md                 # Project documentation and setup guide
>>>>>>> 5a1d72d (Drive)
