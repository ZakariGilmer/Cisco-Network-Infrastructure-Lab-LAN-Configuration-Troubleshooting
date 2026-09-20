# Cisco Network Infrastructure Lab

## Overview

This project is a hands-on networking lab developed using **Cisco Packet Tracer**. The project focuses on designing, configuring, testing, and troubleshooting a functional network using Cisco networking technologies.

The lab demonstrates practical knowledge of **IPv4 addressing, Ethernet switching, routing, DNS, default gateways, and network connectivity troubleshooting**.

The project was completed to strengthen my understanding of fundamental networking concepts and gain hands-on experience working with simulated Cisco network infrastructure.

## Project Objectives

* Design and build a functional network topology
* Configure IPv4 addressing for network devices and end hosts
* Configure routers and switches
* Establish appropriate default gateways
* Configure and verify DNS services
* Test communication between network devices
* Troubleshoot network connectivity issues
* Verify configurations using Cisco IOS commands
* Document the network configuration and testing process

## Technologies & Tools

* **Cisco Packet Tracer**
* **Cisco IOS**
* IPv4
* TCP/IP
* Ethernet
* DNS
* DHCP
* ICMP
* Cisco Routers
* Cisco Switches
* End-user devices

## Network Topology

The network was designed and configured in Cisco Packet Tracer using routers, switches, end devices, and network services.

The topology was built to allow devices on the network to communicate with one another and to demonstrate fundamental routing and switching concepts.

![Network Topology](screenshots/network-topology.png)

## Network Configuration

### IPv4 Addressing

Network devices and end hosts were configured with the appropriate IPv4 settings, including:

* IP address
* Subnet mask
* Default gateway
* DNS server

Addressing was configured according to the requirements of the network topology.

### Switching

Cisco switches were used to connect end devices within the local network.

Switch operation was verified by examining the MAC address table and confirming that connected devices were being learned by the switches.

### Routing

Routers were configured to allow communication between different network segments.

Router interfaces and routing information were verified using Cisco IOS commands and connectivity testing.

### DNS

DNS services were configured to provide hostname resolution for network resources.

DNS functionality was tested from connected end devices to verify that hostnames could be resolved correctly.

## Testing & Verification

After configuration, the network was tested to verify connectivity and proper operation.

Testing included:

```text
ping
ipconfig
tracert
nslookup
show ip interface brief
show ip route
show mac address-table
```

Ping tests were used to verify communication between devices, while Cisco IOS commands were used to inspect network configurations and routing information.

![Connectivity Test](screenshots/connectivity-test.png)

## Troubleshooting

During the development of the network, connectivity issues were investigated and resolved through systematic troubleshooting.

The troubleshooting process included checking:

* IP addresses
* Subnet masks
* Default gateways
* DNS settings
* Router interfaces
* Switch connectivity
* Cable connections
* Routing configuration
* Device configuration

Rather than changing configurations randomly, individual network components were checked to identify the source of connectivity problems.

This process provided hands-on experience with diagnosing and resolving common networking issues.

![Troubleshooting](screenshots/troubleshooting.png)

## Results

The completed project demonstrated successful network configuration and connectivity between the required devices.

The final network was verified through connectivity testing and configuration checks.

Key results included:

* Successful communication between network devices
* Proper IPv4 configuration
* Functional switching
* Functional routing
* Successful DNS resolution
* Successful connectivity testing
* Identification and resolution of configuration issues

## Skills Demonstrated

### Networking

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

### Cisco

* Cisco Packet Tracer
* Cisco IOS
* Router configuration
* Switch configuration
* Interface configuration
* Routing verification
* MAC address table analysis
* Network connectivity testing

### Technical Skills

* Troubleshooting
* Problem solving
* Configuration analysis
* Network documentation
* Technical communication
* Systematic testing and verification

## Project Files

| File                  | Description                                   |
| --------------------- | --------------------------------------------- |
| `network-project.pkt` | Cisco Packet Tracer network project           |
| `README.md`           | Project documentation                         |
| `screenshots/`        | Network configuration and testing screenshots |

## Future Improvements

Potential improvements to the network include:

* VLAN implementation
* Inter-VLAN routing
* Dynamic DHCP configuration
* Access Control Lists (ACLs)
* Wireless networking
* Additional network segments
* Network redundancy
* Additional security configurations
* Expanded network monitoring and troubleshooting

## Author

**Zakari Gilmer**

Aspiring IT and networking professional developing hands-on experience with Cisco networking, network configuration, troubleshooting, and technical documentation.
