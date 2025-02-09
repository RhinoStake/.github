<p align="center">
  <img src="https://grabup.teamhim.com/eudemonics-nipponize-tearproof-hyponoia.png" />
</p>

[RHINO](https://rhinostake.com) is a blockchain infrastructure and services organization built on over 30 years of infrastructure, security and program delivery experience.

Launched in 2021, the RHINO team works closely with a significant number of blockchain projects across multiple ecosystems. We have been a part of multitude genesis ceremonies, contributed to the success of blockchain projects, and have been instrumental during testnet, launches, upgrades, and chain "incident" management.

Our strengths include delivering **secure, redundant and geo-distributed infrastructure at-scale** for **institutional investors, web3 project teams, venture capital**, as well as for our own staking operations.

We like to get involved in projects "early", offering a high amount of engagement, tooling, analytics, automation and needed assistance for new L1s. We're clear communicators, with experience in working with geo-distributed diverse validator teams and assist in the coordination, communication and documentation of efforts for efficient and performant testnets and mainnet launches.

## Our Involvement

Today we run operations for many different types of projects:

- RHINO is a selected "genesis" node operator for [Aptos](https://aptoslabs.com/), including the responsibility of managing the staking pool validator operations for Aptos Labs Corporation. We provide the Aptos ecosystem's largest global API service at [aptos-apis.com](https://aptos-apis.com).
- RHINO is a [Chainlink](https://chain.link/) node operator providing [Decentralized Data Feeds](https://chain.link/data-feeds), [Proof of Reserve](https://chain.link/proof-of-reserve), and [VRF](https://chain.link/vrf) across multiple ecosystems.
- RHINO is a Chinlink Risk Management Network node operator, a crucial part of the [Chainlink Cross-Chain Interoperability Protocol (CCIP)](https://chain.link/cross-chain). We provide transaction verification across all CCIP participating networks, with global redundancy and distribution of nodes.
- We run validators and infrastructure for many tendermint based chains including [Sei](https://www.mintscan.io/sei/validators/seivaloper146m089lq8mkqw6w0mmlhxz6247g2taha89at74), [Juno](https://www.mintscan.io/juno/validators/junovaloper166r5ylkp70xe0ysq2hjxn26m4q9vfn8q3lv46c), [Evmos](https://www.mintscan.io/evmos/validators/evmosvaloper1vrruadnv4glvjze923m9rjaq96fyzks6egmspz), [Stargaze](https://www.mintscan.io/stargaze/validators/starsvaloper1xru87608vdps23q4s79006lcsm0tfxcl4juuy5), [Omniflix](https://www.mintscan.io/omniflix/validators/omniflixvaloper1kwrz43n3u7ha6a4k6rndxdw3rt2rw6us2jqet2), [Stride](https://www.mintscan.io/stride/validators/stridevaloper1x6vpftuzdy44uxpsumhr8sxyapth8nf5crq6sy), [eMoney](https://www.mintscan.io/emoney/validators/emoneyvaloper1ght4t8sf4xv4eyma2su7evvdfcx0w89kaphfnk), [Chihuahua](https://www.mintscan.io/chihuahua/validators/chihuahuavaloper14wgwtldstxfp93tcvgkdulpje3mn5u2pum7xsl), [Nomic](https://app.nomic.io/#/staking), and more.
- The RHINO team runs multiple validators and analytics infrastructure for the world’s largest network, [Helium](https://www.helium.com/).
- Lastly, we operate some of the largest RPC, API and IPFS arrays in web3. For both public and private clients, the RHINO team manages dozens of nodes that provide the rpc infrastructure backbone for [Stargaze](https://stargaze.zone), the [Sei Network](https://app.sei.io/), the [MetaMask Snap for Cosmos](https://github.com/cosmos/snap), [Aptos](https://aptos-apis.com), and more. Currently our nodes handle over 30 Billion RPC requests/month globally.

Although a small team, we utilize our deep experiences in security, network operations, infrastructure and automation to deliver operations "at-scale" &mdash; working to reduce downtime, increase delegator rewards, and ultimately deliver better and more secure experiences to project teams and end-users.

## Our Infrastructure

RHINO utilizes a mix of RHINO-owned and cloud based infrastructure to deliver highly-available, redundant infrastructure for blockchain projects across ecosystems.

The following diagram outlines the high-level approach:

<p align="center">
  <img src="https://grabup.teamhim.com/achievement-precedentable-greekery-meschantly.png" />
</p>

Notable points and benefits to this redundant DC-based architecture:

- Within our RHINO owned data centers, all servers and network infrastructure have a minimum of n+1 redundancy across power supplies, power delivery, and battery backup.
- Network infrastructure includes dual 10Gb attach for all servers, and Virtual Routing and Forwarding (VRF) separation providing secure segmentation between management systems and per-customer chain infrastructure.
- Hypervisor virtualization is provided by VMWare, with node clustering and vMotion capabilities to distributed workloads for optimum performance as well as seamless maintenance.
- Additional use of bare metal servers allow for on-metal compute & direct disk access where necessary.
- Secure, high bandwidth, encrypted connectivity is in place between data center networks and public nodes to allow for node relocation, data duplication, and encrypted communication across sites.
- High availability firewalls provide secure, least privileged access and connectivity between systems, with 100% of all connections logged to a cloud monitoring system
- Netflow data is generated for all network traffic, and is sent to a flow analytics system for threat detection.
- All traffic is subject to Snort based Intrusion Detection and Prevention.
- Secure, out of band, multi-factor based remote management is in place for 24x7 monitoring and support by RHINO team.
- [Horcrux](https://github.com/strangelove-ventures/horcrux) based RAFT signing infrastructure exists in both RHINO owned racks with the 3rd node running in a geo-local region (where applicable).
- On-premises and cloud-based monitoring and alerting systems are employed to monitor network, security and server hardware, hypervisor workload performance, security analytics, intrusion detection, chain-metrics, signing performance, as well as event logging from all networking, server, and security infrastructure.
- 24x7 event escalation and alarm notification provided by PagerDuty.

## Our Contributions

We also try to contribute to each ecosystem we're in, through the production of tools and best practices valuable to node operators, partners and project teams.

- **Open source tooling for validators/node runners**:
  - [Monitor Your Aptos validator and validator fullnodes with Prometheus and Grafana](https://github.com/RhinoStake/aptos_monitoring)
  - [Ansible playbook for Aptos Node Management (Bare Metal)](https://github.com/RhinoStake/ansible-aptos)
  - [Ansible playbook for Berachain Node Management (Bare Metal)](https://github.com/RhinoStake/ansible-berachain)
  - [Ansible playbook for Secure Server Setup, including server setup, Cosmos/tenderint chains, Aptos, Chainlink, horcrux, and more](https://github.com/RhinoStake/secure-server-setup-ansible)
- We provide **public RPC, API, gRPC endpoints, and seed nodes** for devnet, testnet and mainnet blockchains.

## Our Yawping

[![Game of Nodes](https://grabup.teamhim.com/seminormal-talukas-inscenation-sidewise.png)](https://rss.com/podcasts/game-of-nodes/)

Finally, be sure to catch members of the RHINO team on **[Game of Nodes](https://twitter.com/gameofnodes_)**! We broadcast live on [YouTube](https://www.youtube.com/channel/UCWsyvi27z0i2bmOyBw1MAKA/videos?reload=9) and [Twitter](https://twitter.com/gameofnodes_) every **Wednesday at 21:00 UTC**.

Game of Nodes is weekly long-form podcast featuring independent validator teams discussing tech, governance, drama, and airdrops across Ethereum, Cosmos, Aptos, and everywhere else. Holistically wholesome since 2022.

Add [Game of Nodes](https://rss.com/podcasts/game-of-nodes/) to your favorite podcast player today!
