---
layout: area
slug: service-mesh
name: Service Mesh
description: Service mesh is a dedicated infrastructure layer for handling service-to-service communication in microservices architectures. It provides traffic management, mutual TLS security,…
area_url: https://service-mesh.apievangelist.com
area_host: service-mesh.apievangelist.com
icon: https://service-mesh.apievangelist.com/icon-thumb.png
provider_count: 41
providers:
- slug: solo-io
  name: Solo.io
  description: Solo.io is a cloud-native application-networking company founded in 2017 that builds enterprise and open-source API gateways, service mesh, and agentic-AI infrastructure. Its products include Kgateway Enterprise (formerly Gloo Gateway), an Envoy-powered Kubernetes Gateway API ingress and API gatewa…
  api_count: 15
  score_band: exemplar
  score_composite: 68.2
  shared: 1
- slug: aws-app-mesh
  name: AWS App Mesh
  description: AWS App Mesh is a service mesh based on the Envoy proxy that provides application-level networking to make it easy for services to communicate with each other across multiple types of compute infrastructure including Amazon ECS, EKS, EC2, and Fargate. App Mesh standardizes service communication, gi…
  api_count: 4
  score_band: developing
  score_composite: 52.5
  shared: 1
- slug: kong
  name: Kong
  description: Kong is the AI Connectivity Company. Its platform spans Kong Gateway (the open-source API gateway built on NGINX and Lua), Kong Konnect (the SaaS control plane), Kong AI Gateway (LLM, MCP, and agent-to-agent traffic governance with semantic caching, token budgeting, and prompt firewalls), Kong Agen…
  api_count: 139
  score_band: developing
  score_composite: 51.7
  shared: 1
- slug: amazon-app-mesh
  name: Amazon App Mesh
  description: AWS App Mesh is a service mesh that provides application-level networking to make it easy for your services to communicate with each other across multiple types of compute infrastructure.
  api_count: 4
  score_band: developing
  score_composite: 46.6
  shared: 1
- slug: tetrate
  name: Tetrate
  description: Tetrate is an enterprise service mesh company that provides Tetrate Service Bridge (TSB), a multi-cluster, multi-cloud service mesh management platform built on Istio and Envoy Proxy. Tetrate offers management APIs for traffic, security, and observability across distributed microservice environment…
  api_count: 15
  score_band: developing
  score_composite: 41.1
  shared: 1
- slug: amazon-vpc-lattice
  name: Amazon VPC Lattice
  description: Amazon VPC Lattice is an application networking service that consistently connects, monitors, and secures communications between your services, helping you to improve productivity so that your developers can focus on building features that matter to your business. It simplifies service-to-service c…
  api_count: 73
  score_band: developing
  score_composite: 40.9
  shared: 1
- slug: google-cloud-service-mesh
  name: Google Cloud Service Mesh
  description: Google Cloud Service Mesh is Google's managed service mesh solution for GKE and supported GKE Enterprise environments, enabling secure, observable, and reliable communication between microservices. It provides a managed Istio control plane, Google Cloud-native service routing APIs, mTLS security, a…
  api_count: 13
  score_band: thin
  score_composite: 39.2
  shared: 1
- slug: istio
  name: Istio
  description: Istio is an open-source service mesh platform that provides a comprehensive solution for managing, securing, and monitoring microservices in a distributed system. It acts as a middle layer between services, handling communication, routing, and load balancing, as well as providing visibility into th…
  api_count: 14
  score_band: thin
  score_composite: 38.9
  shared: 1
- slug: vmware-tanzu
  name: VMware Tanzu
  description: VMware Tanzu (now part of Broadcom) is a portfolio of products for modernizing applications and infrastructure with a common approach to building, running, and managing Kubernetes across multi-cloud environments. Key APIs include the Tanzu Service Mesh REST API for cluster and global namespace mana…
  api_count: 5
  score_band: thin
  score_composite: 38.8
  shared: 1
- slug: consul
  name: HashiCorp Consul
  description: HashiCorp Consul is a distributed, highly available service-networking control plane that automates network configuration, discovers services, enables secure service-to-service communication, and exposes a strongly consistent key/value store. The Consul HTTP API is a REST + JSON service exposed by…
  api_count: 14
  score_band: thin
  score_composite: 38.3
  shared: 1
