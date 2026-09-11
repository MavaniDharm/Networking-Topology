# 🔗 EtherChannel – Auto Mode (PAgP)

## 📌 Project Overview

This project demonstrates **EtherChannel configuration using PAgP (Port Aggregation Protocol)** in Cisco Packet Tracer.

Multiple physical links between switches are bundled together to create a single logical link called an **EtherChannel**.

## 🛠️ Technologies Used

- 🖥️ Cisco Packet Tracer
- 🔗 EtherChannel
- ⚡ PAgP (Port Aggregation Protocol)
- 🔄 Auto & Desirable Modes
- 🌐 VLAN
- 🔀 Cisco 2960 Switches
- 📡 Router

## 🏗️ Network Topology

The topology contains multiple Cisco switches connected using EtherChannel links.

### 🔗 EtherChannel Groups

| Channel | Connection |
|---------|------------|
| CH1 | Switch0 ↔ Switch1 |
| CH2 | Switch1 ↔ Switch2 |
| CH3 | Switch2 ↔ Switch3 |
| CH4 | Switch3 ↔ Switch4 |
| CH5 | Switch4 ↔ Switch5 |
| CH6 | Switch5 ↔ Switch6 |

Multiple physical links are combined into logical EtherChannel connections.

## ⚙️ Configuration

### 🔹 PAgP

**PAgP stands for Port Aggregation Protocol.**

PAgP is a Cisco proprietary protocol used to automatically negotiate and form EtherChannel between switches.

### 🔹 Auto Mode

In **Auto mode**, the switch waits for a PAgP negotiation request from the other side.

### 🔹 Desirable Mode

In **Desirable mode**, the switch actively attempts to negotiate and establish an EtherChannel.

An EtherChannel can be formed when one side is **Desirable** and the other side is **Auto**.

## 🎯 Objectives

- ✅ Understand EtherChannel
- ✅ Configure PAgP
- ✅ Configure Auto & Desirable modes
- ✅ Combine multiple physical links
- ✅ Improve network bandwidth
- ✅ Provide link redundancy
- ✅ Configure Port-Channel interfaces

## 🧪 Testing

The EtherChannel configuration was tested in Cisco Packet Tracer to verify:

- 🔗 EtherChannel status
- ⚡ PAgP negotiation
- 🌐 Link connectivity
- ✅ Port-channel operation
- 📡 Network communication

## 📚 Learning Outcome

Through this project, I gained practical knowledge of:

- EtherChannel configuration
- PAgP (Port Aggregation Protocol)
- Auto & Desirable modes
- Port-channel configuration
- Link aggregation
- Network redundancy
- Cisco switch configuration
- Network troubleshooting

---

⭐ **Practical Networking Project**

💻 Built and tested using **Cisco Packet Tracer**
