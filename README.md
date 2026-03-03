🖥 Computer Lab Network Design Project
📌 Project Overview

This project demonstrates the design and configuration of a complete Computer Lab Network using Cisco Packet Tracer.

The lab contains 50 computers connected through multiple switches to a central router. The goal of the project is to ensure all devices can communicate within the same network.

🎯 Objectives

Design a structured network topology

Configure router and switches

Assign IP addresses to all PCs

Ensure full network connectivity

Test communication using ping

🏗 Network Topology

The network uses a hierarchical design:

Router
→ Core Switch
→ Access Switches
→ 50 PCs

Devices Used

1 Router (2911)

1 Core Switch (2960)

3 Access Switches (2960)

50 PCs

Wireless Access Point (optional)

🌐 IP Addressing Scheme

Network Address: 192.168.1.0/24
Subnet Mask: 255.255.255.0
Default Gateway: 192.168.1.1

IP Assignment

Router:

192.168.1.1

PC Range:

192.168.1.10 – 192.168.1.70

Each PC has:

Unique IP address

Subnet Mask: 255.255.255.0

Default Gateway: 192.168.1.1

⚙ Router Configuration
enable
configure terminal
hostname LAB-RTR
interface g0/0
ip address 192.168.1.1 255.255.255.0
no shutdown
exit
⚙ Switch Configuration
enable
configure terminal
hostname CORE-SW

All switch ports were verified to be active and connected properly.

🧪 Testing & Verification

Network connectivity was tested using:

ping 192.168.1.1

Results:

PCs successfully ping router

PCs successfully ping other PCs

All links show green (active)

📈 Key Networking Concepts Used

Hierarchical Network Design

IP Addressing

Subnetting (/24 network)

Router and Switch configuration

End-to-end connectivity testing

 Future Improvements

Implement VLANs for network segmentation

Configure Inter-VLAN Routing

Add DHCP Server

Add Network Security (ACLs)

Internet connectivity simulation

Author

Name: CHARLES MWANGA 
Project: Computer Lab Network Design
Tool Used: Cisco Packet Tracer
