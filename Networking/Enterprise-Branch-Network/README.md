Enterprise Branch Network Simulation using Cisco Packet Tracer

Overview

This project simulates a small enterprise network using Cisco Packet Tracer. The network consists of a headquarters in Lagos and branch offices in Ogun and Port Harcourt, connected using a linear topology.

The objective was to design, configure, and test a functional enterprise network that supports centralized network services while enabling communication between all branches.

⸻

Network Topology

Topology: Linear

Lagos HQ -------- Ogun -------- Port Harcourt

Headquarters (Lagos)

* Router (R1)
* Switch (SW1)
* 2 Client PCs
* DHCP Server
* DNS Server
* Web Server

Ogun Branch

* Router (R2)
* Switch (SW2)
* 2 Client PCs

Port Harcourt Branch

* Router (R3)
* Switch (SW3)
* 2 Client PCs

⸻

Technologies Used

* Cisco Packet Tracer
* IPv4 Addressing
* Static Routing
* DHCP
* DHCP Relay (IP Helper Address)
* DNS
* HTTP Web Server
* Router and Switch Configuration
* Network Troubleshooting

⸻

IP Addressing Scheme

Network	Address
Lagos LAN	192.168.10.0/24
Ogun LAN	192.168.20.0/24
Port Harcourt LAN	192.168.30.0/24
Lagos ↔ Ogun	10.0.12.0/30
Ogun ↔ Port Harcourt	10.0.23.0/30

⸻

Features Implemented

* Configured router interfaces for all branch networks.
* Configured static routing between Lagos, Ogun, and Port Harcourt.
* Implemented centralized DHCP at Lagos Headquarters.
* Configured DHCP Relay (ip helper-address) on branch routers.
* Configured DNS for hostname resolution.
* Configured an HTTP web server accessible from all branches.
* Verified end-to-end connectivity using ICMP (ping).
* Verified DNS resolution by accessing the web server using www.company.com.

⸻

Testing Performed

* Router interface verification using show ip interface brief
* Routing table verification using show ip route
* End-to-end connectivity tests using ping
* Automatic IP address allocation through DHCP
* DNS resolution testing
* Web server accessibility testing

⸻

Project Screenshots

Include screenshots of:

* Network topology
* DHCP configuration on a branch PC
* Successful ping between branches
* show ip route
* Web page loaded through www.company.com

⸻

What I Learned

This project strengthened my understanding of:

* Enterprise network design
* IP addressing and subnetting
* Static routing
* DHCP and DHCP Relay
* DNS configuration
* Web server configuration
* Network troubleshooting
* End-to-end connectivity testing

⸻

Future Improvements

* Implement VLANs
* Configure Inter-VLAN Routing
* Implement OSPF Dynamic Routing
* Configure SSH for secure router management
* Implement Access Control Lists (ACLs)
* Configure NAT/PAT
* Add network redundancy

⸻

Author

Soluade Abdullahi

Computer Science Student | Networking & Cybersecurity Enthusiast

Building practical networking and cybersecurity projects as I work toward a career in Network Engineering and Cloud Security.
