# Week 2 Task - IP Addressing (FLSM & VLSM) & VLAN Configuration

Network Administration Internship Program at IT-Simplera Solutions.

**Submitted by:** Hammad Zia 

**Reg No:** NETB01-4259 

**Domain:** Network Administration 

**Date of Submission:** 8th July, 2026 

---

## 📋 Overview
This repository contains the documentation and implementation files for Week 2 of the internship. The project focuses on optimizing IPv4 network addresses using Fixed Length Subnet Masking (FLSM) and Variable Length Subnet Masking (VLSM), alongside implementing Layer 2 traffic isolation using Virtual Local Area Networks (VLANs).

## 📂 Repository Contents
- `Report.pdf` – Full technical report covering calculations, topology configurations, and verification steps.
- `Cisco Packet Tracer.pkt` – Simulation project files featuring the dual-switch VLAN network topology. 
- `GNS3 Project/` – Emulation project environment validating configuration parity.
- `Screenshots/` - Screenshots of both topologies, verification of VLAN's and ping test results

## ⚙️ Core Modules Covered

### 1. Fixed Length Subnet Masking (FLSM)
* Uniform sizing mapped to the largest host requirement across Class C and Class B subnets.
* Mathematical proofs and allocation tables for static IP configurations.

### 2. Variable Length Subnet Masking (VLSM)
* Hierarchical sequential layout (largest to smallest subnets) to minimize address space wastage.
* Production-grade calculations for corporate and academic scenarios.

### 3. VLAN Infrastructure & Trunking Configuration
**VLAN Assignments:** VLAN 10 (STAFF), VLAN 20 (SALES), and VLAN 30 (HR).
**802.1Q Trunking:** Aggregated backbone link enabling intra-VLAN transport across multiple hardware nodes.

## 🛠️ Simulation Platforms Used 
**Cisco Packet Tracer** (CLI Command Configuration).

**GNS3** (UI-driven programmatic state configuration map).

## 🔍 Verification Commands 
`show vlan brief` – Validated access port membership and active status.

`show interfaces trunk` – Verified encapsulation protocol state and allowed trunks.

`ping <destination_ip>` – End-to-end multi-platform confirmation of broadcast loop isolation.
