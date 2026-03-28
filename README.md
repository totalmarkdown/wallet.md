# WALLET.md

> *Defines an AI agent's financial identity — budgets, payment methods, and spending authority*

[![License: CC0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Part of agent-md-specs](https://img.shields.io/badge/part%20of-agent--md--specs-blue)](https://github.com/totalmarkdown/agent-md-specs)
[![Maintained by TotalMarkdown](https://img.shields.io/badge/maintained%20by-TotalMarkdown.ai-8B5CF6)](https://totalmarkdown.ai)

**Maintained by TotalMarkdown.ai**
· License: CC0 1.0 Universal — Public Domain
· Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
· [Discussions](https://github.com/totalmarkdown/wallet.md/discussions)

> TotalMarkdown.ai is currently in development. Star this repo to follow progress.

---

## What is WALLET.md?

WALLET.md defines an agent's financial identity across both traditional
finance and decentralized finance. It specifies budgets, spending limits,
payment methods, wallet addresses, and the authority an agent has to
make financial decisions autonomously.

AI agents increasingly need financial identity — not just for enterprise
billing, but for autonomous transactions. In the emerging agent economy,
agents hire other agents, pay for API access, and manage budgets
autonomously. WALLET.md provides the structured, auditable financial
identity that makes this possible.

Without WALLET.md, an agent with financial authority is a liability.
WALLET.md constrains spending, defines approval thresholds, and ensures
financial actions are auditable. It's the difference between an agent
with a corporate card and an agent with a blank check.

---

## Quick Start

```bash
curl -O https://raw.githubusercontent.com/totalmarkdown/wallet.md/main/WALLET.md
```

Add to your project root and customize for your agent.

---

## When to use WALLET.md

- Setting spending limits for an agent that purchases API calls or cloud resources
- Defining budget allocation for an agent that hires sub-agents for specialized tasks
- Establishing payment and billing identity for an agent operating in a marketplace
- Configuring on-chain wallet addresses for DeFi or crypto-native agents
- Enabling agent-to-agent payments in multi-agent systems

## Example Use Cases

**Enterprise:** An agent managing cloud infrastructure has a WALLET.md
linked to the company's AWS billing account with a $10,000/month cap
and automatic degradation to cached results when budget reaches 90%.

**Crypto/DeFi:** A DeFi trading agent holds an on-chain wallet address
with authorized token types, transaction limits, and approved smart
contracts defined in WALLET.md — never storing private keys directly.

**Agent Economy:** Agent A hires Agent B via HIREME.md and pays per
task using the wallet credentials defined in each agent's WALLET.md,
with all transactions logged to AUDITTRAIL.md.

---

## Where it fits

Works with HIREME.md (engagement terms), PRICING.md (service pricing), and BUDGET.md (detailed budget management). Part of the economic identity stack alongside CV.md and OWNER.md. Referenced by AGENTS.md.

---

## The Full Spec

→ [WALLET.md](./WALLET.md)

---

## Part of agent-md-specs

One of 178 specs in [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
— the open standard library covering every dimension of AI agent configuration.

---

## Contributing

1. Open an issue describing your proposed change
2. Fork and make your edit
3. Open a PR — all contributions must be CC0

---

## License

[CC0 1.0 Universal](./LICENSE) — Public Domain.
Use freely for any purpose, no attribution required.

---

*Maintained by TotalMarkdown.ai*
*Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)*
