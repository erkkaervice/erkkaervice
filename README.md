<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./assets/header-light.svg">
    <img alt="Erkka Ala-Lahti — Software Developer, Systems and IT Operations" src="./assets/header-dark.svg" width="100%">
  </picture>
  <p>
    Helsinki, Finland &middot;
    <a href="https://linkedin.com/in/erkka-ala-lahti/">LinkedIn</a> &middot;
    Ervice Oy
  </p>
</div>

---

### Professional Profile

I bridge the gap between complex technical infrastructure and pragmatic business requirements. Following an extensive career in entrepreneurship and operational leadership, I graduated from **Hive Helsinki** to turn a lifelong passion for Linux and systems engineering into a profession.

I build hardened, reliable systems — from low-level network protocols and Linux infrastructure to full-stack TypeScript platforms and governed AI-assisted engineering workflows — always keeping functional reliability and real-world usability at the center. Operating through **Ervice Oy**, I am open to freelance engagements, contract assignments, and full-time engineering roles, negotiated case-by-case.

---

### Technical Skills

- **Languages:** C, C++, TypeScript, JavaScript, Python, SQL, Shell Scripting (Bash, Zsh, Fish)
- **Backend, Web & Databases:** Node.js, Fastify, tRPC, Zod, React, Next.js, PostgreSQL, PostGIS, Drizzle ORM, MariaDB, Prisma ORM
- **DevOps & Infrastructure:** Linux (Debian, openSUSE, Arch, Alpine, NixOS, Fedora), systemd, Docker, Docker Compose, NGINX, Tailscale, Git, GNU Make
- **Security & Quality:** OWASP ASVS, TLS & PKI, OpenSSH & GnuPG Hardening, Network Isolation, SAST & Secret Scanning, Automated Testing
- **Networking & Diagnostics:** TCP/IP, HTTP/1.1, Sockets, I/O Multiplexing, Subnetting, Routing, Wireshark, TCPDump, Nmap, Valgrind
- **AI & Workflow Automation:** Multi-model LLM orchestration, deterministic security and test guardrails, CI/CD automation

---

### Key Technical Projects

#### Event & Streaming Platform *(Private — Ervice Oy)*
*Full-Stack Architecture, Offline-First PWA & Live Media*
- **The Challenge:** Designing a resilient, multi-tenant event platform that works reliably without cellular coverage at festivals while also supporting low-latency ticketed video streams and continuous background radio.
- **The Solution:** Architected a TypeScript monorepo using **Fastify**, **tRPC**, **Zod**, **PostgreSQL/PostGIS**, **Drizzle ORM**, **MediaMTX**, and an offline-first foldable PWA, hardened with Fail-Closed admin authentication, constant-time HMAC signing, and SSRF protection.
- **Competency:** End-to-end TypeScript architecture, geospatial data modeling, media streaming pipelines, and OWASP-aligned security design.

#### Self-Hosted AI Engineering Platform *(Private — Ervice Oy)*
*Multi-Model Orchestration, Guardrails & Constrained-Hardware Operations*
- **The Challenge:** Accelerating software maintenance, testing, and refactoring using multiple LLM providers on constrained, self-hosted Debian hardware without compromising security or code quality.
- **The Solution:** Engineered a self-hosted **Node.js** orchestration and telemetry platform (`systemd`, `cgroups`, `zram`, TLS, Tmux web terminal) that coordinates multiple AI providers behind deterministic SAST, secret-scanning, path-containment, and drift-verification gates, with human review before every merge.
- **Competency:** Resilient Linux systems administration, AI workflow governance, defensive security automation, and real-time telemetry.

#### [.dotfiles](https://github.com/erkkaervice/.dotfiles)
*Cross-Platform Shell Parity & Environment Hardening*
- **The Challenge:** Maintaining identical security tooling, shell ergonomics, and non-root compatibility across disparate operating systems (Debian, openSUSE, Arch, Alpine, NixOS, Fedora, macOS, Termux).
- **The Solution:** Built a unified **Bash/Zsh** and **Fish** configuration ecosystem with **OpenSSH/GnuPG** hardening, responsive Tmux defaults, and automated parity and secret-leak test suites.
- **Competency:** Cross-platform Unix engineering, security-first configuration management, and test-driven shell automation.

#### [hive-webserv](https://github.com/erkkaervice/hive-webserv) *(Public)*
*Network Engineering & Protocol Implementation*
- **The Challenge:** Managing concurrent client connections and HTTP traffic without high-level frameworks.
- **The Solution:** Engineered a functional **HTTP/1.1** server in **C++** from scratch focusing on non-blocking sockets and I/O multiplexing (`poll`/`select`).
- **Competency:** RFC protocol adherence, socket programming, and low-level network performance.

