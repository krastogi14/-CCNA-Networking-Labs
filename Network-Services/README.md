# Network Services Labs

## Overview

This folder contains Cisco Packet Tracer labs demonstrating fundamental network services and remote device management concepts. The labs provide practical experience in configuring DHCP, DNS, HTTP, Telnet, SSH, and RADIUS services for network communication, resource access, and secure device administration.

---

## Objectives

* Configure DHCP for automatic IP address assignment.
* Configure DNS for hostname-to-IP address resolution.
* Configure HTTP services for web-based resource access.
* Configure Telnet for remote device administration.
* Configure SSH for secure remote device administration.
* Configure RADIUS for centralized authentication.
* Verify network services and connectivity between devices.

---

## Labs Included

| **Lab**                               | **Description**                                                                                                 |
| ------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| DHCP, DNS & HTTP Server Configuration | Configure network servers to provide automatic IP addressing, hostname resolution, and HTTP-based web services. |
| Telnet & SSH                          | Configure and verify remote access to network devices using Telnet and secure SSH.                              |
| RADIUS Server                         | Configure centralized authentication using a RADIUS server for network device access.                           |

---

## Technologies Used

* Cisco Packet Tracer
* Cisco IOS
* DHCP
* DNS
* HTTP
* Telnet
* SSH
* RADIUS
* TCP/IP

---

## Key Configurations

### DHCP, DNS & HTTP Server Configuration

* Configured DHCP services for automatic IP address allocation.
* Configured DHCP parameters such as default gateway and DNS server.
* Configured DNS records for hostname resolution.
* Configured HTTP service on the server.
* Verified IP address assignment and hostname resolution.
* Tested access to the hosted web service.

### Telnet & SSH

* Configured remote access on Cisco network devices.
* Configured VTY lines for remote management.
* Configured Telnet access.
* Generated RSA keys for SSH where required.
* Configured SSH authentication and access.
* Verified remote connectivity using Telnet and SSH.

### RADIUS Server

* Configured a RADIUS server for centralized authentication.
* Configured authentication credentials on the RADIUS server.
* Configured the network device to communicate with the RADIUS server.
* Configured AAA authentication for remote device access.
* Verified authentication through the centralized RADIUS server.

---

## Concepts Demonstrated

* DHCP
* DNS
* HTTP
* Dynamic IP Address Assignment
* Name Resolution
* Remote Device Management
* Telnet
* SSH
* Secure Remote Access
* AAA Authentication
* RADIUS
* Client-Server Communication
* Network Troubleshooting

---

## Verification Commands

```text
ipconfig
show ip interface brief
show running-config
show users
show ip ssh
show aaa
```

---

## Outcome

Successfully configured and verified essential network services using Cisco Packet Tracer. The labs demonstrate practical implementation of DHCP, DNS, HTTP, Telnet, SSH, and RADIUS for IP address management, name resolution, web services, remote device administration, and centralized authentication.

---

## Software

* Cisco Packet Tracer
* Cisco IOS

