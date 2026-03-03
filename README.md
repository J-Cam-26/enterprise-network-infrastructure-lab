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
Insert your topology screenshot here.
VLAN Structure
VLAN	Department	Subnet
10	HR	10.10.10.0/24
20	IT	10.10.20.0/24
30	Sales	10.10.30.0/24
50	Servers	10.10.50.0/24
Routing
Dynamic routing is implemented using OSPF.
Routers exchange routes between the HQ and branch networks allowing full connectivity across VLANs and locations.
Network Services
The lab includes:
Internal DNS server
Domain name resolution for corp.local
centralized server subnet
Connectivity Testing
Network connectivity was validated using ICMP tests between VLANs and across sites.
Skills Demonstrated
VLAN configuration
trunking
router-on-a-stick
dynamic routing (OSPF)
DNS configuration
ACL security filtering
multi-site enterprise network design
