---
layout: area
slug: cloud
name: Cloud
description: Cloud is a topic profile in the API Evangelist Network covering the major public cloud platforms and their APIs. The topic indexes the hyperscalers (Amazon Web Services, Microsoft Azure, Google Cloud, Oracle Cloud, IBM Cloud, Alibaba Cloud) alongside developer-focused alternatives (DigitalOcean, Linode, Vultr, Hetzner, Scaleway), GPU and AI clouds (CoreWeave, Crusoe, Lambda Labs, RunPod), and edge / network-attached compute (Cloudflare Workers, Fastly Compute, Akamai Connected Cloud). It is the parent topic to specialized profiles in the network such as cloud-storage, cloud-cost-management, and cloud-native.
tags:
- Cloud
- Cloud Computing
- Compute
- Hyperscaler
- IaaS
- Infrastructure
- PaaS
- Public Cloud
- SaaS
resource_count: 16
provider_count: 377
resources:
- name: Amazon Web Services
  description: Amazon Web Services is the largest public cloud, exposing 200+ services through service-specific REST and AWS-query APIs signed with SigV4. Compute (EC2, Lambda, ECS, EKS), storage (S3, EBS, EFS), database (RDS, DynamoDB, Aurora), networking (VPC, Route 53, CloudFront), and AI/ML (Bedrock, SageMaker) all expose progra…
  url: https://aws.amazon.com/
  tags:
  - AWS
  - Hyperscaler
  - IaaS
  - PaaS
  properties:
  - type: Documentation
    url: https://docs.aws.amazon.com/
- name: Microsoft Azure
  description: Microsoft Azure provides public-cloud compute, storage, database, AI, and identity services through Azure Resource Manager (ARM) REST APIs. Authentication uses Microsoft Entra ID (formerly Azure AD) OAuth tokens. Microsoft Graph exposes the M365 surface alongside the ARM control plane.
  url: https://azure.microsoft.com/
  tags:
  - Azure
  - Hyperscaler
  - IaaS
  - PaaS
  properties:
  - type: Documentation
    url: https://learn.microsoft.com/en-us/rest/api/azure/
- name: Google Cloud
  description: Google Cloud Platform exposes 100+ services through Google APIs (REST + gRPC) authenticated with OAuth 2.0 service accounts. Compute Engine, GKE, Cloud Run, BigQuery, Spanner, Firestore, Vertex AI, and Cloud Storage all share the consistent google apis.com endpoint pattern.
  url: https://cloud.google.com/
  tags:
  - GCP
  - Google
  - Hyperscaler
  - IaaS
  - PaaS
  properties:
  - type: Documentation
    url: https://cloud.google.com/apis/docs/overview
- name: Oracle Cloud Infrastructure
  description: Oracle Cloud Infrastructure exposes IaaS and database APIs signed with OCI request signatures. Compute, networking, storage, autonomous database, and Oracle Database@Azure / GCP multicloud surfaces are accessible via region-specific REST endpoints.
  url: https://www.oracle.com/cloud/
  tags:
  - Oracle
  - OCI
  properties:
  - type: Documentation
    url: https://docs.oracle.com/en-us/iaas/api/
- name: IBM Cloud
  description: IBM Cloud exposes Kubernetes Service, VPC compute, Cloud Object Storage, Watsonx AI, Db2, and Cloudability cost management APIs. Authentication uses IAM API keys exchanged for bearer tokens.
  url: https://www.ibm.com/cloud
  tags:
  - IBM
  properties:
  - type: Documentation
    url: https://cloud.ibm.com/apidocs
- name: Alibaba Cloud
  description: Alibaba Cloud is the largest public cloud in Asia. APIs cover ECS, OSS object storage, ApsaraDB, Function Compute, and PAI AI services. RPC and ROA-style endpoints are signed with HMAC using AccessKey credentials.
  url: https://www.alibabacloud.com/
  tags:
  - Alibaba
  - Asia
  - Hyperscaler
  properties:
  - type: Documentation
    url: https://www.alibabacloud.com/help/en/api-references
- name: DigitalOcean
  description: DigitalOcean offers a developer-friendly REST API for Droplets, Kubernetes, App Platform, Spaces, Volumes, Load Balancers, Databases, and Functions. Authentication uses bearer tokens.
  url: https://www.digitalocean.com/
  tags:
  - DigitalOcean
  - Developer Cloud
  properties:
  - type: Documentation
    url: https://docs.digitalocean.com/reference/api/
