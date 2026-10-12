# Roberto Alejandro Morales Pérez (`SavianAlexander`)

### Sovereign Systems Architect · Distributed Rust Engineer · Fiduciary Technologist

[![Cluster Health](https://img.shields.io/badge/Proxmox%20Fleet-22%20LXC%20Workloads%20%7C%20100%25%20Operational-brightgreen.svg)](https://github.com/SavianAlexander/proxmox-fleet)
[![Systems Standard](https://img.shields.io/badge/architecture-100%25%20Sovereign%20Rust%20First-orange.svg)](#core-engineering-invariants)
[![Database Engines](https://img.shields.io/badge/databases-PostgreSQL%2016%20%7C%20SQLite%20WAL-blue.svg)](#sovereign-production-cluster-registry)
[![Fiduciary Compliance](https://img.shields.io/badge/compliance-2%20CFR%20200%20%7C%20Act%2060%20%7C%20WIOA%20%7C%20WOTC-emerald.svg)](#fiduciary--statutory-engines)
[![Ingress Gateway](https://img.shields.io/badge/ingress-Caddy%202.8%20%7C%20HTTP%2F3%20QUIC-blueviolet.svg)](https://github.com/SavianAlexander/proxmox-fleet)

Architect and builder of the **Sovereign Autonomous Holding Suite** and **Proxmox VE 9.2 Production Microservice Cluster**. Specializing in bare-metal systems engineering, memory-efficient low-latency architectures in **Rust** (Axum 0.7, Tokio, mimalloc, zero-alloc SIMD), and institutional compliance platforms across federal and Puerto Rico statutory frameworks.

---

## 🏛️ Core Engineering Invariants

* **Sovereign Rust-First Architecture:** Core daemons, background watchdogs, CLI tools, MCP servers, and data pipelines are engineered exclusively in native Rust (`mimalloc`, LLD fast-linking, branchless SIMD).
* **Zero-Mock Institutional Law:** Every UI action connects to a live Axum or native route; every route connects to typed PostgreSQL 16 or SQLite WAL repositories. Zero facade apps, zero dummy alerts.
* **Proxmox Cluster Priority ("Design Here, Compute Over There"):** Workstations serve as dedicated CAD shops; all persistent databases, vector search indexes, and warm services execute across 24/7 Proxmox VE nodes (`192.168.1.46` / `192.168.1.210`).
* **Closed-Loop Knowledge Grounding:** All agents and developer workflows ground before acting against the sovereign knowledge vault (95,000+ chunks, AST graph, ColBERT MaxSim reranking).

---

## 🚀 Sovereign Production Cluster Registry

Authoritative inventory of active autonomous microservices across the Proxmox cluster:

| Ecosystem / Project | Repository | Node / Container | Ports & Domains | Primary Stack & Authority |
| :--- | :--- | :---: | :--- | :--- |
| **Cluster Ingress & IaC** | [`proxmox-fleet`](https://github.com/SavianAlexander/proxmox-fleet) | Node Alpha | `80`, `443`, `*.lan` | Caddy 2.8 Reverse Proxy (HTTP/3 QUIC), IaC blueprints, 23-service registry |
| **Neuro Alexander** | [`uroboros-knowledge-engine`](https://github.com/SavianAlexander/uroboros-knowledge-engine) | CT 109 | `neuro.lan:8000`<br/>PG: `5433`, Voice: `8880` | Sovereign Tri-Engine RAG, 95k+ chunk vault, Kokoro-82M neural TTS, 62 dispatch tools |
| **EVE WALL / EORO** | [`eve-wall`](https://github.com/SavianAlexander/eve-wall) | CT 108 | `eve.lan:8080`<br/>PG: `5438` | Tactical Intelligence Engine, 150+ Maud domain views, Dogma simulator, 173 MCP tools |
| **Cloud PR Fiduciary** | [`cloud-pr`](https://github.com/SavianAlexander/cloud-pr) | CT 100 | `cloud_pr.lan:8087`<br/>PG: `5432` | 2 CFR 200 Uniform Guidance, WIOA OJT, DDEC FIE Ley 60, WOTC § 51, AES-256 Vault |
| **Task Master (Tududi)**| [`task-master`](https://github.com/SavianAlexander/task-master) | CT 107 | `taskmaster.lan:3002`<br/>Port `3000` | Sovereign Sprint Store, 6,102+ active tasks, TududiSyncActor multi-agent lease locks |
| **Vantage PR Payroll** | [`vantage-pr-payroll`](https://github.com/SavianAlexander/vantage-pr-payroll) | CT 111 | `payroll.lan:5000`<br/>PG: `5435` | Puerto Rico Statutory Payroll, Rust 4-crate workspace, SURI/DTRH returns, NACHA ACH |
| **HR PR Compliance** | [`hr_analytics_app`](https://github.com/SavianAlexander/hr_analytics_app) | CT 112 | `hr.lan:5005`<br/>PG: `5436` | Monaco HR Analytics (15 metrics), Ley 4 leave accruals, Ley 148 bonus, Form 499 R-4.1 |
| **Vantage PR Civic** | [`vantage-pr-compliance`](https://github.com/SavianAlexander/vantage-pr-compliance) | CT 113 | `vantage.lan:5007`<br/>PG: `5437` | Sovereign Civic & Procurement OS, Law 42 preference scoring, Rust C-ABI engine |
| **BorinquenPass PRO** | [`borinquen-pass`](https://github.com/SavianAlexander/borinquen-pass) | CT 114 | `borinquen.lan:3003` | Puerto Rico Act 60 Platform, 14 statutory engines, IRS LB&I shield, WGS-84 GIS |
| **Vocal Media Archiver**| [`vocal-media-archiver`](https://github.com/SavianAlexander/vocal-media-archiver) | CT 119 | `vocal.lan:8085`<br/>Port `3009` | Sovereign Rust 4-crate workspace, 64-bit DSP mastering, OpenSubsonic v1.16.1 |
| **MERCATUS Commercial** | [`mercatus`](https://github.com/SavianAlexander/mercatus) | CT 110 | `marketing.lan:8090`<br/>PG: `5434` | Direct-Response Commercial OS, Multi-Tenant Core, 12-channel distribution stacks |
| **Periodic Table App** | [`periodic-table-app`](https://github.com/SavianAlexander/periodic-table-app) | CT 115 | `periodic_table.lan:3005` | Academic Chemistry Reference, WebGL 3D Bohr visualizer, 118 chemical elements |
| **Architecture System** | [`programming-architecture`](https://github.com/SavianAlexander/programming-architecture) | Workstation | CLI Toolchain | Universal Programming Architecture Scaffolding Framework (STD-SOV-031 / STD-SOV-033) |
| **Scalability Handbook**| [`scalability-expert`](https://github.com/SavianAlexander/scalability-expert) | Knowledge | 22 Skill Modules | Enterprise Systems Scalability & High-Throughput Engineering Handbook |
| **Executive Portfolio** | [`Portafolio`](https://github.com/SavianAlexander/Portafolio) | SPA Portal | Web / Mobile | Bilingual Career Intelligence Single-Page Application with CareerChat AI Assistant |
| **Ponytail Pragmatism** | [`ponytail`](https://github.com/SavianAlexander/ponytail) | Skill Engine | Agentic | Ruthless Occam compression & minimalist code optimization agent |

---

## 🛠️ Specialized Architectural Domains

### 1. Fiduciary & Statutory Engines
* **Federal Uniform Guidance (2 CFR 200)**: Electronic compliance, allowable cost principles (§ 200.400), single audit workpapers, and federal procurement standards (§ 200.317–327).
* **Puerto Rico Act 60-2019 (Ley 60)**: Bona fide resident investor compliance (IRC § 937), statutory donation allocations, and IRS LB&I campaign audit shields.
* **Workforce & Employment Subsidies**: Automated WIOA Title I OJT reimbursement solvers and DDEC FIE job creation reconcilers.

### 2. High-Throughput Systems & Audio DSP
* **64-Bit Studio DSP Mastering**: Bauer binaural headphone crossfeed, ISO 10-band biquad filters, TPDF dither, and -1.0 dBFS True-Peak limiters.
* **Low-Latency Vector Search**: 1-bit binary ColBERT MaxSim reranking, Matryoshka dimension reductions, and SQLite memory-mapped BLOB fast-paths.

---

## 📬 Contact & Coordination

* **GitHub**: [@SavianAlexander](https://github.com/SavianAlexander)
* **Secure Email**: `tinthalexander@proton.me`
* **Cluster Portal**: `http://cloudpr.lan` (Local Mesh)
