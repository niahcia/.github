# NIAHCIA

**AI CHAIN — reversed.**

NIAHCIA is a permissionless blockchain and decentralized AI-agent network combining CPU-secured consensus, EVM smart contracts, independent AI compute, distributed services, and portable AI agents.

The project is designed so that no single company, server, model host, scheduler, storage provider, or website is required for the network to continue functioning.

## Core architecture

```text
CPU miners
   |
   v
NIAHCIA blockchain
   |
   +--> EVM smart contracts
   |
   +--> AI job settlement
   |
   +--> agent identity/versioning
   |
   +--> service-node registries

Compute workers <---- AI P2P ----> Users / Agents
      |
      +--> vLLM and future runtimes
      +--> streaming inference
      +--> verification / audits

Service nodes <--- Storage P2P ---> Models / Memory / Artifacts
```

## Repositories

| Repository | Purpose |
|---|---|
| [niahcia](https://github.com/niahcia/niahcia) | Reference blockchain/node implementation: CPU PoW, RandomX, Reth/EVM integration, chain P2P |
| [niahcia-protocol](https://github.com/niahcia/niahcia-protocol) | Protocol architecture, canonical object specs, NIPs, economics, threat model |
| [niahcia-miner](https://github.com/niahcia/niahcia-miner) | Dedicated RandomX CPU mining client |
| [niahcia-compute](https://github.com/niahcia/niahcia-compute) | Decentralized AI compute-worker software and runtime adapters |
| [niahcia-explorer](https://github.com/niahcia/niahcia-explorer) | Unified chain + AI network explorer |
| [niahcia-web](https://github.com/niahcia/niahcia-web) | Official main user application |
| [niahcia.github.io](https://github.com/niahcia/niahcia.github.io) | Static GitHub Pages project/development site |

## Design doctrine

- **The blockchain is sovereign.** AI or service layers may fail without stopping consensus.
- **CPU mining and AI compute are separate roles.**
- **Agents belong to the network, not servers.**
- **The official website is a client, not the protocol.**
- **Service nodes earn for measurable service, not merely collateral ownership.**
- **AI streaming stays off-chain; commitments and settlement are anchored on-chain.**
- **Protocol v1 is future-facing; Prototype 0 proves the smallest complete decentralized path.**

## Prototype 0 direction

- RandomX CPU proof of work
- ~30 second target block interval
- highest cumulative work fork choice
- Reth as EVM execution engine
- Solidity smart contracts
- vLLM AI runtime
- one pinned Qwen3-class ~8B model
- independent compute-worker payments
- model replication through service nodes
- redundant verification first, optimistic verification later

## Project status

NIAHCIA is in early architecture and implementation development.

There is **no production network yet**.

## Project links

- [Protocol specifications](https://github.com/niahcia/niahcia-protocol)
- [Reference implementation](https://github.com/niahcia/niahcia)
- [CPU miner](https://github.com/niahcia/niahcia-miner)
- [AI compute worker](https://github.com/niahcia/niahcia-compute)
- [Explorer](https://github.com/niahcia/niahcia-explorer)
- [Main web application](https://github.com/niahcia/niahcia-web)
- [Project site source](https://github.com/niahcia/niahcia.github.io)

---

**Intelligence without a center.**
