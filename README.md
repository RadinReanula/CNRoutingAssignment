# CNRoutingAssignment

## Overview
[cite_start]This repository contains my practical assignment for the **Computer Networks** module[cite: 2], completed during my first year in the Network Engineering program. Developed under the guidance of course director Ilham, this project demonstrates core networking concepts, specifically focusing on router configuration, static routing, and dynamic routing protocols using Cisco Packet Tracer.

## Project Structure
[cite_start]The repository consists of the following files as per the submission requirements[cite: 105]:
* [cite_start]`Task1_BasicConfig.pkt`: Packet Tracer file demonstrating foundational router security and identity setup[cite: 106].
* [cite_start]`Task2_StaticRouting.pkt`: Packet Tracer file containing a triangular, three-router topology fully routed via static paths[cite: 106].
* [cite_start]`Task3_DynamicRouting.pkt`: Packet Tracer file showcasing the implementation of both RIPv2 and EIGRP routing protocols[cite: 106].
* [cite_start]`Routing_Assignment_Report.pdf`: Comprehensive documentation including network diagrams, full configuration commands, routing tables, and successful ping test verifications[cite: 107].

## Technical Implementations

### Task 1: Basic Router Configuration
[cite_start]Focused on establishing fundamental device identity and administrative security access[cite: 8]. 
* [cite_start]Configured custom hostnames mapped to specific campuses and student IDs (e.g., `KandyNSBM_StudentID`)[cite: 11, 12].
* [cite_start]Secured the physical console line (Line Console 0) with password authentication (`NSBM`)[cite: 15, 16].

### Task 2: Static Routing Configuration
[cite_start]Designed to manually control traffic flow across a multi-subnet network[cite: 22, 46].
* [cite_start]**Topology:** Three routers (Computing, Business, and Science) [cite: 36, 27, 35] [cite_start]connected via `/30` point-to-point WAN links[cite: 26, 29, 32].
* [cite_start]**LANs:** Three isolated `/24` networks representing different departments[cite: 25, 30, 34].
* [cite_start]**Routing:** Implemented manual static routes (`ip route`) on all routers to guarantee precise, end-to-end communication between all end devices[cite: 46, 47].

### Task 3: Dynamic Routing Configuration
[cite_start]Showcases the scalability and automation of dynamic routing protocols in a linear three-router topology (Kandy, Colombo, Galle)[cite: 61, 71, 72, 73].
* [cite_start]**Part A - RIPv2:** Configured the Routing Information Protocol (RIP) with `no auto-summary` to support VLSM across the `/16` LANs and `/30` WAN links[cite: 77, 78].
* [cite_start]**Part B - EIGRP:** Replaced RIP with the Enhanced Interior Gateway Routing Protocol (EIGRP)[cite: 80, 81], utilizing an Autonomous System (AS) number and wildcard masks for highly efficient, exact-match subnet advertisements.
* [cite_start]Verified successful convergence and full network connectivity for both protocols[cite: 79, 82].

## Tools Used
* [cite_start]**Simulation Software:** Cisco Packet Tracer [cite: 6]
* **Protocols:** IPv4, RIPv2, EIGRP

## Author
* Radin Reanula
