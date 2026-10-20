<h3 align="center">VOID//SEARCH — OSINT Intelligence Framework (Made in 2026)</h3>

<p align="center">
  Single-file, client-side OSINT platform — 188+ platforms, 50+ tools, 13 modes.<br>
  Runs entirely in your browser · No backend · No tracking
</p>

<p align="center">
  <img src="https://img.shields.io/badge/VOID-SEARCH-red?style=for-the-badge&logo=torproject&logoColor=white" alt="VoidSearch"/>
  <img src="https://img.shields.io/badge/HTML-Single%20File-orange?style=for-the-badge&logo=html5" alt="HTML"/>
  <img src="https://img.shields.io/badge/No-Backend-green?style=for-the-badge" alt="No Backend"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License"/>
  <img src="https://img.shields.io/badge/Made%20in-2026-purple?style=for-the-badge" alt="2026"/>
</p>

<p align="center">
  <b>Developer:</b> 𝐕𝐎𝐈𝐃〆𝐇𝐄𝐀𝐕𝐄𝐍 ·
  <a href="https://t.me/he6ca">DM</a> ·
  <a href="https://t.me/SWGHEV">Channel</a>
</p>

---

## Overview

**VOID//SEARCH** is a self-contained OSINT (Open-Source Intelligence) framework delivered as a **single HTML file**. Open it in any browser — Termux, desktop, mobile — and you get 188+ platform lookups, 50+ specialized tools, geo-intelligence, a full security terminal, and an AI analyst, with **zero server, zero install, zero tracking**.

Everything runs locally. Nothing you type leaves your device unless you explicitly open one of the outbound tool links.

---

## Features

### Core Modes (13)
- 📱 **Phone** — reverse lookup across 12+ caller-ID databases
- 👤 **Username** — cross-platform handle detection
- 📧 **Email** — breach checks, footprint mapping, MX analysis
- 🔤 **Name** — people search, records, public documents
- 🔬 **OSINT** — 50+ curated investigation tools by category
- 🤖 **AI** — 10 AI providers (WormGPT default, OpenAI, Claude, Gemini, Groq, Mistral, and more)
- 🧅 **TOR OSINT** — curated `.onion` services for dark-web research
- 🎯 **Scanner** — IP · Domain · Port · Photo · Link · API deep-scan
- 🌍 **GEOINT** — photo EXIF → GPS → street-level map, IP geolocation
- 💻 **Terminal** — 20 real security tools (Nmap, SQLMap, Sherlock, theHarvester, etc.) with command builders
- 📝 **Notes** — investigation notes with AI analysis
- 🧠 **PSYCH** — MBTI + behavioral profiling
- 🕵️ **HUMINT** — photo analysis, ID-document checks, profile building, social map

### Bonus Modes
- 🌐 **Social Networks** — per-platform OSINT tool directory (Holehe, Blackbird, Sherlock, etc.)
- 🕸️ **Web Recon** — WHOIS + subdomains via crt.sh, headers, tech stack, SSL
- 🗄️ **Database** — local-only data search (your own notes / contact lists)
- ⬡ **Result Fork** — Google & Shodan dork generator

### Under the hood
- 🔐 **Email → code → terms** auth flow (no password)
- 🛡️ **VoidFirewall** — 150+ threat signatures (XSS, SQLi, SSRF, prompt injection, etc.)
- ⚡ **Rate limiting** — 25/min soft, 200/hr hard, 3-strike ban
- 🧅 **VPN/Proxy detection** → friendly 404 page
- 🎨 **Full terminal UI** — scanlines, grain, ASCII masthead
- 📦 **Zero dependencies** — no Flask, no requests, no Python

---

## Requirements

| Component | Minimum |
|-----------|---------|
| OS | Windows / Linux / macOS / Android / iOS |
| Browser | Any modern browser (Chrome, Firefox, Edge, Safari) |
| Internet | Required (for outbound tool links) |
| Install | **None** — it's one HTML file |

---

## Installation

```bash
# Clone the repository
git clone https://github.com/swagheav/VoidSearch.git
cd VoidSearch

# Open in your browser — that's it
# Just double-click VoidSearch_v7_2_red.html
```

**Termux:**
```bash
pkg install python -y
python -m http.server 8080
# then open http://127.0.0.1:8080/VoidSearch_v7_2_red.html
```

**Or** open the file directly from your file manager / browser — no server needed.

---

## Usage

1. Open `VoidSearch_v7_2_red.html` in your browser
2. Sign in with **any email** — a 6-digit code is logged to your console (F12)
3. Accept the terms
4. Pick a mode from the sidebar

**Quick examples:**
- **Phone scan** → `+201001234567` → 12+ caller-ID sources fire at once
- **Domain scan** → `example.com` → WHOIS + DNS + SSL + subdomains
- **Photo GEOINT** → upload a photo → EXIF GPS → street view
- **Terminal** → select `nmap` → set target → get the exact command

---

## Project Structure

```
VoidSearch/
├── VoidSearch_v7_2_red.html   # The entire tool
├── README.md
└── LICENSE
```

---

## Technical Details

| Property | Details |
|----------|---------|
| Language | HTML / CSS / JavaScript |
| Framework | None — vanilla |
| Backend | None — pure client-side |
| Storage | localStorage only (per-browser) |
| AI Providers | 10 (WormGPT, OpenAI, Claude, Gemini, Groq, Mistral, Together, Perplexity, xAI, Cohere) |
| Firewall | 150+ signatures |
| Platforms | 188+ |
| Tools | 50+ OSINT · 20 terminal |

---

## Notes & Limitations

- **Ethical use only** — this is for authorized security research, journalism, and self-verification.
- **AI features** require a key for the chosen provider — WormGPT is pre-filled for convenience; swap it in the AI tab.
- **VPN/Proxy detection** will trigger a 404-style blocker. Disable your VPN if you don't want it.
- **Photo EXIF** is often stripped by social platforms — GEOINT works best on original photos.
- **Phone username / social links** only open **public search pages** — nothing is scraped or bypassed.

---

## Legal Disclaimer

> VOID//SEARCH is designed **strictly for authorized security testing and educational purposes**. Unauthorized lookup of individuals may violate GDPR, CCPA, and local laws. You are solely responsible for how you use this tool.

---

## Contact

| Type | Link |
|------|------|
| 📢 Channel | [t.me/SWGHEV](https://t.me/SWGHEV) |
| 💬 DM | [t.me/he6ca](https://t.me/he6ca) |
| 🐙 GitHub | [@swagheav](https://github.com/swagheav) |
| 📦 Repo | [github.com/swagheav/VoidSearch](https://github.com/swagheav/VoidSearch) |

---

<p align="center">© 2026 VOID//SEARCH • All Rights Reserved</p>
