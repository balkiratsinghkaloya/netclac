# netclac
A browser-based networking utility covering IPv4 subnetting, VLSM planning, ICMP ping/traceroute simulation, and port reference. Built to apply networking concepts learned in coursework.
# NetCalc — Network Subnet Calculator & Planner

A browser-based networking utility I built to apply and strengthen my understanding
of IP addressing, subnetting, and network protocols.

## Live Demo
https://balkiratsinghkaloya.github.io/netcalc/

## Features

**Subnet Calculator**
- Enter any IPv4 address and CIDR prefix
- Calculates network address, broadcast, subnet mask, wildcard mask, host range
- Shows full binary representation with network/host bits highlighted
- Identifies IP class (A/B/C/D/E) and private/public type

**VLSM Planner**
- Add multiple subnets with different host requirements
- Allocates addresses using Variable Length Subnet Masking (largest subnet first)
- Generates complete allocation table with network, broadcast, and host ranges

**Ping / Traceroute Simulator**
- Simulates ICMP Echo Request/Reply with RTT, TTL, and packet loss
- Traceroute shows hop-by-hop path with latency
- Covers ICMP Type 8 (Echo Request) and Type 0 (Echo Reply) — RFC 792

**Port Reference**
- 35+ well-known TCP/UDP ports with OSI layer and risk classification
- Searchable and filterable by protocol type and risk level

## Concepts Covered
- IPv4 addressing and binary conversion
- CIDR (Classless Inter-Domain Routing)
- Subnet masking, wildcard masks, network/broadcast address calculation
- Variable Length Subnet Masking (VLSM)
- ICMP protocol, TTL, Round-Trip Time (RTT)
- TCP/UDP well-known ports and their security implications

## Tech Stack
- HTML5, CSS3, Vanilla JavaScript
- No external libraries or frameworks
- All subnet math done using JavaScript bitwise operators (`>>>`, `&`, `|`, `~`)

## How to Run
Download `index.html` and open it in any browser. No installation needed.

## Author
Balkirat Singh
B.Tech  — Computer Science .
[LinkedIn](https://linkedin.com/in/balkiratsingh) | [GitHub](https://github.com/balkiratsinghkaloya)
