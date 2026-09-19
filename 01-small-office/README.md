# Project 1: Small Office Network (Dual-Stack)

**Status:** Completed

## Objective
Build a small office LAN with one router, one switch and three PCs,
using both IPv4 and IPv6 (dual-stack).

## Topology
(screenshot will be added)

## Addressing Table
| Device | IPv4 | IPv6 |
|---|---|---|
| R1 G0/0 | 192.168.10.1/24 | 2001:DB8:ACAD:10::1/64 |
| S1 VLAN 1 | 192.168.10.2/24 | - |
| PC1 | 192.168.10.10/24 | 2001:DB8:ACAD:10::10/64 |
| PC2 | 192.168.10.11/24 | 2001:DB8:ACAD:10::11/64 |
| PC3 | 192.168.10.12/24 | 2001:DB8:ACAD:10::12/64 |

## Skills Practiced
- Basic Cisco IOS configuration
- Device hardening (passwords, banner)
- IPv4 and IPv6 addressing
- Connectivity testing with ping
