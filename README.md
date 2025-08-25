# Enterprise Multi-Site Network Simulation

This project simulates a 3-site enterprise network in GNS3 with VLAN segmentation, OSPF routing, ACLs, NAT, DHCP, and GRE over IPsec VPN for secure LAN-to-LAN communication.

## Features
- VLAN segmentation (HR, Sales, IT at each site)
- Inter-VLAN Routing
- OSPF for inter-branch routing
- GRE over IPsec VPN tunnels
- ACLs for security between VLANs
- NAT for internet access simulation
- DHCP configuration

## Repository Structure
- **Network-Diagram.png** → Topology
- **Configs/** → Device configurations
- **Screenshots/** → Key verification outputs
- **Project-Report.pdf** → Documentation

## Tools Used
- GNS3 (IOSv, IOSvL2)
- Wireshark (packet verification)
- Draw.io (diagramming)

---
Created by Prinson Rodrigues
