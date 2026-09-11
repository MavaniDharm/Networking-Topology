# 🌐 Dynamic & VTP Network Topology

## 📌 Project Overview

This project demonstrates a **Dynamic & VTP (VLAN Trunking Protocol)** network topology created using **Cisco Packet Tracer**.

The topology uses multiple Cisco switches connected through trunk links. VTP is used to manage and synchronize VLAN information across the switches.

## 🛠️ Technologies Used

- 🖥️ Cisco Packet Tracer
- 🌐 VLAN
- 🔄 VTP (VLAN Trunking Protocol)
- 🔗 Trunking
- 🔀 Cisco 2960 Switches
- 📡 Router
- 💻 End Devices

## 🏗️ Network Topology

The network contains multiple VLANs:

| VLAN | Network |
|------|---------|
| VLAN 10 | 192.168.10.0/24 |
| VLAN 11 | 192.168.11.0/24 |
| VLAN 12 | 192.168.12.0/24 |
| VLAN 13 | 192.168.13.0/24 |
| VLAN 14 | 192.168.14.0/24 |
| VLAN 15 | 192.168.15.0/24 |
| VLAN 16 | 192.168.16.0/24 |

## ⚙️ Configuration

### 🔹 VLAN Configuration

Multiple VLANs are created to logically separate different network segments.

### 🔹 VTP Configuration

**VTP stands for VLAN Trunking Protocol.**

VTP is used to synchronize VLAN information between multiple Cisco switches.

The switches are configured using VTP to simplify VLAN management across the network.

### 🔹 Trunk Configuration

Trunk links are configured between switches to carry traffic from multiple VLANs over a single link.

### 🔹 Dynamic VLAN Management

VLAN information can be distributed across the switches using VTP, reducing the need to manually create the same VLANs on every switch.

## 🎯 Objectives

- ✅ Configure multiple VLANs
- ✅ Understand VTP (VLAN Trunking Protocol)
- ✅ Configure VTP between switches
- ✅ Configure trunk links
- ✅ Synchronize VLAN information
- ✅ Assign end devices to different VLANs
- ✅ Test network connectivity

## 🧪 Testing

Connectivity was tested using **ping** and VLAN verification commands.

Testing was performed to verify:

- 🔗 Trunk connectivity
- 🌐 VLAN configuration
- 🔄 VTP VLAN synchronization
- 📡 Network connectivity
- ✅ End-to-end communication

## 📚 Learning Outcome

Through this project, I gained practical knowledge of:

- VLAN configuration
- VTP configuration
- VTP Server and Client concepts
- Trunking
- Cisco switch configuration
- Network segmentation
- Basic network troubleshooting
- Cisco Packet Tracer

---

⭐ **Practical Networking Project**

💻 Built and tested using **Cisco Packet Tracer**
