# CompTIA Network+ Study Guide

This directory contains my technical documentation and study notes for CompTIA Network+ (Domain 1 & Domain 2). These notes lay the networking foundation required for advanced offensive security and enterprise IT operations.

## Topics Covered

### 1. Network Components & Models
* Infrastructure Devices: Roles of Routers, Switches, Access Points (APs), Hubs, and Controllers.
* Security & Optimization: Implementations of Firewalls, IDS, IPS, Proxies, and Load Balancers.
* Storage Solutions: Differentiating NAS (Network Attached Storage) and SAN (Storage Area Network).
* Resource Models: Client/Server vs. Peer-to-Peer models.
* Network Geography: Scope definitions covering PAN, LAN, CAN, MAN, and WAN.

### 2. Network Topologies
* Wired Configurations: Point-to-Point, Ring (FDDI), Bus, Star, and Hub-and-Spoke.
* Mesh Networks: Full-Mesh vs. Partial-Mesh architecture. 
  * *Mathematical formulation for Full-Mesh connections:* $$x = \frac{n(n-1)}{2}$$ 
  *(where n = number of nodes)*
* Wireless Configurations: Infrastructure Mode, Ad Hoc Mode, and Wireless Mesh.

### 3. Enterprise Data Center Architecture
* Traditional Hierarchy: The Three-Tiered model (Core $\rightarrow$ Distribution/Aggregation $\rightarrow$ Edge/Access).
* Modern Architectures: Collapsed Core and high-performance Spine-and-Leaf designs.
* Traffic Flows: * North-South: Traffic entering/exiting the data center.
  * East-West: Traffic moving internally between servers.

---
### 4. The OSI Reference Model
A comprehensive breakdown of the OSI stack, from physical transmission to data formatting.

* Layer 1: Physical (Bits)
  * Functions: Handles bit transmission, transition modulation, and cables/topology perspectives. Also covers synchronous/asynchronous communications, baseband/broadband, and multiplexing (TDM, Stat TDM, FDM).
  * Devices: Hubs, Access Points (APs), and Media Converters.
* Layer 2: Data Link (Frames)
  * Functions: Manages MAC addresses, LLC, and isochronous/synchronous transfers. 
  * Devices: Switches and Bridges.
* Layer 3: Network (Packets)
  * Functions: Handles IPv4/IPv6 addressing, route discovery/selection, routing protocols, flow control, and packet reordering. Utilizes packet, circuit, and message switching.
  * Protocols & Devices: ICMP (e.g., ping), Routers, and Multilayer Switches.
* Layer 4: Transport (Segments/Datagrams)
  * Functions: The dividing line between upper and lower layers. Handles windowing and buffering.
  * TCP: Reliable, connection-oriented, uses segment retransmission, flow control (windowing), and segment sequencing.
  * UDP: Unreliable, connectionless, with no windowing, flow control, or sequencing.
  * Devices: WAN accelerators, Load Balancers, and Firewalls.
* Layer 5: Session (Data)
  * Functions: Responsible for setting up, maintaining (transferring data, reestablishing connections, acknowledging receipt), and tearing down sessions.
  * Protocols: H.323, NetBIOS, RTP.
* Layer 6: Presentation (Data)
  * Functions: Data formatting and encryption. Handles scripting languages, standard text, pictures, movie files, and encryption algorithms.
  * Formats & Security: ASCII, GIF, JPG, PNG, and TLS encryption.
 
---
Status: In Progress 
Primary Goal: Mastering enterprise-level network behavior for penetration testing and infrastructure analysis.
