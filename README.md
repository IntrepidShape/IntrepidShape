# Jake Colson

**Senior software engineer — low-latency & systematic-quant systems · audit-ready Solidity.**
Founder of [Intrepid Development](https://intrepiddev.com.au) (Perth, Australia). **Available for contract — remote or Perth.**

I work at two hard edges: the **low-latency hot path** — execution systems in Zig, deterministic and memory-tight, with FPGA acceleration — and **audit-ready Solidity** (Foundry invariant + fuzz, formal methods, EVM). Alongside, I design and validate **systematic trading strategies** with real statistical discipline. My deepest systems work is under NDA; what's public below is the engineering rigor I bring to it, shown in the open.

📫 [intrepiddev.com.au](https://intrepiddev.com.au) · [jake@intrepiddev.com.au](mailto:jake@intrepiddev.com.au)
🔬 **Systematic engine — method & approach:** [intrepid-quant.vercel.app](https://intrepid-quant.vercel.app) · live output on request

---

### Selected open source — the same code I ship in production

| Project | What it is | Why it's hard |
|---|---|---|
| **[elm-web3](https://github.com/IntrepidShape/elm-web3)** | Type-safe EVM interaction for Elm — wallet & transaction state machines, opaque validated types (Address / TxHash / ChainId / BigInt), **a pure-Elm Solidity ABI encoder with zero JS runtime dependencies**. Published to the Elm package registry, MIT. | Misusing a `TxHash` where an `Address` is expected is a **compile error**. Core types and codecs are backed by **Lean 4 proofs + TLC-model-checked TLA+ state machines** — with a [coverage doc](https://github.com/IntrepidShape/elm-web3/blob/main/proofs/COVERAGE.md) that's honest about what's proved, what's model-checked, and what's still open. |
| **[pre-audit-hardening-pack](https://github.com/IntrepidShape/pre-audit-hardening-pack)** | What an auditor wants to see on day one — 70-item readiness checklist, threat-model template, Foundry invariant skeleton, CI gates. MIT. | Encodes an audit-ready methodology as a forkable template — invariant-first, fail-on-medium static analysis, ≥90% coverage gates. |
| **[elm-web3-ui](https://github.com/IntrepidShape/elm-web3-ui)** | 38 composable dApp UI primitives — wallet, transaction, balance, signing, staking, ve-lock, gauge, bonding curve. Published, MIT. | Pure functions of their inputs — no internal `Msg`, no hidden state. The compiler forces exhaustive handling of every wallet/tx state. |
| **[dapp-gen](https://github.com/IntrepidShape/dapp-gen)** | Verified contract → forkable, type-safe Elm dApp in one command. | Generates the whole type-safe bridge from an on-chain verified contract. |

### Under NDA — walkthrough available on request
- **Low-latency quantitative / arbitrage execution** — Zig + FPGA, deterministic hot path, memory-tight.
- **Systematic trading system** — deflated-Sharpe + walk-forward validation, survivorship-corrected (Carver / López de Prado methodology); currently paper-traded behind a regime gate.

### Stack
`Zig` · `Solidity` · `TypeScript` · `Go` · `Rust` · `Python` · `Haskell` · `Elm` · `Foundry` · `Lean 4` · `TLA+` · `Cloudflare Workers` · `AWS` · `Linux`

---

**Contracting through Intrepid Development Pty Ltd — day-rate, invoiced directly. Available now.**
