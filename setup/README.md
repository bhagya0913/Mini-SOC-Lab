# ⚙ Setup & Installation Guide

## Overview

This folder contains the complete setup instructions for building the Virtual SOC Lab environment.

The lab is deployed using virtualization and configured in an isolated internal network.

---

## 🖥 Virtual Machine Setup

### 1️⃣ Kali Linux (Attacker)
- Install Kali Linux in VirtualBox
- Assign internal network adapter
- Configure static IP address

### 2️⃣ Victim Machine
- Install Ubuntu Desktop or Windows
- Assign internal network adapter
- Enable SSH service (for lab testing)

### 3️⃣ Monitoring Server
- Install Ubuntu Server
- Assign internal network adapter
- Configure static IP
- Install required packages

---

## 🔐 IDS Installation

- Install Snort
- Configure network interface
- Define custom detection rules
- Configure alert logging path

---

## 📊 ELK Stack Setup

- Install Elasticsearch
- Install Logstash
- Install Kibana
- Create Logstash pipeline to parse Snort logs
- Verify logs appear in Kibana dashboard

---

## 🌐 Network Configuration

- Use Internal Network mode in VirtualBox
- Assign static IPs to all machines
- Test connectivity using ping
- Verify traffic capture using Wireshark

---

## Validation Steps

- Perform Nmap scan from Kali
- Verify Snort detection
- Confirm log ingestion to ELK
- View alert in Kibana dashboard