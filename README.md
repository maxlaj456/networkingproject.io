# Networking Lab

# Overview
A lab giving a insight on how I built and made a network between routers and devices, in two different subnets, work. I made it possible for devices to reach the internet through the routers, to get all DHCP configuration to devices without manual intervention, the firewall rules only accepted ICMP traffic/SSH and it all work after a reboot with no me having to manually do changes. 

# Objectives
- Make devices to reach the internet
- Firewall rules should drop everything except ICMP traffic and SSH between networks
- All devices should get all necessary configuration from DHCP with no manual configuration
- All configuration and services should work after reboot with no manual intervention

# Lab Environment
- Linux
- 4 virtual machines in VirtualBox:
- 2 routers
- 2 devices

# Lab Scope
This lab focuses on building a functioning network

# Key Technologies
- VirtualBox
- NAT
- Iptables
- Routing
- IP-forwarding
- YAML configuration
- DHCP configuration

# Network Topology
![Network Topology](https://github.com/maxlaj456/networkingproject.io/blob/main/images/networktopology.drawio.png)

# Status
Planning phase
