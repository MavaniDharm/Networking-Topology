# HTTP Server – Cisco Packet Tracer

## 📌 Project Overview

This project demonstrates the configuration of a **DHCP Server and HTTP Web Server** using Cisco Packet Tracer.

The topology contains a router, switch, server, and multiple PCs connected in the same network. The server is configured to provide **DHCP services** and **HTTP web services**.

## 🖥️ Topology

![DHCP & HTTP Server Topology](topology.png)

## 🔧 Devices Used

- 1 × Router
- 1 × Cisco 2960 Switch
- 1 × Server
- 3 × PCs

## 🌐 IP Addressing

| Device | IP Address |
|---|---|
| Router | 192.168.1.254 |
| Server | 192.168.1.1 |
| PC0 | 192.168.1.3 |
| PC1 | 192.168.1.4 |
| PC2 | 192.168.1.2 |

## ⚙️ Configuration

### DHCP Server
- DHCP service configured on the Server.
- Network: `192.168.1.0/24`
- Default Gateway: `192.168.1.254`
- PCs receive IP addresses automatically from the DHCP Server.

### HTTP Server
- HTTP service enabled on the Server.
- Web page hosted at:
  `http://192.168.1.1`

## 🧪 Testing

- Verified DHCP IP assignment on PCs.
- Verified connectivity using `ping`.
- Accessed the hosted web page using the PC Web Browser.
- Successfully tested HTTP communication with the server.

## 🎯 Learning Outcomes

- DHCP Server configuration
- HTTP/Web Server configuration
- IP addressing and subnetting
- Router and switch connectivity
- Basic network troubleshooting
- Client-server communication

## 🛠️ Tool Used

**Cisco Packet Tracer**
