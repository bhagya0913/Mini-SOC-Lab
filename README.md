# 🛡 Mini SOC Lab – Virtual Security Monitoring Project

## 📌 Project Description

This project demonstrates the implementation of a Virtual Security Operations Center (SOC) Lab.

The system simulates cyber attack scenarios in a controlled environment and detects them using IDS and SIEM integration.

The lab replicates real-world SOC monitoring workflows including attack detection, log analysis, and incident reporting.

---

## 🎯 Project Objectives

- Create a virtual cybersecurity lab
- Simulate network-based attacks
- Detect threats using Snort IDS
- Integrate logs into ELK Stack
- Visualize security events
- Produce professional incident reports

---

## 🏗 Lab Architecture

The lab consists of three primary systems:

| Machine | Role |
|----------|------|
| Kali Linux | Attacker |
| Ubuntu / Windows | Victim |
| Ubuntu Server | Monitoring + SIEM |

Detailed architecture explanation available in:


---

## 🧰 Tools & Technologies

- VirtualBox
- Kali Linux
- Ubuntu Server
- Snort (IDS)
- Wireshark
- Elasticsearch
- Logstash
- Kibana (SIEM Dashboard)

---

## 🔍 Attack Simulations

- Port Scanning (Nmap)
- SSH Brute Force (Lab Only)
- Network Traffic Monitoring
- Controlled DoS Simulation

All attacks were performed in an isolated environment.

---

## 📊 SIEM Integration

- Snort generates alert logs
- Logstash parses logs
- Elasticsearch stores structured data
- Kibana visualizes security incidents

Dashboards include:
- Top attacker IP
- Alert categories
- Incident timeline
- Attack count analysis

---

## 📂 Project Structure

Mini-SOC-Lab/
- architecture/
- setup/
- screenshots/
- reports/
- logs/

---

## 📄 Reports & Documentation

Inside `/reports`:
- Incident analysis report
- Risk assessment
- Final project report (PDF)

Inside `/screenshots`:
- Detection alerts
- Dashboard visualizations
- Network capture evidence

---

## 👩‍💻 Team Members

- @bhagya0913
- xxx

---

## 📚 Learning Outcomes

- SOC workflow implementation
- Intrusion Detection System configuration
- SIEM pipeline setup
- Log analysis and alert monitoring
- Cyber incident documentation

---

## ⚠ Disclaimer

This project was conducted in a controlled laboratory environment for educational purposes only.