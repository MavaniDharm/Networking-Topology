# 🌐 DHCP Configuration – Network Topology

## 🎯 Objective

To configure a network using **DHCP (Dynamic Host Configuration Protocol)** and automatically assign IP addresses to connected PCs.

The network is created in **Cisco Packet Tracer** using a router and multiple switches. 🌐💻

---

## 🛠️ Tools Used

- 🖥️ Cisco Packet Tracer
- 🌐 Cisco Router
- 🔀 Cisco 2960 Switches
- 💻 PCs
- 📡 DHCP

---

## 📚 Topics Covered

- 📡 DHCP Configuration
- 🌐 IPv4 Addressing
- 🔄 Dynamic IP Address Assignment
- 🚪 Default Gateway
- 🔀 Switch Connectivity
- 🌐 Router Connectivity
- 🧪 Network Connectivity Testing

---

## 🌐 Network Details

**Network:** `192.168.1.0/24`

**Subnet Mask:** `255.255.255.0`

**Router / Default Gateway:** `192.168.1.254`

---

## 💻 IP Addressing

| 🖥️ Device | 📍 IP Address |
|---|---|
| Router | `192.168.1.254` |
| PC0 | `192.168.1.10` |
| PC1 | `192.168.1.9` |
| PC2 | `192.168.1.2` |
| PC3 | `192.168.1.1` |
| PC4 | `192.168.1.3` |
| PC5 | `192.168.1.6` |
| PC6 | `192.168.1.4` |
| PC7 | `192.168.1.5` |
| PC8 | `192.168.1.8` |
| PC9 | `192.168.1.7` |

---

## ⚙️ DHCP Configuration

DHCP is configured on the router to provide network configuration to client devices. 📡

### 🔧 Basic DHCP Configuration

```text
Router> enable
Router# configure terminal

Router(config)# ip dhcp pool LAN
Router(dhcp-config)# network 192.168.1.0 255.255.255.0
Router(dhcp-config)# default-router 192.168.1.254
Router(dhcp-config)# dns-server 8.8.8.8

Router(dhcp-config)# exit
Router(config)# exit
