# Networking - SOC Analyst Diploma

This section documents my networking training and practical work completed as part of my SOC Analyst diploma.

## Project Overview

As part of the networking module, I designed and configured an enterprise network using Cisco Packet Tracer.

The project focused on routing, VLSM addressing, network services, VLANs, and end-to-end connectivity.

## Technologies & Concepts

- IPv4 Addressing
- VLSM
- Static Routing
- OSPF
- OSPF Area 0
- DHCP
- SSH
- DNS
- HTTP
- VLANs
- Network Connectivity Testing
- Cisco IOS
- Cisco Packet Tracer

## Network Topology

The project contains four routers connected through multiple network segments.

The network uses:

- Static Routing on one side
- OSPF Area 0 on the other side
- VLSM for IP addressing
- Multiple LAN networks
- VLAN segmentation

![Network Topology]([Screenshots/Topology.png](https://github.com/kareemmousa478/SOC-Level1-Journey/blob/main/SOC-Diploma/Networking/Topology.png))

## Network Services

### DHCP

DHCP was configured to automatically provide IP addressing information to clients.

### SSH

SSH was configured to allow secure remote management of the router.

### DNS & HTTP

A DNS server and an HTTP server were configured.

Clients were tested to access the web service using a domain name instead of directly using the server IP address.

### VLANs

Three VLANs were configured:

- VLAN 10
- VLAN 20
- VLAN 30

Six PCs were connected across the VLANs.

## Routing

### Static Routing

Static routes were configured on the designated side of the topology to provide connectivity between networks.

### OSPF

OSPF was configured using Area 0 on the other side of the topology.

## IP Addressing

VLSM was used to allocate subnet sizes according to network requirements.

The project uses variable subnet masks rather than default classful /8, /16, or /24 networks.

Examples include:

- /26
- /28
- /29
- /30

## Verification

The following functionality was tested:

- End-to-end connectivity
- DHCP address assignment
- SSH remote access
- DNS name resolution
- HTTP access using a domain name
- VLAN configuration
- Routing connectivity

## Tools

- Cisco Packet Tracer
- Cisco IOS

## Project File

The complete Cisco Packet Tracer project is available in the `Packet-Tracer` directory.

## Learning Outcome

This project strengthened my understanding of enterprise networking concepts and provided practical experience with routing, IP addressing, network services, VLAN segmentation, and network troubleshooting.
