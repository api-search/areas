---
layout: area
slug: circuit-breaker
name: Circuit Breaker
description: The Circuit Breaker is a stability pattern for distributed systems and API architectures that prevents cascading failure when a downstream service degrades. A breaker wraps a remote call and tracks failures against a threshold; when the threshold is exceeded the breaker "opens" and short-circuits subsequent calls (typically returning an error or fallback) without contacting the downstream service. After a cooldown the breaker enters a "half-open" probe state and either resets to "closed" on success or re-opens on failure. The pattern was popularized by Michael Nygard in *Release It!* and is now standard in resilient microservice and API gateway design.
tags:
- Circuit Breaker
- Distributed Systems
- Fault Tolerance
- Microservices
- Patterns
- Resilience
- Stability
resource_count: 0
provider_count: 127
resources: []
providers:
- slug: resilience4j
  name: Resilience4j
  description: Resilience4j is a lightweight fault tolerance library designed for Java 17+ and functional programming, providing higher-order functions to enhance functional interfaces with Circuit Breaker, Rate Limiter, Retry, Bulkhead, TimeLimiter, and Cache patterns. Designed as a replacement for Netflix Hystr…
  api_count: 1
  score_band: thin
  score_composite: 35.2
  shared: 4
- slug: netflix-hystrix
  name: Netflix Hystrix
  description: Netflix Hystrix is a latency and fault tolerance library designed to isolate points of access to remote systems, services, and third-party libraries, stop cascading failure, and enable resilience in complex distributed systems where failure is inevitable. Now in maintenance mode, with Resilience4j…
  api_count: 1
  score_band: minimal
  score_composite: 29.5
  shared: 4
- slug: polly
  name: Polly
  description: Polly is a .NET resilience and transient-fault-handling library that allows developers to express resilience strategies such as Retry, Circuit Breaker, Hedging, Timeout, Rate Limiter, and Fallback in a fluent and thread-safe manner. A .NET Foundation member project.
  api_count: 1
  score_band: minimal
  score_composite: 27.3
  shared: 4
- slug: scalable-architecture
  name: Scalable Architecture
  description: A subject-matter collection covering APIs, patterns, tools, and frameworks for building scalable system architecture. This topic encompasses microservices design, service mesh, event-driven architecture, CQRS, saga patterns, container orchestration, caching, message queuing, and observability patte…
  api_count: 8
  score_band: thin
  score_composite: 35.4
  shared: 3
- slug: spring-cloud
  name: Spring Cloud
  description: Spring Cloud provides tools for developers to quickly build some of the common patterns in distributed systems including configuration management, service discovery, circuit breakers, intelligent routing, micro-proxy, control bus, and distributed tracing. It builds on the Spring Boot approach to si…
  api_count: 7
  score_band: thin
  score_composite: 34.8
  shared: 3
- slug: zeebe
  name: Zeebe
  description: Zeebe is the cloud-native workflow engine that powers Camunda 8, providing scalable, resilient workflow automation and microservices orchestration without relying on a central database, enabling high throughput with horizontal scaling. It implements BPMN 2.0 process execution and provides a REST AP…
  api_count: 1
  score_band: developing
  score_composite: 48.0
  shared: 2
- slug: dapr
  name: Dapr
  description: Dapr (Distributed Application Runtime) is a portable, event-driven runtime that makes it easy for developers to build resilient, stateless, and stateful applications that run on the cloud and edge. It provides building block APIs for state management, pub/sub messaging, service invocation, bindings…
  api_count: 13
  score_band: developing
  score_composite: 47.5
  shared: 2
- slug: service-fabric
  name: Service Fabric
  description: Azure Service Fabric is an open-source distributed systems platform for packaging, deploying, and managing scalable and reliable microservices and containers. Service Fabric powers many Microsoft Azure core services, and thousands of services at scale including Azure SQL Database, Azure Cosmos DB,…
  api_count: 2
  score_band: developing
  score_composite: 46.9
  shared: 2
- slug: microsoft-azure-service-fabric
  name: Azure Service Fabric
  description: Azure Service Fabric REST API provides management of microservices clusters, applications, and services. It supports creating and scaling clusters, deploying applications, managing partitions and replicas, and monitoring cluster health for distributed systems.
  api_count: 1
  score_band: developing
  score_composite: 46.0
  shared: 2
- slug: spring-cloud-config
  name: Spring Cloud Config
  description: Spring Cloud Config provides server-side and client-side support for externalized configuration in a distributed system. It offers a central place to manage external properties for applications across all environments, backed by Git, SVN, or filesystem repositories with support for encryption, decr…
  api_count: 1
  score_band: thin
  score_composite: 44.7
  shared: 2
- slug: akka
  name: Akka
  description: Akka is a toolkit and runtime for building highly concurrent, distributed, and resilient message-driven applications on the JVM using the actor model for Java and Scala. Maintained by Lightbend, Akka provides a comprehensive set of libraries including actors, HTTP, streams, cluster, persistence, an…
  api_count: 4
  score_band: thin
  score_composite: 43.4
  shared: 2
