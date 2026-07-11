---
layout: area
slug: consensus
name: Consensus
description: Consensus is the distributed systems problem of getting a set of unreliable processes to agree on a value or sequence of values. Consensus algorithms power state-machine replication for databases, key-value stores, configuration systems, and blockchains. The consensus topic spans classical crash-fault tolerant algorithms (Paxos, Raft, Multi-Paxos, Zab, Viewstamped Replication) and Byzantine fault tolerant algorithms (PBFT, Tendermint, HotStuff, Casper FFG/CBC), and the impossibility result FLP that bounds what is possible in fully asynchronous models.
tags:
- Algorithms
- BFT
- Blockchain
- Consensus
- Crash Fault Tolerance
- Distributed Systems
- Replication
- State Machine
resource_count: 5
provider_count: 191
resources:
- name: Paxos
  description: Paxos is the classical crash-fault-tolerant consensus algorithm introduced by Leslie Lamport in 1989. Paxos and its derivatives (Multi-Paxos, Cheap Paxos, Vertical Paxos, EPaxos, Flexible Paxos) are foundational to distributed systems theory and are used in Google Chubby, Spanner, Megastore, and others.
  url: https://lamport.azurewebsites.net/pubs/paxos-simple.pdf
  tags:
  - Lamport
  - Paxos
  - Replication
  properties:
  - type: Specification
    url: https://lamport.azurewebsites.net/pubs/paxos-simple.pdf
  - type: Reference
    url: https://www.cs.utexas.edu/users/lorenzo/corsi/cs380d/papers/paper2-1.pdf
  - type: Reference
    url: https://en.wikipedia.org/wiki/Paxos_(computer_science)
- name: Raft
  description: Raft is a consensus algorithm designed for understandability, published by Ongaro and Ousterhout in 2014. Raft separates leader election, log replication, and safety into distinct concepts and is implemented widely in etcd, Consul, CockroachDB, TiKV, MongoDB, and many other production systems.
  url: https://raft.github.io/
  tags:
  - etcd
  - Leader Election
  - Log Replication
  - Raft
  properties:
  - type: Specification
    url: https://raft.github.io/raft.pdf
  - type: Documentation
    url: https://raft.github.io/
  - type: Reference
    url: https://thesecretlivesofdata.com/raft/
- name: Practical Byzantine Fault Tolerance (PBFT)
  description: PBFT, by Castro and Liskov (1999), is a Byzantine fault-tolerant consensus protocol that tolerates up to f Byzantine failures with 3f+1 replicas. PBFT influenced subsequent BFT protocols including Tendermint and HotStuff.
  url: http://pmg.csail.mit.edu/papers/osdi99.pdf
  tags:
  - BFT
  - PBFT
  properties:
  - type: Specification
    url: http://pmg.csail.mit.edu/papers/osdi99.pdf
  - type: Reference
    url: https://en.wikipedia.org/wiki/Byzantine_fault
- name: Tendermint / CometBFT
  description: Tendermint (now CometBFT) is a Byzantine fault-tolerant consensus engine that powers Cosmos SDK chains. CometBFT decouples consensus from application logic via the Application Blockchain Interface (ABCI), allowing custom blockchain applications in Go, Rust, and other languages.
  url: https://docs.cometbft.com/
  tags:
  - ABCI
  - BFT
  - Blockchain
  - CometBFT
  - Cosmos
  properties:
  - type: Documentation
    url: https://docs.cometbft.com/
  - type: GitHubRepository
    url: https://github.com/cometbft/cometbft
  - type: Reference
    url: https://docs.cometbft.com/main/spec/consensus/consensus.html
- name: HotStuff
  description: HotStuff is a leader-based BFT consensus protocol with linear view change and three-chain commit, designed by Yin et al. HotStuff is the foundation for Diem/Libra BFT and inspired modern protocols like Aptos AptosBFT and Sui's Mysticeti.
  url: https://arxiv.org/abs/1803.05069
  tags:
  - BFT
  - HotStuff
  - Linear
  properties:
  - type: Specification
    url: https://arxiv.org/abs/1803.05069
  - type: Reference
    url: https://github.com/hot-stuff/libhotstuff
  - type: Reference
    url: https://github.com/aptos-labs/aptos-core
providers:
- slug: consensus
  name: Consensus
  description: Consensus is the distributed systems problem of getting a set of unreliable processes to agree on a value or sequence of values. Consensus algorithms power state-machine replication for databases, key-value stores, configuration systems, and blockchains. The consensus topic spans classical crash-fa…
  api_count: 5
  score_band: minimal
  score_composite: 23.3
  shared: 8
