VLAN and Trunking Configuration Project

Project Overview

This project demonstrates VLAN creation, port assignment, and trunking between two Cisco switches using Cisco Packet Tracer.

The network is divided into four departments using separate VLANs. A trunk link is configured between the switches to carry traffic from multiple VLANs over a single physical connection.

VLAN Details

| VLAN ID | VLAN Name | Department             |
| ------- | --------- | ---------------------- |
| 10      | MKT       | Marketing              |
| 20      | IT        | Information Technology |
| 30      | HR        | Human Resources        |

Network Topology

The topology consists of two Cisco switches connected through a trunk link.

End devices are connected to access ports on the switches and assigned to their respective VLANs.

The departments are distributed across both switches. The trunk link allows the same VLANs to extend across both switches.

VLAN Configuration

The following VLANs are created on the switches:

VLAN 10 - MKT

VLAN 20 - IT

VLAN 30 - HR

Access ports are assigned to the appropriate VLAN according to the department of the connected device.

Trunk Configuration

A trunk link is configured between the two switches.

The trunk allows multiple VLANs to travel between the switches through a single physical connection.

The trunk carries traffic for:

VLAN 10 - MKT

VLAN 20 - IT

VLAN 30 - HR

This allows devices belonging to the same VLAN to communicate even when they are connected to different switches.

Concepts Used

* VLAN
* VLAN ID
* Access Port
* Trunk Port
* IEEE 802.1Q
* Broadcast Domain
* MAC Address Learning
* Cisco IOS
* Cisco Packet Tracer

Verification Commands

VLAN configuration can be checked using:

```text
show vlan brief
```

Trunk configuration can be verified using:

```text
show interfaces trunk
```

The current switch configuration can be viewed using:

```text
show running-config
```

Connectivity can be tested using:

```text
ping <destination-IP-address>
```

Expected Result

Devices belonging to the same VLAN should be able to communicate with each other, including devices connected to different switches through the trunk link.

Devices belonging to different VLANs will not communicate directly because inter-VLAN routing is not configured in this project.

Learning Outcomes

Through this project, I learned how to:

* Create VLANs on Cisco switches.
* Assign switch ports to specific VLANs.
* Configure access ports.
* Configure a trunk link between switches.
* Carry multiple VLANs over a single trunk connection.
* Understand VLAN segmentation.
* Verify VLAN and trunk configurations.
* Test network connectivity using ping.

Author
Saara Bhosale