- slug: apollo-config
  name: Apollo Config
  description: Apollo is a reliable, open-source configuration management system suitable for microservice configuration management scenarios, providing centralized configuration management, real-time updates, versioning, and multi-environment support. Originally developed by Ctrip, now maintained by the apolloco…
  api_count: 1
  score_band: thin
  score_composite: 43.2
  shared: 2
- slug: amazon-sqs
  name: Amazon SQS
  description: Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
  api_count: 1
  score_band: thin
  score_composite: 42.9
  shared: 2
- slug: restate
  name: Restate
  description: Restate is a low-latency durable execution engine for building resilient applications that tolerate all infrastructure faults. It provides durable execution for workflows, event-driven handlers, and stateful orchestration of microservices with exactly-once semantics, automatic retries, and built-in…
  api_count: 1
  score_band: thin
  score_composite: 41.2
  shared: 2
- slug: spring-cloud-gateway
  name: Spring Cloud Gateway
  description: Spring Cloud Gateway provides an intelligent, programmable router built on Spring WebFlux that serves as the entry point to microservice architectures. It offers routing, predicate evaluation, filter chaining, load balancing, circuit breaking, rate limiting, and runtime route management through an…
  api_count: 2
  score_band: thin
  score_composite: 39.2
  shared: 2
- slug: scalable-services
  name: Scalable Services
  description: A curated topic collection covering APIs, patterns, tools, and best practices for designing and operating scalable services. This includes cloud-native microservices, API gateways, load balancers, container orchestration, serverless platforms, service meshes, and the architectural patterns that ena…
  api_count: 8
  score_band: thin
  score_composite: 35.3
  shared: 2
- slug: scalable-software-and-systems
  name: Scalable Software and Systems
  description: A topic collection exploring the APIs, design patterns, frameworks, and platforms that enable scalable software and systems engineering. Covers architectural patterns such as CQRS, event sourcing, saga, MACH architecture, API-first design, and modular monoliths, as well as the tooling ecosystems th…
  api_count: 8
  score_band: thin
  score_composite: 33.5
  shared: 2
- slug: moleculer
  name: Moleculer
  description: Moleculer is a fast, modern, and powerful microservices framework for Node.js. It provides built-in service discovery, load balancing, fault tolerance with circuit breaker, request retries, distributed event handling, and support for multiple serializers and transporters including NATS, Redis, MQTT…
  api_count: 1
  score_band: minimal
  score_composite: 29.3
  shared: 2
- slug: go-micro
  name: Go Micro
  description: Go Micro is a distributed systems framework for building microservices in Go, providing service discovery, load balancing, message encoding, RPC, and async messaging out of the box.
  api_count: 1
  score_band: minimal
  score_composite: 28.1
  shared: 2
- slug: go-kit
  name: Go Kit
  description: Go Kit is a programming toolkit for building microservices in Go, emphasizing domain-driven design, transport-agnostic service definitions, and best practices for distributed systems.
  api_count: 1
  score_band: minimal
  score_composite: 26.2
  shared: 2
- slug: apigee
  name: Apigee
  description: Apigee is Google Cloud's native API management platform for building, managing, and securing APIs across any use case, environment, or scale. It provides API proxies, security, rate limiting, quotas, analytics, monetization, and developer portal capabilities.
  api_count: 5
  score_band: strong
  score_composite: 66.8
  shared: 1
- slug: aws-app-mesh
  name: AWS App Mesh
  description: AWS App Mesh is a service mesh based on the Envoy proxy that provides application-level networking to make it easy for services to communicate with each other across multiple types of compute infrastructure including Amazon ECS, EKS, EC2, and Fargate. App Mesh standardizes service communication, gi…
  api_count: 1
  score_band: developing
  score_composite: 58.1
  shared: 1
- slug: nvidia-nim
  name: NVIDIA NIM
  description: NVIDIA NIM (NVIDIA Inference Microservices) is a catalog of GPU-accelerated, containerized AI inference microservices that package optimized model engines (TensorRT-LLM, vLLM, SGLang, Triton) behind industry-standard OpenAI-compatible REST APIs. NIM covers large language models, embeddings and rera…
  api_count: 10
  score_band: developing
  score_composite: 55.8
  shared: 1
- slug: websphere
  name: IBM WebSphere
  description: IBM WebSphere is a family of enterprise software products that provide middleware and application server capabilities for building, deploying, and managing enterprise applications.
  api_count: 8
  score_band: developing
  score_composite: 55.1
  shared: 1
related:
- slug: consensus
  name: Consensus
  shared: 1
- slug: cqrs
  name: CQRS
  shared: 1
repo: https://github.com/api-evangelist/circuit-breaker
overview: 'Circuit Breaker on the [APIs.io](https://apis.io/) network is a curated area collecting 0 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including Resilience4j, Netflix Hystrix, Polly, Scalable Architecture, Spring Cloud, Zeebe, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Consensus and CQRS. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
