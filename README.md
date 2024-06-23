# campus-network-topology
![campus network topology](https://github.com/ThomasShikalepo/campus-network-topology/assets/137569260/71147f61-0bd4-4a8b-853d-27423863f3f3)
Coursework Brief
Namibia University of Science and Technology

The Namibia University of Science and Technology (NUST) is a large institution with two campuses situated 20 miles apart. The university’s students and staff are distributed across four faculties: Health and Science, Business, Engineering/Computing, and Art/Design. Each staff member has a PC, and students have access to PCs in the labs.

Requirements
Network Topology
Create a network topology with the main components to support the following:

Main Campus

Building A: Administrative staff in the departments of Management, HR, and Finance. The admin staff PCs are distributed in the building offices, and it is expected that they will share the same network equipment (Hint: use of VLAN is expected here). The Faculty of Business is also situated in this building.
Building B: Faculty of Engineering and Computer Science, Art and Design.
Building C: Student labs and the IT department, which hosts the university web servers.
An email server is hosted externally on the cloud.

Smaller Campus

Faculty of Health and Science (staff and students on separate floors).
Configuration Requirements
Configure the core devices and a few end devices to provide end-to-end connectivity and access to internal services and external servers.

Each department/faculty should be on its own separate IP network.
Switches should be configured with appropriate VLANs and security settings.
RIPV2 will be used to provide routing in the internal network and static routing for the external server.
Devices in Building A will be expected to acquire dynamic IP addresses from the router-based DHCP server.
Tasks
Plan, design, and prototype the network topology for the NUST network using Cisco Packet Tracer.
Configure the network in Packet Tracer with appropriate settings to achieve the connectivity and functionalities specified in the requirements.
Project Overview
This project outlines a comprehensive network design for an IT company with two branches, leveraging RIP routing and VLANs for efficient communication and network management. The simulation is implemented using Cisco Packet Tracer.

Features
RIP Routing: Utilizing RIP for dynamic routing to ensure efficient and adaptive routing between devices within the network.
VLAN Implementation: Segmentation of the network into VLANs to enhance security, optimize traffic flow, and simplify network management.
Inter-VLAN Routing: Implementation of routing between VLANs to facilitate communication between different segments of the network.
Network Topology
Main Campus Configuration
Router 1 (R1): RIP routing configuration, VLAN configuration, and inter-VLAN routing.
Layer 3 Switches: VLAN assignment for various departments (e.g., Administration, Development, and Sales).
Branch 2 Configuration
Router 2 (R2): RIP routing configuration, VLAN configuration, and inter-VLAN routing.
Switches: VLAN assignment for various departments.
How to Use
Open in Cisco Packet Tracer:
Open the project file (it-company-network-design.pkt) in Cisco Packet Tracer.
Explore and Simulate:
Navigate through the network topology in Cisco Packet Tracer.
Simulate different scenarios to observe the behavior of RIP routing and VLAN segmentation.
