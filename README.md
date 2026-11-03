## Hi, I'm Furkan

I build on-chain products and fix bugs in the open-source infrastructure they depend on. Most of my work is in
TypeScript, Rust and Solidity, across Stellar, Solana and EVM chains. I care most about the parts that move money:
signing flows, contract checks and the places where an agent or a user could be tricked into the wrong transaction.

### Projects

**[Touchmark](https://github.com/furkan3152/Touchmark_agent)**: security audits for AI agents that hold Stellar
authority. It reads an agent's code, checks it against Stellar-specific rules (fee bumps, asset issuers, SEP-10,
`__check_auth`), has a second model re-check each serious finding, and records a passing result on Stellar as a
non-transferable credential. Benchmarked on real defects that maintainers fixed upstream in public Stellar repositories.
· [Live demo](https://touchmark-stellar.vercel.app)
<br><sub>Python · Rust (Soroban) · TypeScript</sub>

**The Kletia family**: three products built on one idea. A plain-language goal is compiled into an auditable
graph of steps, every step is checked against a fail-closed rule book, and the user's own wallet signs. The server
never holds keys.

- **[Kletia](https://github.com/furkan3152/Kletia)**: intent infrastructure for EVM and Solana, across nine networks.
  A sentence like *"bridge 50 USDC from Base to Solana, then swap half to JitoSOL"* becomes wallet-signed steps, each
  verified on chain before the next one unlocks. Ships as an app, API, SDK, React widget, CLI and MCP server.
  · [kletiaai.xyz](https://kletiaai.xyz)
- **[Lykia](https://github.com/furkan3152/Lykia)**: the agent and stablecoin desk, built on Arc. Each agent works
  inside a typed *Fence* (caps, recipients, slippage, health factor, FX band), and sub-agents can never exceed their
  parent's limits. Uses Circle's rails (USDC, CCTP V2, Gateway, StableFX), ERC-8004 agent identities and Arc memos.
  Live on Arc mainnet in beta, capped per step.
- **[Elyia](https://github.com/furkan3152/Elyra)**: the trading and portfolio deck for Elysium, HyperEVM and
  HyperCore: bridge, swap, trade and track from one place, with HyperCore signing payloads checked against golden
  test vectors. Testnet first.

<sub>TypeScript · React · Solidity · Node.js</sub>

**[HaPaPay](https://github.com/furkan3152/HaPaPay)**: pay a social handle, not an address. Send stablecoins and
tokenized stocks to a GitHub, X, Telegram, Discord or Farcaster account across Robinhood Chain, Solana and Arc.
Unclaimed payments wait in an on-chain vault. The server never holds keys or signs.
<br><sub>TypeScript · React · Solidity (Foundry) · Rust (Solana)</sub>

**[Ringio](https://github.com/furkan3152/ringio)**: a rotating savings circle (*Altın Günü*) on Solana. Members who
are paid early lock collateral, so "take the pot and disappear" is handled by the program. The program was rewritten
from Anchor to Pinocchio (657 KB → 92 KB), and a differential test checks that both builds behave the same.
<br><sub>Rust (Pinocchio) · Next.js</sub>

**[Splitdev](https://github.com/furkan3152/ponsplit)**: a pump.fun launchpad that permanently splits a coin's creator
fees between up to nine GitHub developers through pump.fun's own fee sharing, with admin rights revoked.
· [splitdev.app](https://splitdev.app)
<br><sub>Next.js · Solana</sub>

**[Elymum](https://github.com/furkan3152/Solagel)**: a real-time coin-eats-coin arena game on Elysium (Kinetiq's
L2 on HyperEVM), with a 30 Hz authoritative server, NFT mint and on-chain round payouts.
<br><sub>TypeScript · Solidity</sub>

### Open source

| Project | Contribution | Status |
|---|---|---|
| [Fhenix CoFHE SDK](https://github.com/FhenixProtocol/cofhesdk/pull/486) | Encrypt inputs in the security zone they were created with, instead of silently using the default zone | Merged |
| [OpenZeppelin Stellar Contracts](https://github.com/OpenZeppelin/stellar-contracts/pull/963) | Reject expired or out-of-range `live_until_ledger` values in confidential token allowances | In review |
| [Tempo](https://github.com/tempoxyz/tempo/pull/8825) | Skip invalidated lanes in the payload prewarmer instead of rebuilding its buffer (16k txs: 4.9 s → 5.5 ms) | In review |
| [Fhenix CoFHE contracts](https://github.com/FhenixProtocol/cofhe-contracts/pull/163) | Require `select`'s condition to share the security zone of its branches | In review |
| [Seismic Foundry](https://github.com/SeismicSystems/seismic-foundry/pull/235) | Apply `eth_call` request sanitization to `eth_createAccessList` | In review |
| [Agent Commerce Kit](https://github.com/agentcommercekit/ack/pull/261) | Apply the resolver timeout to `did:jwks` fetches | In review |
| [XMTP](https://github.com/xmtp/libxmtp/pull/4870) | Reject config values with the wrong TOML shape | In review |
| [Seaport.js](https://github.com/ProjectOpenSea/seaport-js/pull/1068) | Use `accountAddress` as the offerer in `createBulkOrders` | In review |
| [Ink node](https://github.com/inkonchain/node/pull/99) | Let snapshot downloads overwrite a leftover archive on retry | In review |

[All my pull requests →](https://github.com/pulls?q=is%3Apr+author%3Afurkan3152+-user%3Afurkan3152)

### Stack

**Languages:** TypeScript, Rust, Solidity, Python
<br>**Chains:** Stellar / Soroban, Solana, EVM (Base, Arbitrum, Arc, HyperEVM / HyperCore)
<br>**Tools:** React, Next.js, Node.js, Foundry, Anchor / Pinocchio, PostgreSQL, Docker

### Contact

[furkanakdogan92@gmail.com](mailto:furkanakdogan92@gmail.com)
