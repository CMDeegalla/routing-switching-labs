# Routing & Switching Labs

Hands-on routing and switching configurations demonstrating practical
network setup and troubleshooting skills.

## Topics Covered
- VLAN Configuration
- Inter-VLAN Routing
- Static Routing
- OSPF
- Network Design

## Tools
- Cisco Packet Tracer
- Linux CLI

## 🧠 Skills Demonstrated
- VLAN configuration and segmentation
- Static routing and OSPF (single area)
- Cisco router and switch configuration
- Network topology design and verification

  ## ✅ Lab Verification
The following commands were used to verify correct operation:

- `show ip route`
- `show ip ospf neighbor`
- `show vlan brief`
- `ping` and `tracert` between end devices


## 📥 Cisco Packet Tracer Lab Downloads

The following Packet Tracer lab files demonstrate hands-on experience with
routing, switching, and firewall configuration. All files are available for
download and verification.

🔹 **Basic ASA Firewall Configuration**  
[⬇️ Download Packet Tracer File](https://github.com/CMDeegalla/routing-switching-labs/raw/main/packet-tracer/C.M.Deegalla_34169_BasicASA.pkt)

🔹 **Cisco Routing & Switching Lab**  
[⬇️ Download Packet Tracer File](https://github.com/CMDeegalla/routing-switching-labs/raw/main/packet-tracer/cisco.pkt)

📁 **View All Packet Tracer Labs**  
👉 https://github.com/CMDeegalla/routing-switching-labs/tree/main/packet-tracer

---

## Quick Diagram: Routing Topology

```mermaid
flowchart LR
PC1["PC1"] --- SW1["Switch"] --- R1["Router 1"]
R1 --- R2["Router 2"] --- R3["Router 3"] --- SW2["Switch"] --- PC2["PC2"]

