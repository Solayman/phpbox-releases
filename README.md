<div align="center">

# Phpbox Desktop IDE

### The Lightweight, High-Performance Desktop Code Editor for PHP & Laravel Projects

[![Release](https://img.shields.io/github/v/release/Solayman/phpbox-releases?color=10b981&label=Release&logo=github)](https://github.com/Solayman/phpbox-releases/releases/latest)
[![Download .deb (Linux)](https://img.shields.io/badge/Direct%20Download-.deb%20(Linux)-E95420?logo=ubuntu&logoColor=white)](https://github.com/Solayman/phpbox-releases/releases/download/v1.0.2/Phpbox_1.0.2_amd64.deb)
[![Download .exe (Windows)](https://img.shields.io/badge/Direct%20Download-.exe%20(Windows)-0078D4?logo=windows&logoColor=white)](https://github.com/Solayman/phpbox-releases/releases/download/v1.0.2/Phpbox_1.0.2_x64-setup.exe)
[![Memory Footprint](https://img.shields.io/badge/Idle%20RAM-~150MB%20(Win)%20%7C%20~450MB%20(Linux)-06b6d4)](#-authentic-performance--hardware-benchmarks)
[![Facebook](https://img.shields.io/badge/Facebook-Nobo%20Tech-1877F2?logo=facebook&logoColor=white)](https://www.facebook.com/NobotechLab)
[![Publisher](https://img.shields.io/badge/Publisher-Nobo%20Tech-10b981)](https://nobotech.org)

**[Official Website](https://nobotech.org/phpbox)** • **[Direct Linux (.deb)](https://github.com/Solayman/phpbox-releases/releases/download/v1.0.2/Phpbox_1.0.2_amd64.deb)** • **[Direct Windows (.exe)](https://github.com/Solayman/phpbox-releases/releases/download/v1.0.2/Phpbox_1.0.2_x64-setup.exe)** • **[Facebook Page](https://www.facebook.com/NobotechLab)** • **[Live Benchmarks](https://nobotech.org/benchmarks)**

</div>

---

## ⚡ What is Phpbox?

**Phpbox** is a modern, ultra-lightweight desktop integrated development environment (IDE) specifically engineered for **PHP** and **Laravel** developers. Built from the ground up with **Tauri 2 (Rust)** and **React**, Phpbox eliminates the excessive memory consumption, sluggish indexing, and heavy runtime overhead of legacy Electron- or JVM-based IDEs.

It delivers familiar, full-featured IDE workflows—including on-demand language server intelligence (Intelephense), deep Laravel framework navigation, an integrated terminal, Composer/PHPUnit runners, Xdebug integration, and a complete visual Git suite—while idling at a fraction of standard IDE memory usage.

### 🌟 Key Highlights & Capabilities
- 🚀 **Sub-Second Cold Boot**: Launches and loads your codebase in **under 1.0 second**.
- 🍃 **Radical Efficiency**: Idles at **~150 MB RAM on Windows** and **~450 MB RAM on Linux**—never starving system memory needed for local Docker containers, MySQL/PostgreSQL databases, or test suites.
- 🎯 **Deep PHP & Laravel Intelligence**: Instant symbol resolution, Eloquent relationship navigation, Blade template formatting, Artisan command palette, and route inspector.
- 🛠️ **Developer-Centric Tooling**: Visual 3-way Git merge conflict resolver, Patch Vault, low-latency ConPTY/PTY terminal tabs, and Xdebug DBGp debugger.
- 🤖 **Sandboxed AI Coding Agents**: Native ACP client supporting Claude, Antigravity, and Codex with strict manual approval safety boundaries.

---

## 📦 Official Binary Releases & Direct Downloads (v1.0.2)

Download official production packages directly for your operating system:

| Operating System | Package Type | Architecture | Direct Download | SHA-256 Checksum |
| :--- | :--- | :--- | :--- | :--- |
| 🐧 **Linux (Ubuntu / Debian / Mint)** | `.deb` (Debian Package) | 64-bit (`amd64`) | [📥 **Download Linux (.deb)**](https://github.com/Solayman/phpbox-releases/releases/download/v1.0.2/Phpbox_1.0.2_amd64.deb) | `494b7b93938ac62eac88da621a806dec88fb0bbc632360fc68c3674bd4416557` |
| 🪟 **Windows 10 / 11** | `.exe` (NSIS Installer) | 64-bit (`x64`) | [📥 **Download Windows (.exe)**](https://github.com/Solayman/phpbox-releases/releases/download/v1.0.2/Phpbox_1.0.2_x64-setup.exe) | `4d458f2d2c6b53ead9e2610c7e06f2485d830d4773694ff71a9dc5e7b440a6a7` |

> 🔗 For complete changelogs and previous versions, explore the [**Releases Hub**](https://github.com/Solayman/phpbox-releases/releases).

---

## 🚀 Installation Guide

### 🐧 Linux Direct Download & Installation (Debian / Ubuntu / Linux Mint)

You can download and install the official `.deb` package directly from your Linux terminal using `wget` or `curl`:

#### Method 1: Using `wget`
```bash
# 1. Direct download the latest .deb package
wget https://github.com/Solayman/phpbox-releases/releases/download/v1.0.2/Phpbox_1.0.2_amd64.deb

# 2. Install Phpbox
sudo dpkg -i Phpbox_1.0.2_amd64.deb

# 3. Resolve any desktop dependencies (e.g. WebKit2GTK) if prompted
sudo apt-get install -f

# 4. Launch Phpbox
phpbox
```

#### Method 2: Using `curl`
```bash
# 1. Direct download with curl
curl -LO https://github.com/Solayman/phpbox-releases/releases/download/v1.0.2/Phpbox_1.0.2_amd64.deb

# 2. Install with apt (auto-resolves dependencies)
sudo apt install ./Phpbox_1.0.2_amd64.deb
```

---

### 🪟 Windows Installation
1. Click to direct download [`Phpbox_1.0.2_x64-setup.exe`](https://github.com/Solayman/phpbox-releases/releases/download/v1.0.2/Phpbox_1.0.2_x64-setup.exe).
2. Run the installer and follow the guided setup.
3. *Code Signing & Trust:* Production Windows binaries are officially signed by **Nobotech** with SHA-256 and RFC 3161 timestamps.

---

## 📊 Authentic Performance & Hardware Benchmarks

Phpbox is engineered with transparent, verified metrics measured directly on physical hardware without artificial marketing deflation:

| Performance Metric | Phpbox Desktop IDE | Traditional PHP IDEs |
| :--- | :--- | :--- |
| **Cold Startup Time** | **< 1.0 Second** | 8 – 25 Seconds |
| **Windows Idle RAM** | **~150 MB** | 1,800 – 3,500 MB |
| **Linux Idle RAM** | **~450 MB** | 2,200 – 4,000 MB |
| **Installer Size** | **~3.5 MB** | 600 – 1,200 MB |
| **Underlying Architecture** | **Tauri 2 (Rust) + Native Webview** | Heavyweight Electron / JVM |

---

## ✨ Core Feature Overview

### 🐘 PHP & Laravel First-Class Intelligence
- **Intelephense LSP Integration**: On-demand initialization with zero background thread leaks.
- **Composer Intelligence**: PSR-4 auto-discovery, multi-app namespace mapping, and plural `resolveClasses` declaration chooser.
- **Laravel Navigation**: Direct navigation to Eloquent models, relationships, controllers, and Blade template syntax formatting.
- **Artisan & Routes Panel**: Interactive Artisan command runner and categorized route inspector with direct method jump navigation.

### 🔀 Complete Integrated Git Studio
- **Commit Management**: Native Git status grouping, hunk inspection, and unstage resilience.
- **3-Way Merge Conflict Resolver**: Visual 3-column conflict resolution with per-hunk actions and inline editing.
- **Patch Vault**: Save, manage, compare, and revert custom patches and stashes with a dedicated Recently Deleted recycle bin.
- **Git Safety Guards**: Built-in argument injection prevention and dubious ownership verification (`safe.directory`).

### ⌨️ Multi-Keymap Architecture
Transition seamlessly without losing muscle memory:
- **Phpbox Standard Keymap** (Default)
- **PhpStorm Compatible Preset**
- **VS Code Compatible Preset**
- Dynamic keyboard shortcuts editor (`Ctrl+Alt+S`) with conflict detection.

### 🤖 Sandboxed AI Coding Agents
- Native **ACP (Agent Client Protocol)** client with header selectors for **Claude**, **Antigravity**, and **Codex**.
- Strict **Manual Approval Controls** preventing unintended terminal command chains or destructive shell execution.
- Centralized session history stored securely in user AppData.

---

## 🔒 Security, Integrity & Verification

Every official Phpbox binary package is verified and authenticated:
- **Code Signing**: Windows installers are signed using the official **Nobotech** certificate (`SHA-256`, RFC 3161 timestamped).
- **Dual-Verification Endpoint**: Built-in update client verifies releases using Ed25519 cryptographic signatures served through `console.nobotech.org`.

### Verifying SHA-256 Checksums

**Linux (Bash):**
```bash
sha256sum Phpbox_1.0.2_amd64.deb
# Expected: 494b7b93938ac62eac88da621a806dec88fb0bbc632360fc68c3674bd4416557  Phpbox_1.0.2_amd64.deb
```

**Windows (PowerShell):**
```powershell
Get-FileHash -Path "Phpbox_1.0.2_x64-setup.exe" -Algorithm SHA256
# Expected: 4D458F2D2C6B53EAD9E2610C7E06F2485D830D4773694FF71A9DC5E7B440A6A7
```

---

## 🌐 Official Resources, Community & Connect

Connect with the Nobo Tech team, follow live release announcements, and access official developer channels:

| Resource & Channel | Purpose | Direct Access |
| :--- | :--- | :--- |
| 🌍 **Phpbox Official Portal** | Product specifications, latest updates & feature highlights | [**nobotech.org/phpbox**](https://nobotech.org/phpbox) |
| 🏢 **Nobo Tech Systems** | Parent engineering lab, architectural philosophy & full ecosystem | [**nobotech.org**](https://nobotech.org) |
| 📢 **Official Facebook Page** | Live release announcements, engineering blogs & community news | [**Nobo Tech on Facebook**](https://www.facebook.com/NobotechLab) |
| ⚡ **Hardware Benchmarks** | Authentic RAM and latency metrics from production hardware | [**nobotech.org/benchmarks**](https://nobotech.org/benchmarks) |
| 🐛 **Issue & Bug Tracker** | Report defects, request capabilities & track ongoing fixes | [**GitHub Issues**](https://github.com/Solayman/phpbox-releases/issues) |
| 🛡️ **Security Inquiries** | Responsible security disclosure and verification | [`security@nobotech.org`](mailto:security@nobotech.org) |

---

<div align="center">

### Built with Radical Efficiency by Nobo Tech

**Phpbox Desktop IDE** is engineered and maintained by **Solayman Ali** at **[Nobo Tech](https://nobotech.org)**.  
*Building ultra-lightweight tools that boot in microseconds and respect system resources.*

[Official Website](https://nobotech.org/phpbox) • [Facebook Community](https://www.facebook.com/NobotechLab) • [Releases Hub](https://github.com/Solayman/phpbox-releases/releases) • [Issue Tracker](https://github.com/Solayman/phpbox-releases/issues)

<br/>

<sub>Copyright © 2026 Solayman Ali / Nobo Tech. All rights reserved. Proprietary software.</sub>

</div>
