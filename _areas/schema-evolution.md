---
layout: area
slug: schema-evolution
name: Schema Evolution
description: Schema Evolution is the practice of managing changes to data schemas over time while preserving compatibility between producers and consumers. It covers backward compatibility, forward compatibility, full compatibility, breaking change detection, schema migration strategies, and versioning patterns for REST APIs, event streaming (Kafka/Avro), GraphQL, database schemas, and Protocol Buffers. Effective schema evolution is critical for maintaining API contracts and enabling independent deployment of distributed system components.
tags:
- Schema Evolution
- Backward Compatibility
- Forward Compatibility
- API Versioning
- Breaking Changes
- Schema Registry
- Data Migration
- Kafka
resource_count: 3
provider_count: 31
resources:
- name: Confluent Schema Registry API
  description: The Confluent Schema Registry provides a serving layer for your metadata. It provides a RESTful interface for storing and retrieving your Avro, JSON Schema, and Protobuf schemas. It stores a versioned history of all schemas based on a specified subject name strategy, provides multiple compatibility settings and allows…
  url: https://docs.confluent.io/platform/current/schema-registry/develop/api.html
  tags:
  - Schema Registry
  - Confluent
  - Kafka
  - Avro
  - Compatibility
  properties:
  - type: Documentation
    url: https://docs.confluent.io/platform/current/schema-registry/develop/api.html
  - type: Reference
    url: https://docs.confluent.io/platform/current/schema-registry/fundamentals/schema-evolution.html
  - type: OpenAPI
    url: openapi/schema-evolution-openapi.yml
  - type: GraphQL
    url: graphql/schema-evolution-graphql.md
- name: AWS Glue Schema Registry API
  description: AWS Glue Schema Registry is a feature that enables you to centrally discover, control, and evolve data stream schemas. The AWS Glue Schema Registry API supports creating, deleting, listing, updating, and fetching schemas, and it supports compatibility checking for Avro and JSON Schema formats.
  url: https://docs.aws.amazon.com/glue/latest/dg/schema-registry.html
  tags:
  - AWS
  - Schema Registry
  - Cloud
  - Avro
  properties:
  - type: Documentation
    url: https://docs.aws.amazon.com/glue/latest/dg/schema-registry.html
- name: Apicurio Schema Registry API
  description: Apicurio Registry is a datastore for standard event schemas and API designs. Apicurio Registry enables you to add, update, and remove artifacts from the registry using a REST API interface. It supports Apache Avro, JSON Schema, Protobuf, GraphQL SDL, and more, with configurable compatibility rules including backward,…
  url: https://www.apicur.io/registry/
  tags:
  - Schema Registry
  - Open Source
  - Avro
  - Compatibility
  properties:
  - type: Documentation
    url: https://www.apicur.io/registry/
  - type: GitHubRepository
    url: https://github.com/Apicurio/apicurio-registry
providers:
- slug: schema-evolution
  name: Schema Evolution
  description: Schema Evolution is the practice of managing changes to data schemas over time while preserving compatibility between producers and consumers. It covers backward compatibility, forward compatibility, full compatibility, breaking change detection, schema migration strategies, and versioning patterns…
  api_count: 3
  score_band: thin
  score_composite: 31.1
  shared: 8
