This project presents a structured Local Area Network (LAN) design and simulation for a driving school, developed using Cisco Packet Tracer. The network architecture is divided into five dedicated subnets to ensure high availability, efficient data flow, and seamless communication across administrative, operational, and student departments.
Additionally, the project integrates IoT (Internet of Things) smart sensors and automated safety mechanisms (smoke detection, automated window operation, and smartphone-based alarm controls) to enhance building security and safety.
Key Features & Network Architecture:
 Subnetting & Addressing: Custom Class C IP addressing scheme (⁠192.168.1.0/24⁠ with subnetting) configured to serve 5 primary functional zones.
 Network Segmentation (5 Departments):
1. Management: Dedicated Switch (2960-24TT), PCs, Network Printer, and IP Phones (⁠7960⁠) with Gateway ⁠192.168.20.1⁠.
2. Core Services / Servers: Centralized HTTP (Web), EMAIL, and dynamic DHCP servers serving the network.
3. Students: Student workstations, laptops, and VoIP communication linked via Cisco 2811 Router.
4. Guests: Isolated guest network access with verified cross-subnet communication tests (Ping tests).
5. Smart Security & IoT: Integrated smoke detectors, automatic smart windows, alarm sprinklers, and authenticated mobile control access.
 Verification: Full connectivity and routing verified via CLI Ping tests across subnets with 0% packet loss.
Tools & Technologies:
 Cisco Packet Tracer
 Networking Protocols: IPv4, Subnetting, Dynamic Host Configuration Protocol (DHCP), HTTP, SMTP/POP3, VoIP.
 Hardware: Cisco 2811 Routers, Cisco 2960 Switches, IoT Smart Sensors, IP Phones.
