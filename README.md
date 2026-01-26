# Privacy on Solana

A collection of projects and resources exploring the privacy landscape on Solana

---

## Here for Privacy Hack?

[Privacy Hack](https://solana.com/privacyhack) is a hackathon focused on building privacy solutions on Solana. Below are the sponsors, bounties, and resources to help you get started.

### Main Tracks

| Track            | Prize   | Focus                                                                                     |
| ---------------- | ------- | ----------------------------------------------------------------------------------------- |
| Private Payments | $15,000 | Build innovative solutions for confidential or private transfers on Solana                |
| Privacy Tooling  | $15,000 | Develop tools and infrastructure that make it easier for developers to build with privacy |
| Open Track       | $18,000 | Build privacy applications on Solana (supported by Light Protocol)                        |

### Sponsor Bounties

#### Arcium - $10,000

End-to-end private DeFi using Arcium and the C-SPL token standard. Build fully confidential swaps, lending, borrowing, and more.

| Resources       | Link                                                                    |
| --------------- | ----------------------------------------------------------------------- |
| Website         | [arcium.com](https://arcium.com)                                        |
| Docs            | [docs.arcium.com](https://docs.arcium.com/)                             |
| Getting Started | [Arcium Quickstart](https://docs.arcium.com/developers/getting-started) |
| Examples        | [Arcium Examples](https://github.com/arcium-hq/examples)                |

#### Aztec (Noir) - $10,000

Build ZK applications using Noir on Solana. Prizes: Best Overall ($5k), Best Non-Financial Use ($2.5k), Most Creative ($2.5k).

| Resources               | Link                                                                                  |
| ----------------------- | ------------------------------------------------------------------------------------- |
| Noir Docs               | [noir-lang.org/docs](https://noir-lang.org/docs/)                                     |
| Noir on Solana Examples | [solana-foundation/noir-examples](https://github.com/solana-foundation/noir-examples) |
| Sunspot Verifier        | [reilabs/sunspot](https://github.com/reilabs/sunspot)                                 |

#### Inco - $6,000

Best confidential apps using Inco Lightning. Categories: DeFi ($2k), Consumer/Gaming/Prediction Markets ($2k), Payments ($2k).

| Resources | Link                                                |
| --------- | --------------------------------------------------- |
| Docs      | [docs.inco.org/svm](https://docs.inco.org/svm/home) |
| Website   | [inco.org](https://inco.org)                        |

#### MagicBlock - $5,000

Best privacy app leveraging on MagicBlock's Private Ephemeral Rollup.

| Resources | Link                                                                                                  |
| --------- | ----------------------------------------------------------------------------------------------------- |
| Website   | [magicblock.xyz](https://magicblock.xyz)                                                              |
| Docs      | [docs.magicblock.gg](https://docs.magicblock.gg/)                                                     |
| GitHub    | [magicblock-labs](https://github.com/magicblock-labs)                                                 |
| Example   | [Quickstart](https://docs.magicblock.gg/pages/private-ephemeral-rollups-pers/how-to-guide/quickstart) |

#### Helius - $5,000

Best privacy project leveraging Helius RPCs and developer tooling.

| Resources | Link                                          |
| --------- | --------------------------------------------- |
| Website   | [helius.dev](https://helius.dev)              |
| Docs      | [docs.helius.dev](https://docs.helius.dev/)   |
| GitHub    | [helius-labs](https://github.com/helius-labs) |

#### Encrypt.trade - $1,000

Educate users about privacy. Wallet Surveillance Education ($500), Jargon-Free Privacy Explanation ($500).

| Resources | Link                                   |
| --------- | -------------------------------------- |
| Website   | [encrypt.trade](https://encrypt.trade) |

#### Privacy Cash - $6,000

Use Privacy Cash SDK to build privacy-enabled apps on Solana. Ideas include private lending, whale wallets, private bridging, games, and more. Grand Prize ($3k), Best Integration to Existing App ($1.5k), Honorable Mentions ($500 x 3).

| Resources | Link                                                                      |
| --------- | ------------------------------------------------------------------------- |
| GitHub    | [Privacy-Cash/privacy-cash](https://github.com/Privacy-Cash/privacy-cash) |

#### Range - $1,500

Build compliant-privacy solutions using Range tools for pre-screening and selective disclosure to make private/confidential applications safe and compliant. All participating teams get free API credits for 2 months.

| Resources | Link                               |
| --------- | ---------------------------------- |
| Website   | [range.org](https://www.range.org) |

#### Radr Labs - $15,000

Privacy-First DeFi on Solana. Transfer privately with ShadowWire. Swap across chains with ShadowSwap. Trade anonymously with ShadowTrade. All powered by zero-knowledge proofs.

| Resources | Link                                                                                           |
| --------- | ---------------------------------------------------------------------------------------------- |
| Website   | [radr.fun](https://radr.fun)                                                                   |
| Docs      | [Radr API](https://registry.scalar.com/@radr/apis/shadowpay-api#description/what-is-shadowpay) |
| GitHub    | [radrdotfun](https://github.com/radrdotfun)                                                    |
| X         | [x.com/radrlabs](https://x.com/radrlabs)                                                       |

### Submission Requirements

- Open source code mandatory
- Integrate Solana with privacy-preserving technologies
- Deploy to Solana devnet or mainnet
- Include demo video (max 3 minutes)
- Provide documentation for running/using your project

---

## Projects

- [Arcium](https://www.arcium.com/) - MPC network allowing for verifiable trustless computation
- [encrypt.trade](https://app.encifher.io/) - encrypted private DeFi using encryption and TEEs
- [Privacy.cash](https://github.com/Privacy-Cash/privacy-cash) - private SOL/SPL transfers using ZK proofs and privacy pools (no frontend, do not trust any frontend)
- [Umbra](https://umbra.cash/) - private transactions via shielded pools (built on Arcium)
- [Hush](https://hush.so/) - privacy-first wallet stealth addresses
- [MagicBlock](https://www.magicblock.gg/) - ephemeral rollups with TEEs

# Developers

## Education Resources

- [Noir examples](https://github.com/solana-foundation/noir-examples) - examples of Noir projects on Solana (unaudited, education only)
- [Solana mixer example](https://github.com/catmcgee/solana-mixer-circom) - simple demo-only mixer using Circom
- [Confidential transfers guide](https://solana.com/docs/tokens/extensions/confidential-transfer) - learn how the confidential transfers token extension works
- [Arcium docs](https://docs.arcium.com/) - MPC framework that feels similar to Anchor
- [Private transactions on Solana with Arcium (for Anchor developers)](https://www.youtube.com/watch?v=X3Y6sL7A8O0) - an animated guide and video for experienced Anchor developers to create private transactions using Arcium.

## Tooling

- [Sunspot](https://github.com/reilabs/sunspot) - Noir/Groth16 verifier on Solana
- [Light Protocol](https://github.com/Lightprotocol/light-protocol) - ZK compression for scalability + privacy
- [groth16-solana](https://github.com/Lightprotocol/groth16-solana) - Groth16 verifier by Light Protocol
- [Arcium SDK](https://docs.arcium.com/) - MPC development framework

---

# Research

- [Zero-Knowledge Extensions on Solana: A Theory of ZK Architecture](https://arxiv.org/abs/2511.00415) - proposes a two-axis model for ZK use covering scalability vs privacy and on-chain vs off-chain placement. Covers ZK Compression, Confidential Transfers, and light clients/bridges.
