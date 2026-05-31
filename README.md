# NATBreaker

**Automated NAT traversal for self-hosted servers — expose any port through a VPS without port forwarding.**

NATBreaker sets up a WireGuard tunnel between your home server and a cheap VPS, automatically routing traffic so your services are publicly reachable via the VPS IP — no ISP cooperation required.

---

## Download

Head to the [**Releases**](../../releases) tab and download the latest installer for Windows.

| Platform | File |
|---|---|
| Windows 10/11 (x64) | `NATBreaker-Setup-x.x.x.exe` |

> The app requires a license key after the trial period.

---

## Screenshots

<!-- Dashboard -->
### Dashboard
<img width="1190" height="1119" alt="image" src="https://github.com/user-attachments/assets/2568f0d8-f478-4e01-8ce8-27a9138c5f17" />

<!-- Settings -->
### Settings
<img width="1184" height="814" alt="image" src="https://github.com/user-attachments/assets/cc103e9b-4b35-4ef5-bd87-319941348f1e" />

---

## What it does

- **One-click tunnel setup** — connects your home VM to a VPS via WireGuard with zero manual config
- **Automatic NAT rules** — generates and applies iptables rules on both ends
- **Port forwarding management** — manage which ports route through the VPS
- **WireGuard peer management** — add additional devices (phones, game servers, etc.) to the tunnel
- **Live monitoring** — CPU, memory, and network throughput for both VPS and VM
- **Auto-updates** — the app checks this repository for new releases

---

## Requirements

- Windows 10 or 11 (64-bit)
- A VPS running Ubuntu 22.04+ (DigitalOcean, Vultr, Hetzner, etc.)
- SSH access to your VPS
- A home server or VM (Proxmox, Unraid, Windows, etc.)

---

## Installation

1. Download `NATBreaker-Setup-x.x.x.exe` from the [Releases](../../releases) page
2. Run the installer and follow the prompts
3. Launch NATBreaker and complete the Setup Wizard
4. Enter your license key when prompted (or continue with the trial)

---

## Updating

NATBreaker checks for updates automatically. When an update is available, a notification appears in the app — click **Download & Install** to apply it.

You can also manually download the latest version from [Releases](../../releases) and run it over the existing installation.

---

## Support

- Issues: [github.com/Mavrag/NATBreaker-releases/issues](https://github.com/Mavrag/NATBreaker-releases/issues)
- Email: support@natbreaker.io

---

## License

See [LICENSE](LICENSE). NATBreaker is proprietary software — source code is not included in this repository.

---

<p align="center">
  <a href="https://github.com/Mavrag/NATBreaker-releases/releases/latest">Download latest release</a>
</p>
