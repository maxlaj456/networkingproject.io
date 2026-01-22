# Verification
This document demonstrates that the lab functions as intended.

## Internal Connectivity Tests
- VM1 successfully pings VM3 across routed networks
- Routers can reach each other via the transit network
- SSH access between networks is functional

## External Connectivity Tests

- Clients can ping public IP addresses (1.1.1.1, 8.8.8.8)
- DNS resolution works (ping google.com)
- Routers provide Internet access via NAT

## Observations

- Misconfigured netplan files can silently override settings
- Firewall rules must explicitly allow forwarding traffic
- NAT configuration is essential for client Internet access