- slug: calico
  name: Calico
  description: Calico is an open source networking and network security solution for containers, virtual machines, and native host-based workloads. Created and maintained by Tigera, it is the most widely adopted solution for container networking and security, powering over 8 million nodes daily across 166 countri…
  api_count: 10
  score_band: thin
  score_composite: 38.0
  shared: 1
- slug: envoy
  name: Envoy
  description: Envoy is a high-performance, open-source edge and service proxy designed for cloud-native applications and microservice architectures. It provides advanced load balancing, observability, and traffic management features, and serves as the data plane for many service mesh implementations including Is…
  api_count: 15
  score_band: thin
  score_composite: 37.7
  shared: 1
- slug: kuma
  name: Kuma
  description: Kuma is a platform-agnostic open-source service mesh built on top of Envoy proxy. It provides universal connectivity, security, and observability for services and microservices running on any infrastructure including Kubernetes and VMs.
  api_count: 38
  score_band: thin
  score_composite: 37.2
  shared: 1
- slug: linkerd
  name: Linkerd
  description: Service mesh without the mess. Linkerd adds security, observability, and reliability to any Kubernetes cluster without the complexity of bloat of other meshes.
  api_count: 11
  score_band: thin
  score_composite: 36.7
  shared: 1
- slug: google-anthos
  name: Google Anthos
  description: Google Anthos is a managed application platform that extends Google Cloud services and engineering practices to hybrid and multi-cloud environments. Built on Kubernetes, Anthos enables consistent development and operations across on-premises data centers, Google Cloud, and other public clouds like…
  api_count: 4
  score_band: thin
  score_composite: 35.9
  shared: 1
- slug: isovalent
  name: Isovalent
  description: Isovalent is the company founded in 2017 by the creators of Cilium, the eBPF-based networking, security, and observability platform for Kubernetes and cloud-native infrastructure. Isovalent builds and maintains the open source Cilium project (a CNCF graduated project), the Hubble observability laye…
  api_count: 10
  score_band: thin
  score_composite: 35.6
  shared: 1
- slug: apache-dubbo
  name: Apache Dubbo
  description: Apache Dubbo is a high-performance, Java-based open-source RPC framework that provides service discovery, traffic management, and observability capabilities for building enterprise-level microservices. It supports multiple protocols including Triple (gRPC-compatible), Dubbo, and REST, with SDKs for…
  api_count: 16
  score_band: thin
  score_composite: 34.9
  shared: 1
- slug: consul-connect
  name: Consul Connect
  description: Consul Connect is the service mesh subsystem of HashiCorp Consul. Connect provides service identity, mTLS, traffic authorization via intentions, and L7 traffic management through Envoy sidecar proxies. Consul Connect ships with a built-in certificate authority that can also be backed by Vault or ex…
  api_count: 4
  score_band: thin
  score_composite: 34.4
  shared: 1
- slug: scalable-services
  name: Scalable Services
  description: A curated topic collection covering APIs, patterns, tools, and best practices for designing and operating scalable services. This includes cloud-native microservices, API gateways, load balancers, container orchestration, serverless platforms, service meshes, and the architectural patterns that ena…
  api_count: 14
  score_band: thin
  score_composite: 32.4
  shared: 1
- slug: pubmed
  name: PubMed
  description: NCBI PubMed is the primary biomedical literature database providing free access to over 35 million citations and abstracts from life science journals and online books. The Entrez Programming Utilities (E-utilities) REST API enables programmatic searching, retrieval, and linking of citations, articl…
  api_count: 10
  score_band: thin
  score_composite: 32.1
  shared: 1
- slug: traefik-mesh
  name: Traefik Mesh
  description: Traefik Mesh (formerly Maesh) is a lightweight, non-invasive service mesh built on top of Traefik Proxy for Kubernetes. It provides automatic traffic management, observability, and security for microservices without requiring sidecar containers. Traefik Mesh is compliant with the Service Mesh Inter…
  api_count: 3
  score_band: thin
  score_composite: 32.1
  shared: 1