#### [hive-transcendence](https://github.com/erkkaervice/hive-transcendence) *(Public)*
*Full-Stack Architecture & Real-Time Systems*
- **The Challenge:** Delivering a real-time, multi-user web application with centralized authentication and a containerized backend while coordinating team delivery.
- **The Solution:** Developed a Single Page Application using **TypeScript**, **Next.js**, **MariaDB**, and **Docker**, serving as **Product Owner** to drive shared architecture and execution.
- **Competency:** Full-stack integration, real-time synchronization, and technical team coordination.

#### [hive-inception](https://github.com/erkkaervice/hive-inception) *(Public)*
*Container Orchestration & System Administration*
- **The Challenge:** Orchestrating a secure, multi-tier web stack with persistent storage and strict network isolation.
- **The Solution:** Built a multi-container **Docker** infrastructure (**NGINX**, **WordPress**, **MariaDB**) from base Alpine/Debian images with TLS termination and isolated networks.
- **Competency:** Container hardening, network isolation, volume persistence, and service orchestration.

*Source walkthroughs and live demonstrations of private Ervice Oy systems are available during technical interviews.*

<!-- AUTO-COLLAB:START -->
<!-- AUTO-COLLAB:END -->

---

### Operational Seniority & Technical Pivot

**Business Operations & Rollouts**
Founded and led businesses across hospitality, events, coaching, and manufacturing. Coordinated nationwide digital kitchen management system rollouts (**Koutsit**) and executed customer migrations, account configuration, data validation, and independent technical support (**TableOnline**) — bridging software providers and end-users under operational pressure.

**Systems Engineering & Community IT**
Graduate of **Hive Helsinki**'s peer-to-peer curriculum, grounded in low-level C/C++ and Unix fundamentals. Also serve as Volunteer IT Specialist and Vice Board Member for **FSE**, managing end-to-end infrastructure (Moodle server, WordPress sites, web hosting, Netvisor and Paytrail integrations) and building an on-site information security training program for students in Tanzania.

---

### Contact & Collaboration

