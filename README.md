# 🛒 Supermarket Network Infrastructure Design

This project is part of the *Advanced Routing & Switching* coursework, focused on designing a secure, scalable, and centralized enterprise network for a supermarket chain with outlets across multiple provinces.

## 📌 Project Overview

The goal is to provide a modern network solution that:
- Supports **three outlet types**: Mega, Standard, and Small
- Enables **centralized control** via the head office
- Supports **future scalability** without major reconfiguration
- Implements **software-defined WAN (SD-WAN)** and **private cloud** connectivity
- Facilitates essential services like VoIP, CCTV, PoE, public Wi-Fi, digital signage, and ATM/Banking

## 🧩 Key Features

- 🔀 VLAN-based segmentation for logical traffic isolation
- 📶 Wi-Fi support for staff and customers
- 🔒 VPN tunnels simulating SD-WAN for secure inter-branch communication
- 🖥️ Cisco Packet Tracer simulation for design demonstration

## 👩‍💻 My Contribution

As part of this group project, I was responsible for:
- **Assigning and creating VLANs** for all outlet types (Mega, Standard, Small)
- Ensuring proper segmentation to isolate services like:
  - Management
  - POS
  - CCTV
  - VoIP
  - Staff Wi-Fi
  - Customer Wi-Fi
  - Digital Ads
  - ATM/Banking
  - Delivery/Orders

## 🗂️ VLAN Plan Example

| VLAN ID | Name            | Purpose             |
|---------|-----------------|---------------------|
| 10      | Management      | Admin/NOC access    |
| 20      | POS             | Sales systems       |
| 30      | CCTV            | Surveillance cams   |
| 40      | VoIP            | IP phone systems    |
| 50      | Staff Wi-Fi     | Internal Wi-Fi      |
| 60      | Customer Wi-Fi  | Guest network       |
| 70      | Digital Ads     | Signage, clocks     |
| 80      | ATM/Banking     | Banking services    |
| 90      | Delivery        | Order management    |

## 🧰 Tools & Technologies

- Cisco Packet Tracer
- VLAN Configuration
- IP Addressing & Subnetting
- Static & Dynamic Routing (OSPF)
- Network Simulation & Testing

## ✅ Verification

Connectivity was verified between branches and the head office using simulated ping and firewall communication paths.

----------------------------

🎓 *This project was developed as part of the CN301.3 – Advanced Routing & Switching module (Batch 22.2) under the guidance of Mr. Chamindra Attanayake.*



