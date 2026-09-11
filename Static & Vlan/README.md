# 🌐 Static IP & VLAN Network Topology

## 📌 Project Overview

This project demonstrates a **Static IP & VLAN network topology** created using **Cisco Packet Tracer**.

The network consists of a Cisco router, a Cisco 2960 switch, and multiple PCs configured with different VLANs and static IP addresses.

## 🛠️ Technologies Used

- 🖥️ Cisco Packet Tracer
- 🌐 VLAN
- 📍 Static IP Addressing
- 🔀 Cisco 2960 Switch
- 📡 Router
- 💻 End Devices

## 🏗️ Network Topology

The topology contains two different VLANs:

| VLAN | Network | Device |
|------|---------|--------|
| VLAN 2 | 192.168.2.0/24 | PC0 |
| VLAN 3 | 192.168.3.0/24 | PC1 |

### 📋 IP Addressing

| Device | VLAN | IP Address |
|--------|------|------------|
| Router | - | 192.168.1.254 |
| PC0 | VLAN 2 | 192.168.2.1 |
| PC1 | VLAN 3 | 192.168.3.1 |

## ⚙️ Configuration

### 🔹 VLAN Configuration

Two VLANs are created on the switch:

- **VLAN 2**
- **VLAN 3**

Each PC is connected to a separate VLAN.

### 🔹 Static IP Configuration

The PCs are manually configured with static IP addresses instead of receiving addresses through DHCP.

### 🔹 Router Configuration

The router is connected to the switch and provides network connectivity for the VLAN environment.

## 🎯 Objectives

- ✅ Create and configure VLANs
- ✅ Assign switch ports to different VLANs
- ✅ Configure static IP addresses
- ✅ Understand VLAN-based network segmentation
- ✅ Configure router and switch connectivity
- ✅ Test network connectivity

## 🧪 Testing

Network connectivity was tested using **ping** to verify communication between devices.

The testing helps confirm:

- 🔗 Correct VLAN assignment
- 📍 Correct static IP configuration
- 🌐 Network connectivity
- ✅ Proper router and switch configuration

## 📚 Learning Outcome

Through this project, I gained practical knowledge of:

- VLAN configuration
- Static IP addressing
- Cisco switch configuration
- Router configuration
- Network segmentation
- Basic network troubleshooting
- Cisco Packet Tracer

---

⭐ **Practical Networking Project**

💻 Built and tested using **Cisco Packet Tracer**
