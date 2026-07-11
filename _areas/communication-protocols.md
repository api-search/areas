---
layout: area
slug: communication-protocols
name: Communication Protocols
description: Communication protocols are systems of rules that allow two or more entities in a networked system to exchange information. Modern API platforms rely on layered protocol stacks that span the physical and link layers, network and transport layers, and application protocols such as HTTP, gRPC, MQTT, AMQP, WebSockets, SSE, and Webhooks. The communication protocols topic surveys the most relevant standards bodies (IETF, W3C, IEEE, ITU, ISO), the most widely deployed protocols at each layer, and the way protocol choice shapes API design, performance, security, and interoperability.
tags:
- APIs
- Application Protocols
- Communication Protocols
- Internet
- IETF
- Networking
- Real-Time
- Standards
- Transport
- Web
resource_count: 8
provider_count: 241
resources:
- name: Hypertext Transfer Protocol (HTTP)
  description: The application layer protocol that powers the World Wide Web and the majority of REST and HTTP APIs. HTTP/1.1 is defined in RFC 9110-9114, HTTP/2 in RFC 9113, and HTTP/3 in RFC 9114, the latter running over QUIC. HTTP defines methods, status codes, headers, content negotiation, caching, and conditional requests that…
  url: https://httpwg.org/specs/
  tags:
  - Application Protocol
  - HTTP
  - IETF
  - REST
  - Web
  properties:
  - type: Specification
    url: https://www.rfc-editor.org/rfc/rfc9110
  - type: Specification
    url: https://www.rfc-editor.org/rfc/rfc9112
  - type: Specification
    url: https://www.rfc-editor.org/rfc/rfc9113
  - type: Specification
    url: https://www.rfc-editor.org/rfc/rfc9114
  - type: Working Group
    url: https://datatracker.ietf.org/wg/httpbis/about/
- name: gRPC
  description: A high-performance, contract-first RPC framework built on HTTP/2 with Protocol Buffers as the default IDL. gRPC supports unary, server streaming, client streaming, and bidirectional streaming and is widely used for microservice-to-microservice communication and for polyglot APIs across cloud-native platforms.
  url: https://grpc.io/
  tags:
  - CNCF
  - HTTP/2
  - Protocol Buffers
  - RPC
  - Streaming
  properties:
  - type: Documentation
    url: https://grpc.io/docs/
  - type: Specification
    url: https://github.com/grpc/grpc/blob/master/doc/PROTOCOL-HTTP2.md
  - type: GitHubOrganization
    url: https://github.com/grpc
- name: GraphQL
  description: A query language and runtime for client-driven data APIs over HTTP and WebSockets. GraphQL exposes a single endpoint with a typed schema defining queries, mutations, and subscriptions, allowing clients to request precisely the data they need.
  url: https://graphql.org/
  tags:
  - API
  - GraphQL
  - HTTP
  - Schema
  - Subscriptions
  properties:
  - type: Specification
    url: https://spec.graphql.org/
  - type: Documentation
    url: https://graphql.org/learn/
  - type: Reference
    url: https://github.com/graphql/graphql-spec
  - type: GraphQL
    url: graphql/communication-protocols-graphql.md
- name: WebSocket
  description: A bidirectional, full-duplex communication protocol over a single TCP connection, defined in RFC 6455. WebSocket upgrades from HTTP and is widely used for chat, collaborative editing, live dashboards, and game servers.
  url: https://www.rfc-editor.org/rfc/rfc6455
  tags:
  - Bidirectional
  - IETF
  - Real-Time
  - Web
  - WebSocket
  properties:
  - type: Specification
    url: https://www.rfc-editor.org/rfc/rfc6455
  - type: Documentation
    url: https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API
