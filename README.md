Network Scanning & Information Gathering

Project Overview

This project demonstrates network scanning and information gathering using Kali Linux and Nmap in an authorized virtual lab environment.

The objective was to discover live hosts, identify open ports, detect running services and versions, perform OS detection, and use Nmap Scripting Engine (NSE) for additional information gathering.

Objectives

- Discover live hosts on a network
- Identify open ports
- Detect running services and versions
- Perform operating system detection
- Use Nmap Scripting Engine (NSE)
- Analyze and document scanning results

Lab Environment

| Component | Details |
|---|---|
| Scanner | Kali Linux |
| Target | Windows VM |
| Tool | Nmap |
| Virtualization | VMware Fusion |
| Environment | Authorized Virtual Lab |

Lab Topology


             VMware Fusion
                  │
          Virtual Lab Network
                  │
        ┌─────────┴─────────┐
        │                   │
   Kali Linux          Windows VM
     Scanner              Target
        │                   │
        └────── Nmap ───────┘
