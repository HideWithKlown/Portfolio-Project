# Portfolio Project

CCNA Enterprise Network Lab
A full three-tier hierarchical enterprise network built and documented as a hands-on portfolio project, covering the core technologies tested in the Cisco CCNA 200-301 exam.

Video Walkthrough
Watch the full lab walkthrough on YouTube - https://youtu.be/bfdyJJQUyms

Project Overview
This lab simulates a realistic enterprise network environment with a Core, Distribution, and Access layer topology. All devices are fully configured and functional in Cisco Packet Tracer.
Technologies implemented:
CategoryTechnologiesSwitchingVLANs, Trunk/Access ports, Rapid PVST+, LACP EtherChannel (802.3ad)RedundancyHSRP (L3 switch SVI-based), STP root bridge alignmentRoutingOSPF single-area, inter-VLAN routing via SVIsNAT/DHCPPAT (overload), DHCP server, DHCP relay (ip helper-address)SecurityExtended ACLs, SSH hardening, Port Security, DHCP Snooping, Dynamic ARP Inspection (DAI)ManagementNTP, DNS, centralized logging

Repository Structure
ccna-enterprise-lab/
├── README.md
├── lab/
│   └── enterprise-lab.pkt        # Cisco Packet Tracer file
├── configs/
│   └── *.txt                     # Per-device running configs
├── diagrams/
│   └── topology.png              # Network topology diagram
└── docs/
    └── lab-documentation.docx    # Full 15-page technical documentation

How to Use

Download and install Cisco Packet Tracer (free with NetAcad account)
Open lab/enterprise-lab.pkt
Refer to docs/lab-documentation.docx for full design decisions, IP addressing, and configuration rationale
