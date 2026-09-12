# 🌐 Networking Labs & Configurations

Welcome to my **Networking Labs Repository**! 🚀 This collection documents a series of hands-on practical exercises built and tested using **Cisco Packet Tracer**. Each lab focuses on a fundamental networking concept — ranging from VLAN management and dynamic/static routing to link aggregation (Etherchannel) and server configuration.

This repository is intended as both a **learning reference** and a **portfolio of practical networking skills** for concepts typically covered in CCNA-level studies. 💻

---

## 📂 Repository Structure

To keep things consistent and easy to follow, every folder in this repository contains **three key components**:

| 📌 Item | 📝 Description |
|---------|----------------|
| 🖧 **Topology File** | The original `.pkt` Cisco Packet Tracer project file, ready to open and explore |
| 🖼️ **Topology Diagram** | A clear image showing the network layout, devices, and connections |
| 📸 **Output Screenshot** | A photo/screenshot demonstrating the successfully working configuration (e.g., ping results, routing tables, VLAN status) |

This structure makes it easy to understand *what* was built, *how* it was connected, and *proof* that it actually works. ✅

---

## 📁 Lab Index & Descriptions

### 🔄 Dynamic & VTP
Demonstrates how **VTP (VLAN Trunking Protocol)** allows VLAN information to be automatically propagated across multiple switches in a domain, eliminating the need to manually configure VLANs on every switch.

### 🔀 Dynamic & VLAN
Covers dynamic VLAN assignment and management within a switched LAN environment, showing how devices are grouped into logical broadcast domains.

### 🌐 Dynamic IP Configuration
Focuses on automatic IP address assignment to end devices using **DHCP (Dynamic Host Configuration Protocol)**, including scope configuration and lease verification.

### 🔗 Etherchannel (Active-Passive)
Explains link aggregation using **PAgP (Port Aggregation Protocol)** configured in **Active-Passive mode**, bundling multiple physical links into a single logical connection for redundancy and increased bandwidth.

### 🔗 Etherchannel (Auto-Desirable)
Similar concept to above, but implemented using **LACP (Link Aggregation Control Protocol)** in **Auto-Desirable mode**, showing an alternative standard-based approach to Etherchannel.

### 🛣️ OSPF Routing
Implements **OSPF (Open Shortest Path First)**, a link-state dynamic routing protocol, to enable routers to automatically learn and share routes within a network.

### 🛤️ RIP Routing
Demonstrates **RIP (Routing Information Protocol)**, a distance-vector routing protocol, and how routers exchange routing table information to determine the best path.

### 🖥️ Server
Covers setting up and configuring essential **network services** on a server device — such as DHCP, DNS, HTTP, or FTP — within Packet Tracer's simulated environment.

### 🏷️ Static & VLAN
Combines **VLAN segmentation** with **static routing**, showing inter-VLAN communication using manually defined routes.

### 📌 Static IP Configuration
Covers the manual assignment of **static IP addresses** to routers, switches, and end devices, along with subnetting basics.

### 🗺️ Static Routing
Demonstrates how to manually configure **static routes** between routers to enable communication across different networks without a dynamic routing protocol.

---

## 🎯 Purpose of This Repository
- 📚 To document my learning journey in **Computer Networking**
- 🛠️ To build a practical reference for common networking configurations
- 💼 To showcase hands-on skills for academic and portfolio purposes

## 🧰 Tools Used
- 🖥️ **Cisco Packet Tracer** — for designing, configuring, and simulating network topologies

## 📝 How to Use
1. Open the desired folder based on the topic you want to explore
2. Open the `.pkt` file in Cisco Packet Tracer to view/edit the live configuration
3. Refer to the topology image for a quick visual overview
4. Check the screenshot to see the expected working output

## 👨‍💻 Author
**Mavani Dharm**
Student | Networking & Cybersecurity Enthusiast 🔐

---

⭐ If you find this repository helpful, feel free to **star** it and share your feedback!
📩 Suggestions and improvements are always welcome.
