# DEPI-Project-CybersecurityEngineerTrack
## 📡 Implementing a Secure Multi-Branch Office Network

A hands-on graduation project under the **Digital Egypt Pioneers Initiative (DEPI)**. The goal was to design, implement, and secure a simulated enterprise network interconnecting a main office with multiple branches, using Cisco technologies.

### 🛠️ Project Overview
This project simulates a real-world enterprise network setup, focusing on:
* **Branch interconnectivity**
* **VLAN segmentation**
* **Routing protocols (OSPF)**
* **Site-to-site IPsec VPN**
* **Firewall rules & ACLs**
* **Security hardening**

### 🧩 Network Architecture
* **Main Office** + 3 Branches (HR, Finance, Sales)
* **Interconnected via VPN over public cloud**
* **Internal segmentation using VLANs & Inter-VLAN Routing**
* **OSPF for dynamic routing**
* **Security layers via ACLs and IDS/IPS**


### 🔐 Key Features
* VLANs and subinterfaces for segmentation
* OSPF for branch-to-branch and main office routing
* IPsec VPN tunnels for secure communication
* Access Control Lists (ACLs) for traffic filtering
* Basic IDS/IPS configuration and testing
* Documentation of policies and hardening techniques


### 📁 Project Structure

```
/DEPI-MultiBranch-Network
│
├── Configration File.pdf
├── DEPU Final Project.pkt
├── Documentation File.pdf
├── Project Design.png
├── README.md
├── Assests
│   ├── Video 01
│   ├── Video 02
│   ├── Video 03
│   ├── Video 04
│   └── Video 05
└── 
```

### 🧪 Testing & Validation
* Ping & traceroute between all segments
* VPN tunnel health and encryption confirmation
* ACL test cases: allowed vs blocked traffic
* VLAN isolation testing


### 📌 Tools & Technologies
* Cisco Packet Tracer / GNS3
* Cisco IOS Commands
* Wireshark (for VPN traffic inspection)
* Microsoft Visio (network diagram)

### 📌 Team Members
* Ahmed Mohamed Gharib
* Abdul Rahman Mohammed Hamed
* Hassan Muhammed Abdelnabi
* Muhammed Samy Elhamzawy
* Muhammed Mustafa Gomaa
