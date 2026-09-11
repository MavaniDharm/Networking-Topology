# 🔗 EtherChannel Active-Passive

## 📌 Project Overview

This project demonstrates **EtherChannel configuration using LACP (Link Aggregation Control Protocol)** in Cisco Packet Tracer.

Multiple physical links between switches are combined into a single logical link called an **EtherChannel**.

## 🛠️ Technologies Used

- 🖥️ Cisco Packet Tracer
- 🔗 EtherChannel
- ⚡ LACP (Link Aggregation Control Protocol)
- 🔄 Active & Passive Modes
- 🌐 VLAN
- 🔀 Cisco 2960 Switches
- 📡 Router

## 🏗️ Network Topology

The topology contains multiple Cisco 2960 switches connected using EtherChannel links.

### 🔗 EtherChannel Groups

| Channel | Connected Switches | Mode |
|---------|--------------------|------|
| CH1 | Switch0 ↔ Switch1 | Active / Passive |
| CH2 | Switch1 ↔ Switch2 | Active / Passive |
| CH3 | Switch2 ↔ Switch3 | Active / Passive |

Each EtherChannel combines multiple physical links into one logical connection.

## ⚙️ Configuration

### 🔹 LACP

**LACP stands for Link Aggregation Control Protocol.**

LACP is used to combine multiple physical interfaces into a single logical EtherChannel.

### 🔹 Active Mode

In **Active mode**, the switch actively sends LACP negotiation packets to establish the EtherChannel.

### 🔹 Passive Mode

In **Passive mode**, the switch waits for LACP negotiation from the other side.

An EtherChannel using LACP can be formed when one side is **Active** and the other side is **Passive**.

## 🎯 Objectives

- ✅ Understand EtherChannel
- ✅ Configure LACP
- ✅ Configure Active and Passive modes
- ✅ Combine multiple physical links
- ✅ Improve link redundancy
- ✅ Increase available bandwidth
- ✅ Understand logical channel interfaces

## 🧪 Testing

The EtherChannel configuration was tested using Cisco Packet Tracer commands to verify:

- 🔗 EtherChannel status
- ⚡ LACP negotiation
- 🌐 Link connectivity
- ✅ Port-channel operation
- 📡 Network communication

## 📚 Learning Outcome

Through this project, I gained practical knowledge of:

- EtherChannel configuration
- LACP
- Active & Passive modes
- Port-channel configuration
- Link aggregation
- Network redundancy
- Cisco switch configuration
- Network troubleshooting

---

⭐ **Practical Networking Project**

💻 Built and tested using **Cisco Packet Tracer**
