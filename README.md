# 🌐 Network Simulation with VLSM & Routing Protocols

**Tool:** Cisco Packet Tracer  

## 📜 Project Overview
This project demonstrates the design and simulation of a **multi-subnet network topology** using **Variable Length Subnet Masking (VLSM)** for optimal IP address allocation.  
Both **static** and **dynamic routing protocols** (RIP & OSPF) are implemented for seamless inter-network communication.

## 🗺️ Network Layout
The network includes:
- Multiple subnets with VLSM-based IP allocation
- Serial connections between routers
- VLAN segments for logical separation
- ISP/Cloud simulation for internet access

## ⚙️ Features & Configurations
- **VLSM** for efficient IP address usage.
- **Static Routing** for fixed, manual path configuration.
- **Dynamic Routing** using:
  - RIP (Routing Information Protocol)
  - OSPF (Open Shortest Path First)
- **Serial Link Configuration** between routers.
- **Connectivity Testing** with ICMP (`ping`) and `traceroute`.
- **Documentation** of IP tables, subnet masks, and routing setups.

## 🛠️ Technologies Used
- Cisco Packet Tracer
- VLSM (Variable Length Subnet Masking)
- Static Routing
- RIP & OSPF Protocols
- VLAN
- Serial Links
- TCP/IP Protocols


## 🚀 How to Use
1. Open **Cisco Packet Tracer**.
2. Load the `vlsm_routing.pkt` file.
3. Verify configurations using:
   ```bash
   ping <destination_IP>
   traceroute <destination_IP>
