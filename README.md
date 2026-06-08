# Portfolio Project

A full three-tier hierarchical enterprise network built and documented as a hands-on portfolio project, covering the core technologies tested in the Cisco CCNA 200-301 exam.

---

## Video Walkthrough

[Watch the full lab walkthrough on YouTube](https://youtu.be/bfdyJJQUyms)

---

## Project Overview

This lab simulates a realistic enterprise network environment with a Core, Distribution, and Access layer topology. All devices are fully configured and functional in Cisco Packet Tracer.

**Technologies implemented:**

| Category | Technologies |
|---|---|
| Switching | VLANs, Trunk/Access ports, Rapid PVST+, LACP EtherChannel (802.3ad) |
| Redundancy | HSRP (L3 switch SVI-based), STP root bridge alignment |
| Routing | OSPF single-area, inter-VLAN routing via SVIs |
| NAT/DHCP | PAT (overload), DHCP server, DHCP relay (ip helper-address) |
| Security | Extended ACLs, SSH hardening, Port Security, DHCP Snooping, Dynamic ARP Inspection (DAI) |
| Management | DNS, centralized logging |

---

## Repository Structure

- `README.md` — project overview and documentation
- `lab/enterprise-lab.pkt` — Cisco Packet Tracer file
- `configs/` — per-device running configurations
- `docs/lab-documentation.docx` — full 15-page technical documentation

---

## How to Use

1. Download and install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) (free with NetAcad account)
2. Open `lab/enterprise-lab.pkt`
3. Refer to `docs/lab-documentation.docx` for full design decisions, IP addressing, and configuration rationale
