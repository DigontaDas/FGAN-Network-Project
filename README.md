# Federal Flight Agency Network (FGAN)

A mission-critical network designed in Cisco Packet Tracer for a 
next-generation autonomous aircraft fleet.

## Overview
- Base Network: 1.2.0.0/16 (VLSM subnetting)
- 7 routers, 5 switches, 3 servers
- Protocols: Static routing, RIPv2, DHCP, DNS, HTTP, SMTP/POP3

## Units
- Command Center HQ (2000 devices)
- AI Navigation Unit (850 devices)  
- Aircraft Simulation Lab (1200 devices)
- Maintenance Hangar (600 devices)
- Emergency Control Node (80 devices)
  
## Network Topology

![Labeled Topology Diagram](Labeled%20Topology%20Diagram.png)

## Key Features
- Floating static route with AD=88 for redundancy
- Centralized DNS/Web server
- Inter-domain email (hq.federal ↔ ai.federal)
- Strict routing isolation per spec requirements

## Group Members
| Name | ID | Role |
|---|---|---|
| Khadizatul Kubra | 22201294 | HQ & Emergency |
| Digonta Das | 22201633 | AI Navigation Unit |
| Apurba Roy | 23101012 | Simulation Lab |
| Mihir Das | 22299480 | Hangar & Integration |
