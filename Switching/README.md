

# Switching Labs

## Overview

This folder contains Cisco Packet Tracer labs demonstrating fundamental Layer 2 switching concepts used in enterprise networks. The labs provide practical experience in VLAN management, switch-to-switch connectivity, link aggregation, Spanning Tree Protocol optimization, and switch port security.

---

## Objectives

* Configure and manage switches using Cisco IOS.
* Configure VTP for VLAN information management between switches.
* Configure EtherChannel for link aggregation and redundancy.
* Configure PortFast to optimize STP behavior for end devices.
* Configure Port Security to restrict unauthorized devices.
* Verify switch configurations and Layer 2 connectivity.

---

## Labs Included

| **Lab**       | **Description**                                                                                   |
| ------------- | ------------------------------------------------------------------------------------------------- |
| VTP           | Configure VLAN Trunking Protocol for managing and distributing VLAN information between switches. |
| EtherChannel  | Combine multiple physical links into a single logical connection between switches.                |
| PortFast      | Enable faster transition of access ports to the forwarding state for end devices.                 |
| Port Security | Restrict access to switch ports using MAC address-based security.                                 |

---

## Technologies Used

* Cisco Packet Tracer
* Cisco IOS
* VLAN
* VTP
* Trunking
* EtherChannel
* STP
* PortFast
* Port Security
* MAC Address Security

---

## Key Configurations

### VTP

* Configured switches using appropriate VTP modes.
* Configured VTP domain information.
* Created and managed VLANs.
* Configured trunk links between switches.
* Verified VLAN information across switches.
* Verified VTP status and configuration.

### EtherChannel

* Configured multiple physical switch interfaces for link aggregation.
* Created an EtherChannel group between switches.
* Configured appropriate interface settings.
* Verified the logical EtherChannel connection.
* Verified bundled interfaces and port status.
* Tested network connectivity.

### PortFast

* Configured switch ports as access ports for end devices.
* Enabled PortFast on appropriate interfaces.
* Applied PortFast to optimize STP behavior for end devices.
* Verified PortFast and spanning-tree status.
* Tested end-device connectivity.

### Port Security

* Configured switch interfaces as access ports.
* Enabled port security.
* Configured MAC address-based access control.
* Configured appropriate security violation settings.
* Verified secured MAC addresses.
* Tested unauthorized device behavior.

---

## Concepts Demonstrated

* Layer 2 Switching
* VLAN Management
* VTP
* Trunking
* EtherChannel
* Spanning Tree Protocol (STP)
* PortFast
* Port Security
* MAC Address Filtering
* Network Redundancy
* Switch Configuration
* Layer 2 Network Security
* Network Troubleshooting

---

## Verification Commands

```text
show vlan brief
show vtp status
show interfaces trunk
show etherchannel summary
show spanning-tree
show port-security
show port-security interface
show mac address-table
```

---

## Outcome

Successfully configured and verified multiple Cisco switching technologies using Cisco Packet Tracer. The labs demonstrate practical implementation of VTP, EtherChannel, PortFast, and Port Security, along with VLAN management, trunking, STP optimization, link aggregation, and Layer 2 security.

---

## Software

* Cisco Packet Tracer
* Cisco IOS

