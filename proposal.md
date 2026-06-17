> ℹ️ **Have feedback?** This proposal is open for community input before it goes on-chain for vote. Submit yours via our [feedback form](https://docs.google.com/forms/d/e/1FAIpQLSeqrk8mv2xiAI3ii2tZeB8e-ej9zGZL4-bLzVdYj7w6cNfghw/viewform).

# Blockfrost's Transformation to Not-for-Profit

## Introduction

Blockfrost is the lingua franca of Cardano. It lets developers read from and interact with the Cardano blockchain through a simple, hosted REST interface — without having to run and maintain their own node. By providing an abstraction layer over raw blockchain data, Blockfrost removes the operational complexity of building on Cardano, so teams can focus on their applications instead of their infrastructure.

Blockfrost was founded in 2020 by Five Binaries and joined IOG in 2024 with the goal of decentralizing it.

---

## Current Usage Metrics

According to the annual [*State of the Cardano Developer Ecosystem*](https://cardano-foundation.github.io/state-of-the-developer-ecosystem) survey hosted by the Cardano Foundation, Blockfrost is the **number-one hosted platform** developers use in their projects, and its adoption has grown every year:

| Year | Adoption |
|------|----------|
| [2022](https://cardano-foundation.github.io/state-of-the-developer-ecosystem/2022/) | 39.3%    |
| [2023](https://cardano-foundation.github.io/state-of-the-developer-ecosystem/2023/) | 56.5%    |
| [2024](https://cardano-foundation.github.io/state-of-the-developer-ecosystem/2024/) | 65.5%    |
| [2025](https://cardano-foundation.github.io/state-of-the-developer-ecosystem/2025/) | 71.5%    |

Last month alone, Blockfrost served **781k unique visitors** across more than **1.84 billion API requests** — almost 700 rps — and delivered over **7 TB of API data**.

In most Cardano epochs, more than **50% of all transactions** are submitted through Blockfrost. This was the impetus to begin decentralizing Blockfrost last year, with a mandate from the community. Since then, more than **100 Icebreakers** — decentralized Blockfrost operators — have joined the effort.

---

## The Transformation to Not-for-Profit

Since day one, our primary mission has been to support Cardano ecosystem developers and, most importantly, to onboard new ones. At present, **90% of all Cardano traffic** served through the Blockfrost API comes from the free tier, and it has been challenging to leverage the commercial model to finance this public-good operation.

We have come to a decision: we can go either fully commercial or fully public-good, but not both at the same time. The commercial path would inevitably harm adoption, as it would force us to raise prices, eliminate the free tier, and take similar steps. Given Blockfrost's importance as a critical infrastructure component, we decided this would do more harm to the ecosystem than we are willing to accept. An earlier Blockfrost proposal was not funded, and we took the feedback to heart — particularly the community's hesitation around the treasury supporting a commercial venture — and have reshaped our approach accordingly.

Therefore, we would like to ask the community to support transitioning Blockfrost into a **fully not-for-profit, community-governed public API of Cardano**.

The not-for-profit will provide an open, free, public API to everyone, covering the Cardano **mainnet**, **preview**, and **preprod** networks in their current format.

---

## Governance

The not-for-profit governance of Blockfrost will be led by a **board approved by the community**, with a mandate to negotiate and lead the future of Blockfrost. The legal and organizational structure — whether a newly formed entity or integration into an existing open-source not-for-profit organization (with PRAGMA being the candidate currently under consideration) — will be determined during the formation process in consultation with the preliminary board and legal counsel, with the goal of minimizing overhead and maximizing credibility and community trust.

The board will have **five seats**. Four are dedicated to open-source infrastructure development entities (any company focused on Cardano infrastructure with an open-source history), and one is a community seat open to anyone, to provide proper transparency and oversight. We hope to run the elections by the end of the year, with the new board appointed no later than the **end of Q1 2027**.

### Preliminary Board

To set up the not-for-profit and guide it through a successful transition to the board election, a preliminary board will be appointed:

- **Beatrice Anihiri / Bee** (chair)
- NOTE: All other members of the preliminary board are in discussion and we encourage the community to nominate people to it. We would like to see mostly people with open-source infrastructure experience.

During the first year of operation, **IOG will hold a non-voting, purely advisory seat** to help ensure a successful transition.

### Transparency

The infrastructure costs of running the Blockfrost service will be shared and approved by the board, with a **public dashboard** showing current Blockfrost usage. All Blockfrost intellectual property — including source code, trademarks, domain names, and associated assets — will be **transferred to the governing not-for-profit entity**, whether newly formed or existing, as part of the transition.

---

## Path to Sustainability

Decisions about long-term sustainability beyond the 18-month funding period will rest with the community-led board and will need to adapt to market and ecosystem conditions.

We propose that the board first consider **adding a commercial offering alongside the free public API**, operated by the not-for-profit itself, with all future revenue returned to the Cardano Treasury. The not-for-profit would offer paid tiers — with dedicated SLAs and infrastructure — under community governance, with pricing decisions remaining under the oversight of the community-elected board, ensuring the commercial arm never undermines the free public good. In effect, the treasury's initial support becomes an investment: the ecosystem funds the transition, and commercial proceeds flow back to the community that financed it, with revenue and costs verifiable through the public dashboard and quarterly reports. Over time, commercial revenue should offset the cost of running the free tier, eliminating the need for further treasury funding.

The board could also consider a **vendor-backed not-for-profit model**. The not-for-profit would continue to run the free-tier public API and retain ownership of all Blockfrost intellectual property, while coordinating the product's development within a broader vendor ecosystem.

An open set of vendors, acting as official partners of the not-for-profit, would serve commercial needs beyond the free tier: any qualifying party could join, offer services on top of the public API under their own terms, and pay membership fees to the not-for-profit. Users who need a commercial solution would choose from a published list of partner vendors and negotiate directly.

The vendors could also jointly provide the technical infrastructure behind the public API itself, operating it as a **federated network of operators**. We hope many currently serving Icebreakers take on this role too, as they bring extensive experience running Blockfrost products.

Neither model is novel: similar structures have proven successful in other ecosystems, such as **Drupal** and **OpenStreetMap**. Both keep the public good free and community-governed while building a revenue stream that does not depend on continued treasury funding.

---

## Deliverables

| Timeline | Milestone | Description |
|----------|-----------|-------------|
| Q3 2026 | **Milestone 1: Entity establishment & transition kickoff** | Not-for-profit entity legally established (or host-organization agreement signed) under the preliminary board; technical transition architecture and migration plan published for community review; public usage dashboard live. |
| Q4 2026 | **Milestone 2: Board election** | Board election held via on-chain voting under publicly published rules; results verifiable on-chain and the newly elected board formally assumes its mandate from the preliminary board. |
| Q1 2027 | **Milestone 3: Transition of services** | All public API traffic (mainnet, preview, preprod) served by the new stack; all Blockfrost intellectual property — source code, trademarks, domain names, and associated assets — legally transferred to the governing entity; service performance maintained at current levels throughout the cutover. |
| Q2–Q3 2027 | **Milestone 4: Sustainability consultation** | The newly elected board opens a public discussion on the long-term sustainability model, publishes a proposal (including the vendor-backed model outlined in this document) for community feedback, and documents the outcomes and chosen direction. |
| 2027 | **Operational milestones 5–12: Sustained operations** | Public API operated at a minimum 99% monthly uptime SLA, measured and verifiable on the public dashboard; quarterly reports published covering technical metrics and budget summary. Each monthly milestone is independently verifiable against the published dashboard data. |

---

## Budget Allocation

The total funding requested for this proposal is **1,868,266 USD**, to be disbursed in ADA at a conversion rate of **0.19 USD per ADA** — a total of **9,832,979 ADA** for 18 months of operations (including the transition period).

> Any unspent post-transition infrastructure budget will be returned to the treasury. The board will publish a **quarterly report** including technical data and a budget summary.

| Component | Weight | Allocation (USD) | Allocation (ADA) |
|-----------|--------|-----------------|-----------------|
| Staffing | 79.1% | $1,478,266 | 7,780,347 |
| Ops & Infrastructure | 19.3% | $360,000 | 1,894,737 |
| Legal & Accounting | 1.6% | $30,000 | 157,895 |
| **TOTAL** | **100%** | **$1,868,266** | **9,832,979** |

The **Staffing** budget includes salaries and overhead for a team of six: one project manager, one community manager, and four developers. The team will deliver the technical transition and cover the ongoing maintenance and development of the product after the transition period, and may explore future directions aligned with the broader vision as capacity allows.

The **Ops & Infrastructure** budget covers the **entire infrastructure stack** — compute, hosting, and tooling, along with the DevOps personnel who monitor and operate it — at an expected cost of approximately $20,000 per month.

The **Legal & Accounting** budget covers legal fees and the costs of establishing the not-for-profit entity or migrating existing services to it, including the transfer of intellectual property.