- slug: apache-helix
  name: Apache Helix
  description: Apache Helix is a generic cluster management framework for partitioned and replicated distributed resources. It automates partition management, replication, fault tolerance, and cluster expansion for distributed systems, providing a REST API for cluster administration and a Java API for participant…
  api_count: 2
  score_band: thin
  score_composite: 43.3
  shared: 2
- slug: etcd
  name: Etcd
  description: etcd is a CNCF graduated distributed, reliable key-value store used as the backing store for all Kubernetes cluster data. It provides strong consistency guarantees using the Raft consensus algorithm, supporting watch operations, lease-based TTLs, and atomic compare-and-swap transactions. etcd is de…
  api_count: 5
  score_band: thin
  score_composite: 40.1
  shared: 2
- slug: pocket-network
  name: Pocket Network
  description: Pocket Network is the decentralized RPC layer of Web3 — a permissionless, fully open data delivery protocol built on Cosmos SDK and CometBFT (the Shannon upgrade, June 2025). 5,000+ independent supplier nodes serve relays across 60-69+ blockchains, metered in compute units at $1/billion and settled…
  api_count: 3
  score_band: strong
  score_composite: 60.4
  shared: 1
- slug: blockfrost
  name: Blockfrost
  description: Blockfrost is a RESTful API service providing access to the Cardano blockchain and its ecosystem. It serves as an infrastructure layer for developers building dApps, wallets, NFT platforms, DeFi protocols, and analytics tools on Cardano. Blockfrost provides endpoints for querying blocks, transactio…
  api_count: 1
  score_band: developing
  score_composite: 59.4
  shared: 1
- slug: solana
  name: Solana
  description: Solana is a high-performance blockchain platform designed for fast, secure, and scalable decentralized applications and marketplaces. It exposes a JSON-RPC 2.0 API over HTTP and WebSocket for querying accounts, transactions, programs, token balances, blocks, and cluster state, as well as submitting…
  api_count: 7
  score_band: developing
  score_composite: 58.3
  shared: 1
- slug: amazon-managed-blockchain
  name: Amazon Managed Blockchain
  description: Amazon Managed Blockchain is a fully managed service that allows you to create and manage scalable blockchain networks using popular open-source frameworks such as Hyperledger Fabric and Ethereum. It eliminates the overhead required to create the network or join a public network, and automatically…
  api_count: 1
  score_band: developing
  score_composite: 56.9
  shared: 1
- slug: covalent
  name: Covalent
  description: ''
  api_count: 6
  score_band: developing
  score_composite: 56.8
  shared: 1
