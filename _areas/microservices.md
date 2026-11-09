---
layout: area
slug: microservices
name: Microservices
description: An index of microservices architecture frameworks, service discovery, resilience, messaging, workflow orchestration, and distributed systems tooling repositories.
area_url: https://microservices.apievangelist.com
area_host: microservices.apievangelist.com
icon: https://microservices.apievangelist.com/icon-thumb.png
provider_count: 102
providers:
- slug: datadog-apm
  name: Datadog APM
  description: Datadog APM provides end-to-end distributed tracing, continuous profiling, and real-time performance monitoring for applications and microservices. It automatically instruments applications to provide deep visibility into request traces, latency, and error rates across distributed systems.
  api_count: 2
  score_band: exemplar
  score_composite: 82.0
  shared: 1
- slug: apigee
  name: Apigee
  description: Apigee is Google Cloud's native API management platform for building, managing, and securing APIs across any use case, environment, or scale. It provides API proxies, security, rate limiting, quotas, analytics, monetization, and developer portal capabilities.
  api_count: 5
  score_band: exemplar
  score_composite: 69.6
  shared: 1
- slug: microsoft-azure-service-fabric
  name: Azure Service Fabric
  description: Azure Service Fabric REST API provides management of microservices clusters, applications, and services. It supports creating and scaling clusters, deploying applications, managing partitions and replicas, and monitoring cluster health for distributed systems.
  api_count: 4
  score_band: strong
  score_composite: 65.9
  shared: 1
- slug: signadot
  name: Signadot
  description: 'Signadot is a Kubernetes-native platform for validating microservices and AI-generated code changes against real dependencies before merge. Its core is environment virtualization: large numbers of lightweight ephemeral "sandboxes" spin up in seconds by routing request-level traffic to only the chan…'
  api_count: 1
  score_band: strong
  score_composite: 65.2
  shared: 1
- slug: amazon-cloud-map
  name: Amazon Cloud Map
  description: Amazon Cloud Map is a cloud resource discovery service that maintains an updated registry of application resources and their locations. Define custom names for application resources and use Cloud Map to dynamically discover service dependencies with integrated health checking and automatic updates.
  api_count: 5
  score_band: strong
  score_composite: 62.8
  shared: 1
- slug: aws-app-runner
  name: AWS App Runner
  description: AWS App Runner is a fully managed service that makes it easy to build, deploy, and run containerized web applications and APIs at scale. It automatically builds and deploys applications from container images or source code, load balances traffic with encryption, and scales to meet traffic needs wit…
  api_count: 16
  score_band: strong
  score_composite: 61.6
  shared: 1
- slug: websphere
  name: IBM WebSphere
  description: IBM WebSphere is a family of enterprise software products that provide middleware and application server capabilities for building, deploying, and managing enterprise applications.
  api_count: 7
  score_band: strong
  score_composite: 59.9
  shared: 1
- slug: amazon-sqs
  name: Amazon SQS
  description: Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
  api_count: 1
  score_band: strong
  score_composite: 59.8
  shared: 1
- slug: azure-container-apps
  name: Azure Container Apps
  description: Azure Container Apps is a serverless container service for running microservices and containerized applications with built-in autoscaling, traffic splitting, and Dapr integration. It enables developers to deploy containers without managing complex infrastructure while supporting event-driven archit…
  api_count: 1
  score_band: strong
  score_composite: 59.8
  shared: 1
- slug: nvidia-nim
  name: NVIDIA NIM
  description: NVIDIA NIM (NVIDIA Inference Microservices) is a catalog of GPU-accelerated, containerized AI inference microservices that package optimized model engines (TensorRT-LLM, vLLM, SGLang, Triton) behind industry-standard OpenAI-compatible REST APIs. NIM covers large language models, embeddings and rera…
  api_count: 3
  score_band: strong
  score_composite: 59.8
  shared: 1
- slug: lumigo
  name: Lumigo
  description: Lumigo is an observability and troubleshooting platform for microservices and serverless environments. It provides distributed tracing, logs, and metrics with automatic, no-code instrumentation for AWS Lambda, Amazon ECS, AWS AppSync, API Gateway, Kubernetes, and OpenTelemetry workloads. Lumigo cap…
  api_count: 1
  score_band: strong
  score_composite: 57.6
  shared: 1
