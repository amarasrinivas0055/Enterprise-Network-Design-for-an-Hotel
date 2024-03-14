Enterprise Network Design for Hotel
===================================

Overview :
---------
The enterprise network for the hotel is designed to provide efficient communication and management across its three floors. With a focus on scalability, security, and seamless interdepartmental collaboration, the network architecture optimizes performance and productivity for all hotel operations.

Floor-wise Departments :
------------------------

First Floor :-
--------------

Reception: VLAN 80, Network of 192.168.8.0/24

Store: VLAN 70, Network of 192.168.7.0/24

Logistics: VLAN 60, Network of 192.168.6.0/24

Second Floor :-
---------------

Finance: VLAN 50, Network of 192.168.5.0/24

HR: VLAN 40, Network of 192.168.4.0/24

Sales/Marketing: VLAN 30, Network of 192.168.3.0/24

Third Floor :-
--------------

Admin: VLAN 20, Network of 192.168.2.0/24

IT: VLAN 10, Network of 192.168.1.0/24

Network Infrastructure :-
-------------------------
Each floor is equipped with a switch and a router to ensure seamless connectivity and routing capabilities. Key network features include:

VLAN Segmentation:-
------------------
Utilized separate VLANs for each department to enhance network security and manageability.

Inter-VLAN Routing:-
-------------------
Implemented router-on-a-stick protocol for inter-VLAN communication, enabling efficient data exchange between departments.

Dynamic IP Assignment:-
----------------------
Configured DHCP protocol in each router to dynamically assign IP addresses to end devices, ensuring hassle-free network connectivity.

Routing Protocol:-
-----------------
Deployed OSPF for dynamic routing, facilitating efficient data exchange and fault tolerance.

Security Measures:-
------------------
Implemented port security for the IT department to restrict unauthorized access and enhance network security.

Remote Access:-
--------------
Enabled SSH configuration for remote login to network devices, ensuring secure management and monitoring.

Conclusion :-
------------
The enterprise network design for the hotel reflects a commitment to efficiency, security, and scalability. By leveraging advanced networking technologies and best practices, the hotel can optimize its operations, enhance guest experiences, and stay competitive in the hospitality industry.



