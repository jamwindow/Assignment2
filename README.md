# Assignment2

This project is a Cisco Packet Tracer simulation of a multi-site network with VLAN segmentation, NAT, and GRE tunnels. It demonstrates the design, configuration, and testing of a scalable, secure, and interconnected enterprise network.

*Network Design
  The network is divided into 3 sites with the following structure:
  
- Main Site (Building A and Building B):
  + 10 VLANs (5 for wired, 5 for wireless)
  + Separate VLANs for different departments, IoT, and guest Wi-Fi
  + Centralized routing and NAT for internet access
  + GRE tunnel for inter-site communication
- Branch Site 1:
  + 6 VLANs (3 for wired, 3 for wireless)
  + Includes isolated VLANs for security and performance
  + NAT for public IP translation
  + GRE tunnel to Main Site and Branch Site 2
- Branch Site 2:
  + 6 VLANs (3 for wired, 3 for wireless)
  + Independent routing with NAT
  + GRE tunnel to Main Site and Branch Site 1

