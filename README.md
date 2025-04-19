# 🏫 Campus Network Project - Data Communication & Networking (DCN)

This project represents a **Campus Area Network (CAN)** designed for academic purposes in the **Data Communication and Networking** course. The aim is to simulate or design an efficient, scalable, and secure network infrastructure for a university or educational institute.

---

## 🎯 Objective

The primary objective of this project is to:
- Understand and implement core concepts of networking.
- Design a hierarchical network model.
- Configure networking devices and simulate inter-departmental communication.
- Apply subnetting, VLANs, and routing protocols.

---

## 🛠️ Technologies / Tools Used

- **Cisco Packet Tracer** *(or)* **GNS3**
- **Networking Devices**: Routers, Switches, Access Points, PCs, Servers
- **Protocols**: RIP / OSPF / EIGRP (based on design)
- **Others**: Static/Dynamic Routing, VLAN, DHCP, DNS, etc.

---

## 🗺️ Network Design Overview

### 🏢 Departments / Blocks
- **Admin Block**
- **Computer Science Department**
- **Electrical Engineering Department**
- **Library**
- **Hostel / Residential Area**
- **Central Data Center**

### 🌐 Features Implemented
- **IP Addressing & Subnetting**
- **VLAN Configuration** (e.g., Faculty, Students, Admin)
- **Inter-VLAN Routing**
- **Static or Dynamic Routing Protocols**
- **DHCP Configuration**
- **DNS & Web Server Setup**
- **Wireless Access Points for Hostel Areas**
- **Network Security with ACLs (Optional)**

---

## 📁 Project Structure

📁 Campus-Network-DCN │ ├── campus_network.pkt # Cisco Packet Tracer simulation file ├── README.md # This file

---

## 📊 IP Addressing Plan

| Department        | Network Address | Subnet Mask     | VLAN ID | Range         |
|------------------|-----------------|-----------------|---------|---------------|
| Admin Block      | 192.168.10.0    | 255.255.255.0   | 10      | 192.168.10.1-254 |
| CS Department     | 192.168.20.0    | 255.255.255.0   | 20      | 192.168.20.1-254 |
| EE Department     | 192.168.30.0    | 255.255.255.0   | 30      | 192.168.30.1-254 |
| Hostel           | 192.168.40.0    | 255.255.255.0   | 40      | 192.168.40.1-254 |
| Server Room      | 192.168.100.0   | 255.255.255.0   | 100     | 192.168.100.1-254 |

*(Adjust as per your subnetting scheme)*

---

## 🚀 How to Run

1. Open the `.pkt` file using **Cisco Packet Tracer**.
2. Review the network topology and start simulation.
3. Test connectivity using:
   - `ping`
   - `tracert`
   - Accessing web/DNS servers (if configured)
4. View CLI configurations on routers/switches.

---

## ✅ Learning Outcomes

- Real-world application of OSI & TCP/IP model.
- Hands-on VLAN, Subnetting, Routing Protocols.
- Improved understanding of logical and physical topologies.
- Team collaboration and project documentation.

---

## 👨‍🏫 Course Details

**Course Name:** Data Communication and Networking  
**Instructor:** *[Instructor Name]*  
**Semester:** *Spring/Fall 20XX*  
**Team Members:**  
- [Your Name]  
- [Teammate 1]  
- [Teammate 2]  

---
