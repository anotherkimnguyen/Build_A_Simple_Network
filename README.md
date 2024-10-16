# Building a Simple Network for Hackers Poulette

## What?
This exercise features the creation of a basic network infrastructure for Hackers Poulette, which is designed to be scalable in order to support the start-up's growth. The infrastructure includes three hosts connected to a switch, with added internet connectivity through an ISR4331 router.

## Why?
The goal of this challenge is to establish a reliable and scalable network which would allow the team at Hackers Poulette to communicate internally and access the internet.

## When?
The project was completed to meet the deadline of 18/10/2024.

## How?
Equipment and Software Used

Cisco Packet Tracer: For designing and simulating the network.\
Switch: Cisco 2960\
Router: Cisco ISR4331 with IP 192.168.1.1\
Hosts: Three PCs (Windows 10)\
Cabling: Ethernet cables for connections

### Configuration Steps
Designing the Network: The network was designed using Cisco Packet Tracer, incorporating a Cisco 2960 switch and an ISR4331 router to connect three Windows 10 PCs (PC-Robert, PC-Camille, PC-Renaud).

### IP Addressing:
#### Router (ISR4331): Configured with the IP address 192.168.1.1 on its LAN interface to act as the gateway for the network.
#### PCs: Assigned the following IP addresses and subnet masks:
PC-Robert: 192.168.1.10/24\
PC-Camille: 192.168.1.11/24\
PC-Renaud: 192.168.1.12/24

#### Testing Connectivity:
Ping utility to verify internal connectivity among the devices and their ability to reach the internet through the router.

#### Simulating Connectivity:

## Who
Solo challenge completed by Kim G. 

## Pending Tasks
Optimize router configurations for enhanced security.\
Implement VLANs for network segmentation as the company grows.\
Set up a firewall for secure internet access.\
Internet conectivity for the network.\
Develop a network monitoring system for performance tracking.\
Scale the network infrastructure to support future growth.
