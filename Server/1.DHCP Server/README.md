# 🌐 DHCP Server Network Topology

## 📌 Project Overview

This project demonstrates a **DHCP Server-based network topology** created using **Cisco Packet Tracer**.

The topology consists of multiple routers, switches, PCs, and dedicated DHCP servers. Each network contains a DHCP server that provides IP address configuration to devices automatically.

## 🛠️ Technologies Used

- 🖥️ Cisco Packet Tracer
- 📡 DHCP (Dynamic Host Configuration Protocol)
- 🌐 IP Addressing
- 🔀 Cisco 2960 Switches
- 📡 Cisco Routers
- 🖥️ DHCP Servers
- 💻 End Devices

## 🏗️ Network Topology

The topology contains three different networks:

| Network | Router | DHCP Server | PC |
|---------|--------|-------------|----|
| 192.168.1.0/24 | 192.168.1.254 | 192.168.1.1 | PC0 |
| 194.168.1.0/24 | 194.168.1.254 | 194.168.1.1 | PC1 |
| 200.168.1.0/24 | 200.168.1.254 | 200.168.1.1 | PC2 |

Each network has a dedicated DHCP server connected through a Cisco switch.

## ⚙️ Configuration

### 🔹 DHCP

**DHCP stands for Dynamic Host Configuration Protocol.**

DHCP automatically provides network configuration to client devices, including:

- 📍 IP Address
- 🌐 Subnet Mask
- 🚪 Default Gateway
- 🌎 DNS Server

### 🔹 DHCP Server

A dedicated server is configured as a DHCP server for each network.

The DHCP server automatically assigns IP addresses to connected client devices instead of configuring them manually.

### 🔹 Router Configuration

The routers provide connectivity between the different networks.

Router interfaces are configured with the respective gateway IP addresses.

## 🎯 Objectives

- ✅ Configure a DHCP Server
- ✅ Automatically assign IP addresses
- ✅ Configure default gateways
- ✅ Understand DHCP operation
- ✅ Configure routers and switches
- ✅ Connect multiple networks
- ✅ Test network connectivity

## 🧪 Testing

The configuration was tested using Cisco Packet Tracer.

Testing was performed to verify:

- 📡 Automatic IP address assignment
- 🌐 Correct subnet configuration
- 🚪 Default gateway assignment
- 🔗 Network connectivity
- ✅ Communication between devices

## 📚 Learning Outcome

Through this project, I gained practical knowledge of:

- DHCP Server configuration
- Dynamic IP addressing
- DHCP address pools
- Default gateway configuration
- Router configuration
- Switch configuration
- Network connectivity
- Basic network troubleshooting
- Cisco Packet Tracer

---

⭐ **Practical Networking Project**

💻 Built and tested using **Cisco Packet Tracer**
