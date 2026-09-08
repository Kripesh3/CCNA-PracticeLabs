# Day 012 - Life of a Packet

## Objective

* Understand how a packet travels from a PC in one network to a PC in another network.
* Learn how IP and MAC addresses are used during communication.
* Understand how the packet's Layer 2 information changes as it passes through routers.

## Topology / Setup

Created a network topology in Cisco Packet Tracer with PCs connected through switches and routers.

Observed the packet's journey from the source PC to a destination PC located on a different network.

## What I Learned

* The **IP addresses** of the source and destination generally remain the same throughout the packet's journey.
* The **MAC addresses** change at each Layer 2 hop as the packet moves from one network segment to another.
* When a packet reaches a router, the router removes the incoming Ethernet frame and creates a new frame for the next network segment.
* The destination MAC address on each network segment is determined based on the next hop.
* The source and destination IP addresses are used for end-to-end communication, while MAC addresses are used for local, hop-by-hop delivery.
* Learned how **ARP** can be used to discover the MAC address needed for local Ethernet delivery.
* Observed the life of a packet in Cisco Packet Tracer and gained a better understanding of how switches and routers work together to deliver data between different networks.

