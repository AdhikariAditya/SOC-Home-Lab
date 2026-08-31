# Home SOC Lab — Defensive Security Portfolio

A hands-on lab series where I build, attack, and defend my own Security Operations Center. Every project runs in an isolated VirtualBox environment and is documented end-to-end — including the troubleshooting.

## Projects

| # | Project | Status | Summary |
|---|---------|--------|---------|
| 1 | [Building the SOC Lab](./01-lab-build/) | Complete | Wazuh SIEM + Sysmon-instrumented Windows 10 endpoint |
| 2 | [Attack & Detect](./02-attack-detect/) | Complete | Kali Linux attacker box, real offensive techniques, and custom Wazuh detection rules for what the stock ruleset misses |

## Lab Stack

- **Virtualization:** Oracle VirtualBox (isolated host-only network)
- **SIEM:** Wazuh — manager, indexer, dashboard
- **Endpoint telemetry:** Sysmon with the SwiftOnSecurity configuration
- **Endpoints:** Ubuntu 22.04 (server), Windows 10 (monitored), Kali Linux (attacker)

## Why this exists

Reading about detection is not the same as watching your own SIEM light up. This repo documents the difference — each project ends with a working, validated result and the lessons learned getting there.

---

*Follow along — new projects are added as they're completed.*

*Check out my File Integrity Manager —— [AdhikariAditya/FileIntegrityManager](https://github.com/AdhikariAditya/FileIntegrityManager)*
