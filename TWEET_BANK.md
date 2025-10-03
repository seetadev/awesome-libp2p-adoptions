# Tweet Bank: libp2p Adoptions

This github page contains a ready-to-use set of tweets highlighting **how projects use libp2p in production**.
They are written to be **technical and informative** — intended as replies under the libp2p or Protocol Labs thread.


## Core Networks: Filecoin, Ethereum & Optimism

**1. Filecoin (@Filecoin)**
Filecoin is deeply tied to **libp2p** — every storage deal, retrieval, and consensus message is propagated through libp2p’s gossip and pubsub layers.

**2. Ethereum (@ethereum / @ethereumfndn)**
The Ethereum consensus layer depends on **libp2p** to power all validator-to-validator communication. Every block, attestation, and sync message flows through libp2p’s modular networking stack.

**3. Prysm (@prysmaticlabs) & Lighthouse (@sigp_io)**
Ethereum consensus clients like **Prysm** and **Lighthouse** use libp2p for peer discovery, gossip, and secure data propagation — enabling cross-client interoperability across the network.

**4. Nethermind (@nethermindeth)**
As a full Ethereum client, **Nethermind** integrates libp2p to ensure robust p2p networking, enabling synchronization and communication across heterogeneous Ethereum nodes.

**5. Optimism (@optimismFND)**
Optimism’s OP Stack uses **libp2p** for networking across nodes, sequencers, and rollups, providing modular peer discovery and communication.

**6. Base (@BuildOnBase)**
Base, built on the OP Stack, inherits its networking foundation from **libp2p** — providing a resilient peer-to-peer layer for transaction and block propagation.

**7. Magi (@a16zcrypto)**
Magi, an OP Stack rollup client, integrates **libp2p** for decentralized node-to-node networking, enabling modular rollup communication across Ethereum’s L2 ecosystem.

---

## Polkadot & Parachains

**8. Polkadot (@Polkadot) / Substrate (@substrate_io)**
Polkadot’s relay chain and Substrate-based chains use **Rust-libp2p** for all networking. Peer discovery, message routing, and block propagation are handled by libp2p modules.

**9. Moonbeam (@MoonbeamNetwork)**
Moonbeam, a Polkadot parachain, leverages **libp2p** to handle cross-chain communication and parachain-collator networking, ensuring interoperability across the Polkadot ecosystem.

---

## Rollups & Scaling

**10. Arbitrum (@arbitrum)**
The Arbitrum rollup stack uses **libp2p** to coordinate communication across sequencers and validators, ensuring reliable propagation of L2 state updates.

**11. Starknet (@Starknet)**
Starknet’s ZK-Rollup relies on **libp2p** to coordinate node communication, ensuring reliable propagation of proofs and state updates across its scaling network.

**12. Taiko Labs (@taikoxyz)**
Taiko integrates **libp2p** into its ZK-Rollup infra for decentralized networking, enabling efficient peer discovery and propagation of rollup transactions.

---

## Storage & Data Availability (Other than Filecoin)

**13. Celestia (@CelestiaOrg)**
Celestia uses **libp2p** for its data availability sampling network. Light clients rely on libp2p’s gossip to verify data without downloading the entire chain.

**14. Avail (@AvailProject)**
Avail employs **libp2p** to power its light client network — ensuring robust peer-to-peer sampling for scalable data availability.

---

## Other Blockchain Networks

**15. ENS DAO (@ensdomains)**
ENS depends on the Ethereum consensus layer — and thus **libp2p** — for secure validator communication, making decentralized naming resilient at its core.

**16. Flow (@flow_blockchain)**
Flow integrates **libp2p** at its networking layer, enabling validator nodes to communicate efficiently across a high-throughput chain for NFTs & dApps.

**17. Mina (@MinaProtocol)**
Mina leverages **libp2p** for its lightweight blockchain, providing gossip and peer discovery so succinct proofs can circulate efficiently across its network.

**18. Algorand (@Algorand)**
Algorand is evolving its stack to include **libp2p** for decentralized networking, enabling modular peer-to-peer communication in consensus operations.

**19. MultiversX (@MultiversX)**
MultiversX adopted **libp2p** to enhance connectivity across validators, supporting multiple transport protocols for greater network flexibility.

---

## Messaging & Social

**20. Waku (@waku_org)**
Waku is built on **libp2p**, extending its stack for decentralized, censorship-resistant messaging with pluggable transports and pubsub-based routing.

**21. Status (@ethstatus)**
Status created **nim-libp2p** to power its secure messenger and browser, showing the adaptability of libp2p beyond blockchains into everyday communication.

**22. XMTP (@xmtp_)**
XMTP uses **libp2p** as the backbone for wallet-to-wallet messaging — a decentralized communication layer integrated across apps and wallets.

**23. Coinbase Wallet (@CoinbaseWallet)**
Coinbase Wallet integrates XMTP (built on **libp2p**) to enable secure, decentralized, peer-to-peer messaging between Ethereum accounts.

**24. Lens Protocol (@LensProtocol)**
Lens uses XMTP, backed by **libp2p**, for social messaging — enabling a decentralized, interoperable communication layer for social dApps.

**25. Hey (@heydotxyz) & Orb (@orbapp)**
Both Hey and Orb integrate XMTP (built on **libp2p**) for direct messaging, making social applications interoperable on Lens.

**26. Farcaster (@farcaster_xyz)**
Farcaster runs “Hubs,” a decentralized server network that synchronizes social data peer-to-peer, using **libp2p-inspired networking** primitives.

---

## Databases & Compute

**27. OrbitDB (@OrbitDB)**
OrbitDB is a peer-to-peer, serverless database built on **IPFS + libp2p**, enabling decentralized storage and replication without central control.

**28. Berty (@berty)**
Berty builds privacy-first messaging using **libp2p**’s peer-to-peer stack, ensuring censorship resistance and encrypted communication without servers.

**29. Peergos (@Peergos)**
Peergos builds an encrypted, peer-to-peer filesystem on top of **libp2p**, with fine-grained access control and global sharing.

**30. Huddle01 (@huddle01com)**
Huddle01 uses **libp2p** for decentralized video conferencing, ensuring efficient, low-latency communication between peers in real time.

**31. Drand (@drand_loe)**
Drand uses **libp2p** to securely coordinate randomness beacon nodes, providing distributed randomness for blockchains and verifiable applications.

**32. Fluence (@fluence_project)**
Fluence integrates **libp2p** for its decentralized compute network, enabling peer-to-peer function execution and modular services.

**33. EdgeVPN (@EdgeVPN)**
EdgeVPN builds a decentralized VPN using **libp2p** for peer discovery and secure tunneling, coordinated by a lightweight blockchain.

**34. Nillion (@nillionnetwork)**
Nillion employs **libp2p’s circuit relay** for distributed compute nodes, enabling secure multiparty computation across its network.

**35. Spacedrive (@spacedriveapp)**
Spacedrive uses **libp2p** to establish lazy connections between devices, enabling peer-to-peer file exploration across platforms.

**36. Espresso Systems (@EspressoSys)**
Espresso relies on **libp2p** to handle cross-chain communication, supporting privacy-preserving and scalable rollup interactions.


✅ Each section groups related projects.

✅ Copy-paste any entry into X/Twitter to share directly.


