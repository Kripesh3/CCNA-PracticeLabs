# Day 020 - Spanning Tree Protocol (STP)

## Objective

* Understand the purpose of Spanning Tree Protocol (STP).
* Learn about network redundancy and why it is important.
* Understand Layer 2 loops and broadcast storms.
* Learn about root cost and how STP uses it to determine paths.
* Understand different STP port states.
* Use Cisco IOS CLI to observe STP information on switches.

## Topology / Setup

Created a redundant switch topology in Cisco Packet Tracer and used the switch CLI to observe how STP manages redundant links and prevents Layer 2 loops.

## Configuration Summary

* Created a topology with redundant connections between switches.
* Used Cisco IOS CLI commands to view STP information.
* Observed the roles and states of switch ports.
* Examined root cost and how it influences the STP path selection.

## What I Learned

* **STP (Spanning Tree Protocol)** prevents Layer 2 loops in Ethernet networks.
* Network redundancy provides alternate paths and improves availability if a link fails.
* Redundant Layer 2 paths can create loops when STP is not used.
* Layer 2 loops can result in **broadcast storms** and excessive network traffic.
* **Root cost** helps STP determine the best path toward the Root Bridge.
* STP places certain ports into different states to prevent forwarding loops.
* Cisco IOS CLI commands can be used to inspect STP information, including the Root Bridge, root cost, port roles, and port states.
* Gained hands-on experience observing STP operation and port information through the switch CLI in Cisco Packet Tracer.

