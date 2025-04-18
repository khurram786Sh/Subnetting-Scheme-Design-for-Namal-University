# Subnetting Scheme Design for Namal University 🏫📡

This project presents a complete subnetting scheme designed to optimize IP address utilization at Namal University, Mianwali. It addresses current departmental needs and future expansion with structured subnet allocations, network planning, and simulation.

---

## 📋 Project Overview

As part of the **EE-342 (L) – Computer Communication Networks Lab**, this Complex Engineering Problem (CEP) involves designing a scalable and efficient subnetting strategy for the university’s internal network.

### 🎯 Objectives

- Efficiently allocate IP addresses using a **Class C** network (`192.168.1.0/24`)
- Support multiple departments and facilities:
  - BBA, CS, Engineering, and Mathematics Departments
  - Chagda Hostel
  - Guest Wi-Fi
- Include reserved subnets for **future expansion**
- Use **Ring Topology** for better fault tolerance
- Simulate and validate design via **Cisco Packet Tracer**

---

## 🛠️ Tools & Technologies

- **Cisco Packet Tracer** – Network simulation and testing
- **IPv4 Subnetting** – Class C addressing with VLSM
- **Ring Topology** – Reliable network design
- **PDU Analysis** – Validated with ping commands

---

## 🧮 Subnetting Details

| Department         | Hosts Required | Subnet Allocated | Network Address | Usable IP Range     |
|--------------------|----------------|------------------|------------------|----------------------|
| BBA Dept           | 5              | /29              | 192.168.1.x      | x.x.x.x – x.x.x.x    |
| CS Dept            | 5              | /29              | 192.168.1.x      | x.x.x.x – x.x.x.x    |
| Engineering Dept   | 5              | /29              | 192.168.1.x      | x.x.x.x – x.x.x.x    |
| Mathematics Dept   | 5              | /29              | 192.168.1.x      | x.x.x.x – x.x.x.x    |
| Chagda Hostel      | 7              | /28              | 192.168.1.x      | x.x.x.x – x.x.x.x    |
| Guest Wi-Fi        | 10             | /28              | 192.168.1.x      | x.x.x.x – x.x.x.x    |
| Reserved Subnets   | 3 Subnets      | /29               | –                | Reserved for future |
| Routing Subnets    | 7 Subnets      | /30               | –                | Router connections  |

*(Exact IPs defined in full report)*

---

## 🌐 Topology Used

**Ring Topology** was chosen for its:
- High reliability with bidirectional data flow
- Minimal data collisions
- Easy fault isolation
- Cost-effectiveness for medium-sized institutions

---

## 🧪 Simulation & Validation

- ✅ **Ping commands** between subnets to verify connectivity
- 📸 **PDU success snapshots** included
- 🔄 Realistic topology implementation using Cisco Packet Tracer

---

## 📈 Future Planning

- 3 subnets reserved for departmental or infrastructure expansion
- Design allows for flexible scaling with minimal reconfiguration

---

## 👨‍🎓 Project Info

- **Author:** Khurram Shehzad (Electrical Engineer) 

---

## 📁 Files Included
  
- `.pkt` file – Cisco Packet Tracer topology  

---

## 📌 Learning Outcomes

- Mastered IP addressing and subnetting for real-world scenarios  
- Gained practical exposure to network simulation and design  
- Learned to document and justify network planning decisions effectively  

---