- name: MQTT
  description: A lightweight publish-subscribe messaging protocol designed for constrained devices and unreliable networks. MQTT is an OASIS standard and is widely used in IoT, automotive, and edge environments. MQTT 5 adds user properties, reason codes, shared subscriptions, and other modern features.
  url: https://mqtt.org/
  tags:
  - IoT
  - Lightweight
  - OASIS
  - Pub/Sub
  properties:
  - type: Specification
    url: https://docs.oasis-open.org/mqtt/mqtt/v5.0/mqtt-v5.0.html
  - type: Documentation
    url: https://mqtt.org/getting-started/
  - type: Reference
    url: https://www.hivemq.com/mqtt/mqtt-essentials/
- name: AMQP
  description: The Advanced Message Queuing Protocol, an OASIS standard for interoperable, broker-mediated messaging. AMQP 1.0 defines a wire protocol with strong typing, links, sessions, and connection-level security and is used by RabbitMQ, Azure Service Bus, and many other brokers.
  url: https://www.amqp.org/
  tags:
  - Brokered
  - Enterprise Messaging
  - OASIS
  - Queuing
  properties:
  - type: Specification
    url: https://docs.oasis-open.org/amqp/core/v1.0/os/amqp-core-overview-v1.0-os.html
  - type: Documentation
    url: https://www.rabbitmq.com/protocol.html
- name: Webhooks
  description: An HTTP-based pattern for delivering event notifications from one service to another by performing an outbound HTTP POST to a URL registered by the consumer. Webhooks are not a single specification but the broader pattern is increasingly governed by efforts such as the CloudEvents specification and the IETF Webhook se…
  url: https://webhooks.fyi/
  tags:
  - Async
  - Events
  - HTTP
  - Push
  properties:
  - type: Reference
    url: https://webhooks.fyi/
  - type: Specification
    url: https://cloudevents.io/
  - type: Documentation
    url: https://www.standardwebhooks.com/
- name: Server-Sent Events (SSE)
  description: A simple, one-way, server-to-client streaming protocol defined as part of the HTML living standard. SSE runs over plain HTTP, supports automatic reconnection, and is widely used for live status feeds and LLM token streaming.
  url: https://html.spec.whatwg.org/multipage/server-sent-events.html
  tags:
  - HTML
  - HTTP
  - Real-Time
  - Streaming
  properties:
  - type: Specification
    url: https://html.spec.whatwg.org/multipage/server-sent-events.html
  - type: Documentation
    url: https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events
providers:
- slug: communication-protocols
  name: Communication Protocols
  description: Communication protocols are systems of rules that allow two or more entities in a networked system to exchange information. Modern API platforms rely on layered protocol stacks that span the physical and link layers, network and transport layers, and application protocols such as HTTP, gRPC, MQTT,…
  api_count: 8
  score_band: minimal
  score_composite: 25.0
  shared: 10
- slug: tcp-ip
  name: TCP/IP
  description: TCP/IP (Transmission Control Protocol/Internet Protocol) is the foundational communication protocol suite that powers the internet and most computer networks. It provides reliable, ordered delivery of data between applications across diverse network hardware through a layered architecture of protoc…
  api_count: 1
  score_band: minimal
  score_composite: 21.7
  shared: 4
- slug: transportapi
  name: TransportAPI
  description: TransportAPI is a managed data service provider for UK public transport, offering real-time and scheduled bus, rail, and multimodal transport data via REST and WebSocket APIs to power apps, websites, analytics, and data-mining workflows.
  api_count: 1
  score_band: thin
  score_composite: 44.1
  shared: 2
- slug: w3c
  name: W3C
  description: The World Wide Web Consortium (W3C) is the main international standards body for the World Wide Web, founded by Tim Berners-Lee in 1994. W3C develops web standards and guidelines to ensure the long-term growth of the Web, focusing on accessibility, internationalization, privacy, and security. W3C s…
  api_count: 10
  score_band: thin
  score_composite: 42.2
  shared: 2
