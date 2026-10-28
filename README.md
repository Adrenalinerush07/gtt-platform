<div align="center">

# GTT Platform

### Your guide to the product, the crypto and the code.

**Business understanding → Technical understanding → Confident project handover**

[Start with the business guide](docs/BUSINESS_ANALYSIS.md) · [Explore the architecture](docs/TECHNICAL_ARCHITECTURE.md)

</div>

---

> [!IMPORTANT]
> **Know what you are looking at.** This repository currently contains documentation for a restricted developer review package. Sixteen proprietary modules were deliberately stripped from that package, and live trading workflows are blocked. The application source has not been uploaded here.

## Choose your starting point

| | Guide | What you will learn |
| :---: | :--- | :--- |
| 💼 | **[Business Analysis & Crypto Beginner Guide](docs/BUSINESS_ANALYSIS.md)** | What GTT provides, who uses it, crypto fundamentals, customer journeys, plans, GTT Coins and actual feature availability |
| ⚙️ | **[Technical Architecture & Developer Handover](docs/TECHNICAL_ARCHITECTURE.md)** | Frontend and backend structure, data models, APIs, security, integrations, workers, setup, verification limits and engineering priorities |

**New to the project?** Read the business guide first. Its worked examples explain the terms used throughout the technical guide.

## The product in one minute

GTT — branded **Gujju The Trader** in the billing configuration — brings market research, strategy exploration, simulated trading, portfolio visibility and paid tools into one application. The intended longer-term journey includes automation in a customer’s own exchange account.

| Keep these separate | What it means |
| :--- | :--- |
| **Exchange funds** | Real capital held in a customer’s external trading account |
| **Paper capital** | Simulated money used to measure hypothetical trading results |
| **GTT Coins** | Internal software credits used for metered features |

Buying GTT Coins does not fund an exchange account, and simulated profits are not withdrawable funds.

## What is inside

- **Two detailed guides** written in simple language, with source references.
- **Ten Mermaid diagrams** covering the product ecosystem, approvals, customer journeys, payments, architecture, data relationships and execution flows.
- **Worked examples** for leverage, margin and options.
- **Feature-status tables** distinguishing implemented code, missing engines, external dependencies and future capabilities.
- **A practical handover plan** with client questions, engineering findings and suggested acceptance stages.

## How to read the evidence

| Label or statement | Interpretation |
| :--- | :--- |
| **Implemented code** | Source implementation exists; this does not imply a verified live deployment |
| **Stubbed / removed** | Function signatures remain, but the proprietary implementation was deliberately omitted |
| **Legacy-dependent** | Data or behavior relies on the original application outside the supplied package |
| **Planned / intended** | Describes a target capability, not a delivered feature |
| **Static finding** | Derived from reading source; runtime reproduction is still required |
| **Repository defaults** | Values in the reviewed code; administrators or deployments may override them |

> [!TIP]
> GitHub renders the diagrams directly in these Markdown files. The Mermaid source remains editable, so architecture changes can be reviewed alongside documentation changes.

## Review scope

| | |
| :--- | :--- |
| **Audience** | Kartik and developers joining the freelance project |
| **Source package** | Developer review copy prepared on 25 September 2026 |
| **Analysis date** | 29 October 2026 |
| **Method** | Source inspection, documentation reconciliation and official references for crypto terminology |
| **Not performed** | Test/build execution, production inspection, real-account access, payment processing or live trading |

Source paths inside the guides refer to the original application package. They are kept as code references rather than broken links to files that have not been uploaded.

---

<div align="center">

**Start with the product. Follow the data. Verify the boundaries.**

[Business & crypto →](docs/BUSINESS_ANALYSIS.md) · [Technical architecture →](docs/TECHNICAL_ARCHITECTURE.md)

</div>
