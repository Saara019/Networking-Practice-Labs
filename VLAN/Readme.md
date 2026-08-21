VLAN Configuration Project

Project Overview

This project demonstrates the configuration and implementation of Virtual Local Area Networks (VLANs) using Cisco Packet Tracer.

VLANs are used to logically divide a physical network into separate broadcast domains. In this project, different departments are separated into individual VLANs for better network organization and segmentation.

VLAN Details

| VLAN ID | VLAN Name | Department             |
| ------- | --------- | ---------------------- |
| 10      | MKT       | Marketing              |
| 20      | IT        | Information Technology |
| 30      | SALES     | Sales                  |
| 40      | HR        | Human Resources        |

Objectives

* Create and configure multiple VLANs.
* Assign switch ports to specific VLANs.
* Separate different departments into individual broadcast domains.
* Configure PCs with appropriate IP addresses.
* Verify connectivity between devices within the same VLAN.
* Understand VLAN segmentation and switch configuration.

Network Components

* Cisco Switch
* PCs/End Devices
* VLAN 10 - MKT
* VLAN 20 - IT
* VLAN 30 - SALES
* VLAN 40 - HR

Concepts Used

* VLAN Configuration
* Access Ports
* Switch Port Configuration
* Broadcast Domains
* MAC Address Learning
* Cisco IOS
* Cisco Packet Tracer

Verification

The VLAN configuration can be verified using the following commands:

```text
show vlan brief
show running-config
```

Connectivity can be tested using:

```text
ping <destination-IP-address>
```

Devices within the same VLAN can communicate with each other. Devices in different VLANs cannot communicate because inter-VLAN routing is not configured.

Project Files

* VLAN.pkt - Cisco Packet Tracer topology and VLAN configuration.
* README.md - Project documentation.
* topology.png - Screenshot of the network topology.
* configuration.txt - VLAN configuration commands.

Learning Outcomes

Through this project, I learned how to:

* Create VLANs on a Cisco switch.
* Assign switch ports to specific VLANs.
* Configure access ports.
* Separate departments into different broadcast domains.
* Verify VLAN configurations.
* Test connectivity using the ping command.
* Understand network segmentation using VLANs.

Author

Saara Bhosale
