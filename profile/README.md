<p align="center">
  <img src="https://grabup.teamhim.com/eudemonics-nipponize-tearproof-hyponoia.png" />
</p>

[RHINO](https://rhinostake.com) is a blockchain infrastructure and services organization built on over 30 years of infrastructure, security and program delivery experience.

Launched in 2021, the RHINO team works closely with a significant number of blockchain projects across multiple ecosystems. We have been a part of multitude genesis ceremonies, contributed to the success of blockchain projects, and have been instrumental during testnet, launches, upgrades, and chain "incident" management.

Today we run infrastructure and operations for many different types of PoS blockchains:

- Tendermint based chains running in mainnet include [Juno](https://www.mintscan.io/juno/validators/junovaloper166r5ylkp70xe0ysq2hjxn26m4q9vfn8q3lv46c), [Evmos](https://www.mintscan.io/evmos/validators/evmosvaloper1vrruadnv4glvjze923m9rjaq96fyzks6egmspz), [Stargaze](https://www.mintscan.io/stargaze/validators/starsvaloper1xru87608vdps23q4s79006lcsm0tfxcl4juuy5), [Omniflix](https://www.mintscan.io/omniflix/validators/omniflixvaloper1kwrz43n3u7ha6a4k6rndxdw3rt2rw6us2jqet2), [Stride](https://www.mintscan.io/stride/validators/stridevaloper1x6vpftuzdy44uxpsumhr8sxyapth8nf5crq6sy), [eMoney](https://www.mintscan.io/emoney/validators/emoneyvaloper1ght4t8sf4xv4eyma2su7evvdfcx0w89kaphfnk), [Chihuahua](https://www.mintscan.io/chihuahua/validators/chihuahuavaloper14wgwtldstxfp93tcvgkdulpje3mn5u2pum7xsl), [Konstellation](https://www.mintscan.io/konstellation/validators/darcvaloper1zta4mcnrn08a0wwwku7wxsef3y2rv8zqwr0mg0), and [Nomic](https://app.nomic.io/#/staking). We provide global, redundant RPC and API services for [Stargaze](https://www.stargaze.zone/), the largest and fastest growing NFT platform in the Cosmos ecosystem.
- The RHINO team runs multiple validators and analytics infrastructure for the world’s largest network, [Helium](https://www.helium.com/).
- RHINO is a [Chainlink](https://chain.link/) [node operator](https://market.link/nodes/RHINO) providing [Decentralized Data Feeds](https://chain.link/data-feeds), [Proof of Reserve](https://chain.link/proof-of-reserve), and [VRF](https://chain.link/vrf) across multiple ecosystems.
- Most recently, RHINO is a selected "genesis" node operator for [Aptos](https://aptoslabs.com/), including the responsibility of running the staking pool for Aptos Labs Corporation.

Although a small team, we utilize our deep experiences in security, network operations, infrastructure and automation to deliver operations "at-scale" &mdash; working to reduce downtime, increase delegator rewards, and ultimately deliver a better and more secure experiences to project teams and end-users.

## Our Infrastructure

RHINO utilizes a mix of RHINO-owned and cloud based infrastructure to deliver highly-available, redundant infrastructure for blockchain projects across ecosystems.

The following diagram outlines the high-level approach:

<p align="center">
  <img src="https://grabup.teamhim.com/achievement-precedentable-greekery-meschantly.png" />
</p>

Notable points and benefits to this redundant DC-based architecture:

- All servers and network infrastructure have redundant power supplies, connected to separate data center circuits
- Network infrastructure includes dual 10Gb attach for all servers, and Virtual Routing and Forwarding (VRF) separation providing secure segmentation between management systems and per-customer chain infrastructure
- Hypervisor virtualization is provided by VMWare, with node clustering and vMotion capabilities to distributed workloads for optimum performance as well as seamless maintenance
- Addition of bare metal servers allow for on-metal compute & direct disk access where necessary
- Secure, high bandwidth, encrypted connectivity is in place between data center networks to allow for node relocation and data duplication between sites
- High availability firewalls provide secure, least privileged access and connectivity between systems, with 100% of all connections logged to a cloud monitoring system
- Netflow data is generated for all network traffic, and is sent to a flow analytics system for threat detection
- All traffic is subject to Snort based Intrusion Detection and Prevention
- Secure, out of band, multi-factor based remote management is in place for 24x7 monitoring and support by RHINO team
- [Horcrux](https://github.com/strangelove-ventures/horcrux) based RAFT signing infrastructure exists in both RHINO owned racks with the 3rd node running on AWS in a geo-local region (where applicable)
- On-premises and cloud management systems are employed to monitor network, security and server hardware, hypervisor workload performance, security analytics and intrusion detection, as well as event logging from all networking, server, and security infrastructure
- 24x7 event escalation and alarm notification provided by PagerDuty

## Our Contributions

We also try to contribute to each ecosystem we're in, through the production of tools and best practices valuable to node operators, partners and project teams.

- We provide **public RPC, API, and gRPC endpoints** for devnet, testnet and mainnet blockchains.
- We provide a public **seed node** for networks we operate on.
- **Open source tooling for validators/node runners**:
  - [Monitor Your Aptos validator and validator fullnodes with Prometheus and Grafana](https://github.com/RhinoStake/aptos_monitoring)
  - [Ansible playbook for Aptos Node Management (Bare Metal)](https://github.com/RhinoStake/ansible-aptos)
  - [Ansible playbook for Secure Server Setup, including server setup, cosmos, horcrus, ](https://github.com/RhinoStake/secure-server-setup-ansible)

Finally, be sure to catch members of the RHINO team on [Game of Nodes](https://twitter.com/gameofnodes_)! Broadcast live on [YouTube](https://www.youtube.com/channel/UCWsyvi27z0i2bmOyBw1MAKA/videos?reload=9) and [Twitter](https://twitter.com/gameofnodes_) every **Wednesday at 21:00 UTC**.

Find [Game of Nodes](https://rss.com/podcasts/game-of-nodes/) in your favorite Podcast Player.