- slug: amazon-fargate
  name: Amazon Fargate
  description: Amazon Fargate is a serverless compute engine for containers that works with both Amazon ECS and Amazon EKS. Fargate removes the need to provision and manage servers, letting you specify and pay for resources per application, and improves security through application isolation by design.
  api_count: 6
  score_band: strong
  score_composite: 55.4
  shared: 1
- slug: aws-app-mesh
  name: AWS App Mesh
  description: AWS App Mesh is a service mesh based on the Envoy proxy that provides application-level networking to make it easy for services to communicate with each other across multiple types of compute infrastructure including Amazon ECS, EKS, EC2, and Fargate. App Mesh standardizes service communication, gi…
  api_count: 1
  score_band: strong
  score_composite: 55.0
  shared: 1
- slug: zeebe
  name: Zeebe
  description: Zeebe is the cloud-native workflow engine that powers Camunda 8, providing scalable, resilient workflow automation and microservices orchestration without relying on a central database, enabling high throughput with horizontal scaling. It implements BPMN 2.0 process execution and provides a REST AP…
  api_count: 1
  score_band: developing
  score_composite: 53.2
  shared: 1
- slug: amazon-vpc-lattice
  name: Amazon VPC Lattice
  description: Amazon VPC Lattice is an application networking service that consistently connects, monitors, and secures communications between your services, helping you to improve productivity so that your developers can focus on building features that matter to your business. It simplifies service-to-service c…
  api_count: 73
  score_band: developing
  score_composite: 52.3
  shared: 1
- slug: docker
  name: Docker
  description: Docker is a platform for developers and sysadmins to build, share, and run applications in containers, packaging code and dependencies together for consistent deployment across environments.
  api_count: 1
  score_band: developing
  score_composite: 52.0
  shared: 1
- slug: encore-dev
  name: Encore
  description: Encore is a backend application framework and developer cloud that lets engineering teams build type-safe distributed systems in TypeScript (Encore.ts) and Go (Encore.go) using declarative Infrastructure from Code. Developers describe APIs, databases, Pub/Sub, object storage, caches, cron jobs, and…
  api_count: 2
  score_band: developing
  score_composite: 51.9
  shared: 1
- slug: folio
  name: FOLIO
  description: FOLIO (Future of Libraries is Open) is an open source library services platform (LSP) built by a community of libraries, developers and vendors. Developer documentation and an API reference are published on the FOLIO developer portal (dev.folio.org), user documentation at docs.folio.org, and source…
  api_count: 101
  score_band: developing
  score_composite: 51.2
  shared: 1
- slug: aws-x-ray
  name: AWS X-Ray
  description: AWS X-Ray is a service that helps developers analyze and debug distributed applications by providing end-to-end tracing of requests as they travel through the application, identifying performance bottlenecks and errors. It is now part of Amazon CloudWatch Application Signals for unified observabili…
  api_count: 1
  score_band: developing
  score_composite: 50.3
  shared: 1
- slug: mist-ai
  name: Juniper Mist AI
  description: Juniper Mist AI is the AI-driven enterprise networking platform that powers Juniper Networks' AI-Native Networking portfolio. Acquired by Juniper Networks in 2019, Mist pioneered cloud-native, microservices Wi-Fi and extended its AIOps approach across Wired Assurance (EX/QFX switches), WAN Assuranc…
  api_count: 1
  score_band: developing
  score_composite: 47.5
  shared: 1
- slug: opslevel
  name: OpsLevel
  description: OpsLevel is a prescriptive internal developer portal for cataloging, measuring, and scaffolding services according to engineering best practices.
  api_count: 1
  score_band: developing
  score_composite: 47.1
  shared: 1
- slug: purplebricks
  name: Purplebricks
  description: Purplebricks is the United Kingdom's largest online (hybrid) estate agency, founded in 2014 by Michael and Kenny Bruce and David Shepherd, selling and letting residential property across England, Wales and Scotland through a fixed-fee, remote model staffed by local property experts rather than a hi…
  api_count: 18
  score_band: developing
  score_composite: 47.1
  shared: 1
