Packet Tracer Networks
----------------------

This repository contains 2 files, each being a packet tracer file containing a network set up according to a corresponding specification sheet. 

Multi-area OSPF and VTP Network file contains a network built based on topology in the specification and features 5 different areas (4 OSPF, 1 Static routing) and 2 VTP domains. Each area (except for static and central routing area) has VLANs set up and route on a stick is set up in top area. Basic security was implemented here - primarily plaintext passwords.

Secured and Managed Network file contains a network (already connected previously) where ACLs are set up on routers to provide access for certain packets to pass through depending on the origin, and deny (i.e. drop) the rest. OSPF is also set up in this network. Encrypted passwords were set and unused ports were disabled. Ports on switches that are used have sticky MAC address enabled, so that a different unauthorised device couldn't connect to the network. All network devices send logs to a server using Syslog. Management PC can manage network devices using SNMP. 
