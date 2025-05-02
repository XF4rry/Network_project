# Network Infrastructure Project

This project showcases the design and implementation of a secure and scalable network environment using key networking concepts such as VLANs, trunking, ACLs, subnetting, and a DMZ.

## Features

### VLAN Configuration

The network is segmented into multiple Virtual LANs to separate traffic between departments (e.g., HR, IT, Finance) and improve performance and security.

### Trunk Links

Switch trunk ports are configured using 802.1Q encapsulation to carry traffic for multiple VLANs across a single physical link, ensuring efficient communication between switches.

### Subnetting

Each VLAN is assigned a unique subnet. CIDR and VLSM techniques are applied to optimize IP address usage and minimize waste.

### Access Control Lists (ACLs)

Standard and extended ACLs are implemented to control access between VLANs, restrict unauthorized traffic, and enforce security policies based on source/destination IP, protocols, and ports.

### Demilitarized Zone (DMZ)

A DMZ is set up to host public-facing services such as web and mail servers. It is isolated from the internal LAN and protected by firewall rules to minimize exposure to external threats.

### Inter-VLAN Routing

A Layer 3 device (router-on-a-stick or Layer 3 switch) is configured to enable communication between VLANs while adhering to ACL restrictions.



## Tools Used

* Cisco Packet Tracer / GNS3 / EVE-NG (for simulation)

## License

This project is licensed under the MIT License. Feel free to use, modify, and share it.
