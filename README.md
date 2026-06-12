# Nikola Kisel

**CTO @ [FLIPgo](https://flipgo.tv) - real-time on-chain data streaming · ex-Glassnode · Rust · Solana · Go**

I build the layer between node internals and live products: real-time blockchain data infrastructure. Currently building [FLIPgo](https://flipgo.tv) - a live-streaming platform with real-time on-chain trading data (Hyperliquid, Ethereum, Solana, Base, BSC and more L2s). Before that, 3.5 years at Glassnode: node-level extraction (GETH/Erigon), ingestion pipelines handling millions of on-chain events per day, and streaming systems with separated control and data planes.

[LinkedIn](https://www.linkedin.com/in/niklone/) · [Web](https://nikl.one)
---

## On-chain / Solana

- **[redio-contract](https://github.com/ic-n/redio-contract)** - Solana escrow program (Rust/Anchor) for instant USDC affiliate payouts: deterministic settlement, SDK, integration tests, Shopify/WooCommerce plugins. Live at [redio.app](https://redio.app). 3rd place, Superteam Buildstation 2025.
- **[flipgo-sol](https://github.com/ic-n/flipgo-sol)** - open-source Solana programs behind [flipgo.tv](https://flipgo.tv): live streaming with real-time on-chain trading data.
- **[ye](https://github.com/ic-n/ye)** - Jest mock for `@triton-one/yellowstone-grpc` that emits real serialized on-chain data (SPL token account layouts, Metaplex metadata), so tests exercise the full parse pipeline - not just the app logic after parsing.
- **[getblock-workshop](https://github.com/ic-n/getblock-workshop)** - demo from the Yellowstone gRPC workshop I ran for GetBlock: indexes per-wallet hold duration for an NFT mint and computes token allocations from it. Fully testable offline against the `ye` mock - no live RPC required.
- **[sage](https://github.com/ic-n/sage)** - on-chain IP registry: register intellectual property on Solana, spin up AI agents that govern it, license it to people, and lease it to other agents via x402 payments. [thesage.cc](https://thesage.cc)
- **[Solrover](https://solrover.xyz)** - fully on-chain multiplayer survival game (solo project): on-chain token economy with resource tokens, AMM/CLMM liquidity, and player-owned yield-generating factories. Satellite repos: [solrover-market](https://github.com/ic-n/solrover-market) - experimental Rust implementation of Toly's percolator for the in-game market · [airpregame](https://github.com/ic-n/airpregame) - three.js balloon-battle raffle with on-chain payout · [mintzilio](https://github.com/ic-n/mintzilio) - NFT minting on the latest Metaplex standard.

## Go infrastructure

- **[universal-telegram-miniapp-backend](https://github.com/ic-n/universal-telegram-miniapp-backend)** - self-contained Go backend for Telegram Mini Apps; works standalone or as a head start for a full-stack mini app. Telegram Mini Apps Hackathon winner.
- **[wait](https://github.com/ic-n/wait)** - `Promise.all`-style goroutine orchestration with generics: launch, gather typed results, collect errors. MIT.
- **[caichat](https://github.com/ic-n/caichat)** - template for building a fully self-hosted, chat-AI-assisted SaaS.
- **[legacy-endpoint](https://github.com/ic-n/legacy-endpoint)** - pattern and library for decomposing heavy monolithic endpoints into modular services without breaking existing clients.

## Products

- **[Coping](https://apps.apple.com/rs/app/coping/id6450903073)** - iOS app that helps people quit addictions and build healthier habits. [Open-source core](https://github.com/ic-n/coping-open).
- **[Taskwire](https://github.com/ic-n/taskwire)** - cross-platform local & SSH terminal: Flutter UI over a Go core (`mvdan/sh`), bridged via FFI/CGO. [Demo](https://www.linkedin.com/posts/ic-n_taskwire-2-activity-6967183184304197632-CcPs)

---

**Stack:** Rust (Anchor, SPL, Metaplex) · Go · TypeScript · Yellowstone gRPC · Kubernetes · Terraform · PostgreSQL · AWS / GCP


---

[![](https://www.codewars.com/users/ic-n/badges/large)](https://www.codewars.com/users/ic-n)
