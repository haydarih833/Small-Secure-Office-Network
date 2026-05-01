# 📡 Small Secure Office Network (Cisco Packet Tracer)

## 🧠 Overview
This project simulates a small secure office network designed in Cisco Packet Tracer.  
It demonstrates fundamental networking concepts such as VLAN segmentation, DHCP, inter-VLAN routing, and basic network security using SSH, AAA authentication, and ACLs.

The goal of this project is to build a realistic **enterprise-like network environment** suitable for IT / Network internship level understanding.

---

## 🏗️ Topology

**Devices:**
- 1 Router (R1)
- 1 Switch (S1)
- 2 PCs (PC0, PC1)
- 1 Server

**Network Design:**
- VLAN 10 → Staff Network
- VLAN 20 → Guest Network
- Server placed in VLAN 10

---

## ⚙️ Implemented Features

### 🔹 VLAN Segmentation
- VLAN 10 (Staff)
- VLAN 20 (Guest)
- Logical separation of network traffic

### 🔹 Inter-VLAN Routing (Router-on-a-Stick)
- Single router interface with subinterfaces
- Enables communication between VLANs

### 🔹 DHCP Configuration
- Automatic IP assignment for both VLANs
- Reduces manual configuration errors

### 🔹 SSH Secure Remote Access
- Telnet disabled
- SSH v2 enabled for secure router management

### 🔹 AAA Authentication (Local)
- Username/password-based authentication on router
- Enhances device access security

### 🔹 ACL (Access Control List)
- Restricts Guest VLAN from accessing internal server
- Implements basic network security policy

---

## 🧪 Testing Results

✔ Staff VLAN (PC0)
- Can access Server (192.168.10.100)
- Can SSH into Router

❌ Guest VLAN (PC1)
- Cannot access Server (blocked by ACL)
- Network isolation successfully applied

---

## 📌 Key Skills Demonstrated

- VLAN configuration and segmentation
- Inter-VLAN routing
- DHCP service configuration
- SSH secure remote access
- AAA authentication (local)
- ACL-based traffic filtering
- Basic enterprise network design

---

## 🚀 Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI

---

## 🎯 Project Goal

To simulate a secure small office network environment and demonstrate core networking and security concepts required for entry-level IT / Network internship roles.

---

## 💡 Author Notes

This project is part of a hands-on learning path toward networking fundamentals and cybersecurity basics.
