# Cross-Platform Shell & Security Environment (.dotfiles) — Overview

*Private repository — Ervice Oy (Helsinki, Finland)* · [Back to Profile](../README.md)

A unified, test-verified shell, terminal, and security toolkit engineered for strict feature parity across **Bash**, **Zsh**, and **Fish** on eight operating system families — including non-root environments.

## Core Design

- **Multi-OS Portability:** Tested across Debian/Ubuntu, openSUSE, Arch, Fedora, NixOS, Alpine, macOS, and Termux with automatic `~/.local/bin` fallback when running without root privileges.
- **Shell Parity Contract:** Shared command semantics and ergonomics across `.sh_common` (Bash/Zsh) and `.config.fish` (Fish), including responsive Tmux defaults and cross-platform file/URL helpers.
- **Security Tooling & Hardening:** Opinionated OpenSSH and GnuPG defaults, TLS certificate inspection helpers (`cert-check`, `local-https-check`), and local security audit wrappers (`sec-scan`).
- **Automated Verification:** 77 passing `node:test` cases mocking OS/PATH matrices, paired with a deterministic portability-drift and secret-leak gate.

*Kept private while host-specific network parameters are externalized; walkthroughs available on request.*
