# Learn-SecByte-CTF-Labs-Collection-BGP-OSPF-EIGRP-ACLs-Layer-2-Security
A curated collection of hands-on cybersecurity CTF labs covering BGP Route Control &amp; Hijack Defense, OSPF/EIGRP/RIP Routing, ACLs, Quality of Service (QoS), STP/RSTP Security, LACP Link Aggregation, and Port Security from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a dedicated, searchable index of hands-on router architecture, static and dynamic routing protocols (BGP, OSPF, EIGRP, RIP), BGP hijack defense, Access Control List (ACL) engineering, Quality of Service (QoS) traffic prioritization, and Layer 2 switching security (STP/RSTP, LACP, Port Security) labs designed for cybersecurity students, CTF players, network security engineers, SOC analysts, and enterprise network architects.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Establishing secure, resilient, and high-performance network backbones requires deep technical mastery over core routing protocols, Layer 2 switching defenses, and policy enforcement mechanisms. Hosted on [Learn SecByte](https://learn.secbyte.org/), this advanced routing, switching, and traffic control collection provides practical, hands-on technical training to configure, audit, and defend enterprise network infrastructures.

From verifying packet forwarding mechanics and constructing complex static and dynamic routing topologies (RIP, OSPF, EIGRP) to securing BGP Autonomous System (AS) path control against route hijacking, engineering granular extended Access Control Lists (ACLs), tuning Quality of Service (QoS) queues under saturation, and enforcing Layer 2 switchport defenses (Port Security, BPDU Guard, Root Guard, and LACP link aggregation), these exercises establish complete network infrastructure security capabilities.

---

## Lab Collection & Index

Below is the complete, searchable index of all router operations, static/dynamic routing, BGP hijack defense, ACL policy engineering, QoS management, and Layer 2 switching security challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Router Fundamentals: From Packet Forwarding to Secure Segmentation** | Router Operations, Static & Dynamic Routing | Control vs. data plane architecture, FIB/RIB table lookups, ARP processing, inter-VLAN routing, interface security | [Access Lab](https://learn.secbyte.org/ctf/router-fundamentals-from-packet-forwarding-to-secure-segment) |
| 2 | **Static Routing Fundamentals: Build, Verify, and Troubleshoot** | Router Operations, Static & Dynamic Routing | Next-hop vs. exit-interface routes, floating static routes, route summarization, recursive lookups, routing loop triage | [Access Lab](https://learn.secbyte.org/ctf/static-routing-fundamentals-build-verify-and-troubleshoot-ro) |
| 3 | **Dynamic Routing with RIP: Routing Tables Under Pressure** | Router Operations, Static & Dynamic Routing | Distance-vector mechanics, split horizon, poison reverse, holddown timers, metric infinity limits (15 hops), table convergence | [Access Lab](https://learn.secbyte.org/ctf/dynamic-routing-with-rip-routing-tables-under-pressure) |
| 4 | **Dynamic Routing with OSPF: From Neighbor Discovery to Route Metric** | Router Operations, Static & Dynamic Routing | Link-state advertisement (LSA) types, SPF algorithm, multi-area OSPF design, hello/dead interval tuning, MD5 authentication | [Access Lab](https://learn.secbyte.org/ctf/dynamic-routing-with-ospf-from-neighbor-discovery-to-route-m) |
| 5 | **Dynamic Routing with EIGRP: From Routing Theory to Lab Verification** | Router Operations, Static & Dynamic Routing | Advanced distance-vector mechanics, DUAL algorithm, successor/feasible successor calculation, K-value metrics, MD5 auth | [Access Lab](https://learn.secbyte.org/ctf/dynamic-routing-with-eigrp-from-routing-theory-to-lab-verifi) |
| 6 | **BGP Fundamentals: Routing Trust, Route Control, and Hijack Defense** | BGP Security, Route Control & Hijacking | Path-vector mechanics, eBGP/iBGP peering, AS path prepending, prefix filtering, RPKI validation, BGP hijack mitigation | [Access Lab](https://learn.secbyte.org/ctf/bgp-fundamentals-routing-trust-route-control-and-hijack-defe) |
| 7 | **Mastering Access Control Lists (ACLs)** | ACL Policy Engineering & QoS Control | Standard vs. Extended ACLs, wildcard mask calculations, reflexive ACLs, object groups, order-of-precedence validation | [Access Lab](https://learn.secbyte.org/ctf/mastering-access-control-lists-acls) |
| 8 | **QoS Under Pressure: Prioritizing Traffic in a Busy Network** | ACL Policy Engineering & QoS Control | Differentiated Services (DiffServ), DSCP/CoS marking, LLQ/CBWFQ queuing, police vs. shape mechanisms, congestion avoidance | [Access Lab](https://learn.secbyte.org/ctf/qos-under-pressure-prioritizing-traffic-in-a-busy-network) |
| 9 | **Spanning Tree Protocol (STP): Loop-Free Switching and Defense** | Layer 2 Switching Security & Link Aggregation | 802.1D bridge election, Root Bridge manipulation, port state transitions, BPDU Guard, Root Guard, Loop Guard | [Access Lab](https://learn.secbyte.org/ctf/spanning-tree-protocol-stp-loop-free-switching-and-defense) |
| 10 | **Rapid Spanning Tree Protocol (RSTP) Security Lab** | Layer 2 Switching Security & Link Aggregation | 802.1w convergence optimization, alternate/backup port roles, proposal/agreement handshakes, RSTP BPDU attacks | [Access Lab](https://learn.secbyte.org/ctf/rapid-spanning-tree-protocol-rstp-security-lab) |
| 11 | **LACP Link Aggregation for Defense and Offense** | Layer 2 Switching Security & Link Aggregation | 802.3ad/802.1AX EtherChannel bundling, active/passive negotiation, load-balancing algorithms, LACP spoofing/misconfiguration | [Access Lab](https://learn.secbyte.org/ctf/lacp-link-aggregation-for-defense-and-offense) |
| 12 | **Port Security Configuration** | Layer 2 Switching Security & Link Aggregation | Dynamic vs. static vs. sticky MAC learning, violation modes (protect/restrict/shutdown), errdisable recovery, MAC aging | [Access Lab](https://learn.secbyte.org/ctf/port-security-configuration) |

---

## Categories

### 1. Router Operations, Static & Dynamic Routing (RIP, OSPF, EIGRP)
Audit control plane mechanics, construct floating static routes, analyze RIP distance-vector convergence, and configure secure multi-area OSPF and EIGRP routing topologies.
- [Router Fundamentals: From Packet Forwarding to Secure Segmentation](https://learn.secbyte.org/ctf/router-fundamentals-from-packet-forwarding-to-secure-segment)
- [Static Routing Fundamentals: Build, Verify, and Troubleshoot](https://learn.secbyte.org/ctf/static-routing-fundamentals-build-verify-and-troubleshoot-ro)
- [Dynamic Routing with RIP: Routing Tables Under Pressure](https://learn.secbyte.org/ctf/dynamic-routing-with-rip-routing-tables-under-pressure)
- [Dynamic Routing with OSPF: From Neighbor Discovery to Route Metric](https://learn.secbyte.org/ctf/dynamic-routing-with-ospf-from-neighbor-discovery-to-route-m)
- [Dynamic Routing with EIGRP: From Routing Theory to Lab Verification](https://learn.secbyte.org/ctf/dynamic-routing-with-eigrp-from-routing-theory-to-lab-verifi)

### 2. BGP Security, Route Control & Hijack Defense
Understand Autonomous System path vector propagation, apply eBGP/iBGP route filtering policies, enforce RPKI origin validation, and mitigate BGP route hijacking.
- [BGP Fundamentals: Routing Trust, Route Control, and Hijack Defense](https://learn.secbyte.org/ctf/bgp-fundamentals-routing-trust-route-control-and-hijack-defe)

### 3. ACL Policy Engineering & QoS Traffic Control
Calculate wildcard masks, configure standard/extended/reflexive ACLs, enforce traffic shaping/policing, and prioritize high-priority traffic queues using DiffServ QoS.
- [Mastering Access Control Lists (ACLs)](https://learn.secbyte.org/ctf/mastering-access-control-lists-acls)
- [QoS Under Pressure: Prioritizing Traffic in a Busy Network](https://learn.secbyte.org/ctf/qos-under-pressure-prioritizing-traffic-in-a-busy-network)

### 4. Layer 2 Switching Security, STP/RSTP & Link Aggregation
Harden Ethernet switchports using Port Security, secure Spanning Tree Protocol (STP/RSTP) root election topologies with BPDU/Root Guard, and configure LACP EtherChannels.
- [Spanning Tree Protocol (STP): Loop-Free Switching and Defense](https://learn.secbyte.org/ctf/spanning-tree-protocol-stp-loop-free-switching-and-defense)
- [Rapid Spanning Tree Protocol (RSTP) Security Lab](https://learn.secbyte.org/ctf/rapid-spanning-tree-protocol-rstp-security-lab)
- [LACP Link Aggregation for Defense and Offense](https://learn.secbyte.org/ctf/lacp-link-aggregation-for-defense-and-offense)
- [Port Security Configuration](https://learn.secbyte.org/ctf/port-security-configuration)

---

## Learning Path

Follow this structured progression path to master router packet forwarding, dynamic routing protocols, BGP security, ACL policy design, and Layer 2 switchport hardening:

1. **Phase 1: Router Fundamentals & Static/Dynamic Routing (RIP, OSPF, EIGRP)** — Master FIB/RIB routing table lookups and configure IGP dynamic routing:
   - [Router Fundamentals: From Packet Forwarding to Secure Segmentation](https://learn.secbyte.org/ctf/router-fundamentals-from-packet-forwarding-to-secure-segment)
   - [Static Routing Fundamentals: Build, Verify, and Troubleshoot](https://learn.secbyte.org/ctf/static-routing-fundamentals-build-verify-and-troubleshoot-ro)
   - [Dynamic Routing with RIP: Routing Tables Under Pressure](https://learn.secbyte.org/ctf/dynamic-routing-with-rip-routing-tables-under-pressure)
   - [Dynamic Routing with OSPF: From Neighbor Discovery to Route Metric](https://learn.secbyte.org/ctf/dynamic-routing-with-ospf-from-neighbor-discovery-to-route-m)
   - [Dynamic Routing with EIGRP: From Routing Theory to Lab Verification](https://learn.secbyte.org/ctf/dynamic-routing-with-eigrp-from-routing-theory-to-lab-verifi)

2. **Phase 2: BGP Security & Route Hijack Mitigation** — Master Internet path-vector routing, control AS path attributes, and implement RPKI prefix validation:
   - [BGP Fundamentals: Routing Trust, Route Control, and Hijack Defense](https://learn.secbyte.org/ctf/bgp-fundamentals-routing-trust-route-control-and-hijack-defe)

3. **Phase 3: ACL Policy Engineering & QoS Traffic Prioritization** — Filter network traffic using extended ACLs and enforce DSCP QoS queue management under load:
   - [Mastering Access Control Lists (ACLs)](https://learn.secbyte.org/ctf/mastering-access-control-lists-acls)
   - [QoS Under Pressure: Prioritizing Traffic in a Busy Network](https://learn.secbyte.org/ctf/qos-under-pressure-prioritizing-traffic-in-a-busy-network)

4. **Phase 4: Layer 2 Switch Hardening, STP/RSTP Security & LACP** — Enforce switchport MAC limits, secure Spanning Tree topologies, and audit LACP link bundles:
   - [Spanning Tree Protocol (STP): Loop-Free Switching and Defense](https://learn.secbyte.org/ctf/spanning-tree-protocol-stp-loop-free-switching-and-defense)
   - [Rapid Spanning Tree Protocol (RSTP) Security Lab](https://learn.secbyte.org/ctf/rapid-spanning-tree-protocol-rstp-security-lab)
   - [LACP Link Aggregation for Defense and Offense](https://learn.secbyte.org/ctf/lacp-link-aggregation-for-defense-and-offense)
   - [Port Security Configuration](https://learn.secbyte.org/ctf/port-security-configuration)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario directives, network topology maps, and target requirements on [Learn SecByte](https://learn.secbyte.org/).
3. Deploy emulation toolsets (Cisco IOS/VyOS CLI, FRRouting, GNS3/EVE-NG, Scapy, Wireshark, iPerf3) inside an isolated workstation.
4. Configure routing protocols, mitigate BGP hijacks, enforce extended ACL rules, tune QoS policing/shaping parameters, harden switchports, and capture target flags.

---

## Disclaimer

This repository and its linked challenge resources are strictly intended for educational, threat research, and authorized technical security training purposes. Never execute unauthorized BGP route leaks, BPDU frame spoofing, or packet manipulation attacks against production transit networks, service provider backbones, or enterprise cloud infrastructure.
