# Phantomojo — Michael Irungu Muriithi

Security-focused systems engineer in progress; Year-3 BSc Cybersecurity & Digital Forensics student. GhostWire maintainer; four published Rust crates.

| Anchor | Value |
|---|---|
| Handle | `Phantomojo` (GitHub) · `PHANTOMOJO` (Codeberg) |
| Name | M.I. Muriithi — Michael Irungu Muriithi |
| Affiliation | BSc Cybersecurity & Digital Forensics, Open University of Kenya (Year 3, expected 2027) · GhostWire maintainer · initiated Obsidian Directive |
| Location | Nairobi, Kenya |

[GitHub](https://github.com/Phantomojo) · [Codeberg](https://codeberg.org/PHANTOMOJO) · [Website](https://www.ghostwire.cc/) · [dev.to](https://dev.to/phantomojo) · [LinkedIn](https://www.linkedin.com/in/michaelimuriithi) · [mirungu015@gmail.com](mailto:mirungu015@gmail.com)

## Verified evidence (as of 2026-11-25)

- 28 public GitHub repos (24 non-fork) and 2 Codeberg repos.
- Four crates.io packages owned by `Phantomojo`: sphinx-rs 0.1.1, ghostwire-dtn 0.1.0, hlc-rs 0.1.0, trust-store 0.1.0.
- GhostWire line of record: 379 commits as of 2026-11-24.
- Automation and AI agents contributed to this codebase; provenance is disclosed rather than hidden.

## Flagship projects

### GhostWire — decentralized, offline-first encrypted P2P mesh

Rust protocol and reference node for communication without central infrastructure or continuous connectivity.

- **Stack:** Rust, libp2p (GossipSub, Kademlia DHT), DTN store-carry-forward with PRoPHET.
- **Crypto:** XChaCha20-Poly1305 AEAD; X25519 + ML-KEM-768 hybrid key exchange. Post-quantum interoperability is in code but not yet externally audited; pre-1.0.
- **Routing:** four-layer stack — LightGBM → Gemma 4 → GNN → PRoPHET (GNN layer in progress).
- **Architecture:** application/API (Axum, WebSocket, CLI, TUI) → services (block store, mailbox, Sphinx) → routing → crypto → pluggable transports → libp2p mesh/DTN.

[Website](https://www.ghostwire.cc/) · [Codeberg source](https://codeberg.org/PHANTOMOJO/GhostWire-secure-mesh-communication) · [GitHub mirror](https://github.com/Phantomojo/GhostWire-secure-mesh-communication) · [crates.io profile](https://crates.io/users/phantomojo) · [sphinx-rs crate](https://crates.io/crates/sphinx-rs)

### CERBERUS — bio-adaptive IoT honeynet

Academic research framework that emulates router and CCTV IoT services and correlates attacks across them.

- **Stack:** C (adaptation/correlation engines), Python (Cowrie SSH/Telnet services), nginx (static router/CCTV UIs), Docker Compose.
- **Architecture:** scheduled fingerprint morphing → quorum-sensing correlation of probing across services → suspicion scoring and exploit-chain tracking → canary tokens for lateral movement → local analytics dashboard.
- **Context:** developed at the Open University of Kenya as part of BSc Cybersecurity & Digital Forensics research.

[Source](https://github.com/Phantomojo/cerberus-honeypot) · [Citation](https://github.com/Phantomojo/cerberus-honeypot#citation)

## Open-source portfolio

Full profile: [codeberg.org/PHANTOMOJO](https://codeberg.org/PHANTOMOJO) — source of truth for GhostWire. Broader public work spans:

- **Cybersecurity:** [GhostWire](https://github.com/Phantomojo/GhostWire-secure-mesh-communication), [CERBERUS](https://github.com/Phantomojo/cerberus-honeypot)
- **Agritech:** [Maono](https://github.com/Phantomojo/maono-agriculture-platform), [Mali-Connect](https://github.com/Phantomojo/mali-connect-app)
- **Fintech:** [Passua Bites](https://github.com/Phantomojo/passua-bites-web), [Vanta Ledger](https://github.com/Phantomojo/Vanta-ledger)
- **Climate / geo analytics:** [ORUN.IO](https://github.com/Phantomojo/ORUN.IO)

## Contact

Rust systems, protocol design and security research. Nairobi, Kenya — remote work.

[Email](mailto:mirungu015@gmail.com) · [GitHub](https://github.com/Phantomojo) · [Codeberg](https://codeberg.org/PHANTOMOJO) · [LinkedIn](https://www.linkedin.com/in/michaelimuriithi)
