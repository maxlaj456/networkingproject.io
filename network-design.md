# Network Design
This document will walk you through my thoughts behind the network design. 

## Topology Description
The network consist of 2 routers, 2 clients (I named them VM1 and VM3) and 2 subnets. Each client belongs to one subnet each. The clients are also connected to one router each. The routers are connected to the internet via NAT configuration - I explain this further in the implementation.md file. At the top of the topology is the internet.

## Addressing Scheme
IP-addresses are seperated into two internal subnets. The first one is 192.168.33.0 and the second one is 10.13.37.0. The purpose of having two different subnets is because it should give an example of who a network may look like, but also because it is easier to administrate, safer and is it particulary needed to be able to do routing which is a big part of this lab. The clients reach each other through specified routing tables. 

## Routing Strategy
I choosed default routing, and set the route via routing tables. It is a more default way of setting routes. Since I knew that the firewall were only going to accept ICMP traffic between the specified subnets, I had to go with default routing to be able to make the clients reach each other. 

## Network Topology
![Network Topology](https://github.com/maxlaj456/networkingproject.io/blob/main/images/network-topology.png)
