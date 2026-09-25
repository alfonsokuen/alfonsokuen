# Alfonso Kuen Arroyo

**Founder & Technology Architect at [IDK MANAGER](https://idkmanager.com) · Quito, Ecuador 🇪🇨**

[![Website](https://img.shields.io/badge/idkmanager.com-0A66C2?style=flat-square&logo=googlechrome&logoColor=white)](https://idkmanager.com/equipo/alfonso-kuen-arroyo/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alfonso-kuen-arroyo-5a7a92133)
[![firmar.ec](https://img.shields.io/badge/firmar.ec-open%20source-2EA043?style=flat-square)](https://firmar.ec)

I build infrastructure, software and privacy-first products from Ecuador. My work sits between
enterprise infrastructure and product engineering: design the architecture, build the platform it
needs, run it in production — and open-source the tooling along the way.

- 🏗️ Running a private cloud on **Proxmox VE + TrueNAS SCALE + OPNsense**, with HA and off-site backup
- 🔐 Building **privacy-by-design** software: keys and documents stay on the user's device
- 🤖 Putting **AI agents** to work on real operations: SOC, support, sales and QA
- 🧩 Contributing fixes back upstream: Proxmox VE, TrueNAS storage plugin, PegaProx

## What I'm working on

- **TrueNAS ↔ Proxmox storage.** My fork of the official plugin adds iSCSI CHAP fixes, **NVMe/TCP**
  and snapshot import. Current release: `v2.1.23-alpha1+idk21`. It runs in production and ships as signed
  APT packages.
- **firmar.ec.** An open-source PDF signer and verifier for Ecuador, with PAdES up to **B-LTA**,
  that runs entirely in the browser.
- **PegaProx plugins.** One console for the whole stack: storage, firewall, containers and power.

## Projects

### [firmar.ec](https://firmar.ec): open-source PDF signing for Ecuador

Sign and verify PDF documents with Ecuadorian digital certificates. The `.p12` certificate and the
document are processed entirely in the browser: **the private key never leaves your machine and the
file is never uploaded to a server.**

- PAdES **B-B / B-T / B-LT / B-LTA** signature profiles (RFC 3161 timestamps, OCSP/CRL, LTV)
- Cryptography in the browser (Web Crypto, `pkijs`, `pdf-lib`)
- Offline signature verification: the document never leaves your machine
- Installable PWA · Svelte + Astro + TypeScript
- **AGPL-3.0**, with a commercial license available

→ [`idkmanager/firmar-ec`](https://github.com/idkmanager/firmar-ec)

### Infrastructure tooling

Open-source plugins and tools for the stack I run in production:

| Repository | What it does |
|---|---|
| [`truenas-proxmox-plugin`](https://github.com/alfonsokuen/truenas-proxmox-plugin) | Fork of [truenas/truenas-proxmox-plugin](https://github.com/truenas/truenas-proxmox-plugin): TrueNAS block storage for Proxmox VE with iSCSI CHAP fixes, NVMe/TCP and snapshot import · [write-up](https://idkmanager.com/blog/plugin-truenas-proxmox-nvme-tcp-chap-iscsi/) |
| [`pegaprox-plugin-truenas`](https://github.com/alfonsokuen/pegaprox-plugin-truenas) | Monitor and control TrueNAS SCALE over WebSocket JSON-RPC 2.0. Multi-tenant, with typed confirmation and an audit trail for writes |
| [`pegaprox-docker-manager`](https://github.com/alfonsokuen/pegaprox-docker-manager) | Manage Docker hosts over SSH, whether Swarm clusters or standalone engines, from one dashboard |
| [`pegaprox-plugin-opnsense`](https://github.com/alfonsokuen/pegaprox-plugin-opnsense) | Monitor and configure OPNsense firewalls, HA pairs included |
| [`pegaprox-plugin-proxmox-power`](https://github.com/alfonsokuen/pegaprox-plugin-proxmox-power) | Power control for VMs and containers that respects dependencies and health checks, with dry-run by default |
| [`pegaprox-plugin-wake-on-lan`](https://github.com/alfonsokuen/pegaprox-plugin-wake-on-lan) | Wake-on-LAN for physical office PCs through a Proxmox node |

### IDK MANAGER platforms

Products built and run inside the company:

| Product | What it is |
|---|---|
| [IDKsentinel](https://idksentinel.com) | Managed SOC with AI agents, built for LATAM |
| [Adualis](https://adualis.com) | Customs-broker SaaS for ECUAPASS |
| [3tap](https://3tap.ec) | Electronic invoicing for Ecuador's tax authority (SRI) |
| [IDKpuntual](https://idkpuntual.com) | Workforce attendance compliant with Ecuadorian labor rules |
| [IDKdesk](https://idkdesk.com) | Field service orders with electronic signature |

## Stack

![Proxmox](https://img.shields.io/badge/Proxmox_VE-E57000?style=flat-square&logo=proxmox&logoColor=white)
![TrueNAS](https://img.shields.io/badge/TrueNAS_SCALE-0095D5?style=flat-square&logo=truenas&logoColor=white)
![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?style=flat-square&logo=opnsense&logoColor=white)
![MikroTik](https://img.shields.io/badge/MikroTik-293239?style=flat-square&logo=mikrotik&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_Swarm-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white)
![Odoo](https://img.shields.io/badge/Odoo-714B67?style=flat-square&logo=odoo&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Claude](https://img.shields.io/badge/AI_agents-D97757?style=flat-square&logo=anthropic&logoColor=white)

## Approach

I prefer open technologies, infrastructure you can control, and automation that proves itself: every
backup is restored and every alert is fired at least once before it counts. The goal is systems that
stay efficient and resilient without depending on proprietary platforms.

---

<sub>🇪🇸 Construyo infraestructura, software y productos con privacidad por diseño desde Quito. ¿Proyecto de
nube privada, ciberseguridad o automatización? → [idkmanager.com](https://idkmanager.com)</sub>
