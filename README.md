# 👑 Kingdom OS

> A complete Linux-based desktop operating system — built by a 12-year-old developer from India.

[![License](https://img.shields.io/badge/license-Proprietary-gold)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-gold)](releases)
[![Kernel](https://img.shields.io/badge/kernel-Linux%206.6.30%20LTS-blue)](kernel)
[![Built by](https://img.shields.io/badge/built%20by-Vihaan%2C%20age%2012-gold)](https://github.com/Kingdom-Official)

---

## What is Kingdom OS?

Kingdom OS is a real, installable Linux-based operating system with:

- **Original desktop UI** — gold and dark theme, not macOS, not Windows
- **Worldwide activation server** running on Raspberry Pi 4
- **25-digit product keys** — format changes every 10,000 buyers automatically
- **Anti-piracy protection** — OS crashes if server is offline by design
- **All hardware drivers** — WiFi, GPU, Bluetooth, USB, Ethernet, Printer
- **25 built-in apps** — Files, Terminal, Browser, Music, Code Editor, and more
- **Linux 6.6.30 LTS kernel**
- **Ubuntu 22.04 base** with Red Hat (Rocky Linux 9) compatibility
- **Boot splash, GTK theme, custom sounds**
- **7-day free trial** built in

---

## Pricing

| Edition | Price (USD) | Price (INR) | PCs |
|---------|-------------|-------------|-----|
| Standard | $99 | ₹8,299 | 1 PC |
| Pro | $199 | ₹16,599 | 3 PCs |
| Lifetime | $499 | ₹41,499 | Unlimited |

---

## Tech Stack

- **Desktop UI** — React 18, custom CSS, no libraries
- **Server** — Node.js 20, Nginx, PM2, Redis, Cloudflare Tunnel
- **Hardware** — Raspberry Pi 4 (24/7 international server)
- **OS Base** — Ubuntu 22.04 + Linux 6.6.30 LTS kernel
- **Microcontrollers** — 3x Pi Pico + 1x NodeMCU ESP8266 (status lights)
- **Build system** — Bash scripts, debootstrap, squashfs, xorriso

---

## Product Key Format

```
KGD-XXXX-XXXX-XXXX-XXXX-XXXX  (Standard)
KPR-XXXX-XXXX-XXXX-XXXX-XXXX  (Pro)
KLT-XXXX-XXXX-XXXX-XXXX-XXXX  (Lifetime)
```

Format changes automatically every 10,000 buyers.

---

## Architecture

```
Customer buys → Admin generates key → Customer enters key on first boot
→ Pi4 server verifies → OS activates → Never asks again
→ Silent background check every boot → If Pi4 offline → OS crashes (anti-piracy)
```

---

## Built By

**Vihaan** — 12 years old, India 🇮🇳

Started building Kingdom OS in February 2025. No team, no budget, no adults helping with code. Just a MacBook, a Raspberry Pi 4, a Lenovo IdeaPad, and a vision.

> "I want to sell a real OS for $99 that people actually use."

---

## Company

**Kingdom Systems** © 2025. All rights reserved.

Kingdom OS, the Kingdom crown logo, and all associated software, code, designs, sounds, wallpapers, and documentation are the intellectual property of Kingdom Systems.

**No part of Kingdom OS may be copied, modified, distributed, or used without explicit written permission from Kingdom Systems.**

---

## Copyright Notice

```
Copyright © 2025 Kingdom Systems (Vihaan)
All Rights Reserved.

This software is proprietary and confidential.
Unauthorized copying, modification, distribution, or use
of this software, via any medium, is strictly prohibited.

Kingdom OS™ is a trademark of Kingdom Systems.
```
