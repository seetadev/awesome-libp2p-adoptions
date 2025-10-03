# Tweet Bank: libp2p Adoptions

This file contains a ready-to-use set of tweets highlighting **how projects use libp2p in production**.  
They are written to be **technical and informative** — intended as replies under the [2025 libp2p maintenance update blog post](https://ipshipyard.com/blog/2025-libp2p-maintenance-update/).  

---

## Ethereum & Clients

**1. Ethereum (@ethereum / @ethereumfndn)**  
The Ethereum consensus layer depends on **libp2p** to power all validator-to-validator communication. Every block, attestation, and sync message flows through libp2p’s modular networking stack.  

**2. Prysm (@prysmaticlabs) & Lighthouse (@sigp_io)**  
Ethereum consensus clients like **Prysm** and **Lighthouse** use libp2p for peer discovery, gossip, and secure data propagation — enabling cross-client interoperability across the network.  

**3. Nethermind (@nethermindeth)**  
As a full Ethereum client, **Nethermind** integrates libp2p to ensure robust p2p networking, enabling synchronization and communication across heterogeneous Ethereum nodes.  

---

## Polkadot & Parachains

**4. Polkadot (@Polkadot) / Substrate (@substrate_io)**  
Polkadot’s relay chain and Substrate-based chains use **Rust-libp2p** for all networking. Peer discovery, message routing, and block propagation are handled by libp2p modules.  

**5. Moonbeam (@MoonbeamNetwork)**  
Moonbeam, a Polkadot parachain, leverages **libp2p** to handle cross-chain communication and parachain-collator networking, ensuring interoperability across the Polkadot ecosystem.  

---

## Storage & Data Availability

**6. Filecoin (@Filecoin)**  
Filecoin is deeply tied to **libp2p** — every storage deal, retrieval, and consensus message is propagated through libp2p’s gossip and pubsub layers.  

**14. Celestia (@CelestiaOrg)**  
Celestia uses **libp2p** for its data availability sampling network. Light clients rely on libp2p’s gossip to verify data without downloading the entire chain.  

**18. Avail (@AvailProject)**  
Avail employs **libp2p** to power its light client network — ensuring robust peer-to-peer sampling for scalable data availability.  

---

## Rollups & Scaling

**7. Arbitrum (@arbitrum)**  
The Arbitrum rollup stack uses **libp2p** to coordinate communication across sequencers and validators, ensuring reliable propagation of L2 state updates.  

**8. Optimism (@optimismFND)**  
Optimism’s OP Stack uses **libp2p** for networking across nodes, sequencers, and rollups, providing modular peer discovery and communication.  

**9. Base (@BuildOnBase)**  
Base, built on the OP Stack, inherits its networking foundation from **libp2p** — providing a resilient peer-to-peer layer for transaction and block propagation.  

**10. Magi (@a16zcrypto)**  
Magi, an OP Stack rollup client, integrates **libp2p** for decentralized node-to-node networking, enabling modular rollup communication across Ethereum’s L2 ecosystem.  

**11. Starknet (@Starknet)**  
Starknet’s ZK-Rollup relies on **libp2p** to coordinate node communication, ensuring reliable propagation of proofs and state updates across its scaling network.  

**12. Taiko Labs (@taikoxyz)**  
Taiko integrates **libp2p** into its ZK-Rollup infra for decentralized networking, enabling efficient peer discovery and propagation of rollup transactions.  

---

## Messaging & Social

**22. Waku (@waku_org)**  
Waku is built on **libp2p**, extending its stack for decentralized, censorship-resistant messaging with pluggable transports and pubsub-based routing.  

**23. Status (@ethstatus)**  
Status created **nim-libp2p** to power its secure messenger and browser, showing the adaptability of libp2p beyond blockchains into everyday communication.  

**24. XMTP (@xmtp_)**  
XMTP uses **libp2p** as the backbone for wallet-to-wallet messaging — a decentralized communication layer integrated across apps and wallets.  

**25. Coinbase Wallet (@CoinbaseWallet)**  
Coinbase Wallet integrates XMTP (built on **libp2p**) to enable secure, decentralized, peer-to-peer messaging between Ethereum accounts.  

**26. Lens Protocol (@LensProtocol)**  
Lens uses XMTP, backed by **libp2p**, for social messaging — enabling a decentralized, interoperable communication layer for social dApps.  

**27. Hey (@heydotxyz) & Orb (@orbapp)**  
Both Hey and Orb integrate XMTP (built on **libp2p**) for direct messaging, making social applications interoperable on Lens.  

**28. Farcaster (@farcaster_xyz)**  
Farcaster runs “Hubs,” a decentralized server network that synchronizes social data peer-to-peer, using **libp2p-inspired networking** primitives.  

---

## Databases & Compute

**30. OrbitDB (@OrbitDB)**  
OrbitDB is a peer-to-peer, serverless database built on **IPFS + libp2p**, enabling decentralized storage and replication without central control.  

**34. Fluence (@fluence_project)**  
Fluence integrates **libp2p** for its decentralized compute network, enabling peer-to-peer function execution and modular services.  

**36. Nillion (@nillionnetwork)**  
Nillion employs **libp2p’s circuit relay** for distributed compute nodes, enabling secure multiparty computation across its network.  

---

## Applications

**29. Berty (@berty)**  
Berty builds privacy-first messaging using **libp2p**’s peer-to-peer stack, ensuring censorship resistance and encrypted communication without servers.  

**32. Peergos (@Peergos)**  
Peergos builds an encrypted, peer-to-peer filesystem on top of **libp2p**, with fine-grained access control and global sharing.  

**33. Huddle01 (@huddle01com)**  
Huddle01 uses **libp2p** for decentralized video conferencing, ensuring efficient, low-latency communication between peers in real time.  

**37. Spacedrive (@spacedriveapp)**  
Spacedrive uses **libp2p** to establish lazy connections between devices, enabling peer-to-peer file exploration across platforms.  

---

## Infrastructure

**31. Drand (@drand_loe)**  
Drand uses **libp2p** to securely coordinate randomness beacon nodes, providing distributed randomness for blockchains and verifiable applications.  

**35. EdgeVPN (@EdgeVPN)**  
EdgeVPN builds a decentralized VPN using **libp2p** for peer discovery and secure tunneling, coordinated by a lightweight blockchain.  

**38. Espresso Systems (@EspressoSys)**  
Espresso relies on **libp2p** to handle cross-chain communication, supporting privacy-preserving and scalable rollup interactions.  

---

## Other

**13. ENS DAO (@ensdomains)**  
ENS depends on the Ethereum consensus layer — and thus **libp2p** — for secure validator communication, making decentralized naming resilient at its core.  

**15. Flow (@flow_blockchain)**  
Flow integrates **libp2p** at its networking layer, enabling validator nodes to communicate efficiently across a high-throughput chain for NFTs & dApps.  

**16. Mina (@MinaProtocol)**  
Mina leverages **libp2p** for its lightweight blockchain, providing gossip and peer discovery so succinct proofs can circulate efficiently across its network.  

**17. Algorand (@Algorand)**  
Algorand is evolving its stack to include **libp2p** for decentralized networking, enabling modular peer-to-peer communication in consensus operations.  

**21. MultiversX (@MultiversX)**  
MultiversX adopted **libp2p** to enhance connectivity across validators, supporting multiple transport protocols for greater network flexibility.  

**39. Exo (@exolabs)**  
While not libp2p-based, **Exo** uses a peer-to-peer compute model similar to libp2p to distribute AI workloads across consumer devices.  

---

✅ Each section groups related projects.  
✅ Copy-paste any entry into X/Twitter to share directly.  