- slug: polyapi
  name: PolyAPI
  description: Poly, built using cutting-edge AI and Kubernetes-native technology, accelerates development and simplifies the operation of integrations, orchestrations, and microservices with TypeScript, Python, Java, and C.
  api_count: 1
  score_band: developing
  score_composite: 45.9
  shared: 1
- slug: apollo-config
  name: Apollo Config
  description: Apollo is a reliable, open-source configuration management system suitable for microservice configuration management scenarios, providing centralized configuration management, real-time updates, versioning, and multi-environment support. Originally developed by Ctrip, now maintained by the apolloco…
  api_count: 1
  score_band: developing
  score_composite: 44.4
  shared: 1
- slug: grpc
  name: gRPC
  description: gRPC is a high-performance, open-source universal RPC framework that uses HTTP/2 for transport, Protocol Buffers as the interface description language, and provides features such as authentication, bidirectional streaming and flow control, blocking or nonblocking bindings, and cancellation and time…
  api_count: 1
  score_band: developing
  score_composite: 42.6
  shared: 1
- slug: webflux
  name: Spring WebFlux
  description: Spring WebFlux is a fully non-blocking, reactive-stack web framework built into Spring Framework 5.0+. It enables building highly scalable, asynchronous web applications using the Reactive Streams API with Project Reactor. WebFlux supports annotated controllers, functional routing endpoints, WebSoc…
  api_count: 8
  score_band: developing
  score_composite: 42.2
  shared: 1
- slug: apache-dubbo
  name: Apache Dubbo
  description: Apache Dubbo is a high-performance, Java-based open-source RPC framework that provides service discovery, traffic management, and observability capabilities for building enterprise-level microservices. It supports multiple protocols including Triple (gRPC-compatible), Dubbo, and REST, with SDKs for…
  api_count: 1
  score_band: developing
  score_composite: 41.5
  shared: 1
- slug: kuma
  name: Kuma
  description: Kuma is a platform-agnostic open-source service mesh built on top of Envoy proxy. It provides universal connectivity, security, and observability for services and microservices running on any infrastructure including Kubernetes and VMs.
  api_count: 1
  score_band: developing
  score_composite: 40.7
  shared: 1
- slug: spring
  name: Spring Framework
  description: Spring is the leading open-source application framework for Java. The Spring ecosystem provides a comprehensive programming and configuration model for modern Java-based enterprise applications, covering web MVC, data access, security, messaging, cloud-native patterns, and AI integrations. Spring B…
  api_count: 3
  score_band: developing
  score_composite: 40.0
  shared: 1
- slug: nats
  name: NATS
  description: A high-performance, cloud-native messaging system for microservices, IoT, and edge computing. Provides pub-sub, request-reply, and queue-based messaging patterns with at-most-once and at-least-once delivery guarantees.
  api_count: 2
  score_band: developing
  score_composite: 39.9
  shared: 1
provider_slugs:
- datadog-apm
- apigee
- microsoft-azure-service-fabric
- signadot
- amazon-cloud-map
- aws-app-runner
- websphere
- amazon-sqs
- azure-container-apps
- nvidia-nim
- lumigo
- amazon-fargate
- aws-app-mesh
- zeebe
- amazon-vpc-lattice
- docker
- encore-dev
- folio
- aws-x-ray
- mist-ai
- opslevel
- purplebricks
- polyapi
- apollo-config
- grpc
- webflux
- apache-dubbo
- kuma
- spring
- nats
- pactflow
- dapr
- google-cloud-service-mesh
- spring-cloud-config
- zipkin
- apache-zipkin
- restate
- grokzilla-shop
- express-gateway
- jaeger
- service-fabric
- the-guild-dev
- diagrid
- ocelot
- istio
- beamable
- conductor-oss
- spring-boot
- spring-cloud-gateway
- ambient-mesh
- axon-framework
- vert-x
- akka
- grafana-tempo
- nacos
- spring-cloud-stream
- moleculer
- orkes
- spin
- kratos
- quarkus
- open-liberty
- snapser
- lightstep
- jboss
- x402-micro-pay-com
- nestjs
- spring-boot-admin-console
- devprime
- alibaba-sentinel
- helidon
- resilience4j
- dropwizard
- netflix-eureka
- micronaut
- kitex
- eventuate
- netflix-conductor
- open-service-mesh
- soa
- littlehorse
- telepresence
- seneca
- nameko
- convrgent-ai
- netflix-hystrix
- graftcode
- lura-project
- polly
- go-kit
- qworum
- go-micro
- lagom
- amplication
- gin
- fiber
- mia-platform
- lunchbadger
- micro
- effx
- services-patterns
- restful-services
related:
- slug: containers
  name: Containers
  shared: 4