- slug: global-system-for-mobile-communications
  name: Global System for Mobile Communications
  description: We unite over 1000 mobile operators and businesses across the ecosystem and related industries to advance innovation and reduce inequalities around the world.
  api_count: 25
  score_band: thin
  score_composite: 37.3
  shared: 2
- slug: lumen-technologies
  name: Lumen Technologies
  description: Lumen Technologies is a multinational technology company that delivers networking, edge cloud, security, communication and collaboration, and managed and professional services to global enterprises and consumers. Through its Developer Center, Lumen exposes REST APIs that allow customers to programm…
  api_count: 2
  score_band: thin
  score_composite: 36.7
  shared: 2
- slug: technology-standards
  name: Technology Standards
  description: Technology Standards covers the landscape of formal technical standards, protocols, and normative specifications developed by international standards bodies including IEEE, IETF, W3C, ISO, OASIS, and the Linux Foundation. These standards define how technology systems interoperate, communicate, and…
  api_count: 5
  score_band: thin
  score_composite: 32.9
  shared: 2
- slug: certificate-enrolment-protocols
  name: Certificate Enrolment Protocols
  description: Certificate Enrolment Protocols are the interoperable standards that automate the lifecycle operations of requesting, issuing, renewing, and revoking X.509 digital certificates between Certificate Authorities (CAs), Registration Authorities (RAs), and end entities. The four major protocols in activ…
  api_count: 6
  score_band: thin
  score_composite: 31.4
  shared: 2
- slug: p4
  name: P4
  description: P4 is a Linux Foundation project enabling programmable data planes in networking devices through an open, standardized programming language. It allows network engineers to define how packets are processed by forwarding planes of network devices independent of specific hardware implementations.
  api_count: 1
  score_band: minimal
  score_composite: 21.2
  shared: 2
- slug: polygon
  name: Polygon
  description: Polygon (Polygon.io, rebranded as Massive in early 2026) provides real-time and historical market data APIs across US stocks, options, indices, forex, cryptocurrencies, and futures. Coverage is delivered through REST endpoints and WebSocket streams under a single api.polygon.io surface plus an S3 f…
  api_count: 7
  score_band: exemplar
  score_composite: 70.4
  shared: 1
- slug: shodan
  name: Shodan
  description: Shodan is the world's first search engine for Internet-connected devices. It continuously crawls the public Internet to build a searchable database of servers, IoT devices, industrial control systems, routers, webcams, databases, and any other host that exposes a service. Shodan provides REST, Stre…
  api_count: 5
  score_band: strong
  score_composite: 67.8
  shared: 1
- slug: amazon-elastic-load-balancing
  name: Amazon Elastic Load Balancing
  description: Amazon Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions, ensuring high availability and fault tolerance for your applications.
  api_count: 1
  score_band: strong
  score_composite: 61.8
  shared: 1
- slug: vapi-ai
  name: Vapi
  description: Vapi is a San Francisco-based voice AI platform that lets developers build real-time, low-latency voice agents over phone, web, and SIP. It orchestrates three modular components — a transcriber (STT), an LLM, and a voice (TTS) — into a sub-700ms voice-to-voice pipeline, with first-class support for…
  api_count: 15
  score_band: strong
  score_composite: 60.3
  shared: 1
- slug: aws-app-mesh
  name: AWS App Mesh
  description: AWS App Mesh is a service mesh based on the Envoy proxy that provides application-level networking to make it easy for services to communicate with each other across multiple types of compute infrastructure including Amazon ECS, EKS, EC2, and Fargate. App Mesh standardizes service communication, gi…
  api_count: 1
  score_band: developing
  score_composite: 58.1
  shared: 1
- slug: microsoft-azure-web-pubsub
  name: Azure Web PubSub
  description: Azure Web PubSub is a fully-managed service that enables building real-time, two-way messaging applications using publish-subscribe patterns over WebSockets. It supports broadcasting messages to clients in groups, sending messages to specific connections or users, and integrating with serverless ev…
  api_count: 7
  score_band: developing
  score_composite: 58.0
  shared: 1