- slug: couchbase
  name: Couchbase
  description: Couchbase is a distributed, document-oriented NoSQL cloud database platform that combines the flexibility of JSON, the power of SQL++ querying, and the performance of an in-memory key-value store. The Couchbase product line includes Couchbase Server (self-managed), Couchbase Capella (fully managed…
  api_count: 12
  score_band: developing
  score_composite: 56.4
  shared: 1
- slug: apache-couchdb
  name: Apache CouchDB
  description: Apache CouchDB is an open-source distributed document-oriented NoSQL database governed by the Apache Software Foundation. It uses JSON for data storage, a RESTful HTTP/JSON API for all database operations, and the Couch Replication Protocol for multi-primary synchronization across servers, mobile d…
  api_count: 1
  score_band: developing
  score_composite: 56.3
  shared: 1
- slug: microsoft-azure-migrate
  name: Azure Migrate
  description: Azure Migrate provides a unified platform for discovering, assessing, and migrating on-premises servers, infrastructure, applications, databases, and data to Azure. Its REST APIs enable programmatic management of migration projects, discovery, assessment, and replication workflows for VMs, database…
  api_count: 8
  score_band: developing
  score_composite: 56.2
  shared: 1
- slug: amazon-iot-events
  name: Amazon IoT Events
  description: AWS IoT Events is a managed service that makes it easy to detect and respond to events from IoT sensors and applications. You can use it to build complex event detection logic, create state machines for IoT workflows, and trigger alerts or actions when specific conditions are met.
  api_count: 1
  score_band: developing
  score_composite: 55.9
  shared: 1
- slug: chainstack
  name: Chainstack
  description: Chainstack is a managed multi-chain RPC and node infrastructure platform supporting 70+ blockchain protocols including Ethereum, Solana, Bitcoin, BNB Smart Chain, Polygon, Arbitrum, Optimism, Base, Avalanche, TON, TRON, Starknet, zkSync Era, Hyperliquid, Monad, and many more. The platform exposes a…
  api_count: 26
  score_band: developing
  score_composite: 54.9
  shared: 1
- slug: coingecko
  name: CoinGecko
  description: 'CoinGecko is a cryptocurrency data aggregator providing market data, analytics, and information on thousands of crypto assets, exchanges, derivatives, NFTs, and on-chain decentralized markets worldwide. The CoinGecko Developer Platform exposes three primary APIs: the public Crypto Market Data API (…'
  api_count: 3
  score_band: developing
  score_composite: 54.8
  shared: 1
- slug: cryptocompare
  name: CryptoCompare
  description: CryptoCompare (now CoinDesk Data / CCData, acquired by CoinDesk in late 2024) is a long-standing crypto market data aggregator covering 300+ exchanges, 10,000+ assets, and 300,000+ trading pairs. The platform exposes two REST API surfaces — the legacy min-api.cryptocompare.com (Price, Historical OH…
  api_count: 4
  score_band: developing
  score_composite: 54.8
  shared: 1
- slug: arweave
  name: Arweave
  description: Arweave is a permanent decentralized data storage network that enables developers to store data forever with a single upfront payment. It provides REST and GraphQL APIs for uploading data, querying blocks and transactions by tags and metadata, retrieving wallet balances, and accessing the permaweb…
  api_count: 3
  score_band: developing
  score_composite: 54.2
  shared: 1
- slug: aptos
  name: Aptos
  description: Aptos is a Move-based Layer 1 blockchain platform that exposes a REST API for reading on-chain state and submitting transactions, a GraphQL Indexer API for high-level queries over processed blockchain data (NFTs, objects, custom Move contracts), and a gRPC Transaction Stream for real-time and histo…
  api_count: 4
  score_band: developing
  score_composite: 54.1
  shared: 1
- slug: amazon-qldb
  name: Amazon QLDB
  description: Amazon Quantum Ledger Database (QLDB) is a fully managed ledger database that provides a transparent, immutable, and cryptographically verifiable transaction log. QLDB tracks each and every application data change and maintains a complete and verifiable history of changes over time, making it ideal…
  api_count: 1
  score_band: developing
  score_composite: 54.0
  shared: 1
- slug: amazon-step-functions
  name: Amazon Step Functions
  description: Amazon Step Functions is a serverless workflow orchestration service that lets you coordinate distributed applications and microservices using visual workflows, enabling you to build and update state machines that react to events, manage retries, and orchestrate complex business processes.
  api_count: 1
  score_band: developing
  score_composite: 53.6
  shared: 1
- slug: iota
  name: IOTA
  description: IOTA is an open-source distributed ledger technology built to bring real-world applications on-chain. It is the first internet-scale programmable blockchain platform powered by the Move programming language with horizontal scaling, feeless transactions, and a unique parallel transaction processing…
  api_count: 9
  score_band: developing
  score_composite: 53.0
  shared: 1
- slug: coinbase
  name: Coinbase
  description: Coinbase is a leading cryptocurrency platform providing trading, custody, and payment infrastructure for individuals, businesses, and institutions. The Coinbase Developer Platform (CDP) exposes a wide product surface across retail trading (Advanced Trade), professional and institutional trading (Ex…
  api_count: 8
  score_band: developing
  score_composite: 51.1
  shared: 1
- slug: apache-bookkeeper
  name: Apache BookKeeper
  description: Apache BookKeeper is a scalable, fault-tolerant, and low-latency storage service optimized for real-time workloads developed by the Apache Software Foundation. It provides a simple log-oriented storage abstraction called ledgers for reliable, replicated storage of sequential data. BookKeeper is use…
  api_count: 2
  score_band: developing
  score_composite: 51.0
  shared: 1
- slug: algorand
  name: Algorand
  description: Algorand is a pure proof-of-stake blockchain platform designed for speed, security, and decentralization. It exposes REST APIs through two core daemons — Algod (the Algorand protocol daemon) for real-time node interaction including submitting transactions, querying account balances, retrieving bloc…
  api_count: 3
  score_band: developing
  score_composite: 50.9
  shared: 1
- slug: circle
  name: Circle
  description: Circle Internet Financial is the issuer of USDC and EURC and operates a developer platform for moving regulated stablecoin money across the internet. Their APIs cover programmable wallets (developer- and user-controlled), gas sponsorship, the Cross-Chain Transfer Protocol (CCTP), Gateway unified ba…
  api_count: 10
  score_band: developing
  score_composite: 50.3
  shared: 1
related:
- slug: circuit-breaker
  name: Circuit Breaker
  shared: 1
repo: https://github.com/api-evangelist/consensus
overview: 'Consensus on the [APIs.io](https://apis.io/) network is a curated area collecting 5 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including Consensus, Apache Helix, Etcd, Pocket Network, Blockfrost, Solana, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Circuit Breaker. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
