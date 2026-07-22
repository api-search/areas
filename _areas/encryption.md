---
layout: area
slug: encryption
name: Encryption
description: An index and topic collection covering encryption services, key management systems (KMS), hardware security modules (HSM), envelope encryption, end-to-end encryption SDKs,…
area_url: https://encryption.apievangelist.com
area_host: encryption.apievangelist.com
icon: https://encryption.apievangelist.com/icon-thumb.png
provider_count: 42
providers:
- slug: amazon-kms
  name: Amazon KMS
  description: AWS Key Management Service (KMS) is a managed service that makes it easy to create and control the cryptographic keys used to protect your data, integrated with other AWS services to simplify encryption of data stored and managed in those services.
  api_count: 1
  score_band: strong
  score_composite: 66.3
  shared: 1
- slug: google-cloud-kms
  name: Google Cloud KMS
  description: Google Cloud Key Management Service (KMS) allows you to create, import, and manage cryptographic keys and perform cryptographic operations in a central cloud service. It supports encryption, decryption, signing, and verification using symmetric and asymmetric keys for securing data and workloads.
  api_count: 1
  score_band: developing
  score_composite: 59.2
  shared: 1
- slug: evervault
  name: Evervault
  description: Evervault is a data-security and payments-infrastructure platform that lets developers encrypt, tokenize, and process sensitive data - especially cardholder data - without it touching their own infrastructure. Its model stores encryption keys on Evervault's side while customers hold the ciphertext,…
  api_count: 1
  score_band: developing
  score_composite: 58.6
  shared: 1
- slug: amazon-certificate-manager
  name: Amazon Certificate Manager
  description: AWS Certificate Manager (ACM) handles the complexity of creating, storing, and renewing public and private SSL/TLS X.509 certificates and keys that protect your AWS websites and applications, enabling you to manage certificate lifecycles centrally.
  api_count: 1
  score_band: developing
  score_composite: 57.6
  shared: 1
- slug: vault
  name: HashiCorp Vault
  description: HashiCorp Vault is an open source tool for securely storing and accessing secrets. A secret is anything you want to tightly control access to, such as API keys, passwords, certificates, and more. Vault provides a unified interface to any secret while providing tight access control via policies and…
  api_count: 3
  score_band: developing
  score_composite: 56.8
  shared: 1