- slug: sanity
  name: Sanity
  description: Sanity is a composable content platform providing a headless CMS with a real-time collaborative editor (Sanity Studio) and a powerful HTTP API for managing structured content. The Sanity Content Lake stores content as flexible documents queryable via GROQ (Graph-Relational Object Queries). Key API…
  api_count: 9
  score_band: developing
  score_composite: 57.2
  shared: 1
- slug: amazon-web-services-aws
  name: Amazon Web Services (AWS)
  description: Amazon Web Services offers reliable, scalable, and inexpensive cloud computing services. Free to join, pay only for what you use.
  api_count: 90
  score_band: developing
  score_composite: 56.9
  shared: 1
- slug: azure-networking-services
  name: Azure Networking Services
  description: A comprehensive collection of Azure networking APIs for managing virtual networks, load balancers, application gateways, VPN gateways, DNS, and other networking resources in the Microsoft Azure cloud.
  api_count: 2
  score_band: developing
  score_composite: 56.5
  shared: 1
- slug: citrix
  name: Citrix
  description: Citrix is a global software company providing virtualization, networking, workspace, and digital experience products that allow organizations to deliver applications and desktops securely from data centers and clouds to any device. Citrix exposes its programmable surface through the Citrix Cloud pl…
  api_count: 12
  score_band: developing
  score_composite: 56.2
  shared: 1
- slug: amazon-interactive-video-service
  name: Amazon Interactive Video Service
  description: Amazon Interactive Video Service (Amazon IVS) is a managed live streaming solution designed to provide interactive video experiences. It handles the operational complexity of live streaming so you can focus on building engaging applications.
  api_count: 1
  score_band: developing
  score_composite: 56.0
  shared: 1
- slug: amazon-kinesis
  name: Amazon Kinesis
  description: Amazon Kinesis makes it easy to collect, process, and analyze real-time streaming data so you can get timely insights and react quickly to new information. Amazon Kinesis offers key capabilities to cost-effectively process streaming data at any scale, along with the flexibility to choose the tools…
  api_count: 7
  score_band: developing
  score_composite: 55.8
  shared: 1
- slug: convex
  name: Convex
  description: Convex is a serverless backend platform that provides a real-time database, cloud functions, and infrastructure for building modern web and mobile applications. It offers a TypeScript-first developer experience with reactive queries, transactional mutations, and integrated file storage, all accessi…
  api_count: 6
  score_band: developing
  score_composite: 55.8
  shared: 1
- slug: azure
  name: Microsoft Azure
  description: Microsoft Azure is a comprehensive cloud computing platform offering IaaS, PaaS, and SaaS solutions for building, deploying, and managing applications through Microsoft's global network of datacenters.
  api_count: 3
  score_band: developing
  score_composite: 55.8
  shared: 1
- slug: amazon-direct-connect
  name: Amazon Direct Connect
  description: AWS Direct Connect links your internal network to an AWS Direct Connect location over a standard Ethernet fiber-optic cable. With this connection, you can create virtual interfaces directly to public AWS services or to Amazon VPC, bypassing internet service providers in your network path. An AWS Di…
  api_count: 1
  score_band: developing
  score_composite: 55.7
  shared: 1
related:
- slug: chat
  name: Chat
  shared: 1
- slug: data-quality-standards
  name: Data Quality Standards
  shared: 1
- slug: cybersecurity-standards
  name: Cybersecurity Standards
  shared: 1
repo: https://github.com/api-evangelist/communication-protocols
overview: 'Communication Protocols on the [APIs.io](https://apis.io/) network is a curated area collecting 8 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including Communication Protocols, TCP/IP, TransportAPI, W3C, Global System for Mobile Communications, Lumen Technologies, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Chat, Data Quality Standards, and Cybersecurity Standards. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
