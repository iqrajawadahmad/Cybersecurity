
# Enterprise Network Security Design

## Overview
This project demonstrates the design and implementation of an enterprise-level network using Cisco Packet Tracer. The network is designed for an organization with multiple departments and a branch office, focusing on segmentation, scalability, and operational security.

The design follows real-world enterprise networking practices and emphasizes structured IP addressing, VLAN-based separation, and dynamic routing.

---

## Network Architecture
The network consists of a main campus and a branch network connected through WAN links. Multiple access switches connect departmental users to a centralized Layer 3 device for inter-VLAN routing.

Dynamic routing is implemented between routers to ensure automatic route discovery and efficient communication between distributed network segments.

---

## Routing Protocol
The Open Shortest Path First (OSPF) dynamic routing protocol is used to exchange routing information between routers.

OSPF enhances network reliability and scalability by facilitating automatic route updates, enabling faster convergence, and reducing dependency on manual static routing.

---

## Server Infrastructure
The following servers are deployed within dedicated network segments:
- Email Server  
- Web Server  
- FTP Server  

Servers are logically separated from user networks to improve manageability and reduce unnecessary exposure.

---

## Security Design
- VLAN-based network segmentation to isolate departments and limit unauthorized access  
- Controlled inter-VLAN routing through Layer 3 devices  
- Logical separation of user networks and server networks  
- Use of OSPF dynamic routing to reduce manual routing errors and improve network stability  

---

## Tools and Technologies Used
- Cisco Packet Tracer  
- Cisco Routers and Switches  
- VLANs and Trunking  
- OSPF Dynamic Routing  

---

## Files Included
- `Network_Topology.png` – Enterprise network diagram  
- `Network_Design.pkt` – Cisco Packet Tracer configuration file  

---

## Author
Iqra Jawad Ahmad  
Network Design Project
