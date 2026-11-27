## Hi, I'm Furkan

I build on-chain products in TypeScript, Rust and Solidity across Stellar, Solana and EVM chains, and fix bugs in
the open-source infrastructure they depend on. I focus on the parts that move money: signing flows and contract checks.

### Projects

- **[Touchmark](https://github.com/furkan3152/Touchmark_agent)**: security audits for AI agents that hold Stellar keys, with passing results recorded on chain. · [Demo](https://touchmark-stellar.vercel.app)
- **[Kletia](https://github.com/furkan3152/Kletia)**: turns a plain-language goal into verified, wallet-signed steps across EVM and Solana. · [kletiaai.xyz](https://kletiaai.xyz)
- **[FheCat](https://github.com/FheCat/FheCat)**: an NFT collection whose DNA is drawn and kept encrypted with Fhenix FHE, with on-chain art and a blind PvP arena scored under FHE. · [fhecat.com](https://fhecat.com)
- **[Lykia](https://github.com/furkan3152/Lykia)**: an agent and stablecoin desk on Arc, where every agent stays inside a rule set it cannot exceed.
- **[Elyia](https://github.com/furkan3152/Elyia)**: an intent and trading deck for Elysium, HyperEVM and HyperCore.
- **[HaPaPay](https://github.com/furkan3152/HaPaPay)**: send stablecoins and tokenized stocks to a social handle instead of an address.
- **[Ringio](https://github.com/furkan3152/ringio)**: a rotating savings circle (*Altın Günü*) on Solana, enforced by the program.
- **[Splitdev](https://github.com/furkan3152/ponsplit)**: a pump.fun launchpad that splits creator fees between GitHub developers. · [splitdev.app](https://splitdev.app)

### Open source

| Project | Contribution | Status |
|---|---|---|
| [Nansen CLI](https://github.com/nansen-ai/nansen-cli/pull/876) | Send the whole SPL balance on `--max` for scaled-UI Token-2022 mints | Merged |
| [Miden VM](https://github.com/0xMiden/miden-vm/pull/4125) | Fix `miden-format` output that no longer parsed | Merged |
| [Miden VM](https://github.com/0xMiden/miden-vm/pull/4126) | Keep `miden-format` type bodies within the line limit | Merged |
| [Nansen CLI](https://github.com/nansen-ai/nansen-cli/pull/874) | Report a Hyperliquid order whose connection dropped as possibly placed, not as never sent | Merged |
| [Nansen CLI](https://github.com/nansen-ai/nansen-cli/pull/875) | Read the alert being updated from the API, not the response cache | Merged |
| [Nansen CLI](https://github.com/nansen-ai/nansen-cli/pull/868) | Keep a broadcast Solana send from being reported as failed, which invited a second send | Merged |
| [Nansen CLI](https://github.com/nansen-ai/nansen-cli/pull/851) | Use exact base-unit balances for percent and auto-adjusted trade amounts | Merged |
| [Fhenix CoFHE SDK](https://github.com/FhenixProtocol/cofhesdk/pull/486) | Encrypt inputs in the security zone they were created with | Merged |
| [XMTP](https://github.com/xmtp/libxmtp/pull/4870) | Reject config values with the wrong shape | Merged |
| [OpenZeppelin](https://github.com/OpenZeppelin/stellar-contracts/pull/963) | Reject invalid `live_until_ledger` in confidential token allowances | Merged |
| [Tempo](https://github.com/tempoxyz/tempo/pull/8825) | Faster prewarm invalidation (16k txs: 4.9 s → 5.5 ms) | Merged |
| [Seaport.js](https://github.com/ProjectOpenSea/seaport-js/pull/1069) | Respect `accountAddress` in `createBulkOrders` | Merged in #1069 (co-author) |
| [Seaport.js](https://github.com/ProjectOpenSea/seaport-js/pull/1089) | Check that an offerer can cover all of their orders in a batch | In review |
| [Fhenix CoFHE contracts](https://github.com/FhenixProtocol/cofhe-contracts/pull/180) | Treat an uninitialized handle as zero in `FHE.sol` casts | In review |
| [Fhenix CoFHE contracts](https://github.com/FhenixProtocol/cofhe-contracts/pull/163) | Enforce security zones in `select` | In review |
| [Fhenix CoFHE SDK](https://github.com/FhenixProtocol/cofhesdk/pull/529) | Give concurrent `encryptInputs` calls on the mocks their own state | In review |
| [Arch Wallet Hub](https://github.com/Arch-Network/arch-wallet-hub/pull/195) | Select BTC coins against the fee for the inputs actually used | In review |
| [Seismic Foundry](https://github.com/SeismicSystems/seismic-foundry/pull/235) | Sanitize `eth_createAccessList` requests | In review |
| [Agent Commerce Kit](https://github.com/agentcommercekit/ack/pull/261) | Apply the resolver timeout to `did:jwks` | In review |
| [Ink node](https://github.com/inkonchain/node/pull/99) | Fix snapshot download retries | In review |

#### Bug reports

| Project | Report | Status |
|---|---|---|
| [Celo attribution tags](https://github.com/celo-org/attribution-tags/issues/30) | `verifyTx` returns null for tagged transactions sent through a relayer | Confirmed, fixed in `@celo/attribution-tags` 0.6.0 |
| [Miden VM](https://github.com/0xMiden/miden-vm/issues/4116) | `miden-format` writes signature commas into item comments | Fixed by my PR #4125 |
| [Tempo](https://github.com/tempoxyz/tempo/issues/9529) | `eth_estimateGas` rejects a sponsored request with fees from an unfunded sender | Open, fix linked |
| [Arc](https://github.com/circlefin/arc-node/issues/519) | Docker setup fails on Linux: `arc-snapshots` cannot write the `$ARC_HOME` bind mount | Confirmed, fixed by the Arc team |
| [Arc](https://github.com/circlefin/arc-node/issues/507) | `db` and `stage` subcommands fail with the default `--datadir` | Confirmed, tracked by the Arc team |
| [Arc](https://github.com/circlefin/arc-node/issues/501) | Database rollback leaves rows above the certificate tip | Open |
| [Base](https://github.com/base/base/issues/6392) | `--p2p.discovery.interval 0` crashes peer discovery | Closed as stale |

### Stack

TypeScript · Rust · Solidity · Python · React · Next.js · Foundry · Soroban · Solana · EVM

### Contact

[furkanakdogan92@gmail.com](mailto:furkanakdogan92@gmail.com)
