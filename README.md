# Network Design Project

This project showcases the design and configuration of a multi-building network infrastructure using Cisco Packet Tracer. It includes OSPF routing, subnetting, DHCP, FTP, VLANs, DNS, NAT, PAT, and web server services.

## Buildings and Topologies

- **Building A** – Star Topology
- **Building B** – Ring Topology
- **Building C** – Bus Topology
- **Building D** – Tree Topology
- **Data Center** – Hosts FTP, Web, DNS, and other services

## Network Features

- **Routing Protocol**: OSPF configured across all routers
- **Subnetting**: IP subnetting planned for each building
- **DHCP Server**: Automatically assigns IP addresses to client PCs
- **FTP Server**: Set up for file sharing tests
- **Web Server**: Includes a custom HTML page for testing
- **DNS Server**: Resolves domain `www.datacenter.com`
- **NAT/PAT**: Dynamic NAT in Building B, Static NAT in Building C, PAT in the Data Center
- **VLANs**: Configured for better segmentation and security

## Configuration Highlights

- **Router A**: Connects Building A with IP 193.168.2.1
- **Router B**: Handles dynamic NAT and connects Building B
- **Router C**: Uses static NAT and connects Building C
- **Router D**: Connects Building D with tree topology setup
- **Data Center Router**: Manages core services with PAT enabled



