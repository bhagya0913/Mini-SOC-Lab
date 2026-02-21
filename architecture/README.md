# 🏗 SOC Architecture Design

## Overview

This document explains the architecture of the Mini SOC Lab.

The lab is designed to simulate a real-world Security Operations Center (SOC) environment using virtualization and monitoring tools.

---

## 🖥 Lab Components

### 1️⃣ Attacker Machine
- OS: Kali Linux
- Purpose: Simulate cyber attacks
- Tools Used: Nmap, Hydra, Wireshark

### 2️⃣ Victim Machine
- OS: Ubuntu Desktop / Windows
- Purpose: Target system for attack simulations

### 3️⃣ Monitoring Server
- OS: Ubuntu Server
- Components:
  - Snort (Intrusion Detection System)
  - Logstash
  - Elasticsearch
  - Kibana

---

## 🔄 Data Flow

1. Attacker performs an attack from Kali.
2. Victim machine receives traffic.
3. Snort detects suspicious activity.
4. Logs are generated.
5. Logstash parses and forwards logs.
6. Elasticsearch stores the logs.
7. Kibana visualizes alerts through dashboards.

---

## 🌐 Network Configuration

- All machines are connected through an internal virtual network.
- Static IP addresses are assigned for communication.
- Internet access is isolated for safe experimentation.

---

## 📊 Architecture Diagram

The architecture diagram image is stored in this folder.

File name example:
`soc-architecture-diagram.png`

---

## Key Design Goal

To build a realistic, scalable SOC simulation environment for educational and cybersecurity training purposes.