---
layout: area
slug: service-mesh
name: Service Mesh
description: Service mesh is a dedicated infrastructure layer for handling service-to-service communication in microservices architectures. It provides traffic management, mutual TLS security,…
area_url: https://service-mesh.apievangelist.com
area_host: service-mesh.apievangelist.com
icon: https://service-mesh.apievangelist.com/icon-thumb.png
provider_count: 34
providers:
- slug: aws-app-mesh
  name: AWS App Mesh
  description: AWS App Mesh is a service mesh based on the Envoy proxy that provides application-level networking to make it easy for services to communicate with each other across multiple types of compute infrastructure including Amazon ECS, EKS, EC2, and Fargate. App Mesh standardizes service communication, gi…
  api_count: 1
  score_band: strong
  score_composite: 65.3
  shared: 1
- slug: consul
  name: HashiCorp Consul
  description: HashiCorp Consul is a distributed, highly available service-networking control plane that automates network configuration, discovers services, enables secure service-to-service communication, and exposes a strongly consistent key/value store. The Consul HTTP API is a REST + JSON service exposed by…
  api_count: 1
  score_band: developing
  score_composite: 53.6
  shared: 1
- slug: kong
  name: Kong
  description: Kong is the AI Connectivity Company. Its platform spans Kong Gateway (the open-source API gateway built on NGINX and Lua), Kong Konnect (the SaaS control plane), Kong AI Gateway (LLM, MCP, and agent-to-agent traffic governance with semantic caching, token budgeting, and prompt firewalls), Kong Agen…
  api_count: 10
  score_band: developing
  score_composite: 52.9
  shared: 1
- slug: apache-dubbo
  name: Apache Dubbo
  description: Apache Dubbo is a high-performance, Java-based open-source RPC framework that provides service discovery, traffic management, and observability capabilities for building enterprise-level microservices. It supports multiple protocols including Triple (gRPC-compatible), Dubbo, and REST, with SDKs for…
  api_count: 3
  score_band: developing
  score_composite: 50.9
  shared: 1
- slug: consul-connect
  name: Consul Connect
  description: Consul Connect is the service mesh subsystem of HashiCorp Consul. Connect provides service identity, mTLS, traffic authorization via intentions, and L7 traffic management through Envoy sidecar proxies. Consul Connect ships with a built-in certificate authority that can also be backed by Vault or ex…
  api_count: 3
  score_band: developing
  score_composite: 50.0
  shared: 1
- slug: tetrate
  name: Tetrate
  description: Tetrate is an enterprise service mesh company that provides Tetrate Service Bridge (TSB), a multi-cluster, multi-cloud service mesh management platform built on Istio and Envoy Proxy. Tetrate offers management APIs for traffic, security, and observability across distributed microservice environment…
  api_count: 6
  score_band: developing
  score_composite: 49.4
  shared: 1
- slug: amazon-vpc-lattice
  name: Amazon VPC Lattice
  description: Amazon VPC Lattice is an application networking service that consistently connects, monitors, and secures communications between your services, helping you to improve productivity so that your developers can focus on building features that matter to your business. It simplifies service-to-service c…
  api_count: 1
  score_band: developing
  score_composite: 48.9
  shared: 1
- slug: amazon-app-mesh
  name: Amazon App Mesh
  description: AWS App Mesh is a service mesh that provides application-level networking to make it easy for your services to communicate with each other across multiple types of compute infrastructure.
  api_count: 1
  score_band: developing
  score_composite: 48.2
  shared: 1
- slug: linkerd
  name: Linkerd
  description: Service mesh without the mess. Linkerd adds security, observability, and reliability to any Kubernetes cluster without the complexity of bloat of other meshes.
  api_count: 5
  score_band: developing
  score_composite: 45.1
  shared: 1
- slug: google-cloud-service-mesh
  name: Google Cloud Service Mesh
  description: Google Cloud Service Mesh is Google's managed service mesh solution for GKE and supported GKE Enterprise environments, enabling secure, observable, and reliable communication between microservices. It provides a managed Istio control plane, Google Cloud-native service routing APIs, mTLS security, a…
  api_count: 3
  score_band: thin
  score_composite: 44.7
  shared: 1