- slug: service-mesh
  name: Service Mesh
  shared: 4
- slug: developer-experience
  name: Developer Experience
  shared: 2
- slug: portal
  name: Portal
  shared: 2
- slug: serverless
  name: Serverless
  shared: 2
- slug: aiops
  name: AIOps
  shared: 1
overview: 'Microservices is one of the API Evangelist areas on the [APIs.io](https://apis.io/) network — a focused corner of the API landscape. The full area lives at [microservices.apievangelist.com](https://microservices.apievangelist.com).


  30 providers on the network work in this area, including Datadog APM, Apigee, Azure Service Fabric, Signadot, Amazon Cloud Map, AWS App Runner, and 24 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Containers, Service Mesh, Developer Experience, and Portal. Browse every area at [areas.apis.io](https://apis.io/areas/).'
terms:
- slug: dependency-injection
  name: Dependency Injection
  short: A design pattern in which objects receive their dependencies from external sources rather than creating them internally, promoting loose coupling, easier testi…
  url: /topics/dependency-injection/
- slug: domain-driven-design
  name: Domain-Driven Design
  short: A software development approach that focuses on modeling software to match a domain according to input from domain experts, emphasizing collaboration between t…
  url: /topics/domain-driven-design/
- slug: event-driven-architecture
  name: Event-Driven Architecture
  short: Event-driven architecture (EDA) is a software architecture pattern promoting the production, detection, consumption of, and reaction to events. In this pattern…
  url: /topics/event-driven-architecture/
- slug: integration-patterns
  name: Integration Patterns
  short: Integration Patterns are design patterns and best practices for integrating different software systems and applications, including messaging, data transformati…
  url: /topics/integration-patterns/
- slug: inversion-of-control
  name: Inversion of Control
  short: Inversion of Control (IoC) is a software design principle where the control flow of a program is inverted compared to traditional programming. Instead of appli…
  url: /topics/inversion-of-control/
- slug: microservice-architecture-patterns
  name: Micro-Service Architecture Patterns
  short: Design patterns and best practices for building distributed systems using microservices architecture, including service decomposition, communication patterns,…
  url: /topics/microservice-architecture-patterns/
- slug: microservice-architecture
  name: Microservice Architecture
  short: An architectural style that structures an application as a collection of loosely coupled, independently deployable services organized around business capabilit…
  url: /topics/microservice-architecture/
- slug: microservice-design
  name: Microservice Design
  short: Architectural approach for building applications as a collection of loosely coupled, independently deployable services that are organized around business capab…
  url: /topics/microservice-design/
- slug: microservices-architecture
  name: Microservices Architecture
  short: An architectural style that structures an application as a collection of loosely coupled, independently deployable services, each running in its own process an…
  url: /topics/microservices-architecture/
- slug: microservices-design-patterns
  name: Microservices Design Patterns
  short: Architectural patterns and best practices for designing, building, and maintaining microservices-based applications, including patterns for communication, data…
  url: /topics/microservices-design-patterns/
- slug: modular-monolith
  name: Modular Monolith
  short: An architectural pattern that structures a monolithic application into loosely coupled, well-defined modules with clear boundaries and dependencies, combining…
  url: /topics/modular-monolith/
- slug: monolithic-architecture
  name: Monolithic Architecture
  short: Monolithic Architecture is a software design approach in which an application is built as a single, unified unit where all components, business logic, data acc…
  url: /topics/monolithic-architecture/
- slug: pub-sub
  name: Pub/Sub
  short: A messaging pattern where publishers send messages to topics without knowledge of subscribers, and subscribers receive messages from topics they're interested…
  url: /topics/pub-sub/
- slug: serverless-patterns
  name: Serverless Patterns
  short: A collection of serverless architectures and patterns for building applications on AWS, featuring ready-to-use templates and best practices for Lambda, API Gat…
  url: /topics/serverless-patterns/
---
