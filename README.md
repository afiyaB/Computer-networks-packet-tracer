# Computer Networks Implementations

This repository contains two Computer Networks implementations developed using **Cisco Packet Tracer**.

---

## 1. ARP Implementation and Simulation

### Overview

This implementation demonstrates the **Address Resolution Protocol (ARP)**, which maps a known IP address to its corresponding MAC address within a LAN.

### Network Topology

![ARP Simulation](ARP-Simulation/arp-simulation.png)

### Components

* PC0
* PC1
* PC2
* Server0
* 2960 Switch
* Subnet: `192.168.11.0/24`

### Working

1. PC0 sends a ping request to Server0.
2. PC0 checks its ARP table.
3. If the MAC address is not available, PC0 broadcasts an ARP Request.
4. The switch forwards the broadcast to the connected devices.
5. Server0 sends an ARP Reply containing its MAC address.
6. PC0 updates its ARP table.
7. Communication is completed successfully.

### Result

The simulation successfully demonstrates ARP request broadcasting, ARP reply generation, ARP table updating, and successful ping communication.

---

## 2. LAN-to-LAN WAN Communication

### Overview

This implementation demonstrates communication between two separate LANs using a **WAN connection** in Cisco Packet Tracer.

### Network Topology

![LAN-to-LAN WAN Communication](LAN-to-LAN-WAN-Communication/wan-communication.png)

### Components

* Router A
* Router B
* Switch A
* Switch B
* PC A
* PC B
* Serial WAN connection

### Network Structure

**Site A LAN:** `192.168.1.0/24`

**Site B LAN:** `192.168.2.0/24`

**WAN Link:** `10.0.0.0/30`

### Working

1. IP addresses are assigned to the PCs.
2. Router interfaces are configured.
3. The WAN serial connection is established.
4. Routing is configured.
5. Packets are forwarded from one LAN to the other through the routers.
6. Connectivity is verified using ping.

### Result

The simulation successfully achieved end-to-end communication between the two LANs. Packet forwarding through the routers and WAN link was observed in Cisco Packet Tracer.

---

## Tools Used

* Cisco Packet Tracer
* IPv4
* ARP
* IP Addressing
* Routing
* WAN Communication

---

## Repository Structure

```text
Computer-Networks-Implementations/
│
├── ARP-Simulation/
│   ├── ARP_Simulation.pkt
│   └── arp-simulation.png
│
├── LAN-to-LAN-WAN-Communication/
│   ├── LAN_to_LAN_WAN.pkt
│   └── wan-communication.png
│
└── README.md
```

---

## Conclusion

Both Computer Networks implementations were successfully simulated using Cisco Packet Tracer.

* **ARP Simulation:** Demonstrates IP-to-MAC address resolution within a LAN.
* **LAN-to-LAN WAN:** Demonstrates communication between two separate LANs through a WAN connection.

## Author

**Afiya Babarchi**

B.E. – Computer Science & Engineering
Artificial Intelligence & Machine Learning
