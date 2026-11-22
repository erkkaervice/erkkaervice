<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.svg">
    <img alt="Erkka Ala-Lahti - Systems and Full-Stack Software Engineer" src="./assets/hero-dark.svg" width="100%">
  </picture>
</div>

<div align="center">
  <a href="https://linkedin.com/in/erkka-ala-lahti/"><img src="https://img.shields.io/badge/LinkedIn-Primary_Contact_%26_Hiring-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Location-Helsinki%2C_Finland-1F2328?style=flat-square" alt="Helsinki, Finland">
  <img src="https://img.shields.io/badge/Availability-Freelance_%7C_Contract_%7C_Permanent-1A7F37?style=flat-square" alt="Availability">
  <img src="https://img.shields.io/badge/Entity-Ervice_Oy-30363D?style=flat-square" alt="Ervice Oy">
</div>

<p align="center">
  <a href="#live-engineering-metrics">Metrics</a> &middot;
  <a href="#capabilities-tooling--proven-outcomes">Capabilities</a> &middot;
  <a href="#engineering-ecosystem">Ecosystem</a> &middot;
  <a href="#selected-systems--case-studies">Systems &amp; Projects</a> &middot;
  <a href="#operations--delivery-track-record">Delivery Track Record</a> &middot;
  <a href="#technical-stack">Tech Stack</a>
</p>

---

### Engineering Profile

Software developer and systems engineer combining low-level Linux and network fundamentals, full-stack TypeScript architecture, and governed AI engineering workflows with 15 years of operational and business leadership.

Graduated from **Hive Helsinki** (42 Network), where I built C/C++ network servers and Unix tooling from scratch without external libraries. Today, through **Ervice Oy**, I design and ship security-hardened web platforms, resilient Linux infrastructure, and multi-model AI automation pipelines that deliver tested software at high velocity without sacrificing reliability.

