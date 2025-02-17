# Smart City Infrastructure Project

## Overview
This project represents a smart city infrastructure with interconnected components utilizing computer networking principles. The design ensures seamless communication and integration between smart homes, management offices, city headquarters, and other departments.

## Key Features
- **IP Addressing:** Static and dynamic IP allocation.
- **Network Services:**
  - HTTP/HTTPS
  - DHCP (Server & Router-based)
  - DNS Service
  - SMTP (Email Services)
  - FTP Service
  - IoT Services
  - SSH Protocol (Routers & Switches)
- **Routing:**
  - Default Routing
  - OSPF Dynamic Routing
- **Network Segmentation:**
  - VLAN & Inter-VLAN Routing
  - Subnetting
- **Wireless Connectivity:**
  - Wi-Fi-enabled clusters
  - Cell Towers (3G/4G connectivity)
- **Embedded Systems:**
  - MCU-Board integration

## Infrastructure Topology
1. **Smart Homes**
   - Operate independently without external connections.
   - Centralized wireless HomeGateway for IoT device connectivity.
   - Admin-controlled environment for IoT management.

2. **Management Office**
   - Connects to Energy, Parking, and the Internet Service Provider (ISP).
   - Services include HTTP, HTTPS, IoT, DNS, Email, and DHCP.
   - Wired and wireless connections managed via DHCP.

3. **Energy Cluster**
   - Wireless router with SSID: "Energy" for IoT and laptop connections.
   - IoT devices configured via DHCP from the Management Office.
   - Demonstrates power generation and distribution.

4. **Parking Cluster**
   - Wireless router with SSID: "Parking".
   - IoT devices configured via DHCP.
   - Smart parking technology with MCU-board and motion sensor.

5. **Server Site**
   - Part of City Headquarters.
   - Static IP configuration.
   - Hosts DNS, FTP, Email, and DHCP servers.
   - Network: `192.168.102.64/28` (16 hosts available).

6. **City Headquarters**
   - Contains routers and multilayer switches.
   - Hosts multiple departments:
     - IT, Police HQ, Court, Public Relations, Education Ministry, Canteen.
   - Uses VLAN and inter-VLAN routing for communication.
   - DHCP-enabled network.

7. **Other Departments**
   - Connected to City Headquarters and ISP.
   - Departments include Traffic Police, Healthcare, Private Security, and Education.
   - VLAN segmentation and DHCP management.

8. **Internet Service Provider (ISP)**
   - Provides internet connectivity citywide.
   - Redundant routing ensures failover communication.
   - DHCP services configured on routers.
   - Cell towers for mobile device connectivity.

## Network Configurations
- **VLAN Segmentation & Inter-VLAN Routing**
- **Subnetting & IP Address Allocation**
- **OSPF & Default Routing**
- **SSH Configuration on Switches & Routers**
- **DHCP Implementation across Networks**

## Technologies Used
- Networking protocols (IP, OSPF, DHCP, DNS, FTP, SMTP, SSH)
- Embedded Systems (MCU-Board, IoT)
- Wireless Technologies (Wi-Fi, Cellular 3G/4G)
- Security Implementation (SSH, VLAN)

## Conclusion
This project effectively demonstrates a scalable and robust smart city infrastructure by leveraging network technologies for efficient resource management and communication. The integration of IoT, cloud, and embedded systems enhances automation and security across various departments.
