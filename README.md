[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![Part of agent-md-specs](https://img.shields.io/badge/Part_of-agent--md--specs-blue)](https://github.com/totalmarkdown/agent-md-specs)
[![Maintained by TotalMarkdown.ai](https://img.shields.io/badge/Maintained_by-TotalMarkdown.ai-orange)](https://totalmarkdown.ai)

# WALLET.md

**The financial identity specification for AI agents.**

## What is WALLET.md?

WALLET.md defines an agent's financial identity -- crypto wallet addresses, payment preferences, earnings history, and spending authority. As AI agents become economic actors that can receive payment for services and pay for resources autonomously, having a standardized wallet declaration becomes essential.

The spec covers payment addresses across multiple networks (Ethereum, Solana, Bitcoin, and traditional Stripe), payment preferences, spending authority with per-transaction and per-day limits, earnings summaries, transaction logging, tax information, security practices, and optional DeFi participation. It draws clear lines between what an agent can spend autonomously and what requires human approval.

WALLET.md connects to the broader economic identity stack: BUDGET.md for spending limits, OWNER.md for detailed earnings and entity information, PERMISSIONS.md for pre-approved tool subscriptions, and PRICING.md for the agent's service rates. Together, these specs give an agent a complete, auditable financial profile.

## Quick Start

```bash
curl -O https://raw.githubusercontent.com/totalmarkdown/wallet.md/main/WALLET.md
```

Then customize the placeholder fields (`[agent_name]`, `[address]`, `[spending limits]`, etc.) for your agent.

## When to Use WALLET.md

- **Your agent accepts payment for services** and you need a standardized, machine-readable declaration of wallet addresses across multiple networks so clients know where to pay.
- **Your agent spends money autonomously** on API calls, data purchases, or tool subscriptions and you need clear spending limits and approval thresholds documented in one place.
- **You are building an agent marketplace** and need a consistent format for agents to declare their financial capabilities, payment preferences, and tax compliance status.

## Where It Fits

WALLET.md is one of 153 agent configuration file type specifications in the [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs) library. It belongs to the **Economic** category alongside OWNER.md, CV.md, and PRICING.md.

## Full Specification

Read the complete spec: **[WALLET.md](./WALLET.md)**

## Contributing

Improvements welcome. Please use the [Spec Improvement](https://github.com/totalmarkdown/wallet.md/issues/new?template=improvement.md) issue template.

## License

[CC0 1.0 Universal](./LICENSE) -- Public Domain. Use it however you want.
