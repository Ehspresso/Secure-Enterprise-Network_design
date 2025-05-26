<img width="1150" alt="Screenshot 2025-05-26 at 6 12 16 PM" src="https://github.com/user-attachments/assets/526ce4d5-1ff9-434e-aacf-d0d7cee28620" />

# Enterprise Network Topology – Cisco Packet Tracer

## Overview
This Packet Tracer project simulates a realistic enterprise network using:
- Hierarchical design (Core, Distribution, Access)
- VLANs for segmentation (MGT, LAN, WLAN, VOIP, Servers, Blackhole)
- Redundant Layer 3 switches using HSRP
- OSPF routing between routers, switches, and firewalls
- NAT and dual-WAN setup via two firewalls
- VoIP support with ePhone configuration
- DHCP relay (IP helper-address) from VLANs to centralized DHCP
- Secure switch access using SSH and ACLs

## Features
- **Access Control**: SSH only access, ACL-bound VTY lines
- **Firewall Zoning**: DMZ, OUTSIDE1/2, INSIDE1/2 interfaces
- **Network Address Translation**: Multi-zone dynamic NAT
- **Routing Protocol**: OSPF across all routers and Layer 3 switches
- **Telephony**: Voice Gateway with ePhones and IP telephony service

## Devices & Services
- Core, Distribution, Access Switches
- Firewalls (ASA Simulation)
- Voice Gateway with DHCP Option 150
- Internal Servers in VLAN 90