- name: Linode (Akamai Cloud)
  description: Linode (now Akamai Connected Cloud) exposes a REST API for Linode instances, Kubernetes (LKE), Object Storage, NodeBalancers, and Cloud Firewalls.
  url: https://www.linode.com/
  tags:
  - Akamai
  - Linode
  properties:
  - type: Documentation
    url: https://www.linode.com/docs/api/
- name: Vultr
  description: Vultr provides REST APIs for cloud compute, bare metal, Kubernetes, Object Storage, Block Storage, DNS, and Load Balancers across 30+ global regions.
  url: https://www.vultr.com/
  tags:
  - Vultr
  properties:
  - type: Documentation
    url: https://www.vultr.com/api/
- name: Hetzner Cloud
  description: Hetzner Cloud is a German hyperscaler offering low-cost cloud servers, volumes, networks, and load balancers via a documented REST API with bearer token authentication.
  url: https://www.hetzner.com/cloud
  tags:
  - Europe
  - Hetzner
  properties:
  - type: Documentation
    url: https://docs.hetzner.cloud/
- name: Scaleway
  description: Scaleway is a French cloud provider with REST APIs for Instances, Kubernetes (Kapsule), Object Storage, Serverless, Databases, and AI inference endpoints.
  url: https://www.scaleway.com/
  tags:
  - Europe
  - Scaleway
  properties:
  - type: Documentation
    url: https://www.scaleway.com/en/developers/api/
- name: Cloudflare
  description: Cloudflare offers an edge-attached cloud (Workers, R2, D1, Durable Objects, Queues, AI Gateway) accessible via the Cloudflare REST API authenticated with API tokens.
  url: https://www.cloudflare.com/
  tags:
  - Cloudflare
  - Edge
  - Network
  properties:
  - type: Documentation
    url: https://developers.cloudflare.com/api/
- name: Fastly Compute
  description: Fastly Compute runs WebAssembly workloads at the edge. The Fastly REST API manages services, configurations, dictionaries, and Compute deployments.
  url: https://www.fastly.com/products/edge-compute
  tags:
  - Edge
  - Fastly
  - WebAssembly
  properties:
  - type: Documentation
    url: https://www.fastly.com/documentation/reference/api/
- name: CoreWeave
  description: CoreWeave is a GPU-first cloud focused on AI training and inference workloads. APIs are exposed primarily through Kubernetes-native CRDs and the CoreWeave Cloud REST API.
  url: https://www.coreweave.com/
  tags:
  - AI
  - CoreWeave
  - GPU
  properties:
  - type: Documentation
    url: https://docs.coreweave.com/
- name: Crusoe Cloud
  description: Crusoe Cloud is a sustainable AI-first cloud powered by stranded and renewable energy. The REST API provisions GPU virtual machines, networking, storage, and projects programmatically.
  url: https://crusoecloud.com/
  tags:
  - AI
  - Crusoe
  - GPU
  - Sustainable
  properties:
  - type: Documentation
    url: https://docs.crusoecloud.com/reference/api/
- name: Lambda Labs Cloud
  description: Lambda Cloud provides on-demand and reserved NVIDIA GPU instances. The REST API launches and terminates GPU instances, manages SSH keys, and lists instance types.
  url: https://lambdalabs.com/service/gpu-cloud
  tags:
  - AI
  - GPU
  - Lambda
  properties:
  - type: Documentation
    url: https://cloud.lambdalabs.com/api/v1/docs
