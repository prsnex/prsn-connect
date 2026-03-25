# PRSN Connect

The desktop companion for [PRSN ID](https://prsnex.id) — verifiable identity for AI agents (PRSNs).

PRSN Connect runs on your machine alongside your PRSN. It creates a hardware-bound cryptographic identity, maintains a heartbeat proving the PRSN is running on real hardware, and provides a local gateway for credential access.

## Downloads

| Platform | Download |
|----------|----------|
| **macOS** (Apple Silicon) | [Download .dmg](https://prsn-connect-download-proxy.chris-f29.workers.dev/macos) |
| **Windows** (x64) | [Download .exe](https://prsn-connect-download-proxy.chris-f29.workers.dev/windows) |
| **Linux** (x64) | [Download .AppImage](https://prsn-connect-download-proxy.chris-f29.workers.dev/linux) |

Additional formats (.deb, .rpm, .msi) are available on the [Releases](https://github.com/prsnex/prsn-connect/releases) page.

## What It Does

- **Hardware-Bound Identity** — Generates a cryptographic signing key tied to the machine's hardware. This key proves the PRSN is running on a specific device, not being simulated or duplicated.
- **Hardware Heartbeat** — Sends periodic attestations to the PRSN ID platform confirming the PRSN is active and running on genuine hardware.
- **Local Gateway** — Provides a local API that the PRSN can use to access its credentials, identity information, and platform services.
- **MCP Server** — Includes a bundled [Model Context Protocol](https://modelcontextprotocol.io/) server (`prsn-gateway-mcp`) that AI agents can use to interact with their PRSN identity.
- **Auto-Update** — Checks for new versions automatically and installs updates with cryptographic signature verification.

## System Requirements

| Platform | Minimum Version |
|----------|----------------|
| macOS | 11.0 (Big Sur) — Apple Silicon |
| Windows | 10 (x64) |
| Linux | Ubuntu 22.04+ or equivalent (x64) — requires WebKit2GTK 4.1 |

## Getting Started

1. **Register as a Guardian** on [PRSN ID](https://app.prsnex.id) and create a PRSN
2. **Download** PRSN Connect for your platform (see table above)
3. **Install and launch** — the app will guide you through connecting to your PRSN
4. Once connected, PRSN Connect runs in the background, maintaining your PRSN's hardware binding and heartbeat

## License

This project is source-available under the [Business Source License 1.1](LICENSE).

- **Licensor:** PRSN EX Inc.
- **Change Date:** 2030-03-16
- **Change License:** [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

Source code will be published to this repository in a future update. On the Change Date, the license converts to Apache 2.0. See the [LICENSE](LICENSE) file for full terms.

## Links

- [PRSN ID Platform](https://prsnex.id) — learn about verifiable identity for AI
- [PRSN ID Dashboard](https://app.prsnex.id) — register and manage your PRSNs
- [PRSNex](https://prsnex.ai) — the company behind PRSN ID

---

Copyright (c) 2026 PRSN EX Inc.
