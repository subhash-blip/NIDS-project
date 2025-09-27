# Network Intrusion Detection System (NIDS) using Suricata

This project implements a lightweight *Network Intrusion Detection System (NIDS)* using *Suricata* with custom configuration and local rule sets. The goal is to detect malicious network traffic such as *DoS attacks, port scans, and suspicious payloads* using *signature-based detection*.


 📁 Repository Structure

| File | Description |
|------|-------------|
| Final_Report.pdf | Complete documentation of methodology, implementation, and results |
| suricata.yaml | Main Suricata configuration file |
| local.rules | Custom detection rules for identifying malicious traffic |


 🚀 Setup & Installation

Follow the steps below to deploy this setup on a Linux-based machine:

```bash
# Install Suricata (for Ubuntu/Debian-based systems)
sudo apt update
sudo apt install suricata -y
