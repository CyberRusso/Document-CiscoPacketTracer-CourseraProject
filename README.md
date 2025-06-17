# Document-CiscoPacketTracer-CourseraProject
Focused on implementing foundational network security configurations using Cisco Packet Tracer, a network simulation tool.

## Cisco Packet Tracer: How to Secure Your Network Devices (Coursera Project)

## Overview
This guided project, hosted on Coursera and delivered by Cisco Networking Academy, focused on implementing foundational network security configurations using Cisco Packet Tracer, a network simulation tool. The project simulated real-world practices to secure routers and switches by applying essential hardening techniques aligned with best practices in infrastructure security.

## Project Objectives
- Build a basic network topology using Cisco Packet Tracer
- Secure Cisco routers and switches from unauthorized access
- Implement device hardening, secure remote management, and traffic filtering
- Simulate and verify the impact of security configurations

## Key Tasks Completed
Network Topology Setup:
- Deployed a basic lab environment simulating an enterprise network, including routers, switches, and end-user devices. Configured IP addressing and interface settings for connectivity.

Privilege EXEC Mode Security:
- Secured privileged EXEC mode using encrypted passwords (enable secret) and ensured only authenticated users could make configuration changes.

SSH Configuration for Secure Remote Access:
- Generated RSA encryption keys for SSH access
- Configured VTY lines to accept SSH only
- Disabled insecure protocols like Telnet
- Created local user credentials with privilege levels

Port Security on Switches:
- Enabled port security on switch interfaces to restrict access to only specific MAC addresses and prevent MAC flooding attacks. Configured violation actions like shutdown on unauthorized access attempts.

Disable Unused Ports:
- Administratively shut down unused switch ports to eliminate attack vectors from rogue device connections.

Access Control Lists (ACLs):
- Configured standard ACLs to filter traffic based on source IP addresses, limiting access to the router's management interfaces and securing internal communications.

## Skills Developed
- Cisco IOS CLI Configuration
- Router and Switch Hardening
- Secure Remote Access (SSH)
- MAC-based Port Security
- Interface Management and Shutdown
- Traffic Filtering using ACLs
- Cisco Packet Tracer Simulation and Testing
