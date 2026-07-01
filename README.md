# Hartmut's AI Legal Team

**9 specialised AI agents for mid-market law firms.**

Open source. Sovereign. Customisable.

**Live page:** https://hartmut-ux.github.io/ai-legal-team-en/

---

## What is this?

A complete agentic team of 9 AI skills covering the key workflows of a mid-sized law firm (10–80 solicitors) — from contract analysis and compliance to business development.

No SaaS subscription. No vendor lock-in. Your data stays with you.

The skills work across **Kimi Code CLI**, **Claude Code** and **Codex CLI**.

## The 9 skills

| # | Skill | Function | Download |
|---|-------|----------|----------|
| 1 | [contract-analyst](skills/contract-analyst/) | Contract review, red flags, clause comparison (English Law + Swiss OR/ZGB) | [all](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/contract-analyst-all.zip) · [kimi](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/contract-analyst-kimi.zip) · [claude](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/contract-analyst-claude.zip) · [codex](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/contract-analyst-codex.zip) |
| 2 | [legal-researcher](skills/legal-researcher/) | Case law search, UKSC/BGer decisions, legislative tracking | [all](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/legal-researcher-all.zip) · [kimi](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/legal-researcher-kimi.zip) · [claude](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/legal-researcher-claude.zip) · [codex](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/legal-researcher-codex.zip) |
| 3 | [compliance-monitor](skills/compliance-monitor/) | GDPR UK, SRA, nDSG, GwG, FINMA, EU AI Act — incl. risk heatmap | [all](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/compliance-monitor-all.zip) · [kimi](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/compliance-monitor-kimi.zip) · [claude](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/compliance-monitor-claude.zip) · [codex](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/compliance-monitor-codex.zip) |
| 4 | [client-communicator](skills/client-communicator/) | Client letters, status updates, fee communications | [all](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/client-communicator-all.zip) · [kimi](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/client-communicator-kimi.zip) · [claude](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/client-communicator-claude.zip) · [codex](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/client-communicator-codex.zip) |
| 5 | [due-diligence-assistant](skills/due-diligence-assistant/) | M&A, real estate, restructuring — checklists + findings | [all](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/due-diligence-assistant-all.zip) · [kimi](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/due-diligence-assistant-kimi.zip) · [claude](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/due-diligence-assistant-claude.zip) · [codex](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/due-diligence-assistant-codex.zip) |
| 6 | [litigation-support](skills/litigation-support/) | Briefs, chronologies, evidence structuring, strategy memos | [all](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/litigation-support-all.zip) · [kimi](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/litigation-support-kimi.zip) · [claude](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/litigation-support-claude.zip) · [codex](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/litigation-support-codex.zip) |
| 7 | [knowledge-manager](skills/knowledge-manager/) | Knowledge base, templates, precedent search, onboarding | [all](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/knowledge-manager-all.zip) · [kimi](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/knowledge-manager-kimi.zip) · [claude](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/knowledge-manager-claude.zip) · [codex](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/knowledge-manager-codex.zip) |
| 8 | [legal-bd-marketing](skills/legal-bd-marketing/) | Firm newsletters, LinkedIn, events (SRA/BGFA compliant) | [all](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/legal-bd-marketing-all.zip) · [kimi](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/legal-bd-marketing-kimi.zip) · [claude](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/legal-bd-marketing-claude.zip) · [codex](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/legal-bd-marketing-codex.zip) |
| 9 | [practice-operations](skills/practice-operations/) | Time recording, WIP, profitability, internal comms | [all](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/practice-operations-all.zip) · [kimi](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/practice-operations-kimi.zip) · [claude](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/practice-operations-claude.zip) · [codex](https://github.com/hartmut-ux/ai-legal-team-en/releases/latest/download/practice-operations-codex.zip) |

## How to install

### Kimi Code CLI

```bash
cp -R .kimi/skills/<skill-name> ~/.kimi/skills/
```

Invoke in Kimi with `/<skill-name>`.

### Claude Code

```bash
cp -R .claude/skills/<skill-name> ~/.claude/skills/
```

Invoke in Claude with `<skill-name>`.

### Codex CLI

```bash
cp -R .codex/skills/<skill-name> ~/.codex/skills/
```

Invoke in Codex with `<skill-name>`.

## Why open source?

Enterprise Legal AI (Harvey AI, CoCounsel) is expensive and often US-hosted. This team offers a lean, sovereign alternative — you keep control of your data.

## Technology

- **Multi-platform AI skills** — Kimi Code CLI, Claude Code, Codex CLI
- **MCP** (Model Context Protocol) — Open standard by the Linux Foundation
- **Shared core + thin wrappers** — One workflow, three assistants

## Live demos

- **Liechtenstein Legal Navigator**: [udify.app/chat/ZOvDsVvUxG8fqpRH](https://udify.app/chat/ZOvDsVvUxG8fqpRH) — Built with Dify + Claude
- **Compliance Cockpit Survey**: [umfrage.compliance.mmind.ai](https://umfrage.compliance.mmind.ai/) — AI-powered compliance heatmap

## About the author

**Hartmut Hübner, PhD** combines 20 years of corporate communications in large enterprises (Siemens, financial services) with 10 years of experience in transformation, digitalisation and AI. Co-founder of several startups, including MMIND.ai. Academic background at LMU Munich and PhD from the University of Salford (thesis: *The Communicating Company*).

- 🌐 [mmind.ai](https://mmind.ai) · [MMIND.ai Marketplace](https://mmind.ai/marketplace)
- 💼 [LinkedIn](https://linkedin.com/in/hartmutplass)
- 🐙 [GitHub](https://github.com/hartmut-ux)

## Licence

MIT — Use, modify and share freely.