- slug: vmware-tanzu
  name: VMware Tanzu
  description: VMware Tanzu (now part of Broadcom) is a portfolio of products for modernizing applications and infrastructure with a common approach to building, running, and managing Kubernetes across multi-cloud environments. Key APIs include the Tanzu Service Mesh REST API for cluster and global namespace mana…
  api_count: 2
  score_band: thin
  score_composite: 44.2
  shared: 1
- slug: istio
  name: Istio
  description: Istio is an open-source service mesh platform that provides a comprehensive solution for managing, securing, and monitoring microservices in a distributed system. It acts as a middle layer between services, handling communication, routing, and load balancing, as well as providing visibility into th…
  api_count: 6
  score_band: thin
  score_composite: 42.7
  shared: 1
- slug: envoy
  name: Envoy
  description: Envoy is a high-performance, open-source edge and service proxy designed for cloud-native applications and microservice architectures. It provides advanced load balancing, observability, and traffic management features, and serves as the data plane for many service mesh implementations including Is…
  api_count: 5
  score_band: thin
  score_composite: 41.2
  shared: 1
- slug: solo
  name: Solo.io
  description: Solo.io provides enterprise infrastructure for cloud-native and AI-native environments, including API gateways, service mesh, and agentic AI infrastructure built on Envoy, Istio, and Kubernetes. Products include kgateway (API gateway), Istio-based service mesh, agentgateway (AI gateway), kagent (AI…
  api_count: 4
  score_band: thin
  score_composite: 40.5
  shared: 1
- slug: google-anthos
  name: Google Anthos
  description: Google Anthos is a managed application platform that extends Google Cloud services and engineering practices to hybrid and multi-cloud environments. Built on Kubernetes, Anthos enables consistent development and operations across on-premises data centers, Google Cloud, and other public clouds like…
  api_count: 2
  score_band: thin
  score_composite: 40.4
  shared: 1
- slug: kuma
  name: Kuma
  description: Kuma is a platform-agnostic open-source service mesh built on top of Envoy proxy. It provides universal connectivity, security, and observability for services and microservices running on any infrastructure including Kubernetes and VMs.
  api_count: 3
  score_band: thin
  score_composite: 40.0
  shared: 1
- slug: scalable-services
  name: Scalable Services
  description: A curated topic collection covering APIs, patterns, tools, and best practices for designing and operating scalable services. This includes cloud-native microservices, API gateways, load balancers, container orchestration, serverless platforms, service meshes, and the architectural patterns that ena…
  api_count: 8
  score_band: thin
  score_composite: 37.5
  shared: 1
- slug: traefik-mesh
  name: Traefik Mesh
  description: Traefik Mesh (formerly Maesh) is a lightweight, non-invasive service mesh built on top of Traefik Proxy for Kubernetes. It provides automatic traffic management, observability, and security for microservices without requiring sidecar containers. Traefik Mesh is compliant with the Service Mesh Inter…
  api_count: 1
  score_band: thin
  score_composite: 36.0
  shared: 1
- slug: gloo
  name: Gloo
  description: Gloo is a suite of open-source and enterprise API gateway and service mesh products from Solo.io built on Envoy Proxy, offering advanced traffic management, security, observability, and developer portal capabilities for Kubernetes and cloud-native environments.
  api_count: 4
  score_band: thin
  score_composite: 35.9
  shared: 1
- slug: scalable-architecture
  name: Scalable Architecture
  description: A subject-matter collection covering APIs, patterns, tools, and frameworks for building scalable system architecture. This topic encompasses microservices design, service mesh, event-driven architecture, CQRS, saga patterns, container orchestration, caching, message queuing, and observability patte…
  api_count: 8
  score_band: thin
  score_composite: 35.4
  shared: 1
- slug: gloo-mesh
  name: Gloo Mesh
  description: Gloo Mesh is an enterprise service mesh management platform from Solo.io built on Istio, providing multi-cluster and multi-mesh traffic management, security policy enforcement, and observability across hybrid cloud environments. It simplifies service mesh operations with a unified control plane and…
  api_count: 2
  score_band: thin
  score_composite: 35.1
  shared: 1
- slug: apiclarity
  name: APIClarity
  description: APIClarity is an open source API security and observability tool that analyzes API traffic to reconstruct OpenAPI specifications, detect shadow and zombie APIs, identify API differences and changes, and provide API security alerts. It is part of the OpenClarity project and works with Kubernetes ser…
  api_count: 1
  score_band: thin
  score_composite: 34.1
  shared: 1
- slug: greymatter
  name: Greymatter
  description: Greymatter is a Kubernetes-native, zero trust networking platform that delivers secure, agentic, and scalable service connectivity across multi-cloud, hybrid, and edge environments. It provides a unified platform with five integrated layers covering service connectivity, zero trust security, orches…
  api_count: 3
  score_band: minimal
  score_composite: 29.9
  shared: 1
- slug: tekion
  name: Tekion
  description: Tekion is a cloud-native, AI-native automotive retail platform whose flagship Automotive Retail Cloud (ARC) is a modern dealer management system (DMS) spanning sales, service, parts, inventory, F&I, accounting, and CRM for franchise dealerships and OEMs. Tekion exposes its data and workflows to tec…
  api_count: 6
  score_band: minimal
  score_composite: 29.7
  shared: 1
- slug: calico
  name: Calico
  description: Calico is an open source networking and network security solution for containers, virtual machines, and native host-based workloads. Created and maintained by Tigera, it is the most widely adopted solution for container networking and security, powering over 8 million nodes daily across 166 countri…
  api_count: 3
  score_band: minimal
  score_composite: 28.1
  shared: 1
- slug: buoyant
  name: Buoyant
  description: Buoyant is the creator of Linkerd, the CNCF-graduated service mesh for Kubernetes. Linkerd provides zero-trust security via mutual TLS, ultra-high availability with automated failover, and observability for microservices including AI/LLM workloads. Buoyant Enterprise Linkerd adds enterprise feature…
  api_count: 2
  score_band: minimal
  score_composite: 27.6
  shared: 1
- slug: ambient-mesh
  name: Ambient Mesh
  description: Ambient Mesh is a sidecar-less service mesh architecture built on Istio that simplifies microservices communication, enhances zero-trust security, and improves observability without requiring sidecar proxy injection. It uses a shared per-node proxy (ztunnel) for zero-trust security and optional way…
  api_count: 1
  score_band: minimal
  score_composite: 26.3
  shared: 1
- slug: nginx-service-mesh
  name: NGINX Service Mesh
  description: NGINX Service Mesh (NSM) is a service mesh from F5 NGINX powered by NGINX Plus, designed to manage container-to-container traffic in Kubernetes environments. It provides mTLS, traffic policies via the Service Mesh Interface (SMI), traffic splitting, rate limiting, observability (Prometheus, Grafana…
  api_count: 1
  score_band: minimal
  score_composite: 25.0
  shared: 1
- slug: tripo3d
  name: Tripo3D
  description: Tripo3D (by VAST) is an AI 3D generation platform with text-to-3D, image-to-3D, mesh refinement, and texturing APIs producing game-ready 3D assets. The Tripo API uses an async task-based REST pattern at https://api.tripo3d.ai/v2/openapi/task. Authenticate with API key.
  api_count: 1
  score_band: minimal
  score_composite: 23.4
  shared: 1
- slug: merbridge
  name: Merbridge
  description: Merbridge is an open source, eBPF-based service mesh acceleration tool that replaces iptables rules with eBPF traffic interception and uses msg_redirect to shorten the datapath between sidecars and services. It is a CNCF Sandbox project and supports Istio, Linkerd2, and Kuma.
  api_count: 1
  score_band: minimal
  score_composite: 22.9
  shared: 1
related:
- slug: microservices
  name: Microservices
  shared: 4
- slug: performance
  name: Performance
  shared: 2
- slug: proxy
  name: Proxy
  shared: 1
overview: 'Service Mesh is one of the API Evangelist areas on the [APIs.io](https://apis.io/) network — a focused corner of the API landscape. The full area lives at [service-mesh.apievangelist.com](https://service-mesh.apievangelist.com).


  30 providers on the network work in this area, including AWS App Mesh, HashiCorp Consul, Kong, Apache Dubbo, Consul Connect, Tetrate, and 24 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Microservices, Performance, and Proxy. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
