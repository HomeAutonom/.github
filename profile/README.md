<div align="center">

# 🏠 HomeAutonom

**Smart Home Automation · IoT · Network Infrastructure**

*Home automation org for [iAiFy](https://github.com/enterprises/iAiFy) enterprise*

[![Location](https://img.shields.io/badge/📍-Stockholm,_Sweden-blue)]()
[![Repos](https://img.shields.io/badge/repos-4-green)]()
[![Enterprise](https://img.shields.io/badge/enterprise-iAiFy-purple)]()

</div>

---

## What We Build

HomeAutonom develops the complete smart home stack — from device control and automation engines to network infrastructure management. Every piece is designed to work with Homey Pro, Home Assistant, and a Raspberry Pi–based home server.

### 🏗️ Projects

| Project | Description | Tech |
|---------|-------------|------|
| **[home-auto](https://github.com/HomeAutonom/home-auto)** | Smart home dashboard — Next.js frontend for Homey device control, scenes, and automation rules | TypeScript, Next.js |
| **[homey-smart-home](https://github.com/HomeAutonom/homey-smart-home)** | Complete Homey Pro system — 66 modules, AI-driven automation, 8 development phases | JavaScript |
| **[homey-automation](https://github.com/HomeAutonom/homey-automation)** | Backend service — Express API for Homey devices, Socket.IO real-time updates, automation engine | JavaScript, Express |
| **[home-network](https://github.com/HomeAutonom/home-network)** | Network infrastructure — Raspberry Pi Docker server, Pi-hole DNS, monitoring, dashboard | Python, Docker |

### Architecture

```
HomeAutonom/
├── home-auto/            → Next.js dashboard (frontend)
│   ├── Supabase backend
│   ├── React Query data layer
│   └── i18n (32 languages)
│
├── homey-smart-home/     → Homey Pro integration (66 modules)
│   ├── Device categories (lights, sensors, climate, blinds)
│   ├── AI automation engine
│   └── Scene management
│
├── homey-automation/     → Express API (backend)
│   ├── Homey Local API client
│   ├── Socket.IO real-time
│   ├── Pino structured logging
│   └── Docker deployment
│
└── home-network/         → Infrastructure
    ├── Docker Compose (96 containers)
    ├── Pi-hole DNS
    ├── Prometheus + Grafana monitoring
    └── Cloudflare Tunnel
```

### Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | Next.js 15, React, TypeScript, Tailwind CSS |
| **Backend** | Express 5, Socket.IO, Node.js |
| **IoT Hub** | Homey Pro, Home Assistant, MQTT, Zigbee, Z-Wave |
| **Infrastructure** | Docker Compose, Nginx, Raspberry Pi 5 |
| **Monitoring** | Prometheus, Grafana, Uptime Kuma |
| **DNS** | Pi-hole, Cloudflare Tunnel |
| **Database** | Supabase (PostgreSQL), SQLite |

## Enterprise Context

HomeAutonom is part of the **iAiFy** enterprise alongside:
- **[AiFeatures](https://github.com/AiFeatures)** — AI engineering & agent platforms
- **[AiProducting](https://github.com/AiProducting)** — Production apps & infrastructure
- **[Ai-road-4-You](https://github.com/Ai-road-4-You)** — Shared platform & governance

AI-driven automations are powered by agents from [AiFeatures/agent-hub](https://github.com/AiFeatures/agent-hub).

---

<div align="center">
<sub>Built with 🏠 in Stockholm · Part of <a href="https://github.com/enterprises/iAiFy">iAiFy Enterprise</a></sub>
</div>
