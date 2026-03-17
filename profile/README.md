<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="lasersell-dark.png" />
  <source media="(prefers-color-scheme: light)" srcset="lasersell-light.png" />
  <img alt="LaserSell" src="lasersell-light.png" width="400" />
</picture>

### Exit Smarter.

The traders beating you aren't better. They just aren't selling manually anymore.

[**Download the Desktop App**](https://www.lasersell.io/download) · [Website](https://www.lasersell.io) · [Docs](https://docs.lasersell.io) · [Discord](https://discord.gg/lasersell) · [X](https://x.com/lasersellhq)

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/lasersell/lasersell/blob/main/LICENSE) [![Discord](https://img.shields.io/badge/discord-join-5865F2?logo=discord&logoColor=white)](https://discord.gg/lasersell) [![Rust](https://img.shields.io/badge/rust-stable-orange?logo=rust)](https://github.com/lasersell/lasersell) [![Solana](https://img.shields.io/badge/solana-mainnet-9945FF?logo=solana&logoColor=white)](https://www.lasersell.io)

</div>

---

LaserSell monitors your Solana positions in real time and fires automated sells the instant your conditions are met. 4ms median transaction builds. Sub-200ms exit delivery. No polling, no stale data, no missed exits.

**Supported DEXs:** Pump.fun · PumpSwap · Raydium · Meteora · Bags.fm · SOL and USD1

## Non-custodial. Your keys never leave your machine.

Private keys are stored in an encrypted keystore (Argon2id + XChaCha20-Poly1305) and never leave your machine. Transactions are signed locally and submitted directly to the network. The server only sees your public key, builds unsigned transactions, and sends them to your client to sign.

## Desktop app

Five minutes from download to your first automated exit. Portfolio management, copy trading, exit strategies, and real time position monitoring in a native macOS app.

**[Download for Mac &rarr;](https://www.lasersell.io/download)**

## CLI

Open source. Headless. Built for VPS and server deployments.

```
curl -fsSL https://dl.lasersell.io/install.sh | sh
```

## API and SDKs

REST endpoints for building transactions. A WebSocket stream for real time exits and PnL. SDKs in four languages.

```bash
npm install @lasersell/lasersell-sdk    # TypeScript
pip install lasersell-sdk               # Python
cargo add lasersell-sdk                 # Rust
go get github.com/lasersell/lasersell-sdk/go
```

## AI agents trade on Solana through LaserSell.

Any agent can buy and sell across every major Solana DEX, receive automated exit signals, and track positions in real time. No protocol code required.

## Repositories

| Repository | Description |
| :--- | :--- |
| [`lasersell`](https://github.com/lasersell/lasersell) | Open source Rust client and CLI |
| [`lasersell-sdk`](https://github.com/lasersell/lasersell-sdk) | SDKs for TypeScript, Python, Rust, and Go |

## Links

| | |
| :--- | :--- |
| **Quickstart** | [docs.lasersell.io/start-here/quickstart](https://docs.lasersell.io/start-here/quickstart) |
| **API Reference** | [docs.lasersell.io/api/overview](https://docs.lasersell.io/api/overview) |
| **Build a Trading Agent** | [docs.lasersell.io/ai-agents/build-a-trading-agent](https://docs.lasersell.io/ai-agents/build-a-trading-agent) |
| **Benchmarks** | [38x faster than every major Solana trading API](https://www.lasersell.io/blog/benchmark-results) |
| **Blog** | [lasersell.io/blog](https://www.lasersell.io/blog) |
| **Dashboard** | [app.lasersell.io](https://app.lasersell.io) |

---

## Security

> **We will never ask for your private keys.**

Anyone DMing you claiming to be "LaserSell Support" or asking for seed phrases is a scammer. LaserSell is operated solely by [@haccer](https://github.com/haccer).

**Official channels only:**
- **Email:** [support@lasersell.io](mailto:support@lasersell.io)
- **Security:** [security@lasersell.io](mailto:security@lasersell.io)

---

<div align="center">
<sub>&copy; 2026 Xen LLC. All rights reserved.</sub>
</div>
