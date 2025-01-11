# Secure and Scalable Bank Network Simulation

This project demonstrates the design and implementation of a secure, scalable banking network using **Cisco Packet Tracer**. It connects a centralized head office with four branch offices, integrating dynamic routing (OSPF), DHCP services, and access control (ACL) to ensure secure and efficient operations.

## Project Overview
- **Dynamic Routing (OSPF)** for efficient and adaptive communication.
- **DHCP Services** for automatic IP allocation in branch networks.
- **Access Control Lists (ACLs)** to restrict unauthorized access to the Bank Management System (BMS).

## Network Architecture
- **Head Office** connected to four branches.
- **Centralized BMS Server** hosted at the head office.
- **Routers and Switches** configured for routing, DHCP, and ACL.

### IP Addressing Scheme
| Network Component | Device  | IP Address   | Subnet Mask   |
|-------------------|---------|--------------|---------------|
| Head Office LAN   | Router  | 192.168.0.1  | 255.255.255.0 |
| Branch 1 LAN      | Router  | 192.168.1.1  | 255.255.255.0 |
| Branch 2 LAN      | Router  | 192.168.2.1  | 255.255.255.0 |
| Branch 3 LAN      | Router  | 192.168.3.1  | 255.255.255.0 |
| Branch 4 LAN      | Router  | 192.168.4.1  | 255.255.255.0 |

**WAN links** between branches and the head office are configured with **/30 subnets** for point-to-point connections.

## Features
- **OSPF Routing**: Ensures dynamic and reliable communication.
- **DHCP**: Automates IP address management for clients.
- **ACL Security**: Controls access to critical resources on the BMS server.

## Deliverables
- **Network Topology Diagram**: Designed in Cisco Packet Tracer.
- **Router and Server Configurations**: OSPF, DHCP, and ACLs.
- **Testing Logs**: Connectivity, dynamic IP assignment, and security tests.

## Tools
- **Cisco Packet Tracer** for simulation.
- **Command Prompt (ping, tracert)** for connectivity validation.