- **Availability:** Freelance via **Ervice Oy** — open to contract assignments and full-time roles in **Software Engineering, DevOps, or IT Infrastructure** (case-by-case).
- **Primary Channel:** [LinkedIn](https://linkedin.com/in/erkka-ala-lahti/) *(GitHub serves as my technical portfolio; connect on LinkedIn for roles and collaborations)*.
- **Languages:** Finnish (Native), English (Professional), Swedish & Spanish (Conversational / Basic).

---

<div align="center">
  <h3>Core Tech Stack</h3>

  <p>
    <img src="https://img.shields.io/badge/C-161b22?style=flat-square&logo=c&logoColor=A8B9CC" alt="C">
    <img src="https://img.shields.io/badge/C%2B%2B-161b22?style=flat-square&logo=cplusplus&logoColor=00599C" alt="C++">
    <img src="https://img.shields.io/badge/TypeScript-161b22?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript">
    <img src="https://img.shields.io/badge/JavaScript-161b22?style=flat-square&logo=javascript&logoColor=F7DF1E" alt="JavaScript">
    <img src="https://img.shields.io/badge/Python-161b22?style=flat-square&logo=python&logoColor=3776AB" alt="Python">
    <img src="https://img.shields.io/badge/SQL-161b22?style=flat-square&logo=postgresql&logoColor=4169E1" alt="SQL">
    <img src="https://img.shields.io/badge/Bash-161b22?style=flat-square&logo=gnubash&logoColor=4EAA25" alt="Bash">
    <img src="https://img.shields.io/badge/Zsh-161b22?style=flat-square&logo=gnubash&logoColor=E2E8F0" alt="Zsh">
    <img src="https://img.shields.io/badge/Fish-161b22?style=flat-square&logo=linux&logoColor=38BDF8" alt="Fish">
  </p>

  <p>
    <img src="https://img.shields.io/badge/Node.js-161b22?style=flat-square&logo=nodedotjs&logoColor=339933" alt="Node.js">
    <img src="https://img.shields.io/badge/Fastify-161b22?style=flat-square&logo=fastify&logoColor=FFFFFF" alt="Fastify">
    <img src="https://img.shields.io/badge/tRPC-161b22?style=flat-square&logo=trpc&logoColor=2596BE" alt="tRPC">
    <img src="https://img.shields.io/badge/Zod-161b22?style=flat-square&logo=zod&logoColor=3E67B1" alt="Zod">
    <img src="https://img.shields.io/badge/React-161b22?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
    <img src="https://img.shields.io/badge/Next.js-161b22?style=flat-square&logo=nextdotjs&logoColor=FFFFFF" alt="Next.js">
    <img src="https://img.shields.io/badge/PostgreSQL-161b22?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL">
    <img src="https://img.shields.io/badge/Drizzle_ORM-161b22?style=flat-square&logo=drizzle&logoColor=C5F74F" alt="Drizzle ORM">
    <img src="https://img.shields.io/badge/MariaDB-161b22?style=flat-square&logo=mariadb&logoColor=38BDF8" alt="MariaDB">
    <img src="https://img.shields.io/badge/Prisma-161b22?style=flat-square&logo=prisma&logoColor=FFFFFF" alt="Prisma">
  </p>

  <p>
    <img src="https://img.shields.io/badge/Docker-161b22?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker">
    <img src="https://img.shields.io/badge/NGINX-161b22?style=flat-square&logo=nginx&logoColor=009639" alt="NGINX">
    <img src="https://img.shields.io/badge/systemd-161b22?style=flat-square&logo=linux&logoColor=FCC624" alt="systemd">
    <img src="https://img.shields.io/badge/Tailscale-161b22?style=flat-square&logo=tailscale&logoColor=FFFFFF" alt="Tailscale">
    <img src="https://img.shields.io/badge/Git-161b22?style=flat-square&logo=git&logoColor=F05032" alt="Git">
    <img src="https://img.shields.io/badge/GNU_Make-161b22?style=flat-square&logo=gnu&logoColor=E2E8F0" alt="GNU Make">
    <img src="https://img.shields.io/badge/Biome-161b22?style=flat-square&logo=biome&logoColor=60A5FA" alt="Biome">
    <img src="https://img.shields.io/badge/Neovim-161b22?style=flat-square&logo=neovim&logoColor=57A143" alt="Neovim">
    <img src="https://img.shields.io/badge/Valgrind-161b22?style=flat-square" alt="Valgrind">
  </p>

  <p>
    <img src="https://img.shields.io/badge/OWASP_ASVS-161b22?style=flat-square&logo=owasp&logoColor=FFFFFF" alt="OWASP ASVS">
    <img src="https://img.shields.io/badge/TLS_%2F_PKI-161b22?style=flat-square&logo=letsencrypt&logoColor=38BDF8" alt="TLS / PKI">
    <img src="https://img.shields.io/badge/OpenSSH-161b22?style=flat-square&logo=openssh&logoColor=E2E8F0" alt="OpenSSH">
    <img src="https://img.shields.io/badge/GnuPG-161b22?style=flat-square&logo=gnupg&logoColor=0093DD" alt="GnuPG">
    <img src="https://img.shields.io/badge/Wireshark-161b22?style=flat-square&logo=wireshark&logoColor=1679A7" alt="Wireshark">
    <img src="https://img.shields.io/badge/TCPDump-161b22?style=flat-square" alt="TCPDump">
    <img src="https://img.shields.io/badge/Nmap-161b22?style=flat-square" alt="Nmap">
    <img src="https://img.shields.io/badge/Lynis-161b22?style=flat-square" alt="Lynis">
    <img src="https://img.shields.io/badge/Trivy-161b22?style=flat-square" alt="Trivy">
    <img src="https://img.shields.io/badge/Gitleaks-161b22?style=flat-square" alt="Gitleaks">
  </p>

  <p>
    <img src="https://img.shields.io/badge/Debian-161b22?style=flat-square&logo=debian&logoColor=A81D33" alt="Debian">
    <img src="https://img.shields.io/badge/openSUSE-161b22?style=flat-square&logo=opensuse&logoColor=73BA25" alt="openSUSE">
    <img src="https://img.shields.io/badge/Arch_Linux-161b22?style=flat-square&logo=archlinux&logoColor=1793D1" alt="Arch Linux">
    <img src="https://img.shields.io/badge/Alpine_Linux-161b22?style=flat-square&logo=alpinelinux&logoColor=0D597F" alt="Alpine Linux">
    <img src="https://img.shields.io/badge/NixOS-161b22?style=flat-square&logo=nixos&logoColor=5277C3" alt="NixOS">
    <img src="https://img.shields.io/badge/Fedora-161b22?style=flat-square&logo=fedora&logoColor=51A2DA" alt="Fedora">
    <img src="https://img.shields.io/badge/Ubuntu-161b22?style=flat-square&logo=ubuntu&logoColor=E95420" alt="Ubuntu">
    <img src="https://img.shields.io/badge/Kali_Linux-161b22?style=flat-square&logo=kalilinux&logoColor=557C94" alt="Kali Linux">
    <img src="https://img.shields.io/badge/macOS-161b22?style=flat-square&logo=apple&logoColor=FFFFFF" alt="macOS">
    <img src="https://img.shields.io/badge/Termux-161b22?style=flat-square&logo=termux&logoColor=34D399" alt="Termux">
  </p>
</div>
