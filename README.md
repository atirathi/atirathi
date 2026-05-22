<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=FF0000&width=500&lines=atirathi;Offensive+Security+Engineer;Red+Team+Tooling;Full-Stack+Exploitation" alt="typing animation" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
</p>

---

Building offensive security infrastructure — honeypots, C2 frameworks, CTF platforms, and attack surface intelligence engines. Every project is self-documented with architecture diagrams, deployment playbooks, and solution guides.

---

## Portfolio

### IoT-Honeypot — Multi-Protocol Threat Intelligence Collector
`Python · AsyncIO · Redis · TimescaleDB · Telnet/SSH/HTTP/MQTT`

Production-grade honeypot with fake shells, real-time scoring, alerting, and Grafana analytics. Captures attacker keystrokes, downloads malware samples, and streams events into TimescaleDB for threat intelligence.

- 4 concurrent protocols (Telnet, SSH, HTTP, MQTT)
- Fake shell with 30+ common commands and scoring engine
- Real-time WebSocket dashboard + Grafana panels
- Redis stream event pipeline with TimescaleDB persistence
- SOC alerting via Slack webhooks

[→ github.com/atirathi/iot-honeypot](https://github.com/atirathi/iot-honeypot)

---

### Sarvanga — Attack Surface Intelligence Engine
`Python · 12 modules · AI path generation · 6-layer bypass · 0-day pipeline`

Complete attack surface intelligence engine covering the full kill chain: reconnaissance → graph building → AI path scoring → access → bypass → lateral movement → persistence → exfiltration → OPSEC → deception → AI learning.

- 13 Python tools with async parallel execution, 70+ offensive techniques across 7 domains
- 7 battle plans (AD, Cloud, OT/ICS, WFH, Supply Chain, Startup, Financial)
- 14 documentation pillars with MITRE ATT&CK mapping across all tactics

[→ github.com/atirathi/Sarvanga](https://github.com/atirathi/Sarvanga)

---

### Chakravyuh — CTF Challenge Platform
`JavaScript/Node.js · React 18 · PostgreSQL 16 · Redis 7 · MongoDB 6`

Hard-difficulty Capture The Flag platform with 49 vulnerabilities, 17 real flags, and built-in scoring/anti-cheat.

- 7 Docker services with 8 exploitable VW routes: RCE, SSRF, IDOR, Deserialization, SSTI, LFI, Backdoor, Business Logic
- Multi-cloud Terraform (AWS, Hetzner, Oracle)
- Real-time WebSocket flag submission, Prometheus/Grafana monitoring, Discord bot alerts
- Hardcoded passphrase backdoor, JWT cracking, prototype pollution, race conditions

[→ github.com/atirathi/Chakravyuh](https://github.com/atirathi/Chakravyuh)

---

### C2-Framework — Command & Control
`Python · Go · FastAPI · React · AES-GCM`

Custom C2 framework with encrypted beaconing, multi-platform implant, and web-based operator dashboard.

- Go implant with AES-GCM encrypted C2 channel
- Python FastAPI server with multi-session management
- React dashboard with real-time terminal and file browser
- Docker Compose deployment with PostgreSQL backend
- Modular task framework (shell, upload, download, socks proxy)

[→ github.com/atirathi/C2-Framework](https://github.com/atirathi/C2-Framework)

---

### hirehive-lab — Vulnerable Web Application Lab
`JavaScript · Docker · PostgreSQL`

Vulnerable full-stack recruitment platform for security training and CTF scenario hosting.

[→ github.com/atirathi/hirehive-lab](https://github.com/atirathi/hirehive-lab)

---

### cyber-arsenal — Security Tool Collection
`Python · Go · Bash`

Curated collection of offensive security tools, scripts, and utilities.

[→ github.com/atirathi/cyber-arsenal](https://github.com/atirathi/cyber-arsenal)

---

## Architecture Philosophy

```
Strategic Layer ─── Epic-to-Cyber Mapping (Mahabharata/Ramayana philosophy)
       │
Execution Layer ─── Async Python / Node.js, Docker Compose, Terraform
       │
Data Layer ──────── PostgreSQL, Redis, MongoDB, Prometheus
       │
Presentation ────── React, Grafana, Discord Bots
```

---

## Skills

| Domain | Technologies |
|--------|-------------|
| Offensive Security | Python, Node.js, Go, Rust |
| CTF Engineering | Express, React, Docker |
| C2 Infrastructure | FastAPI, AES-GCM, WebSocket |
| AI/ML for Security | Path scoring, Graph networks |
| Cloud Infrastructure | Terraform (AWS, Hetzner, Oracle) |
| Monitoring & OPSEC | Prometheus, Grafana, Discord Bots |
| Databases | PostgreSQL, MongoDB, Redis, TimescaleDB |
| Frontend | React 18, TypeScript, Nginx |

---

## Roadmap

- [ ] Community CTF events on Chakravyuh
- [ ] Sarvanga + Chakravyuh integration for real-world testing
- [ ] CI/CD pipelines for all repos
- [ ] Docker Hub images for honeypot and C2 services
- [ ] Public release of select tools

---

<p align="center">
  <img src="https://img.shields.io/badge/Offensive%20Security-FF0000?style=for-the-badge&logo=appveyor&logoColor=white" />
  <img src="https://img.shields.io/badge/Red%20Team-CC0000?style=for-the-badge&logo=appveyor&logoColor=white" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-990000?style=for-the-badge&logo=appveyor&logoColor=white" />
  <img src="https://img.shields.io/badge/Threat%20Intelligence-660000?style=for-the-badge&logo=appveyor&logoColor=white" />
</p>
