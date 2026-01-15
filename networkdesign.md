# Network Design
This document will walk you through my thoughts behind the network design. 

## Topology Description
The network consist of 2 routers, 2 clients (I named them VM1 and VM3) and 2 subnets. Each client belongs to one subnet each. The clients are also connected to one router each. The routers are connected to the internet via NAT configuration - I explain this further in the implementation.md file. At the top of the topology is the internet.

## Addressing Scheme
IP-addresses are seperated into two subnets.
