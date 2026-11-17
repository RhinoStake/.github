<p align="center">
  <img src="https://snapshots.rhinostake.com/rhinoshare/twitter_header.jpg" />
</p>

[RHINO](https://rhinostake.com) is an enterprise blockchain infrastructure and services organization built on over 60 years of combined infrastructure, security, and program delivery experience.

Launched in 2020, the RHINO team operates validator, RPC, and cross-chain infrastructure across 70+ blockchain networks, serving over 30 billion RPC requests monthly for 100+ Web3 teams. We have been part of a multitude of genesis ceremonies, contributed to the success of blockchain projects, and have been instrumental during testnets, launches, upgrades, and chain "incident" management.

Our strengths include delivering **secure, redundant and geo-distributed infrastructure at-scale** for **institutional investors, web3 project teams, venture capital**, as well as for our own staking operations. We maintain load-balanced clusters across the US, Europe, East Asia, and Southeast Asia with enterprise SLA commitments of 99.9% to 99.99% uptime.

We like to get involved in projects "early", offering a high amount of engagement, tooling, analytics, automation and needed assistance for new L1s. We're clear communicators, with experience working with geo-distributed diverse validator teams and assist in the coordination, communication and documentation of efforts for efficient and performant testnets and mainnet launches.

## Our Involvement

Today we run operations for many different types of projects:

- RHINO is a selected "genesis" node operator for [Aptos](https://aptoslabs.com/), including the responsibility of managing the staking pool validator operations for Aptos Labs Corporation. We provide the Aptos ecosystem's largest global API service at [aptos-apis.com](https://aptos-apis.com).
- RHINO has been a [Chainlink](https://chain.link/) node operator since 2021. We are one of the 16 independent, security-reviewed node operators in the **Chainlink Committee Verifier**, which reaches consensus on and signs every [CCIP 2.0](https://chain.link/cross-chain) transfer across 54+ blockchains. We also run **Off-Chain Reporting (OCR)** nodes, signing and aggregating market data for [Chainlink Data Feeds](https://chain.link/data-feeds). Every Chainlink node we operate reads from blockchain nodes and RPC services we run ourselves &mdash; no third-party providers. More at [rhinostake.com/chainlink](https://rhinostake.com/chainlink).
- RHINO is one of 8 [designated proposers](https://dydx.forum/t/drc-appoint-designated-proposer-set/) for [dYdX](https://dydx.trade), the leading decentralized derivatives protocol, and leads the chain in signing performance.
- We run validators and infrastructure across many networks including [Sei](https://www.sei.io/), [Monad](https://monad.xyz), [Berachain](https://www.berachain.com/), [DChain](https://dchain.foundation/), [XRPL EVM Sidechain](https://xrplevm.org/), [SEDA](https://www.seda.xyz/), [Mavryk](https://mavryk.org/), and more &mdash; including genesis validator roles on many of them. We're also a [Lido](https://lido.fi/) DVT operator and an [SSV Network](https://ssv.network/) Verified operator. See the full list at [rhinostake.com/networks](https://rhinostake.com/networks).
- We provide [IBC relaying](https://tutorials.cosmos.network/academy/2-cosmos-concepts/13-relayer-intro.html) services for cross-chain connectivity, including supporting routes for Cosmos Hub, Babylon, Noble, Sei, Osmosis, KiiChain and other IBC-enabled chains.
- In 2021, we helped [Helium](https://www.helium.com/) transition from a decentralized hotspot model to a dedicated validator set, running multiple validators and analytics infrastructure for the network during that critical phase.
- We operate some of the largest RPC, API, and IPFS arrays in web3. For both public and private clients, the RHINO team manages dozens of nodes that provide the infrastructure backbone for [Sei](https://sei-apis.com), [Berachain](https://berachain-apis.com), [Aptos](https://aptos-apis.com), [Cosmos Hub](https://cosmos.network/), and more. Currently our nodes handle over 30 billion RPC requests/month globally.

Although a small team, we utilize our deep experiences in security, network operations, infrastructure, and automation to deliver operations "at-scale" &mdash; working to reduce downtime, increase delegator rewards, and ultimately deliver better and more secure experiences to project teams and end-users.

## Our Infrastructure

RHINO utilizes a mix of RHINO-owned and cloud based infrastructure to deliver highly-available, redundant infrastructure for blockchain projects across ecosystems.

The following diagram outlines the high-level approach:

<p align="center">
  <img src="https://grabup.teamhim.com/achievement-precedentable-greekery-meschantly.png" />
</p>

Notable points and benefits to this redundant DC-based architecture:

- Within our [RHINO owned data centers](https://snapshots.rhinostake.com/rhinoshare/troy.rack.jpeg), all servers and network infrastructure have a minimum of n+1 redundancy across power supplies, power delivery, and battery backup.
- Network infrastructure includes dual 10Gb attach for all servers, and Virtual Routing and Forwarding (VRF) separation providing secure segmentation between management systems and per-customer chain infrastructure.
- Hypervisor virtualization with node clustering and live migration to distribute workloads for optimum performance as well as seamless maintenance.
- Additional use of bare metal servers allow for on-metal compute & direct disk access where necessary.
- Secure, high bandwidth, encrypted connectivity is in place between data center networks and public nodes to allow for node relocation, data duplication, and encrypted communication across sites.
- High availability firewalls provide secure, least privileged access and connectivity between systems, with 100% of all connections logged to a cloud monitoring system.
- Overlay networking with signed certificates and granular group controls eliminates traditional VPN vulnerabilities while providing fine-grained access control and complete visibility across our global infrastructure.
- Netflow data is generated for all network traffic, and is sent to a flow analytics system for threat detection.
- All traffic is subject to Snort based Intrusion Detection and Prevention.
- Wazuh provides comprehensive security monitoring including file integrity monitoring, CVE detection, and real-time intrusion detection across all systems.
- Signing keys are held in an encrypted vault requiring hardware security keys for access, on systems hardened to CIS benchmarks.
- [Horcrux](https://github.com/strangelove-ventures/horcrux) based RAFT threshold signing infrastructure runs across both RHINO owned data centers, with the 3rd cosigner in a geo-local cloud region (where applicable).
- Secure, out of band, multi-factor based remote management is in place for 24x7 monitoring and support by RHINO team.
- Zabbix, Wazuh, and Graylog monitor network, security and server hardware, hypervisor workload performance, intrusion detection, chain-metrics, signing performance, and event logging from all networking, server, and security infrastructure.
- 24x7 event escalation and alarm notification provided by PagerDuty.

Our infrastructure and operations are aligned with ISO 27001, and our ISO 27001:2022 certification is in progress.

## Our Contributions

We also try to contribute to each ecosystem we're in, through the production of tools and best practices valuable to node operators, partners and project teams.

- **Open source tooling for validators/node runners**:
  - [Monitor Your Aptos validator and validator fullnodes with Prometheus and Grafana](https://github.com/RhinoStake/aptos_monitoring)
  - [Ansible playbook for Aptos Node Management (Bare Metal)](https://github.com/RhinoStake/ansible-aptos)
- We provide **public RPC, API, gRPC endpoints, and seed nodes** for devnet, testnet and mainnet blockchains.

## Our Yawping

[![Game of Nodes](https://grabup.teamhim.com/seminormal-talukas-inscenation-sidewise.png)](https://rss.com/podcasts/game-of-nodes/)

Members of the RHINO team co-host **[Game of Nodes](https://twitter.com/gameofnodes_)**, a long-form podcast featuring independent validator teams discussing tech, governance, drama, and airdrops across Ethereum, Cosmos, Aptos, and everywhere else. Holistically wholesome since 2022.

The show is currently on hiatus, but the full back catalog is available on [YouTube](https://www.youtube.com/channel/UCWsyvi27z0i2bmOyBw1MAKA/videos?reload=9) and [RSS](https://rss.com/podcasts/game-of-nodes/) &mdash; add it to your favorite podcast player and you'll be first to know when we're back.
