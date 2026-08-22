# Computer Networks Implementations

This repository contains two Computer Networks implementations developed using **Cisco Packet Tracer**.

## Implementations

### 1. ARP Implementation and Simulation

This project demonstrates how **Address Resolution Protocol (ARP)** maps an IP address to its corresponding MAC address within a LAN.

**Components used:**

* PC0, PC1, PC2
* Server0
* 2960 Switch
* IP network: `192.168.11.0/24`

**Process demonstrated:**

* ARP Request broadcast
* Switch broadcast flooding
* ARP Reply from the destination device
* ARP table update
* Successful ping communication

### 2. LAN-to-LAN WAN Communication

This project demonstrates communication between two separate LANs through a **WAN connection** using Cisco Packet Tracer.

**Components used:**

* Two routers
* Two switches
* PCs
* Serial WAN connection
* LAN and WAN IP addressing

**Network structure:**

* Site A: `192.168.1.0/24`
* Site B: `192.168.2.0/24`
* WAN: `10.0.0.0/30`

**Process demonstrated:**

* IP addressing
* Router configuration
* WAN serial connection
* Static/dynamic routing
* Packet forwarding between LANs
* Successful end-to-end communication

## Tools Used

* Cisco Packet Tracer
* Computer Networks concepts
* IPv4
* ARP
* IP Addressing
* Routing
* WAN Communication

## Repository Structure

```text
Computer-Networks-Implementations/
│
├── ARP-Simulation/
│   └── ARP_Simulation.pkt
│
├── LAN-to-LAN-WAN-Communication/
│   └── LAN_to_LAN_WAN.pkt
│
└── README.md
```

## Result

Both implementations were successfully simulated in Cisco Packet Tracer. The ARP simulation demonstrated IP-to-MAC address resolution, while the WAN simulation demonstrated successful communication between two separate LANs through routers.

## Author

**Afiya Babarchi**
B.E. – Computer Science & Engineering (Artificial Intelligence & Machine Learning)
