# ElonXaeA625 • Live AI Architecture

**Real-time AI Coding Infrastructure & Global Telemetry Hub**

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployed-brightgreen)](https://elonxaea625.github.io)
[![Jekyll](https://img.shields.io/badge/Jekyll-4.3-blue)](https://jekyllrb.com)
[![Cloudflare](https://img.shields.io/badge/Cloudflare-Workers-orange)](https://workers.cloudflare.com)

---

## 🚀 Overview

A cutting-edge **live AI coding platform** featuring real-time code analysis, multi-protocol streaming (NDI, SRT, WebRTC), and global edge orchestration using Cloudflare Workers + Durable Objects.

Built as both a **portfolio showcase** and a **production-grade streaming infrastructure**.

---

## ✨ Key Features

- **Real-time AI Code Analysis** overlaid on live streams
- **Multi-Protocol Streaming**:
  - Virtual Camera (local apps)
  - NDI (professional broadcast)
  - SRT (reliable WAN contribution)
  - LiveKit WebRTC
- **OBS Studio Automation** (auto-connect, scene switching, streaming)
- **Enterprise Observability** (Azure Monitor, Grafana, Teams alerts)
- **Cross-Platform** (Windows, Linux, macOS) with automated setup scripts
- **Recording Capabilities** (MP4/MKV)

---

## 🛠 System Architecture

- **Edge Runtime**: Cloudflare Workers + Durable Objects
- **Real-time Layer**: WebSockets + WebRTC
- **Streaming Engine**: Python + FFmpeg + NDI SDK
- **Frontend**: Jekyll Static Site + Custom Electron Control Center
- **AI Layer**: Real-time code analysis & visual overlays

[View Full System Architecture →](/architecture/system-architecture-v1/)

---

## 📁 Project Structure

```bash
docs/                    # Jekyll Portfolio Site
├── _projects/           # Project showcases
├── _articles/           # Technical articles
├── _architecture/       # System design documents
├── _layouts/
└── index.md

apps/streaming-server/   # Core Python streaming engine
electron-client/         # Desktop control center
azure/                   # IaC (Terraform + Bicep)
scripts/                 # Automated setup (Linux/macOS)
