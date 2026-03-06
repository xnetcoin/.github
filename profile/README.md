<div align="center">

# XNET Protocol

### Independent Layer 1 Blockchain

[![Website](https://img.shields.io/badge/Website-xnetcoin.org-orange?style=flat-square)](https://xnetcoin.org)
[![Telegram](https://img.shields.io/badge/Telegram-xnethq-blue?style=flat-square&logo=telegram)](https://t.me/xnethq)
[![Twitter](https://img.shields.io/badge/Twitter-xnethq-black?style=flat-square&logo=x)](https://x.com/xnethq)
[![Email](https://img.shields.io/badge/Email-info@xnetcoin.org-red?style=flat-square&logo=gmail)](mailto:info@xnetcoin.org)

</div>

---

## What is XNET?

XNET is a Layer 1 blockchain built from scratch on Substrate — not a fork, not a parachain, not a template. One engineer. Twelve months. One codebase.

The goal was simple: build a chain where developers don't have to choose between EVM and WASM, where zero-knowledge proofs run natively in the runtime, and where the token supply is hard-capped and mathematically predictable — like Bitcoin. That chain is XNET.

---

## Protocol at a Glance

```
Token           XNET  /  XNC
Supply          53,000,000 XNC hard cap — immutable
Consensus       BABE + GRANDPA
Staking         Nominated Proof-of-Stake (NPoS)
VM Layer 1      EVM — full Ethereum compatibility (Chain ID 2009)
VM Layer 2      WASM — ink! smart contracts
ZK Layer 1      EVM-based Solidity ZK verifiers (live)
ZK Layer 2      pallet-zk-verifier — native Groth16 (final integration)
Interop         XCM cross-chain messaging (testnet phase)
Block Reward    1,117 XNC → halves every ~4 years
Fee Split       60% Treasury · 15% Dev Grants · 25% Validators
```

---

## Current Status

```
✅  Runtime complete — EVM, WASM, NPoS, halving, treasury
🔧  pallet-zk-verifier — native Groth16, final integration
🔜  Public testnet
🔜  XCM — cross-chain messaging (testnet phase)
🔜  Mainnet
```

---

## Repositories

| Repository | Description |
|---|---|
| [xnet](https://github.com/xnetcoin/xnet) | Core protocol — runtime, pallets, EVM, WASM, ZKP |

More repositories will be added as the ecosystem grows — explorer, wallet, SDK.

---

## For Developers

XNET is fully open source. If you're building on XNET — DeFi, NFTs, ZK applications, tooling, infrastructure — you can apply for a grant.

**1,000,000 XNC** from the ecosystem fund and **15% of all transaction fees** are allocated to developer grants. All open source. All on-chain.

→ [info@xnetcoin.org](mailto:info@xnetcoin.org)

---

<div align="center">

**[xnetcoin.org](https://xnetcoin.org) · [t.me/xnethq](https://t.me/xnethq) · [@xnethq](https://x.com/xnethq)**

*Built with Rust & Substrate — from scratch.*

</div>
