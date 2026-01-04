<h1 align="center">
  <br>
  <a href="https://karmagate.com"><img src="https://raw.githubusercontent.com/Karmagate/App/main/assets/logo.svg" width="200px" alt="KarmaGate"></a>
  <br>
  <br>
  KarmaGate
  <br>
</h1>

<h4 align="center">Built to make you extraordinarily effective, KarmaGate is the best way to test web security.</h4>

<p align="center">
  <a href="https://github.com/Karmagate/App/releases/latest">
    <img src="https://img.shields.io/github/v/release/Karmagate/App?style=flat-square&color=00d4aa" alt="Latest Release"/>
  </a>
  <a href="https://github.com/Karmagate/App/releases">
    <img src="https://img.shields.io/github/downloads/Karmagate/App/total?style=flat-square&color=7c3aed" alt="Total Downloads"/>
  </a>
  <a href="https://karmagate.com">
    <img src="https://img.shields.io/badge/website-karmagate.com-blue?style=flat-square" alt="Website"/>
  </a>
</p>

<p align="center">
  <a href="#download">Download</a> •
  <a href="#features">Features</a> •
  <a href="#modules">Modules</a> •
  <a href="#getting-started">Getting Started</a> •
  <a href="#support">Support</a>
</p>

<br>

<p align="center">
  Trusted every day by security researchers worldwide.
</p>

<br>

---

<br>

## Download

> **This is the official release repository.** All binaries are built from our private source repository and published here.

### Latest Release

