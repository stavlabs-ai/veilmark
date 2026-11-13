# Veilmark

**Passports for Solana AI agents. Public proof, private details.**

> 🚧 **Launching soon.** Code and docs are landing in this repo shortly. Star or watch to follow along.

---

## The problem

AI agents now hold wallets, so which ones can you trust?

If you put an agent's identity onchain, everyone can read it: its name, its limits, and its track record. That leaves the owner open to competitors and copy-traders.

## What Veilmark does

Veilmark gives every AI agent a **passport** on Solana. Anyone can check that the passport is real and active. The details stay with the owner.

- **Onchain:** Solana stores only a salted hash, a fingerprint that reveals nothing on its own.
- **Off-chain:** You keep the actual values (label, daily budget, risk limit, track record) in your own browser.
- **Your choice:** You pick who sees what, one statement at a time.

## How it works

1. **You keep the values.** Names, limits and statements never leave your browser.
2. **Solana stores a hash.** A salted fingerprint that reveals nothing on its own.
3. **You choose who sees.** Share one statement with one counterparty. Revoke it any time.

## Features

| Feature | What it does |
| --- | --- |
| **Selective disclosure** | One statement, one counterparty |
| **Kill switch** | Freeze an agent instantly |
| **Key rotation** | Same passport, new key |
| **Agent signature check** | Prove who holds the passport |
| **SDK and HTTP API** | Verify in a few lines |
| **Program gate** | For other Solana programs |

## Verify an agent (no wallet needed)

Before you deal with an agent, check three things:

- The passport is active (not frozen, not revoked).
- The agent holds its key (it signs a challenge you send).
- The statement matches the chain (unchanged since the owner committed it).

Anyone can do this. No wallet or account is needed.

## Owner controls

You stay in charge. In a single transaction you can:

- **Freeze** an agent
- **Rotate** its key and keep the same passport
- **Revoke** the passport permanently

## Status

Veilmark is in active development and **launching soon**. This repository will hold the source code, SDK and documentation at launch.

## License

[MIT](./LICENSE)

---

*Built on Solana.*
