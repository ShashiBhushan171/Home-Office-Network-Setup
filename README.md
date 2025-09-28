# Home/Office Network Setup

## Project Overview
This project demonstrates a small office LAN setup including switches, routers, access points, static & DHCP IP addressing, NAT, and port forwarding.

## Topology
![Topology](Topology-Diagram.png)

## IP Address Plan
| Device     | IP Address      | Subnet Mask       | Assignment |
|------------|----------------|-----------------|------------|
| Router     | 192.168.1.1    | 255.255.255.0   | Static     |
| PC1        | 192.168.1.100  | 255.255.255.0   | DHCP       |
| PC2        | 192.168.1.101  | 255.255.255.0   | DHCP       |
| Printer    | 192.168.1.50   | 255.255.255.0   | Static     |

## Configuration
- Router configuration (CLI commands)  
- Switch configuration (CLI commands)  

## Testing
- `ping` between devices successful  
- NAT and port forwarding verified  

## Tools Used
- Cisco Packet Tracer 8.x