| Platform | Architecture | Download |
|----------|--------------|----------|
| **macOS** | Apple Silicon (M1/M2/M3/M4) | [**Download .dmg**](https://github.com/Karmagate/App/releases/latest/download/KarmaGate-arm64.dmg) |
| **macOS** | Intel | [**Download .dmg**](https://github.com/Karmagate/App/releases/latest/download/KarmaGate-amd64.dmg) |
| **Windows** | x64 | [**Download Installer**](https://github.com/Karmagate/App/releases/latest/download/KarmaGate-x64-setup.exe) |
| **Windows** | ARM64 | [**Download Installer**](https://github.com/Karmagate/App/releases/latest/download/KarmaGate-arm64-setup.exe) |
| **Linux** | x64 (Debian/Ubuntu) | [**Download .deb**](https://github.com/Karmagate/App/releases/latest/download/karmagate_amd64.deb) |
| **Linux** | x64 (Fedora/RHEL) | [**Download .rpm**](https://github.com/Karmagate/App/releases/latest/download/karmagate.x86_64.rpm) |
| **Linux** | x64 (Universal) | [**Download AppImage**](https://github.com/Karmagate/App/releases/latest/download/KarmaGate-x86_64.AppImage) |
| **Linux** | ARM64 (Debian/Ubuntu) | [**Download .deb**](https://github.com/Karmagate/App/releases/latest/download/karmagate_arm64.deb) |
| **Linux** | ARM64 (Fedora/RHEL) | [**Download .rpm**](https://github.com/Karmagate/App/releases/latest/download/karmagate.aarch64.rpm) |
| **Linux** | ARM64 (Universal) | [**Download AppImage**](https://github.com/Karmagate/App/releases/latest/download/KarmaGate-aarch64.AppImage) |

<br>

> **Not sure which version to download?**
> - **macOS**: Choose "Apple Silicon" if you have an M1/M2/M3/M4 Mac, otherwise choose "Intel"
> - **Windows**: Choose "x64" for most Windows PCs
> - **Linux**: Choose ".deb" for Debian/Ubuntu, ".rpm" for Fedora/RHEL, or "AppImage" for any distribution

<br>

---

<br>

## Features

Powerful security testing tools, built for professionals.

<table>
<tr>
<td width="50%">

### Strike finds vulnerabilities fast
High-performance fuzzing at 1000+ requests per second. 4 attack modes, auto-calibration, and smart payload generation.

- 4 attack modes: Sniper, Battering Ram, Pitchfork, Cluster Bomb
- Auto-calibration to detect anomalies
- Smart payload generation and built-in wordlists
- Rate limit detection and throttling

</td>
<td width="50%">

### Intelligent vulnerability detection
Vulnerability scanner with Nuclei template support. Automatic injection point detection and built-in OAST.

- Nuclei template support (12,000+ templates)
- Automatic injection point detection
- Built-in OAST for blind vulnerabilities
- Scan profiles: quick, standard, thorough

</td>
</tr>
<tr>
<td width="50%">

### Complete traffic control
Capture and inspect all HTTP and WebSocket traffic. Full HTTP/2 support with advanced filtering and annotations.

- Full HTTP/2 support for modern applications
- WebSocket inspection and history
- Annotate requests with notes and colors
- Advanced filtering to find what you need

</td>
<td width="50%">

### Workflow automation
Automate multi-step attack sequences with data extraction and conditional logic.

- Automate multi-step attack sequences
- Extract data between requests automatically
- HTTP and WebSocket support
- Conditional logic for complex flows

</td>
</tr>
</table>

<br>

---

<br>

## Modules

Everything you need for professional web security testing in one application.

| Module | Description |
|--------|-------------|
| **Gate** | Capture and inspect all HTTP and WebSocket traffic with full HTTP/2 support |
| **Loop** | Modify and resend requests with a powerful editor supporting HTTP/1.1, HTTP/2, and HTTP/3 |
| **Snag** | Intercept and modify requests and responses in real-time with visual rule builder |
| **Strike** | Blazing fast fuzzing at 1000+ requests per second with intelligent anomaly detection |
| **Probe** | Intelligent vulnerability scanner with Nuclei template support and automatic detection |
| **Chain** | Automate multi-step attack sequences with data extraction and conditional logic |
| **Echo** | Built-in OAST server with WebSocket support for detecting blind vulnerabilities |
| **Reap** | Centralized vulnerability management with import from popular tools |
| **Terminal** | Built-in terminal with kt.* commands and access to KarmaGate environment |

<br>

---

<br>

## Getting Started

### Installation

1. **Download** the appropriate installer for your platform from the [releases page](https://github.com/Karmagate/App/releases/latest)
2. **Install** following your platform's standard procedure:
   - **macOS**: Open the `.dmg` and drag KarmaGate to Applications
   - **Windows**: Run the installer and follow the prompts
   - **Linux**: Install the `.deb`/`.rpm` or run the AppImage directly
3. **Launch** KarmaGate and configure your browser proxy settings

### Quick Start

1. Start KarmaGate and note the proxy port (default: `8080`)
2. Configure your browser or system to use `127.0.0.1:8080` as HTTP/HTTPS proxy
3. Install the generated CA certificate for HTTPS interception
4. Start browsing — all traffic will appear in KarmaGate's History tab

### Documentation

Full documentation is available at [docs.karmagate.com](https://docs.karmagate.com)

<br>

---

<br>

## System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| **OS** | Windows 10, macOS 11, Ubuntu 20.04 | Latest version |
| **RAM** | 4 GB | 8 GB+ |
| **Disk** | 200 MB | 500 MB |
| **Display** | 1280x720 | 1920x1080+ |

<br>

---

<br>

## Support

- **Email**: support@karmagate.com
- **Website**: [karmagate.com](https://karmagate.com)
- **Documentation**: [docs.karmagate.com](https://docs.karmagate.com)
- **Bug Reports**: [GitHub Issues](https://github.com/Karmagate/App/issues)

<br>

---

<br>

## Legal Disclaimer

KarmaGate is designed for authorized security testing and research purposes only. Users are responsible for ensuring they have proper authorization before testing any systems. Unauthorized access to computer systems is illegal. The developers assume no liability for misuse of this software.

<br>

---

<br>

## License

Copyright © 2026 KarmaGate Inc. All Rights Reserved.

This software is proprietary. See [LICENSE](LICENSE) for details.

<br>

<div align="center">
  <sub>Built with love by the <a href="https://karmagate.com">KarmaGate</a> Team</sub>
  <br>
  <br>
  <a href="https://karmagate.com">Website</a> •
  <a href="https://t.me/karmagate">Telegram</a> •
  <a href="https://discord.gg/karmagate">Discord</a>
</div>
