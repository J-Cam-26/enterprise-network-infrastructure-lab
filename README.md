Enterprise Network Infrastructure Lab


Overview


This project simulates an enterprise network with a headquarters and branch office connected through dynamic routing. The environment demonstrates network segmentation, inter-VLAN routing, and internal network services.
Network Architecture


The lab environment includes:


Cisco 1941 routers

Cisco 2960 switches

VLAN segmentation for departments

Inter-VLAN routing using router-on-a-stick

OSPF dynamic routing between HQ and Branch

DNS server for internal domain resolution

DMZ network for shared services


Network Topology

<img width="947" height="496" alt="Network_Topology" src="https://github.com/user-attachments/assets/a3e5babc-d9f3-4f3e-a7fa-3e83c082512e" />


VLAN Structure





<img width="701" height="698" alt="vlan-config" src="https://github.com/user-attachments/assets/f7f929eb-5b26-45f5-bc80-4275f0c4f04f" />

VLAN	Department	Subnet

10	HR	10.10.10.0/24

20	IT	10.10.20.0/24

30	Sales	10.10.30.0/24

50	Servers	10.10.50.0/24


Routing


Dynamic routing is implemented using OSPF.


<img width="701" height="698" alt="ospf-neighbors" src="https://github.com/user-attachments/assets/418ed5bf-3633-43ad-931e-51448ebbf8a5" />



Routers exchange routes between the HQ and branch networks allowing full connectivity across VLANs and locations.


<img width="701" height="698" alt="routing-table" src="https://github.com/user-attachments/assets/98518665-5269-4637-a3ed-0e10c7792949" />



Network Services



The lab includes:

Internal DNS server

Domain name resolution for corp.local

centralized server subnet




Connectivity Testing

Network connectivity was validated using ICMP tests between VLANs and across sites.


<img width="701" height="698" alt="network-connectivity" src="https://github.com/user-attachments/assets/e2c4d2c2-507b-4dff-b231-4c61061caa35" />


Skills Demonstrated
VLAN configuration
trunking
router-on-a-stick
dynamic routing (OSPF)
DNS configuration
ACL security filtering
multi-site enterprise network design
