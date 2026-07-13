---
layout: area
slug: caching
name: Caching
description: An index and topic collection covering API-accessible caching services, in-memory data stores, key-value caches, and edge/CDN cache APIs. Caching reduces latency, lowers backend…
area_url: https://caching.apievangelist.com
area_host: caching.apievangelist.com
icon: https://caching.apievangelist.com/icon-thumb.png
provider_count: 13
providers:
- slug: amazon-elasticache
  name: Amazon ElastiCache
  description: Amazon ElastiCache is a fully managed in-memory caching service supporting Redis and Memcached. ElastiCache makes it easy to deploy, operate, and scale popular open-source compatible in-memory data stores, improving the performance of web applications.
  api_count: 1
  score_band: strong
  score_composite: 67.1
  shared: 1
- slug: apache-ignite
  name: Apache Ignite
  description: Apache Ignite is a distributed database for mission-critical high-velocity applications requiring in-memory performance. It provides ACID transactions, SQL queries, key-value storage, compute grid, and backpressured streaming across distributed clusters. Governed by the Apache Software Foundation u…
  api_count: 3
  score_band: developing
  score_composite: 57.6
  shared: 1
- slug: google-cloud-cdn
  name: Google Cloud CDN
  description: Google Cloud CDN (Content Delivery Network) uses Google's globally distributed edge points of presence to cache HTTP(S) load-balanced content close to users. It accelerates content delivery, reduces serving costs, and improves availability by leveraging Google's global network infrastructure for fa…
  api_count: 1
  score_band: developing
  score_composite: 51.7
  shared: 1
- slug: apache-geode
  name: Apache Geode
  description: Apache Geode is an in-memory data management platform that provides real-time, consistent access to data-intensive applications throughout widely distributed cloud architectures. It pools memory, CPU, network resources, and local disk storage across multiple processes, offering a REST API for data…
  api_count: 2
  score_band: developing
  score_composite: 48.3
  shared: 1
- slug: gridgain
  name: GridGain
  description: GridGain is a unified real-time data platform that provides in-memory computing for transactions, analytics, and AI workloads. Built on top of Apache Ignite, it offers distributed database, caching, and computing capabilities for high-performance data-intensive applications.
  api_count: 2
  score_band: thin
  score_composite: 41.4
  shared: 1
- slug: cloudflare-ai-gateway
  name: Cloudflare AI Gateway
  description: Cloudflare AI Gateway is a managed LLM proxy that sits in front of 23+ AI providers (OpenAI, Anthropic, Google AI Studio, Google Vertex AI, Amazon Bedrock, Azure OpenAI, Workers AI, Mistral, Cohere, Groq, DeepSeek, Cerebras, xAI, Perplexity, Replicate, HuggingFace, OpenRouter, ElevenLabs, Deepgram,…
  api_count: 4
  score_band: thin
  score_composite: 40.0
  shared: 1
- slug: scalable-systems
  name: Scalable Systems
  description: A topic collection focused on APIs, tools, and platforms for designing and operating scalable distributed systems. Covers load balancing, auto-scaling, service discovery, distributed caching, message queues, and the cloud infrastructure APIs that enable systems to handle growth in data, traffic, an…
  api_count: 8
  score_band: thin
  score_composite: 35.7
  shared: 1
- slug: blacksmith-sh
  name: Blacksmith
  description: Blacksmith runs your GitHub Actions up to 2x faster at half the cost on a fleet of modern gaming-CPU bare metal, booting ephemeral Firecracker microVMs in under three seconds. It is a drop-in replacement integrated as a GitHub App and selected via runs-on runner tags, with a co-located CI cache, 40…
  api_count: 5
  score_band: thin
  score_composite: 34.2
  shared: 1
- slug: turborepo
  name: Turborepo
  description: Turborepo is a high-performance build system for JavaScript and TypeScript codebases, built by Vercel and written in Rust. It accelerates monorepo development by orchestrating task pipelines with explicit dependency graphs, hashing task inputs to skip redundant work, and caching task outputs locall…
  api_count: 1
  score_band: minimal
  score_composite: 29.9
  shared: 1
- slug: openpipe
  name: OpenPipe
  description: OpenPipe is a fine-tuning and inference platform for distilling expensive frontier-LLM workloads into smaller, cheaper specialized models. Captures production traces (OpenAI and Anthropic), fine-tunes, evaluates with judges, caches results, and serves the result via OpenAI-compatible API. Also supp…
  api_count: 1
  score_band: minimal
  score_composite: 28.5
  shared: 1
- slug: varnish
  name: Varnish Cache
  description: Varnish Cache is a high-performance HTTP accelerator and reverse proxy designed for content-heavy dynamic websites and APIs. It sits in front of web servers and caches HTTP responses to serve repeated requests without hitting the backend, dramatically reducing load and latency. Varnish is configure…
  api_count: 3
  score_band: minimal
  score_composite: 25.7
  shared: 1
- slug: tailcall
  name: Tailcall
  description: Tailcall is a high-performance GraphQL API gateway and runtime that lets developers compose multiple upstream REST, gRPC, and GraphQL APIs into a unified GraphQL schema. Built in Rust, it offers declarative configuration via .graphql files with directives for HTTP, caching, batching, and security c…
  api_count: 2
  score_band: minimal
  score_composite: 25.2
  shared: 1
- slug: cloudfront
  name: CloudFront
  description: CloudFront is Amazon Web Services' content delivery network (CDN) for delivering data, video, applications, and APIs globally with low latency. This repository is the short-form profile for AWS CloudFront; the canonical AWS service profile lives at amazon-cloudfront in the API Evangelist Network. C…
  api_count: 1
  score_band: minimal
  score_composite: 25.1
  shared: 1
related:
- slug: network
  name: Network
  shared: 1
- slug: proxy
  name: Proxy
  shared: 1
- slug: database
  name: Database
  shared: 1
overview: 'Caching is one of the API Evangelist areas on the [APIs.io](https://apis.io/) network — a focused corner of the API landscape. The full area lives at [caching.apievangelist.com](https://caching.apievangelist.com).


  13 providers on the network work in this area, including Amazon ElastiCache, Apache Ignite, Google Cloud CDN, Apache Geode, GridGain, Cloudflare AI Gateway, and 7 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Network, Proxy, and Database. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
