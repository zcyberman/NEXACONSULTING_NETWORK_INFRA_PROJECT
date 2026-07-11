<img width="1840" height="1270" alt="image" src="https://github.com/user-attachments/assets/ad87b24b-42d9-4b55-8a4f-4ef2bae1e809" />
NexaConsult Enterprise Network Infrastructure (Cisco Packet Tracer)
Overview

This project simulates the network infrastructure of NexaConsult Ltd, a mid-sized IT consulting company. The network was designed and configured in Cisco Packet Tracer to demonstrate enterprise networking concepts commonly covered in the Cisco CCNA curriculum.

The project includes VLAN segmentation, inter-VLAN routing, centralized DHCP, DNS, ACLs, SSH, port security, and network hardening. It was built from the ground up while troubleshooting real networking issues throughout development.

Features
Multi-department enterprise network
VLAN segmentation
Router-on-a-Stick inter-VLAN routing
Centralized DHCP server
Internal DNS server
HTTP intranet server
Extended ACLs for department access control
SSH remote management
Port Security with sticky MAC addresses
Device hardening and password encryption
Network Topology

Departments include:

Management
IT/Admin
Consultants
HR & Finance
Guest WiFi
Server Network

Infrastructure consists of:

Cisco ISR 4331 Routers
Cisco Catalyst 3560 Core Switch
Cisco Catalyst 2960 Access Switches
DHCP Server
DNS Server
HTTP Server
Technologies Used
Cisco Packet Tracer
Cisco IOS
VLANs (802.1Q)
Router-on-a-Stick
DHCP
DNS
HTTP
ACLs
SSH
Port Security
Static & Dynamic IP Addressing
Network Design

The network was segmented into six VLANs:

VLAN	Department
10	Management
20	IT/Admin
30	Consultants
40	HR & Finance
50	Guest WiFi
99	Servers

Each VLAN has its own subnet with centralized DHCP while servers use static IP addressing.

Security Features
VLAN segmentation
SSH-only remote management
Telnet disabled
Encrypted passwords
Port Security (Sticky MAC)
ACLs restricting department communication
Guest network isolated from internal resources
Testing

The following functionality was successfully verified:

Inter-VLAN Routing
DHCP across all VLANs
ACL enforcement
Guest network isolation
HR access restrictions

The only remaining item is completing HTTP access to the internal intranet server.

Lessons Learned

During this project I gained hands-on experience with:

Designing enterprise network topologies
VLAN implementation
Router-on-a-Stick configuration
DHCP relay (ip helper-address)
Network troubleshooting using Cisco IOS commands
Access Control Lists (ACLs)
SSH configuration
Switch security
Diagnosing Layer 2 and Layer 3 connectivity issues
Future Improvements
Complete HTTP server configuration
Implement NAT/PAT for Internet connectivity
Add redundancy with HSRP
Configure EtherChannel
Deploy IPv6
Add wireless access points
Implement monitoring using SNMP
Skills Demonstrated
Cisco Networking
CCNA Concepts
Enterprise Network Design
VLAN Configuration
Routing & Switching
Network Security
Troubleshooting
Cisco IOS CLI
Infrastructure Documentation
