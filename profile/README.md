<div align="center">

<!-- Banner: upload profile/banner.png (1280x320), then uncomment the line below -->
<!-- <img src="https://raw.githubusercontent.com/StructuPath/.github/main/profile/banner.png" alt="StructuPath.AI" width="100%" /> -->

# StructuPath.AI

### AI automation for the steel industry

Estimating, bidding, project controls, and cash flow — built by a fabricator, for fabricators.

[![Website](https://img.shields.io/badge/structupath.ai-0A0A0A?style=flat-square&logo=googlechrome&logoColor=white)](https://www.structupath.ai)
[![Herdr Suite](https://img.shields.io/badge/herdr.structupath.ai-0A0A0A?style=flat-square)](https://herdr.structupath.ai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/109890147)

</div>

---

## Why we exist

Most construction software is built by people who have never priced a job, never chased a mill order, and never had to make payroll on a Friday.

We build from the other side. StructuPath is run out of an AISC-certified fabrication and erection shop in Denver — robotic welder, real tonnage out the door every week. Every tool in this org was built to solve a problem that was costing us money that week, then hardened until it was good enough to hand to someone else.

If it's public here, it runs in production somewhere.

## What we build

| Product | What it does |
|---|---|
| **[SteelCFO](https://github.com/StructuPath/SteelCFO)** | Financial command center for steel contractors — job costing, 13-week cash forecasting, AR/AP, risk scoring, AI analysis |
| **[IronForge](https://github.com/StructuPath/IronForge)** | 50-state wizard for ironworkers going independent — LLC formation, licensing, bonding, insurance, union signatory |
| **[pi-steel](https://github.com/StructuPath/pi-steel)** | Structural steel estimating as agent skills — AISC takeoffs, BOMs, tonnage roll-ups, vendor RFQs |
| **[Bid Extractor](https://github.com/StructuPath/Bid-Extractor)** | Pulls RFQ data out of Gmail, Outlook, BuildingConnected, PlanHub, and Procore, scores it by priority, processes locally |

Our largest build is an operating system a structural steel contractor runs daily work on — model coordination, shop production, quality evidence, field execution, procurement, and project controls. It isn't public, but it's the reason the public repos work the way they do.

## The infrastructure underneath

Shipping this much software with a small team meant building our own tooling for running coding agents. We open-sourced it.

| Tool | What it does |
|---|---|
| **[herdr-swarm](https://github.com/StructuPath/herdr-swarm)** | Parallel coding agents on one repo, safely — worktree-per-agent fan-out, live change visibility, review-first harvest |
| **[herdr-browser](https://github.com/StructuPath/herdr-browser)** | Drivable agent-browser pane with live streaming, real interaction, console capture, and recording |
| **[herdr-guard](https://github.com/StructuPath/herdr-guard)** | Cross-agent command policy — audit, alert, and interrupt dangerous shell commands |
| **[herdr-conductor](https://github.com/StructuPath/herdr-conductor)** | Orchestrate a feature-delivery team as visible agent panes |
| **[bullpen](https://github.com/StructuPath/bullpen)** | Durable agent harness in Rust — resumable sessions, crash recovery, sandboxed execution, hierarchical delegation |
| **[jig](https://github.com/StructuPath/jig)** | Local-first software factory — repeatable phased agent workflows across Git repos |

Full suite and docs at **[herdr.structupath.ai](https://herdr.structupath.ai)**.

## Free, no signup

Reference tools we got tired of looking up. No email gate, no account.

- **[Steel gauge chart](https://www.structupath.ai/tools/steel-gauge-chart)**
- **[Plate weight calculator](https://www.structupath.ai/tools/steel-plate-weight-calculator)**
- Structural shape weights — 1,004 AISC shapes
- Connection reference

More at **[structupath.ai/tools](https://www.structupath.ai/tools)**.

## Work with us

- **Custom automation builds** — scoped to your shop, your ERP, your workflow
- **Frontier model environments** — Claude, ChatGPT, Gemini, and Grok wired into how your team actually works
- **Private on-premise deployment** — for shops whose drawings and financials cannot leave the building

**[Book a consult →](https://www.structupath.ai)**

## Contact

Questions, issues, or partnership: open an issue on the relevant repo, or reach us at **DEV@StructuPath.ai**.

## License

Licensing varies by project — most are MIT, IronForge is AGPL-3.0. Check the `LICENSE` file in each repo.

---

<div align="center">
<sub>Built in Denver, Colorado — from the shop floor, not a coffee shop.</sub>
</div>