- slug: confluent-schema-registry
  name: Confluent Schema Registry
  description: Confluent Schema Registry is the open-source serving layer for schema metadata used in Apache Kafka data pipelines. It exposes a RESTful interface for storing and retrieving Avro, JSON Schema, and Protobuf schemas, manages schema evolution through configurable compatibility rules (BACKWARD, FORWARD…
  api_count: 1
  score_band: thin
  score_composite: 42.0
  shared: 2
- slug: buf
  name: Buf
  description: Buf is a modern developer platform for Protocol Buffers and gRPC, providing a CLI toolchain, schema registry, and streaming infrastructure. It replaces traditional protoc-based workflows with linting, breaking change detection, code generation, remote plugins, and the Buf Schema Registry (BSR) for…
  api_count: 3
  score_band: thin
  score_composite: 33.4
  shared: 2
- slug: amazon-snow-family
  name: Amazon Snow Family
  description: AWS Snow Family is a collection of physical devices and capacity points that help customers with data transfers in and out of AWS when network capacity is limited or unavailable. It includes Snowcone, Snowball, and Snowmobile devices for edge computing and offline data migration.
  api_count: 1
  score_band: developing
  score_composite: 56.8
  shared: 1
- slug: kong
  name: Kong
  description: Kong is the AI Connectivity Company. Its platform spans Kong Gateway (the open-source API gateway built on NGINX and Lua), Kong Konnect (the SaaS control plane), Kong AI Gateway (LLM, MCP, and agent-to-agent traffic governance with semantic caching, token budgeting, and prompt firewalls), Kong Agen…
  api_count: 10
  score_band: developing
  score_composite: 49.8
  shared: 1
- slug: gravitee
  name: Gravitee
  description: Gravitee.io is an open-source API management platform from GraviteeSource, combining a high-performance API Gateway, full-lifecycle API Management, Access Management (IAM), Cockpit (multi-environment control plane), an Alert Engine, a Kubernetes Operator, and a new AI Agent Management suite with na…
  api_count: 7
  score_band: developing
  score_composite: 47.9
  shared: 1
- slug: redpanda
  name: Redpanda
  description: Redpanda is a Kafka API-compatible streaming data platform written in C++ with no JVM and no ZooKeeper, optimized for low latency and operational simplicity. The core broker (redpanda) is open source and available under the Business Source License 1.1, and a fully managed cloud service (Redpanda Cl…
  api_count: 10
  score_band: developing
  score_composite: 46.4
  shared: 1
- slug: wundergraph
  name: WunderGraph
  description: Full Lifecycle API Management for (Federated) GraphQL. Schema Registry, composition checks, analytics, metrics, tracing and routing. Deploy 100% on-prem or use our Managed Service. Apache 2.0 licensed, no vendor-lock.
  api_count: 1
  score_band: developing
  score_composite: 46.4
  shared: 1
- slug: apollo-graphql
  name: Apollo GraphQL
  description: Whether your team is new to GraphQL, or seasoned experts, learn why Apollo is the fastest and safest way to build and scale your APIs.
  api_count: 11
  score_band: thin
  score_composite: 43.1
  shared: 1
- slug: graphql-hive
  name: GraphQL Hive
  description: GraphQL Hive is an open-source GraphQL schema registry and observability platform developed by The Guild. It provides a REST and GraphQL API for schema publishing, validation, usage tracking, breaking change detection, and analytics for GraphQL federation and other GraphQL APIs. Available as a mana…
  api_count: 1
  score_band: thin
  score_composite: 42.9
  shared: 1
- slug: warpstream
  name: WarpStream
  description: WarpStream is a diskless, Apache Kafka-compatible data streaming platform built directly on top of cloud object storage such as S3, GCP, and Azure. It eliminates the need for local disks, brokers to rebalance, and ZooKeeper, delivering Kafka compatibility through a single, stateless Go binary deplo…
  api_count: 1
  score_band: thin
  score_composite: 42.8
  shared: 1
- slug: strimzi
  name: Strimzi
  description: Strimzi is a CNCF project providing a Kubernetes-native operator for running Apache Kafka on Kubernetes and OpenShift. It simplifies the deployment, management, scaling, and configuration of Kafka clusters using Kubernetes Custom Resource Definitions (CRDs). Strimzi manages the full Kafka ecosystem…
  api_count: 2
  score_band: thin
  score_composite: 42.0
  shared: 1
- slug: apache-samza
  name: Apache Samza
  description: Apache Samza is a distributed stream processing framework that provides a simple API for building stateful stream processing applications. It integrates with Apache Kafka for messaging and supports both stream and batch processing.
  api_count: 1
  score_band: thin
  score_composite: 41.8
  shared: 1
- slug: quix
  name: Quix
  description: Quix is a Python-native stream-processing platform for real-time data and ML. It pairs Quix Streams - an open source (Apache 2.0) Python library for building containerized stream-processing applications on Apache Kafka - with Quix Cloud, a fully managed platform offering managed Kafka, Kubernetes d…
  api_count: 5
  score_band: thin
  score_composite: 39.0
  shared: 1
- slug: apache-druid
  name: Apache Druid
  description: Apache Druid is a high-performance, real-time analytics database governed by the Apache Software Foundation, designed for fast slice-and-dice OLAP queries on event-time data. It features a distributed, column-oriented storage engine with automatic rollup, supports both streaming (Kafka, Kinesis) an…
  api_count: 1
  score_band: thin
  score_composite: 36.7
  shared: 1
- slug: specmatic
  name: Specmatic
  description: Specmatic is an AI-powered, no-code platform for API contract testing, service virtualization, and governance. It transforms API specifications (OpenAPI, AsyncAPI, gRPC, GraphQL, WSDL) into executable contracts for contract-driven development, enabling teams to ship APIs 10x faster with zero contra…
  api_count: 1
  score_band: thin
  score_composite: 35.9
  shared: 1
- slug: confluent-the-data-streaming-platform
  name: Confluent | the Data Streaming Platform
  description: Confluent is a fully managed data streaming platform built by the original creators of Apache Kafka. It lets organizations stream, connect, process, and govern data in motion through a cloud-native service (Confluent Cloud) and the on-prem/self-managed Confluent Platform. Confluent's developer surf…
  api_count: 6
  score_band: thin
  score_composite: 34.3
  shared: 1
- slug: table-format
  name: Table Format
  description: Open Table Format is a category of open standards for organizing and managing data in data lakehouses. The three dominant formats are Apache Iceberg (the emerging industry standard with snapshot-based metadata and broad engine support), Delta Lake (Databricks-originated, transaction-log-based), and…
  api_count: 4
  score_band: thin
  score_composite: 33.5
  shared: 1
- slug: risingwave
  name: RisingWave
  description: RisingWave is a distributed SQL streaming platform that continuously ingests event streams from Kafka, Kinesis, and other sources, transforms them using PostgreSQL-compatible SQL, and serves low-latency results through incrementally maintained materialized views. It delivers sub-100ms freshness for…
  api_count: 3
  score_band: thin
  score_composite: 32.8
  shared: 1
- slug: bytewax
  name: Bytewax
  description: Bytewax is a Python-native distributed stream processing framework built on a Rust runtime. Developers define dataflows using the bytewax.dataflow API, composing operators (map, filter, reduce, joins, windowing) over connectors for Kafka, files, stdio, demos, and custom sources/sinks. The Bytewax P…
  api_count: 3
  score_band: thin
  score_composite: 31.6
  shared: 1
- slug: avro
  name: Apache Avro
  description: Apache Avro is a data serialization system that provides rich data structures, a compact binary format, and container files for storing persistent data. Avro uses JSON for defining data types and protocols, and serializes data in a compact binary format.
  api_count: 1
  score_band: thin
  score_composite: 30.9
  shared: 1
- slug: versioning-protocols
  name: Versioning Protocols
  description: Standards and methodologies for managing changes and updates to APIs, software interfaces, and data formats while maintaining backward compatibility and clear communication of breaking changes. Covers Semantic Versioning (SemVer), Calendar Versioning (CalVer), URI path versioning, header-based vers…
  api_count: 5
  score_band: thin
  score_composite: 30.2
  shared: 1
- slug: grafbase
  name: Grafbase
  description: Grafbase is an enterprise GraphQL federation platform for building and deploying federated GraphQL APIs. It provides a high-performance Rust-powered gateway, schema registry, CLI, and a management API for programmatically controlling projects, schemas, branches, and deployed graph endpoints. The pl…
  api_count: 1
  score_band: minimal
  score_composite: 29.2
  shared: 1
- slug: restate-dev
  name: Restate
  description: Restate is a durable execution platform for building resilient distributed applications, microservice orchestration, durable workflows, stateful services, and AI agents. Founded by Apache Flink and Apache Kafka veterans (Stephan Ewen, Igal Shilman, Till Rohrmann), Restate ships a single-binary Rust…
  api_count: 3
  score_band: minimal
  score_composite: 27.1
  shared: 1
related: []
repo: https://github.com/api-evangelist/schema-evolution
overview: 'Schema Evolution on the [APIs.io](https://apis.io/) network is a curated area collecting 3 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including Schema Evolution, Confluent Schema Registry, Buf, Amazon Snow Family, Kong, Gravitee, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.'
---
