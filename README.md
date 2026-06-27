# Jake

**Senior software engineer — audit-ready Solidity, smart-contract audits & type-safe Web3 (Elm).** Also: low-latency & systematic-quant systems.
Founder of [Intrepid Development](https://intrepiddev.com.au) (Perth, Australia). **Available for contract — remote or Perth.**

I specialise in **audit-ready Solidity** — Foundry invariant + fuzz, threat modelling, the hardening an auditor wants to see on day one — and **type-safe Web3 frontends in Elm**, published to the package registry with formal-methods backing. I also build **low-latency execution in Zig** and design **systematic trading strategies**; that deeper systems work I keep private and show on a call. What's public below is the rigour I bring to it, in the open.

📫 [intrepiddev.com.au](https://intrepiddev.com.au) · [jake@intrepiddev.com.au](mailto:jake@intrepiddev.com.au)
🔬 **Systematic engine — method & approach:** [intrepiddev.com.au/quant](https://intrepiddev.com.au/quant) · live output on request

---

### Selected open source — the same code I ship in production

| Project | What it is | Why it's hard |
|---|---|---|
| **[elm-web3](https://github.com/IntrepidShape/elm-web3)** | Type-safe EVM interaction for Elm — wallet & transaction state machines, opaque validated types (Address / TxHash / ChainId / BigInt), **a pure-Elm Solidity ABI encoder with zero JS runtime dependencies**. Published to the Elm package registry, MIT. | Misusing a `TxHash` where an `Address` is expected is a **compile error**. Core types and codecs are backed by **Lean 4 proofs + TLC-model-checked TLA+ state machines** — with a [coverage doc](https://github.com/IntrepidShape/elm-web3/blob/main/proofs/COVERAGE.md) that's honest about what's proved, what's model-checked, and what's still open. |
| **[pre-audit-hardening-pack](https://github.com/IntrepidShape/pre-audit-hardening-pack)** | What an auditor wants to see on day one — 70-item readiness checklist, threat-model template, Foundry invariant skeleton, CI gates. MIT. | Encodes an audit-ready methodology as a forkable template — invariant-first, fail-on-medium static analysis, ≥90% coverage gates. |
| **[elm-web3-ui](https://github.com/IntrepidShape/elm-web3-ui)** | 38 composable dApp UI primitives — wallet, transaction, balance, signing, staking, ve-lock, gauge, bonding curve. Published, MIT. | Pure functions of their inputs — no internal `Msg`, no hidden state. The compiler forces exhaustive handling of every wallet/tx state. |
| **[dapp-gen](https://github.com/IntrepidShape/dapp-gen)** | Verified contract → forkable, type-safe Elm dApp in one command. | Generates the whole type-safe bridge from an on-chain verified contract. |

### Shown on a call — the deeper systems work
- **Low-latency quantitative / arbitrage execution** — Zig + FPGA + GPU acceleration, deterministic hot path, memory-tight.
- **Systematic trading system** — deflated-Sharpe + walk-forward validation, survivorship-corrected (Carver / López de Prado methodology); currently paper-traded behind a regime gate. Live engine output on request.

### Stack
`Solidity` · `Foundry` · `Elm` · `Lean 4` · `TLA+` · `TypeScript` · `EVM` · `Zig` · `Go` · `Rust` · `Python` · `Haskell` · `Cloudflare Workers` · `AWS` · `Linux`

---

**Contracting through Intrepid Development Pty Ltd — day-rate, invoiced directly. Available now.**