- slug: ironcore-labs
  name: IronCore Labs
  description: IronCore Labs builds application-layer encryption tools that keep sensitive data private while it stays usable. Its products include SaaS Shield (tenant-controlled envelope encryption with customer-managed keys / BYOK for multi-tenant SaaS), Cloaked Search (a transparent encrypting proxy for Elasti…
  api_count: 1
  score_band: developing
  score_composite: 55.7
  shared: 1
- slug: signal
  name: Signal
  description: Signal is a privacy-focused messaging platform that provides end-to-end encrypted communication through open-source applications on mobile and desktop. Their developer ecosystem centers around the open-source Signal Protocol, client SDKs, and server infrastructure, enabling developers to study, aud…
  api_count: 6
  score_band: developing
  score_composite: 52.1
  shared: 1
- slug: akeyless
  name: Akeyless
  description: Akeyless is a cloud-native identity security platform that unifies secrets management, machine identity, and privileged access for AI agents, machines, and humans at scale. The platform provides a REST API with 200+ endpoints covering secrets vaulting, dynamic secrets generation, certificate lifecy…
  api_count: 1
  score_band: developing
  score_composite: 51.8
  shared: 1
- slug: virtru
  name: Virtru
  description: Virtru is a data-centric security company whose Data Security Platform is built on OpenTDF, the open Trusted Data Format. Applications encrypt data with attribute-based access control (ABAC) and enforce who can decrypt it through Key Access Servers (KAS), independent of where the data travels — ema…
  api_count: 15
  score_band: developing
  score_composite: 50.0
  shared: 1
- slug: digicert
  name: Digicert
  description: Digicert is a leading provider of digital security solutions, specializing in SSL/TLS certificates, PKI solutions, and website security. They help organizations of all sizes protect their websites, data, and communications from cyber threats by providing secure encryption and authentication service…
  api_count: 5
  score_band: developing
  score_composite: 47.5
  shared: 1
- slug: infisical
  name: Infisical
  description: Infisical is an open-source secrets management platform that provides developers with a centralized, end-to-end encrypted vault for storing, syncing, and rotating secrets across teams, environments, and cloud infrastructure. The platform offers a REST API enabling programmatic management of secrets…
  api_count: 1
  score_band: developing
  score_composite: 46.7
  shared: 1
- slug: hvault
  name: HashiCorp Vault
  description: HashiCorp Vault secures, stores, and tightly controls access to tokens, passwords, certificates, API keys, and other secrets in modern computing. Vault handles leasing, key revocation, key rolling, and auditing. Through a unified API, users can access an encrypted Key/Value store and network encryp…
  api_count: 4
  score_band: developing
  score_composite: 46.6
  shared: 1
- slug: hashicorp-vault
  name: HashiCorp Vault
  description: HashiCorp Vault is a secrets management tool that provides secure storage, access control, and distribution of tokens, passwords, certificates, and encryption keys. It provides a unified interface to any secret while providing tight access control and recording a detailed audit log.
  api_count: 1
  score_band: developing
  score_composite: 45.2
  shared: 1
- slug: seismic-systems
  name: Seismic Systems
  description: Seismic Systems Inc. is a fintech company building a privacy-enabled ("encrypted") blockchain — a shielded EVM implementing the "Mercury" specification — that aims to power a complete stablecoin stack. Backed by a $17M seed led by a16z crypto, Seismic lets developers build private tokens (SRC20) wh…
  api_count: 1
  score_band: thin
  score_composite: 43.1
  shared: 1
- slug: vpn
  name: VPN
  description: A VPN (Virtual Private Network) creates an encrypted tunnel between a user's device and a remote network, protecting data from interception and masking the user's IP address. VPN technology is widely used for secure remote access to corporate networks, protecting privacy on public Wi-Fi, and bypass…
  api_count: 4
  score_band: thin
  score_composite: 42.3
  shared: 1
- slug: blindinsight
  name: BlindInsight
  description: BlindInsight (Blind Insight) is an end-to-end encrypted datastore and privacy-preserving data-analysis platform. It lets teams encrypt, ingest, search, and run machine learning and LLM queries over fully encrypted records without ever exposing plaintext, using a locally deployed Blind Proxy that tr…
  api_count: 1
  score_band: thin
  score_composite: 41.0
  shared: 1
- slug: skyflow
  name: Skyflow
  description: Skyflow is a data privacy vault platform that lets companies isolate, protect, and govern sensitive customer data (PII, PCI, PHI) and secrets in a zero-trust vault, then use it safely through tokenization, encryption, polymorphic de-identification, and fine-grained data governance. Developers integ…
  api_count: 2
  score_band: thin
  score_composite: 41.0
  shared: 1
- slug: sops
  name: SOPS
  description: SOPS (Secrets OPerationS) is a CNCF Sandbox encrypted file editor that supports YAML, JSON, ENV, INI, and binary formats. SOPS encrypts file values while leaving keys in cleartext, enabling secure storage of secrets in version control systems. Supports AWS KMS, GCP KMS, Azure Key Vault, HuaweiCloud…
  api_count: 1
  score_band: thin
  score_composite: 40.2
  shared: 1
- slug: incountry
  name: InCountry
  description: InCountry is a data-residency-as-a-service (DRaaS) platform that lets companies store, process, and comply with the data-localization and privacy laws of specific countries without building in-country infrastructure. Its OAuth2-secured REST API stores regulated records (PII, financial, and health d…
  api_count: 1
  score_band: thin
  score_composite: 39.8
  shared: 1
- slug: truevault
  name: TrueVault
  description: TrueVault provides developer infrastructure for storing and managing sensitive personal data in a compliant way. Its original product, TrueVault Safe, is a HIPAA-oriented REST API and secure datastore that lets applications create Vaults and store encrypted Documents, BLOBs, Users, and Schemas, wit…
  api_count: 1
  score_band: thin
  score_composite: 36.5
  shared: 1
- slug: xmtp
  name: XMTP
  description: XMTP (Extensible Message Transport Protocol) is a decentralized, open messaging protocol that enables end-to-end encrypted communication between Ethereum wallet addresses and other decentralized identifiers. Built on MLS (Messaging Layer Security), XMTP provides developer SDKs and a gRPC-based netw…
  api_count: 7
  score_band: thin
  score_composite: 33.5
  shared: 1
- slug: virgil-security
  name: Virgil Security
  description: Virgil Security is an end-to-end encryption and key-management platform for developers. It ships client SDKs and JWT-authenticated cloud services that let applications add end-to-end encryption for messaging and files (E3Kit), breach-proof password and data protection using Password-Hardened Encryp…
  api_count: 1
  score_band: thin
  score_composite: 31.9
  shared: 1
- slug: lattica
  name: Lattica
  description: LatticaAI is an Israeli privacy-technology company building Fully Homomorphic Encryption (FHE) as a service, letting AI inference and database queries run on encrypted data at cloud scale with zero plaintext exposure. Lattica builds the full stack — the cryptography, a compiler that turns models in…
  api_count: 1
  score_band: thin
  score_composite: 31.1
  shared: 1
- slug: plakar
  name: Plakar
  description: Plakar is an open-source, end-to-end encrypted, deduplicated backup and restore platform powered by Kloset, an immutable data store engine. It encrypts and deduplicates data at the source before it leaves your system (encryption keys stay in your own secret manager), stores it in a non-proprietary…
  api_count: 0
  score_band: emerging
  score_composite: 28.5
  shared: 1
- slug: ciphertrust
  name: CipherTrust
  description: CipherTrust Manager is Thales's centralized key- and data-security management platform and the control plane of the CipherTrust Data Security Platform (CDSP). It provides a unified plane for encryption key lifecycle management, secrets management, certificates, tokenization, data discovery, and pol…
  api_count: 1
  score_band: emerging
  score_composite: 20.3
  shared: 1
- slug: keybase
  name: Keybase
  description: Keybase is an end-to-end encrypted messaging, file-sharing, and key-directory platform built on public-key cryptography, founded by Chris Coyne and Max Krohn and acquired by Zoom in 2020. It maps human-readable usernames to public keys and cryptographically verifiable social-identity proofs (Twitte…
  api_count: 1
  score_band: emerging
  score_composite: 20.0
  shared: 1
- slug: anjuna
  name: Anjuna
  description: Anjuna Security provides a confidential-computing platform that lets organizations run existing applications inside hardware-based secure enclaves (Trusted Execution Environments) across AWS Nitro, AMD SEV, and Intel SGX without code changes, keeping data encrypted at rest, in transit, and in use.…
  api_count: 0
  score_band: emerging
  score_composite: 17.3
  shared: 1
- slug: confide
  name: Confide *
  description: Confide is a confidential messaging application that lets people communicate digitally with the same level of privacy and security as the spoken word. Messages are end-to-end encrypted, ephemeral (they disappear after being read), and screenshot-protected so recipients cannot capture or forward the…
  api_count: 0
  score_band: emerging
  score_composite: 16.6
  shared: 1
- slug: vera
  name: Vera
  description: Vera was a data-centric security company delivering information rights management (IRM) as a service, letting businesses encrypt, track, audit, and revoke access to files anywhere they travel, with an SDK and REST API for embedding AES 256-bit encryption and policy enforcement into applications. Ba…
  api_count: 0
  score_band: minimal
  score_composite: 12.8
  shared: 1
- slug: shardsecure
  name: ShardSecure
  description: ShardSecure is a data security company providing agentless, file-level data protection that keeps sensitive data private, resilient, and compliant across on-premises, cloud, and hybrid or multi-cloud environments. Its platform uses microsharding to cryptographically fragment and distribute data so…
  api_count: 0
  score_band: minimal
  score_composite: 12.3
  shared: 1
related:
- slug: privacy
  name: Privacy
  shared: 1
- slug: security
  name: Security
  shared: 1
overview: 'Encryption is one of the API Evangelist areas on the [APIs.io](https://apis.io/) network — a focused corner of the API landscape. The full area lives at [encryption.apievangelist.com](https://encryption.apievangelist.com).


  30 providers on the network work in this area, including Amazon KMS, Google Cloud KMS, Evervault, Amazon Certificate Manager, HashiCorp Vault, IronCore Labs, and 24 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Privacy and Security. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
