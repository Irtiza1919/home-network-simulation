# 🏠 Home Network Simulation using Cisco Packet Tracer

This project simulates a secure and segmented home network environment using Cisco Packet Tracer. It demonstrates practical networking skills such as device configuration, VLAN implementation, IP addressing, access control, and basic security measures in a virtual lab setup.

---

## 🎯 Objectives

- Design a functional and realistic home network.
- Implement VLANs to isolate traffic between Admin and Guest devices.
- Configure DHCP and NAT for IP management and internet simulation.
- Apply ACLs and port security to restrict unauthorized access.
- Simulate basic cyber attacks (ping flood, port scanning) to validate security.

---

## 🛠️ Tools & Technologies

- **Cisco Packet Tracer** – Network simulation
- **Switch & Router CLI** – Configuration interface
- **Static & Dynamic IPs** – Assigned through DHCP and manual setup
- **Basic Firewall Rules & ACLs** – Enforced at the router level

---

## 🖧 Network Design Summary

**Devices Used:**
- 1 Admin PC (VLAN 10)
- 3 Guest PCs (VLAN 20)
- 1 Printer (VLAN 20)
- 1 Router (with DHCP & NAT)
- 1 Switch
- 1 Server (DNS + File Server on VLAN 10)
- 1 IP Phone (VoIP Simulation, optional)

**Topology:**
- **Star topology** with a central switch
- Devices grouped by VLAN
- Router connects VLANs to simulated internet

**IP Configuration:**
- VLAN 10: `192.168.10.0/24`  
- VLAN 20: `192.168.20.0/24`  
- DHCP pools for both VLANs  
- NAT enabled for external connectivity

---

## 🔐 Security Configurations

- **VLAN Segmentation**: Admin and Guest devices separated
- **Access Control Lists (ACLs)**:
  - Guests restricted from accessing Admin VLAN and Server
  - ICMP traffic blocked between VLANs
  - Port-specific restrictions (e.g., block FTP, allow HTTP/HTTPS)
- **Port Security**: Enabled on switch interfaces to block MAC spoofing
- **MAC Address Filtering**: Applied to allowlist authorized devices

---

## 🧪 Attack Simulation & Testing

Simulated the following scenarios:
- 🔸 **Ping flood** from Guest PC to Admin PC – Blocked via ACLs  
- 🔸 **Port scanning** (Nmap-style simulation) from Guest to Server – Partially blocked and logged  
- 🔸 **Unauthorized access attempts** from Guest to Admin Server – Dropped by ACLs and logged as potential intrusion

---

## 🗺️ Network Topology Diagram
---

## 🚀 How to Run the Simulation

1. Download and install **Cisco Packet Tracer** from [Cisco NetAcad](https://www.netacad.com/).
2. Clone or download this repository.
3. Open                 in Cisco Packet Tracer.
4. Explore CLI configurations on each device (router/switch) to review IPs, VLANs, and ACLs.
5. Use simulation mode to test connectivity and validate security rules.

---

## 📁 Project Files




---

## 📦 Download Links



---

## 💡 Learning Outcomes

- Hands-on experience with VLANs, DHCP, NAT, ACLs, and switch/router configuration.
- Simulated cyber defense techniques against common network attacks.
- Strengthened practical knowledge in network security and architecture.

---

## 📬 Contact

Feel free to connect or reach out if you’d like to discuss this project or collaborate on others!

> ✉️ irtiza1919@gmail.com 
> 🔗 [LinkedIn](https://linkedin.com/in/irtizaur-rahman)  

