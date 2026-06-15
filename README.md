# Computer Networks Practical Assignment

## 📌 Overview
This repository contains my practical assignment for the Computer Networks module, completed during my first year in the Network Engineering program. Developed under the guidance of course director Ilham, this project demonstrates core networking concepts, specifically focusing on router configuration, static routing, and dynamic routing protocols using Cisco Packet Tracer.

---

## 📂 Project Structure
The repository consists of the following files as per the submission requirements:

**`Task1_BasicConfig.pkt`**: Packet Tracer file demonstrating foundational router security and identity setup.
* **`Task2_StaticRouting.pkt`**: Packet Tracer file containing a triangular, three-router topology fully routed via static paths.
* **`Task3_DynamicRouting.pkt`**: Packet Tracer file showcasing the implementation of both RIPv2 and EIGRP routing protocols.
* **`Routing_Assignment_Report.pdf`**: Comprehensive documentation including network diagrams, full configuration commands, routing tables, and successful ping test verifications.

---

## ⚙️ Technical Implementations

### Task 1: Basic Router Configuration
Focused on establishing fundamental device identity and administrative security access.
* Configured custom hostnames mapped to specific campuses and student IDs (e.g., KandyNSBM_StudentID).
* Secured the physical console line (Line Console 0) with password authentication (NSBM).

### Task 2: Static Routing Configuration
Designed to manually control traffic flow across a multi-subnet network.
* **Topology:** Three routers (Computing, Business, and Science) connected via /30 point-to-point WAN links.
* **LANs:** Three isolated /24 networks representing different departments.
* **Routing:** Implemented manual static routes (`ip route`) on all routers to guarantee precise, end-to-end communication between all end devices.

### Task 3: Dynamic Routing Configuration
Showcases the scalability and automation of dynamic routing protocols in a linear three-router topology (Kandy, Colombo, Galle).
* **Part A - RIPv2:** Configured the Routing Information Protocol (RIP) with `no auto-summary` to support VLSM across the /16 LANs and /30 WAN links.
* **Part B - EIGRP:** Replaced RIP with the Enhanced Interior Gateway Routing Protocol (EIGRP), utilizing an Autonomous System (AS) number and wildcard masks for highly efficient, exact-match subnet advertisements.
* **Verification:** Verified successful convergence and full network connectivity for both protocols.

---

## 🛠️ Tools & Protocols
* **Simulation Software:** Cisco Packet Tracer 
* **Protocols:** IPv4, RIPv2, EIGRP

---

## 👨‍💻 Author
**Radin Reanula**
