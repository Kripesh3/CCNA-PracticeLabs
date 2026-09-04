# Day 006 - Ethernet LAN Switching & ARP

## Objective

* Understand the basics of Ethernet LAN switching.
* Learn how a switch dynamically builds its MAC address table.
* Understand the role of ARP in network communication.
* Practice observing switching and ARP behavior using Cisco Packet Tracer.

## Topology / Setup

Created a network topology in Cisco Packet Tracer and generated network traffic between devices to allow the switch to dynamically learn MAC addresses.

Used the switch's CLI to view the dynamically created MAC address table and observed ARP activity during communication between devices.

## Configuration Summary

* Created a basic LAN topology.
* Generated traffic between connected devices.
* Observed the switch learning source MAC addresses and building its dynamic MAC address table.
* Used Cisco IOS commands to view the MAC address table.
* Observed ARP requests and replies during device communication.

## What I Learned

* Ethernet switches use **MAC addresses** to forward frames within a LAN.
* A switch dynamically learns MAC addresses by examining the source MAC address of incoming frames.
* The learned MAC addresses are stored in the switch's **MAC address table**.
* The MAC address table helps the switch determine which interface to use when forwarding frames.
* **ARP (Address Resolution Protocol)** is used to discover the MAC address associated with a known IPv4 address on the local network.
* Observed how ARP and Ethernet switching work together during communication between devices.

