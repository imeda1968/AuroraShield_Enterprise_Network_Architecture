# AuroraShield Enterprise Network Architecture

**Author:** Imeda Sheriphadze  
**Role:** Enterprise Network Architect | IT & Software Specialist  

AuroraShield is a Cisco-based enterprise network architecture designed to demonstrate real-world routing, segmentation, and security controls in a multi-layer topology.

A key objective of this project is **serverless enterprise operations** — the network is designed to operate **without Windows Server dependency**, relying on Cisco-native features and protocol-driven telemetry.

---

## Highlights

- **Hierarchical architecture:** Core / Distribution / Access
- **Routing:** OSPF backbone (Area 0) with secure design principles
- **Segmentation:** VLAN-based isolation for departments and services
- **Security controls:** Control Plane Protection (CoPP), AAA, SSH hardening
- **Monitoring & visibility:** SNMPv3, Syslog, NetFlow readiness
- **Operational model:** Serverless approach (no Windows Server dependency)

---
## Architecture Diagrams

### High Level Architecture
![High Level](diagrams/High_Level_Architecture.png)

### Security Zoning
![Security](diagrams/Security_Zoning_Layout.png)

### VLAN Segmentation
![VLAN](diagrams/VLAN_Segmentation_Map.png)

### OSPF Routing Flow
![OSPF](diagrams/OSPF_Routing_Flow.png)

### Management Isolation
![Mgmt](diagrams/Management_Plane_Isolation.png)



## Repository Contents

- `docs/` — Technical documentation + motivation letter  
- `presentation/` — Professional slide deck  
- `diagrams/` — Architecture illustrations and topology references  
- `configs/` — Configuration references (PDF export)  
- `credentials/` — Certificates & diploma  
- `cv/` — CV in English

---

## How This Project Was Built

- Designed and validated in a lab/simulation environment
- Focused on enterprise-grade structure, security, and clarity of documentation

---

## Contact

**Imeda Sheriphadze**  
Email: isheriphadze@gmail.com  
Phone: +995 555 45 92 70
