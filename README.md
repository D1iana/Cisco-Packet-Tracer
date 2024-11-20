Cisco Packet Tracer: Office Network with Subnetting
This repository contains a Cisco Packet Tracer project showcasing a network designed for an office environment. The network is divided into three departments (IT, HR, and Logistics), each operating within its own subnet, with all IP addresses manually configured.

📜 Project Overview
This project simulates a small office network with the following key features:

Three Departments: IT, HR, and Logistics, each assigned to its own subnet.
Manual IP Configuration: All IP addresses are statically assigned to ensure clear network segmentation and management.
DNS Server Integration: A DNS server is included in the IT subnet to provide name resolution for the network.
Static Routing: Inter-subnet communication is facilitated via routers with manually configured routes.
Subnet Details
IT Department (Subnet 1)

Devices: 2 PCs and a DNS server.
IP Range: 192.168.1.0/24
Default Gateway: 192.168.1.1
HR Department (Subnet 2)

Devices: 2 PCs.
IP Range: 192.168.2.0/24
Default Gateway: 192.168.2.1
Logistics Department (Subnet 3)

Devices: 2 PCs.
IP Range: 192.168.3.0/24
Default Gateway: 192.168.3.1

🚀 How to Use
Download the .pkt file from this repository.
Open it in Cisco Packet Tracer.
Use the "Realtime" or "Simulation" modes to observe network traffic.
Explore the routing tables in the routers to see how inter-subnet communication is configured.
Test connectivity by using the ping command between devices in different subnets.

🎯 Key Concepts Demonstrated
Manual IP Addressing: Each device in the network has a statically assigned IP address.
Subnetting: Logical segmentation of the network into three separate subnets.
DNS Integration: A DNS server resolves local domain names within the network.
Static Routing: Routers are manually configured to enable communication between subnets.

