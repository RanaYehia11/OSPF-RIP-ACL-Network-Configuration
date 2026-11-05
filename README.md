# OSPF, RIP & Access Control Lists (ACLs) – Cisco Packet Tracer

## 📌 Project Overview

This project demonstrates the configuration of a multi-router network using **Cisco Packet Tracer**. It combines dynamic routing protocols (OSPF and RIP) with Access Control Lists (ACLs) to establish network connectivity and control traffic between different network segments.

The network consists of multiple routers, switches, and end devices connected through different IP subnets.

## 🖥️ Network Topology

![Network Topology](topology.png)

### Network Components
- 3 Routers
- 2 Switches
- 5 PCs
- Multiple LAN and WAN segments

### IP Addressing

| Network Segment | Network Address |
|---|---|
| Left LAN | 192.168.1.0 |
| Router-to-Router Link 1 | 2.2.2.0 |
| Router-to-Router Link 2 | 3.3.3.0 |
| Right LAN | 192.168.2.0 |

## ⚙️ Technologies & Concepts Implemented

### 1. Dynamic Routing

**OSPF (Open Shortest Path First)**
- Configured OSPF for dynamic route advertisement.
- Enabled communication between different network segments.
- Verified routing information and network reachability.

**RIP (Routing Information Protocol)**
- Configured RIP for dynamic routing.
- Enabled automatic route learning and exchange.
- Verified connectivity between network devices.

### 2. Access Control Lists (ACLs)

Configured Access Control Lists to manage and filter network traffic.

Implemented:
- **Permit:** Allowing specified traffic.
- **Deny:** Blocking specified traffic.
- Traffic filtering based on ACL rules.
- Testing ACL behavior to verify permitted and denied communication.

### 3. Network Connectivity & Troubleshooting

- Configured router interfaces and IP addressing.
- Verified connectivity using ICMP (Ping).
- Tested communication between PCs across different LANs.
- Troubleshot routing and access control configurations.

## 🧪 Testing & Verification

The following commands were used to verify the network configuration:

| Command | Purpose |
|---|---|
| `show ip route` | Verify routing table entries |
| `show ip protocols` | Verify routing protocols |
| `show ip ospf neighbor` | Check OSPF neighbor relationships |
| `show access-lists` | Verify ACL rules and counters |
| `show ip interface brief` | Check interface status |
| `ping` | Test end-to-end connectivity |

**Test Results:**
- Successful connectivity between permitted network devices.
- Blocked traffic according to configured ACL deny rules.
- Verified dynamic routing operation.
- Confirmed end-to-end communication where allowed.