- slug: apiclarity
  name: APIClarity
  description: APIClarity is an open source API security and observability tool that analyzes API traffic to reconstruct OpenAPI specifications, detect shadow and zombie APIs, identify API differences and changes, and provide API security alerts. It is part of the OpenClarity project and works with Kubernetes ser…
  api_count: 4
  score_band: thin
  score_composite: 29.0
  shared: 1
- slug: tekion
  name: Tekion
  description: Tekion is a cloud-native, AI-native automotive retail platform whose flagship Automotive Retail Cloud (ARC) is a modern dealer management system (DMS) spanning sales, service, parts, inventory, F&I, accounting, and CRM for franchise dealerships and OEMs. Tekion exposes its data and workflows to tec…
  api_count: 6
  score_band: thin
  score_composite: 27.4
  shared: 1
- slug: scalable-architecture
  name: Scalable Architecture
  description: A subject-matter collection covering APIs, patterns, tools, and frameworks for building scalable system architecture. This topic encompasses microservices design, service mesh, event-driven architecture, CQRS, saga patterns, container orchestration, caching, message queuing, and observability patte…
  api_count: 8
  score_band: emerging
  score_composite: 23.4
  shared: 1
- slug: gloo
  name: Gloo
  description: Gloo is a suite of open-source and enterprise API gateway and service mesh products from Solo.io built on Envoy Proxy, offering advanced traffic management, security, observability, and developer portal capabilities for Kubernetes and cloud-native environments.
  api_count: 4
  score_band: emerging
  score_composite: 21.6
  shared: 1
- slug: buoyant
  name: Buoyant
  description: Buoyant is the creator of Linkerd, the CNCF-graduated service mesh for Kubernetes. Linkerd provides zero-trust security via mutual TLS, ultra-high availability with automated failover, and observability for microservices including AI/LLM workloads. Buoyant Enterprise Linkerd adds enterprise feature…
  api_count: 2
  score_band: emerging
  score_composite: 20.7
  shared: 1
- slug: meshery
  name: Meshery
  description: Meshery is the cloud native manager for Kubernetes and cloud native infrastructure. It is an extensible, self-service engineering platform that enables collaborative design, lifecycle and performance management of cloud native applications and infrastructure. Meshery exposes REST and GraphQL APIs f…
  api_count: 0
  score_band: emerging
  score_composite: 20.3
  shared: 1
- slug: ambient-mesh
  name: Ambient Mesh
  description: Ambient Mesh is a sidecar-less service mesh architecture built on Istio that simplifies microservices communication, enhances zero-trust security, and improves observability without requiring sidecar proxy injection. It uses a shared per-node proxy (ztunnel) for zero-trust security and optional way…
  api_count: 1
  score_band: emerging
  score_composite: 19.6
  shared: 1
- slug: greymatter
  name: Greymatter
  description: Greymatter is a Kubernetes-native, zero trust networking platform that delivers secure, agentic, and scalable service connectivity across multi-cloud, hybrid, and edge environments. It provides a unified platform with five integrated layers covering service connectivity, zero trust security, orches…
  api_count: 3
  score_band: emerging
  score_composite: 19.5
  shared: 1
- slug: gloo-mesh
  name: Gloo Mesh
  description: Gloo Mesh is an enterprise service mesh management platform from Solo.io built on Istio, providing multi-cluster and multi-mesh traffic management, security policy enforcement, and observability across hybrid cloud environments. It simplifies service mesh operations with a unified control plane and…
  api_count: 2
  score_band: emerging
  score_composite: 19.0
  shared: 1
related:
- slug: microservices
  name: Microservices
  shared: 5
- slug: proxy
  name: Proxy
  shared: 1
- slug: performance
  name: Performance
  shared: 1
overview: 'Service Mesh is one of the API Evangelist areas on the [APIs.io](https://apis.io/) network — a focused corner of the API landscape. The full area lives at [service-mesh.apievangelist.com](https://service-mesh.apievangelist.com).


  30 providers on the network work in this area, including Solo.io, AWS App Mesh, Kong, Amazon App Mesh, Tetrate, Amazon VPC Lattice, and 24 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Microservices, Proxy, and Performance. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
