# Cisco Network Infrastructure Lab

## Overview

This project is a hands-on networking lab created using **Cisco Packet Tracer**. The goal was to design, configure, test, and troubleshoot a functional network while applying fundamental Cisco networking concepts.

The project demonstrates practical experience with network devices, IPv4 addressing, Ethernet switching, routing, DNS, default gateways, and end-to-end connectivity testing.

## Objectives

* Design a functional LAN topology
* Configure IPv4 addressing
* Configure PCs and network devices
* Configure switches and routers
* Establish default gateways
* Configure DNS services
* Verify end-to-end connectivity
* Troubleshoot connectivity and configuration issues
* Use Cisco Packet Tracer to simulate a real-world networking environment

## Technologies & Tools

* Cisco Packet Tracer
* Cisco IOS
* IPv4
* Ethernet
* TCP/IP
* DNS
* DHCP
* ICMP
* Cisco switches
* Cisco routers
* Windows-based end devices

## Network Topology

The network was designed in Cisco Packet Tracer and consists of end devices, network switches, routers, and supporting network services.

![Network Topology](screenshots/network-topology.png)

## Configuration

### IPv4 Addressing

The network uses IPv4 addressing to allow devices to communicate across the network.

Each device was configured with the appropriate:

* IP address
* Subnet mask
* Default gateway
* DNS server

### Switching

Cisco switches were used to connect end devices within the LAN.

The project demonstrates the use of Ethernet switching and MAC address learning to facilitate communication between connected devices.

### Routing

Routers were configured to provide communication between different network segments.

Routing configuration was verified using connectivity tests and device configuration commands.

### DNS

A DNS server was configured to provide name resolution for network devices and services.

This allowed clients to access network resources using hostnames rather than relying solely on IP addresses.

## Testing & Verification

Network connectivity was tested using tools and commands available within Cisco Packet Tracer.

Examples include:

```text
ping
ipconfig
tracert
nslookup
```

Successful ping tests were used to verify connectivity between network devices and end hosts.

![Connectivity Test](screenshots/connectivity-test.png)

## Troubleshooting

During development, connectivity issues were identified and resolved by checking:

* IP addressing
* Subnet masks
* Default gateways
* DNS configuration
* Router interfaces
* Switch connectivity
* Cable connections
* Routing configuration
* Device configuration

The troubleshooting process helped verify that each layer of the network was functioning correctly.

## Project Results

The completed network successfully demonstrated:

* End-device connectivity
* Communication between network segments
* Proper IP addressing
* DNS name resolution
* Router and switch operation
* Network troubleshooting and verification

## Skills Demonstrated

**Networking**

* IPv4 addressing
* Subnetting fundamentals
* LAN configuration
* Ethernet networking
* Switching
* Routing
* DNS
* DHCP
* Default gateways
* Network troubleshooting

**Cisco**

* Cisco Packet Tracer
* Cisco IOS
* Router configuration
* Switch configuration
* Connectivity verification

**Technical Skills**

* Troubleshooting
* Network documentation
* Configuration analysis
* Problem solving
* Technical documentation

## Project Files

| File                  | Description                                   |
| --------------------- | --------------------------------------------- |
| `network-project.pkt` | Cisco Packet Tracer project file              |
| `README.md`           | Project documentation                         |
| `screenshots/`        | Network configuration and testing screenshots |

## Future Improvements

Potential improvements to this project include:

* VLAN implementation
* Inter-VLAN routing
* DHCP configuration
* Access control lists (ACLs)
* Wireless networking
* Additional network segments
* Redundant network paths
* Network security configuration

## Author

**Kyro Johnson**

Aspiring IT and networking professional with hands-on experience in Cisco networking fundamentals and network troubleshooting.
