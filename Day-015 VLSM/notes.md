# Day 015 - Subnetting, VLSM & Static Routing

## Objective

* Learn the fundamentals of IPv4 subnetting.
* Understand FLSM and VLSM subnetting.
* Learn about CIDR and different subnet masks.
* Practice subnetting a network based on host requirements.
* Configure static routing to enable communication between the subnetted networks.

## Topology / Setup

Created a multi-network topology in Cisco Packet Tracer and divided the available network into multiple subnets based on the number of hosts required by each network.

Configured the routers and used static routing to establish communication between the different subnetworks.

## Configuration Summary

* Calculated subnet sizes based on the required number of hosts.
* Used **VLSM (Variable Length Subnet Masking)** to efficiently divide the network.
* Configured IPv4 addresses and subnet masks on router interfaces and end devices.
* Configured **static routes** between routers.
* Verified communication between devices across different subnets.

## What I Learned

* **Subnetting** divides a larger network into smaller networks called subnets.
* **FLSM (Fixed Length Subnet Masking)** uses the same subnet mask for all subnets.
* **VLSM (Variable Length Subnet Masking)** allows different subnet masks to be used based on host requirements, making address allocation more efficient.
* **CIDR (Classless Inter-Domain Routing)** allows networks to be represented using prefix lengths rather than relying on traditional address classes.
* Learned about different IPv4 address classes and subnet masks.
* Learned how to calculate the network address, broadcast address, usable host range, and number of usable hosts for a subnet.
* Gained hands-on experience subnetting a network according to different host requirements.
* Successfully used static routing to enable communication between the subnetted networks.

