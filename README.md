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
- Netplan configuration
- DHCP configuration

# Network Topology
![Network Topology](https://github.com/maxlaj456/networkingproject.io/blob/main/images/networktopology.drawio.png)

# Results Summary
The result was good. I managed to complete all objectives, even though I sometimes hade to troubleshoot. It was especially the YAML files, and the IP-forwarding that caused problems. With the YAML files, there were old files that had to be deleted for the netplan to work. I did not in the beginning, so my changes to each device IP address was ignored. That made it hard for the DHCP to automatically configure each device. 

# Repository structure
- Lab Plan: Planning & goals with the lab
- Network Design: How the network is designed and the decisions behind it
- Implementation: Overview of the actions taken to reach the objectives
- Verification: Tests & evidence
- Security Analysis: Perspective from the security point of view
- Lessons Learned: Reflections & growth
- Images: Images and visual proof

# Status
Planning phase