providers:
- slug: cloud
  name: Cloud
  description: Cloud is a topic profile in the API Evangelist Network covering the major public cloud platforms and their APIs. The topic indexes the hyperscalers (Amazon Web Services, Microsoft Azure, Google Cloud, Oracle Cloud, IBM Cloud, Alibaba Cloud) alongside developer-focused alternatives (DigitalOcean, Li…
  api_count: 16
  score_band: minimal
  score_composite: 21.4
  shared: 9
- slug: azure-cloud
  name: Microsoft Azure Cloud
  description: A comprehensive collection of Microsoft Azure cloud service APIs covering compute, storage, databases, AI, networking, security, and developer tools. Azure provides IaaS, PaaS, and SaaS delivery models through a global network of datacenters, with REST APIs secured by Microsoft Entra ID authenticat…
  api_count: 10
  score_band: developing
  score_composite: 50.3
  shared: 5
- slug: amazon-ec2
  name: Amazon EC2
  description: Amazon Elastic Compute Cloud (EC2) provides resizable compute capacity in the cloud, allowing you to launch virtual server instances, manage networking, and configure storage with complete control over your computing resources.
  api_count: 1
  score_band: developing
  score_composite: 59.4
  shared: 4
- slug: amazon-web-services-aws
  name: Amazon Web Services (AWS)
  description: Amazon Web Services offers reliable, scalable, and inexpensive cloud computing services. Free to join, pay only for what you use.
  api_count: 90
  score_band: developing
  score_composite: 56.9
  shared: 4
- slug: aws
  name: Amazon Web Services (AWS)
  description: Amazon Web Services is a comprehensive collection of cloud computing services and APIs provided by Amazon, offering infrastructure as a service, platform as a service, and software as a service solutions globally.
  api_count: 5
  score_band: developing
  score_composite: 52.5
  shared: 4
- slug: microsoft-azure-virtual-machines
  name: Azure Virtual Machines
  description: Azure Virtual Machines (VMs) is one of several types of on-demand, scalable computing resources that Azure offers. VMs give you the flexibility of virtualization without having to buy and maintain physical hardware.
  api_count: 10
  score_band: developing
  score_composite: 52.3
  shared: 4
- slug: google-cloud-platform-gcp
  name: Google Cloud Platform
  description: Google Cloud Platform provides a comprehensive suite of cloud computing services including compute, storage, databases, machine learning, networking, and more.
  api_count: 10
  score_band: thin
  score_composite: 41.7
  shared: 4
- slug: oracle
  name: Oracle
  description: Collection of Oracle's APIs and developer resources across cloud infrastructure, databases, AI services, SaaS applications, and platform services.
  api_count: 52
  score_band: strong
  score_composite: 66.4
  shared: 3
- slug: apache-cloudstack
  name: Apache CloudStack
  description: Apache CloudStack is an open-source cloud computing platform developed by the Apache Software Foundation for creating, managing, and deploying infrastructure cloud services. It provides a comprehensive IaaS platform supporting multiple hypervisors (KVM, VMware vSphere, XenServer) and a rich API for…
  api_count: 1
  score_band: developing
  score_composite: 52.6
  shared: 3
- slug: google-cloud-compute-engine
  name: Google Cloud Compute Engine
  description: Google Cloud Compute Engine delivers virtual machines running in Google's innovative data centers and worldwide fiber network. Compute Engine VMs boot quickly, come with persistent disk storage, and deliver consistent performance. It offers predefined and custom machine types, preemptible VMs, and…
  api_count: 1
  score_band: developing
  score_composite: 51.7
  shared: 3
- slug: digital-ocean
  name: Digital Ocean
  description: DigitalOcean Holdings, Inc. is an American multinational technology company and cloud service provider. The company is headquartered in New York City, New York, US, with 15 globally distributed data centers. DigitalOcean provides developers, startups, and SMBs with cloud infrastructure-as-a-service…
  api_count: 1
  score_band: thin
  score_composite: 41.3
  shared: 3
- slug: exoscale
  name: Exoscale
  description: Exoscale is a Swiss cloud infrastructure provider offering secure, reliable, and scalable cloud solutions to businesses of all sizes. Their services include virtual machines, object storage, networking, security, Kubernetes (SKS), Database as a Service (DBaaS), and IAM. Data centers are located in…
  api_count: 1
  score_band: thin
  score_composite: 41.3
  shared: 3
- slug: jarvislabs
  name: JarvisLabs
  description: JarvisLabs.ai is a GPU cloud for AI development that lets you launch on-demand GPU and CPU instances (H100, H200, A100, RTX Pro 6000, A6000, A5000, L4, A30) from the terminal. Its Python SDK (jarvislabs / legacy jlclient) and jl CLI wrap an API for the full instance lifecycle - create, pause, resum…
  api_count: 5
  score_band: thin
  score_composite: 35.8
  shared: 3
- slug: shadeform
  name: Shadeform
  description: Shadeform is a GPU cloud marketplace that exposes a single REST API for deploying and managing GPU compute across many underlying clouds. One interface lets you compare real-time availability and per-GPU-hour pricing, then launch, inspect, restart, and delete instances, attach volumes and SSH keys,…
  api_count: 5
  score_band: thin
  score_composite: 34.5
  shared: 3
- slug: thundercompute
  name: Thunder Compute
  description: Thunder Compute is a low-cost GPU cloud offering on-demand virtual GPU instances (T4, A6000, A100 80GB, L40, H100 PCIe) billed per minute. Developers provision and manage instances primarily through the tnr CLI, with a documented REST API at https://api.thundercompute.com:8443/v1 for creating, list…
  api_count: 4
  score_band: thin
  score_composite: 33.6
  shared: 3
- slug: fluidstack
  name: Fluidstack
  description: Fluidstack is an AI cloud platform that builds and operates high-performance, single-tenant GPU clusters for top AI labs, governments, and enterprises. Founded in 2017 out of Oxford University and now headquartered in New York City, Fluidstack manages more than 100,000 GPUs across its global networ…
  api_count: 1
  score_band: minimal
  score_composite: 26.7
  shared: 3
- slug: google-cloud-platform
  name: Google Cloud Platform
  description: Google Cloud Platform enables developers to build, test, and deploy applications on Google's highly-scalable and reliable infrastructure.
  api_count: 36
  score_band: strong
  score_composite: 65.5
  shared: 2
- slug: daytona-io
  name: Daytona
  description: Daytona is open-source, secure, and elastic infrastructure for running AI-generated code. Daytona sandboxes spin up in under 90 milliseconds and provide isolated Linux, Windows, and macOS environments where autonomous agents and developer workflows can execute untrusted code, perform file system an…
  api_count: 11
  score_band: strong
  score_composite: 64.0
  shared: 2
- slug: adobe-creative-cloud
  name: Adobe Creative Cloud
  description: Adobe Creative Cloud is a suite of software and cloud services for graphic design, video editing, web development, photography, and 3D content creation. Its developer platform provides APIs for generative AI via Firefly Services, cloud storage and asset management, PDF document processing, electron…
  api_count: 17
  score_band: strong
  score_composite: 62.0
  shared: 2
- slug: microsoft-azure-functions
  name: Microsoft Azure Functions
  description: Azure Functions is a serverless compute platform from Microsoft Azure enabling event-driven code execution triggered by HTTP requests, timers, queues, blobs, and other Azure services. The Azure Functions management API provides programmatic access to function app lifecycle management, deployment, c…
  api_count: 2
  score_band: strong
  score_composite: 61.8
  shared: 2
- slug: microsoft-azure
  name: Microsoft Azure
  description: Microsoft Azure is a cloud computing platform and infrastructure for building, deploying, and managing applications and services through Microsoft-managed data centers.
  api_count: 463
  score_band: strong
  score_composite: 60.7
  shared: 2
- slug: azure-networking-services
  name: Azure Networking Services
  description: A comprehensive collection of Azure networking APIs for managing virtual networks, load balancers, application gateways, VPN gateways, DNS, and other networking resources in the Microsoft Azure cloud.
  api_count: 2
  score_band: developing
  score_composite: 56.5
  shared: 2
- slug: mews-com
  name: Mews
  description: Mews is a cloud-native hospitality operating system serving 15,000+ hotels, hostels, and vacation-rental properties across 85 countries. Founded in Prague in 2012 by Richard Valtr and Matthijs Welle and reaching unicorn status in 2024, Mews offers an integrated Property Management System, Point of…
  api_count: 6
  score_band: developing
  score_composite: 55.9
  shared: 2
- slug: azure
  name: Microsoft Azure
  description: Microsoft Azure is a comprehensive cloud computing platform offering IaaS, PaaS, and SaaS solutions for building, deploying, and managing applications through Microsoft's global network of datacenters.
  api_count: 3
  score_band: developing
  score_composite: 55.8
  shared: 2
related:
- slug: linux-server
  name: Linux Server
  shared: 1
- slug: cloud-storage
  name: Cloud Storage
  shared: 1
repo: https://github.com/api-evangelist/cloud
overview: 'Cloud on the [APIs.io](https://apis.io/) network is a curated area collecting 16 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including Cloud, Microsoft Azure Cloud, Amazon EC2, Amazon Web Services (AWS), Amazon Web Services (AWS), Azure Virtual Machines, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Linux Server and Cloud Storage. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
