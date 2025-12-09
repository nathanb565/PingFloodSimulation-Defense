# PingFloodSimulation-Defense
Ping flood attack simulation and defense
# ICMP Ping Flood Simulation & Defense – Ubuntu Server Lab

## 📌 Overview
This project demonstrates how to simulate, detect, and mitigate a **Denial‑of‑Service (DoS)** attack using ICMP ping floods against an Ubuntu Server.  
The lab environment was designed to showcase both offensive testing and defensive hardening techniques.

## 🎯 Objectives
- Simulate ICMP ping flood attacks to study DoS behavior.
- Capture and analyze abnormal traffic patterns with **Wireshark**.
- Ingest system and network logs into **Splunk** for centralized monitoring.
- Configure **custom Splunk alerts** to detect flooding activity.
- Implement **iptables firewall rules** to limit ICMP requests and mitigate attack impact.

## 🛠️ Tools & Technologies
- **Ubuntu Server** – Target environment
- **Wireshark** – Packet capture and traffic analysis
- **Splunk** – Log ingestion, dashboards, and alerting
- **iptables** – Linux firewall for traffic control
- **VirtualBox** – Lab virtualization environment

## 🔎 Attack Simulation
- Used `ping` with high frequency to generate ICMP flood traffic