- **Role of this GitHub profile:** Technical proof-of-work, architecture catalog, and live-verified quality metrics.
- **How I work with teams:** Operating as a freelancer via **Ervice Oy** and open to **freelance engagements, fixed-scope contracts, and full-time engineering roles** — always negotiated case-by-case. For roles, projects, or live technical walkthroughs, connect on **[LinkedIn](https://linkedin.com/in/erkka-ala-lahti/)**.

---

### Live Engineering Metrics

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/metrics-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./assets/metrics-light.svg">
    <img alt="Auto-Synced Engineering Metrics" src="./assets/metrics-dark.svg" width="100%">
  </picture>
</div>

<!-- AUTO-STATUS:START -->
| Repository       | Visibility             | Latest Commit          | Tracked Files | Automated Tests        | Security Gate             |
| :--------------- | :--------------------- | :--------------------- | ------------: | :--------------------- | :------------------------ |
| `event-platform` | Private (Commercial)   | `d5a0a80` (2026-11-22) |           189 | 748 tests (5 packages) | Rule 31 + SAST + 0 CVE    |
| `agent-farm`     | Private (Internal Ops) | `a46e96c` (2026-11-22) |            99 | 68 tests (node:test)   | SAST + SHA-256 0 drift    |
| `.dotfiles`      | Private (Public-Ready) | `72bbe45` (2026-11-22) |            69 | 77 parity & SAST tests | Multi-shell + secret scan |

*Auto-synced on 2026-11-22 by `agent-farm/scripts/readme-autosync.mjs` (24 active models across 4 providers).*
<!-- AUTO-STATUS:END -->

> Commercial and internal Ervice Oy repositories remain private to protect business logic and host configurations. Full source walkthroughs and live demonstrations are available during technical interviews. Publicly inspectable C/C++, Docker, and full-stack repositories are linked below.

---

### Capabilities, Tooling & Proven Outcomes

I treat modern AI models as high-leverage engineering infrastructure — paired with deep systems fundamentals, strict static analysis, automated test suites, and human architectural ownership.

| Focus Area | Core Tooling & Methods | Proven Outcomes |
| :--- | :--- | :--- |
| **Full-Stack & Offline-First Systems** | TypeScript, Node.js 22+, Fastify 5, tRPC 11, Zod 4, PostgreSQL 16 + PostGIS, Drizzle ORM, React, Next.js, Sub-5ms Brotli/Gzip SSR, Service Workers | Architected and delivered `event-platform` across 3 pilot verticals (offline festival bundles, ticketed LL-HLS streaming, background radio + foldable PWA) with **748 automated tests** and **0 production CVEs**. |
| **Linux Infrastructure & Networking** | Debian 13, openSUSE, Arch, Alpine, NixOS, `systemd`, `cgroups`/`zram`/`earlyoom`, Docker, NGINX, Tailscale VPN, TLS 1.3 PKI, C/C++ sockets (`poll`/`select`) | Engineered a 24/7 headless server on constrained hardware (Core 2 Duo, 1.7 GiB RAM) with 3-layer self-healing and sub-5ms TLS 1.3 telemetry; built an RFC HTTP/1.1 server from scratch in C++. |
| **Security-by-Design & Hardening** | OWASP ASVS L3, Fail-Closed auth (`timingSafeEqual`), HMAC token binding, SSRF/DNS-rebinding guards, binary EXIF/GPS stripping, OpenSSH, GnuPG, custom SAST & secret scanners | Enforced Fail-Closed Rule 31 API authentication, 28-pattern secret-leak scanning, symlink-safe write containment, and SHA-256 live-vs-Git drift verification across managed repositories. |
| **Governed AI Engineering & Automation** | Self-hosted multi-provider orchestration (Claude Code Pro, Gemini, Groq, GitHub Models), `LOCAL_FIRST` skill routing, adversarial review gates, CI/CD test verification | Built `agent-farm` to coordinate 24 models behind deterministic SAST, test, and drift gates with mandatory human final review — accelerating refactoring, test coverage, and documentation without vibe-coding risk. |
| **Rollouts, Migrations & Operations** | Data migration & validation, system onboarding, Moodle/WordPress/Netvisor/Paytrail administration, technical training, stakeholder alignment | Delivered customer migrations at **TableOnline (2026)**, led a **40+ city** digital system rollout (**Koutsit**), and manage end-to-end IT infrastructure and security training for **FSE Charity (Tanzania)**. |

---

### Engineering Ecosystem

```mermaid
flowchart LR
    Owner["Erkka Ala-Lahti\nArchitecture, Security Policy\n& Final Review"] --> Delivery["Governed Delivery Loop\nMulti-Provider AI + LOCAL_FIRST Skills\nSAST, Secret Scan, Drift & Test Gates"]

    Delivery --> EP["event-platform\nFastify 5 + tRPC 11 + PostGIS\nOffline PWA + LL-HLS\n748 Tests | 0 CVE"]
    Delivery --> AF["agent-farm\n24-Model Orchestrator\nDebian 13 (1.7 GiB) | TLS 1.3\n68 Tests | 0 Drift"]
    Delivery --> DOT[".dotfiles\nBash / Zsh / Fish Parity\n8 OS Families | Non-Root\n77 Tests | 0 Critical"]

    Owner --> Public["Public Inspectable Code\nhive-webserv (C++ HTTP/1.1)\nhive-transcendence (Full-Stack)\nhive-inception (Docker Stack)"]
```

---

### Selected Systems & Case Studies

#### Ervice Oy Ecosystem *(Private Repositories — Live Code & Demo Available on Request)*

| System | Stack & Runtime | Engineering Highlights |
| :--- | :--- | :--- |
| **`event-platform`** | TypeScript monorepo (`Fastify 5`, `tRPC 11`, `Zod 4`, `PostgreSQL 16 + PostGIS`, `Drizzle ORM`, `MediaMTX`, `SeaweedFS`) | Multi-tenant platform covering three real-world event profiles: offline-first music festivals (`ETag 304`, SHA-256 bundles, Haversine POI distance, `.ics` export), low-latency ticketed LL-HLS streams (constant-time HMAC tokens, zero-dep AWS SigV4 presigner), and continuous radio with foldable tabletop PWA layout and Wear OS glance state. Hardened with Fail-Closed Rule 31 `adminProcedure`, SSRF/DNS-rebinding protection, EXIF/GPS stripping, and **748 passing tests**. |
| **`agent-farm`** | Node.js 22+ ESM, `Debian 13`, `systemd`, `TLS 1.3`, `Python PTY`, `Three.js` | Self-hosted AI engineering platform running 24/7 on a 1.7 GiB RAM host with 3-layer resilience (`cgroups`/`zram`/`earlyoom`, 2-min self-heal timer, `softdog` watchdog). Orchestrates 24 models across 4 providers using deterministic guardrails (`agent-guards.mjs`), SHA-256 manifest drift gates, a single-port TLS 1.3 telemetry dashboard, and a mobile-responsive Tmux web terminal. **68 passing tests**, **0 drift**. |
| **`.dotfiles`** | `Bash`, `Zsh`, `Fish`, `OpenSSH`, `GnuPG`, `Tmux`, `node:test` | Portable shell and security toolkit enforcing strict command and exit-code parity across Bash/Zsh (`.sh_common`) and Fish (`.config.fish`) on 8 OS families (Debian, Arch, Fedora, NixOS, openSUSE, Alpine, macOS, Termux) with non-root `~/.local/bin` fallbacks, SSH agent hardening, and automated secret-leak checks. **77 passing tests**. |

#### Public Inspectable Foundations *(Hive Helsinki / 42 Network)*

| Repository | Focus Area | Engineering Scope |
| :--- | :--- | :--- |
| **[hive-webserv](https://github.com/erkkaervice/hive-webserv)** | Network & Protocol Engineering (`C++`) | Custom RFC-compliant HTTP/1.1 server built from scratch without frameworks, implementing non-blocking sockets and I/O multiplexing (`poll`/`select`). |
| **[hive-transcendence](https://github.com/erkkaervice/hive-transcendence)** | Full-Stack Web & Real-Time (`TypeScript`, `Next.js`, `MariaDB`, `Docker`) | Real-time multi-user web application with centralized authentication and containerized deployment; served as **Product Owner** coordinating team delivery. |
| **[hive-inception](https://github.com/erkkaervice/hive-inception)** | Container Infrastructure (`Docker Compose`, `NGINX`, `MariaDB`, `Alpine/Debian`) | Multi-container stack built from base images with strict network isolation, TLS termination, and persistent volumes. |

<!-- AUTO-COLLAB:START -->
<!-- AUTO-COLLAB:END -->

---

### Operations & Delivery Track Record

- **Customer Onboarding & Data Migration (TableOnline Finland Oy, 2026):** Executed customer system migrations, account configuration, data validation, and independent technical support during a full-time contract assignment.
- **Volunteer IT Specialist & Vice Board Member (FSE Charity, Tanzania Project, 2025-Present):** Manage end-to-end IT infrastructure including Moodle server administration, WordPress sites, web hosting, Netvisor/Paytrail integrations, and an on-site information security training package.
- **Nationwide System Rollout (Koutsit, 2024-2025):** Served as lead implementation trainer across **40+ cities** for a digital kitchen management system rollout, bridging software vendors and end-users under operational pressure.
- **Entrepreneurship & Operations (15 Years):** Built and operated companies across events, hospitality, coaching, and manufacturing (Ervice Oy, Pieni Limonaaditehdas Porvoo, Konseptihelsinki), bringing commercial pragmatism and clear communication to engineering teams.

---

### Technical Stack

<div align="center">

**Languages & Shell**

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white)
![Zsh](https://img.shields.io/badge/Zsh-1F2328?style=flat-square&logo=gnubash&logoColor=white)
![Fish](https://img.shields.io/badge/Fish_Shell-4EAA25?style=flat-square&logo=linux&logoColor=white)

**Backend, Data & Web**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify_5-000000?style=flat-square&logo=fastify&logoColor=white)
![tRPC](https://img.shields.io/badge/tRPC_11-2596BE?style=flat-square&logo=trpc&logoColor=white)
![Zod](https://img.shields.io/badge/Zod_4-3E67B1?style=flat-square&logo=zod&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_%2B_PostGIS-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Biome](https://img.shields.io/badge/Biome-60A5FA?style=flat-square&logo=biome&logoColor=black)

**Infrastructure, DevOps & Security**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white)
![systemd](https://img.shields.io/badge/systemd_%26_cgroups-24292F?style=flat-square&logo=linux&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale_VPN-242424?style=flat-square&logo=tailscale&logoColor=white)
![TLS 1.3](https://img.shields.io/badge/TLS_1.3_%26_PKI-1F6FEB?style=flat-square&logo=letsencrypt&logoColor=white)
![OWASP ASVS L3](https://img.shields.io/badge/OWASP_ASVS_L3-000000?style=flat-square&logo=owasp&logoColor=white)
![GnuPG](https://img.shields.io/badge/GnuPG-0093DD?style=flat-square&logo=gnupg&logoColor=white)
![SSH](https://img.shields.io/badge/OpenSSH-000000?style=flat-square&logo=openssh&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark_%2F_TCPDump-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy_%2F_Lynis_%2F_Gitleaks-004B87?style=flat-square)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white)

**Operating Systems & Environments**

![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white)
![openSUSE](https://img.shields.io/badge/openSUSE-73BA25?style=flat-square&logo=opensuse&logoColor=white)
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=archlinux&logoColor=white)
![Alpine Linux](https://img.shields.io/badge/Alpine_Linux-0D597F?style=flat-square&logo=alpinelinux&logoColor=white)
![NixOS](https://img.shields.io/badge/NixOS-5277C3?style=flat-square&logo=nixos&logoColor=white)
![Fedora](https://img.shields.io/badge/Fedora-294172?style=flat-square&logo=fedora&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Termux](https://img.shields.io/badge/Termux-0C1221?style=flat-square&logo=termux&logoColor=white)

</div>

---

<div align="center">
  <sub>Finnish (Native) &middot; English (Professional) &middot; Swedish &amp; Spanish (Conversational/Basic) &middot; Connect via <a href="https://linkedin.com/in/erkka-ala-lahti/">LinkedIn</a></sub>
</div>
