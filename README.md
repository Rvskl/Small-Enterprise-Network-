# Small Enterprise Network Topology with VLAN Segmentation

This project simulates a small enterprise network using Cisco Packet Tracer.  
It includes multiple switches, VLAN trunking, and VLAN ACL rules to block specific VLANs from internet access.

## Features
- VLAN 10: Management
- VLAN 20: Sales
- VLAN 30: HR
- VLAN 40: Guest (blocked from internet)
- Switch trunk configuration with `switchport trunk allowed`
- Router-on-a-stick inter-VLAN routing

## Diagram
![Network Diagram]

## Files
- **project.pkt** — Cisco Packet Tracer project file
- **config/** — Switch & router CLI configuration scripts
- **notes.txt** — Setup notes
