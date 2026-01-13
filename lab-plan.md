# Lab Plan

# Goal
I will have 2 routers and 2 devices, seperated in two different subnets. One device for each router, in the same subnet. There are several goals with this lab. Make it possible for the devices to reach the internet and to reach each other. Firewall rules should only allow ICMP traffic and SSH to go between the networks, everything else should be dropped. Each devices should get all necessary network configuration from DHCP with no manual configuration. All configruation and services should work after reboot without manual intervention. 

# Tools 
- VirtualBox
- DHCP server
- NAT

# Expected outcome
Being able to reach the internet with the devices. Configure the firewall to only allow ICMP traffic and SSH. Every configuration and service should work after reboot. DHCP should automatically deliver all the necessary configuration to the devices.
