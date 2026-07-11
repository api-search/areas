---
layout: area
slug: configuration-language
name: Configuration Language
description: Configuration languages are formats and DSLs used to express the desired state of software systems, infrastructure, applications, and APIs. Configuration languages span a spectrum from simple text-based formats (INI, JSON, YAML, TOML) to typed and templated formats (HCL, Cue, Dhall, Pkl, Jsonnet, KDL) that support imports, schemas, and validation. The choice of configuration language shapes how teams describe Kubernetes manifests, Terraform infrastructure, OpenAPI specs, CI pipelines, and developer environments.
tags:
- Configuration
- DSL
- Infrastructure as Code
- Schemas
- Serialization
- Templating
- YAML
resource_count: 9
provider_count: 45
resources:
- name: YAML
  description: YAML Ain't Markup Language is a human-friendly data serialization language. YAML 1.2 is widely used for configuration in Kubernetes, OpenAPI, GitHub Actions, Ansible, and many other ecosystems. YAML supports comments, scalars, sequences, mappings, anchors, and tags.
  url: https://yaml.org/
  tags:
  - Human Readable
  - Serialization
  - Standards
  - YAML
  properties:
  - type: Specification
    url: https://yaml.org/spec/1.2.2/
  - type: Documentation
    url: https://yaml.org/
  - type: Reference
    url: https://github.com/yaml/yaml-spec
- name: JSON
  description: JavaScript Object Notation is a lightweight data interchange format defined by RFC 8259 and ECMA-404. JSON is heavily used as a configuration format in Node.js (package.json), VS Code settings, and many other tools, and is the foundation for JSON Schema-based validation.
  url: https://www.json.org/
  tags:
  - ECMA
  - IETF
  - Interchange
  - JSON
  properties:
  - type: Specification
    url: https://www.rfc-editor.org/rfc/rfc8259
  - type: Specification
    url: https://www.ecma-international.org/publications-and-standards/standards/ecma-404/
  - type: Reference
    url: https://json-schema.org/
- name: TOML
  description: Tom's Obvious, Minimal Language is a config file format designed to be human-readable and unambiguous. TOML is used by Cargo for Rust projects, Python packaging via pyproject.toml, and Hugo site config.
  url: https://toml.io/
  tags:
  - Configuration
  - Human Readable
  - TOML
  properties:
  - type: Specification
    url: https://toml.io/en/v1.0.0
  - type: GitHubRepository
    url: https://github.com/toml-lang/toml
- name: HCL
  description: HashiCorp Configuration Language is a structured configuration language designed for human authoring of complex configurations. HCL underpins Terraform, Packer, Vault, Consul, and Nomad and supports expressions, variables, functions, and blocks.
  url: https://github.com/hashicorp/hcl
  tags:
  - HCL
  - HashiCorp
  - Infrastructure as Code
  - Terraform
  properties:
  - type: GitHubRepository
    url: https://github.com/hashicorp/hcl
  - type: Documentation
    url: https://developer.hashicorp.com/terraform/language
- name: Cue
  description: Cue is an open source data validation language with a powerful type system and unification semantics. Cue is used to validate, generate, and transform configuration for Kubernetes, OpenAPI, and Terraform.
  url: https://cuelang.org/
  tags:
  - Cue
  - Schema
  - Type System
  - Validation
  properties:
  - type: Documentation
    url: https://cuelang.org/docs/
  - type: GitHubRepository
    url: https://github.com/cue-lang/cue
- name: Dhall
  description: Dhall is a programmable configuration language that adds types and functions to JSON and YAML. Dhall expressions are total (always terminate) and remote imports are content-addressed for safety.
  url: https://dhall-lang.org/
  tags:
  - Dhall
  - Functional
  - Total
  - Type Safe
  properties:
  - type: Documentation
    url: https://dhall-lang.org/
  - type: GitHubRepository
    url: https://github.com/dhall-lang/dhall-lang
- name: Pkl
  description: Pkl is Apple's open source configuration language with a focus on type safety, composition, and runtime templating. Pkl can render to YAML, JSON, plist, and other formats and offers IDE tooling and language bindings.
  url: https://pkl-lang.org/
  tags:
  - Apple
  - Pkl
  - Templating
  - Type Safe
  properties:
  - type: Documentation
    url: https://pkl-lang.org/main/current/
  - type: GitHubRepository
    url: https://github.com/apple/pkl
- name: Jsonnet
  description: Jsonnet is a data templating language designed for elegant generation of JSON and YAML. It is used heavily for Kubernetes manifests, Grafana dashboards (Grafonnet), and Bazel-based tooling.
  url: https://jsonnet.org/
  tags:
  - Generation
  - Jsonnet
  - Templating
  properties:
  - type: Documentation
    url: https://jsonnet.org/learning/tutorial.html
  - type: GitHubRepository
    url: https://github.com/google/jsonnet
- name: KDL
  description: KDL is a node-oriented document language combining the readability of YAML and TOML with a unique tree-shaped grammar. KDL is used by Zellij, Helix, and other tools.
  url: https://kdl.dev/
  tags:
  - KDL
  - Tree
  properties:
  - type: Specification
    url: https://github.com/kdl-org/kdl/blob/main/SPEC.md
  - type: Documentation
    url: https://kdl.dev/
providers:
- slug: configuration-language
  name: Configuration Language
  description: Configuration languages are formats and DSLs used to express the desired state of software systems, infrastructure, applications, and APIs. Configuration languages span a spectrum from simple text-based formats (INI, JSON, YAML, TOML) to typed and templated formats (HCL, Cue, Dhall, Pkl, Jsonnet, K…
  api_count: 9
  score_band: minimal
  score_composite: 23.3
  shared: 7
- slug: cribl
  name: Cribl
  description: Cribl is an observability pipeline company providing a suite of products for collecting, processing, routing, searching, and storing telemetry data at scale. Cribl's developer platform offers REST APIs across Stream, Edge, Search, Lake, and the As Code product line, exposing programmatic control ov…
  api_count: 6
  score_band: developing
  score_composite: 49.8
  shared: 2
- slug: kustomize
  name: Kustomize
  description: Kustomize is a Kubernetes-native configuration management tool that lets you customize untemplated YAML files for multiple purposes, leaving the original YAML intact and usable as-is, using a template-free approach to configuration customization.
  api_count: 1
  score_band: minimal
  score_composite: 24.6
  shared: 2
- slug: carvel
  name: Carvel
  description: Carvel is a set of reliable, single-purpose, composable command-line tools that help build, configure, and deploy applications to Kubernetes. The toolset includes ytt for YAML templating, kapp for application lifecycle management, kbld for immutable image references, imgpkg for OCI bundling, vendir…
  api_count: 7
  score_band: minimal
  score_composite: 24.5
  shared: 2
- slug: amazon-secrets-manager
  name: Amazon Secrets Manager
  description: Amazon Secrets Manager helps you manage, retrieve, and rotate database credentials, API keys, and other secrets throughout their lifecycle. It provides centralized secrets management with built-in integration for Amazon RDS, Amazon Redshift, and Amazon DocumentDB, enabling automatic rotation of sec…
  api_count: 1
  score_band: strong
  score_composite: 64.4
  shared: 1
- slug: cloudformation
  name: AWS CloudFormation
  description: A collection of APIs provided by AWS for infrastructure as code provisioning and management of AWS and third-party resources using CloudFormation templates and the Cloud Control API.
  api_count: 2
  score_band: strong
  score_composite: 61.5
  shared: 1
- slug: databricks-asset-bundles
  name: Databricks Asset Bundles
  description: Databricks Asset Bundles (DABs) provide an infrastructure-as-code approach to managing Databricks data and AI projects. Bundles enable version control, CI/CD, deployment, and management of Databricks resources such as jobs, pipelines, apps, schemas, experiments, and model serving endpoints across w…
  api_count: 1
  score_band: developing
  score_composite: 56.7
  shared: 1
- slug: mockaroo
  name: Mockaroo
  description: Mockaroo is a realistic mock data generator and API mocking service used by developers and QA teams to produce JSON, CSV, TXT, custom-delimited, SQL, and XML test data. The platform combines a schema designer, 150+ built-in field types (Name, Internet, Address, Business, Date, Currency, Geographic,…
  api_count: 1
  score_band: developing
  score_composite: 55.3
  shared: 1
- slug: amazon-proton
  name: Amazon Proton
  description: AWS Proton is a managed service for platform engineers that helps them publish standardized container and serverless application templates to empower developers. It provides automated infrastructure provisioning and manages deployment pipelines for all your applications, enabling self-service devel…
  api_count: 1
  score_band: developing
  score_composite: 52.9
  shared: 1
- slug: cycloid
  name: Cycloid
  description: Cycloid is a unified Internal Developer Portal & Platform combining self-service Service Catalogs (Stacks and StackForms), Infrastructure as Code orchestration, multi-cloud asset inventory (Asset Inventory and InfraView), CI/CD pipeline centralization, FinOps and GreenOps cost / carbon dashboards,…
  api_count: 1
  score_band: developing
  score_composite: 52.5
  shared: 1
- slug: ansible-automation-platform
  name: Ansible Automation Platform
  description: Ansible Automation Platform (formerly Ansible Tower) provides a REST API for managing automation workflows, job templates, inventories, credentials, and projects. The API enables programmatic access to the automation controller for launching jobs, managing infrastructure inventory, and orchestratin…
  api_count: 4
  score_band: developing
  score_composite: 50.9
  shared: 1
- slug: google-cloud-secret-manager
  name: Google Cloud Secret Manager
  description: Google Cloud Secret Manager is a secure and convenient storage system for API keys, passwords, certificates, and other sensitive data. It provides a central place to manage, access, and audit secrets across Google Cloud with automatic versioning, IAM-based access control, and audit logging.
  api_count: 1
  score_band: developing
  score_composite: 50.4
  shared: 1
- slug: crossplane
  name: Crossplane
  description: Crossplane is a graduated CNCF open-source Kubernetes add-on that transforms a cluster into a universal control plane for cloud infrastructure, services, and applications. Crossplane introduces custom resources including CompositeResourceDefinitions (XRDs), Compositions, Claims, Providers, Provider…
  api_count: 1
  score_band: developing
  score_composite: 49.5
  shared: 1
- slug: consul
  name: HashiCorp Consul
  description: HashiCorp Consul is a distributed, highly available service-networking control plane that automates network configuration, discovers services, enables secure service-to-service communication, and exposes a strongly consistent key/value store. The Consul HTTP API is a REST + JSON service exposed by…
  api_count: 1
  score_band: developing
  score_composite: 46.7
  shared: 1
- slug: chef
  name: Chef
  description: Chef (Progress Chef) provides infrastructure automation, compliance, and application delivery tooling. Chef exposes REST APIs for the Infra Server (managing nodes, cookbooks, roles, environments, and data bags), Chef Automate (visibility into convergence, compliance, and deployment), Habitat Builde…
  api_count: 4
  score_band: thin
  score_composite: 44.9
  shared: 1
- slug: terraform
  name: Terraform
  description: HashiCorp Terraform is an open-source infrastructure-as-code tool that enables teams to define, provision, and manage cloud infrastructure using a declarative configuration language (HCL). HCP Terraform and Terraform Enterprise expose a comprehensive REST API for automating workspace management, ru…
  api_count: 2
  score_band: thin
  score_composite: 43.6
  shared: 1
- slug: scalr
  name: Scalr
  description: Scalr is an enterprise-grade, drop-in replacement for Terraform Cloud and a remote Terraform operations backend that provides cost estimation, policy enforcement, and collaborative infrastructure management. Scalr features a hierarchical account-environment-workspace model, full compatibility with…
  api_count: 4
  score_band: thin
  score_composite: 43.5
  shared: 1
- slug: pulumi
  name: Pulumi
  description: Pulumi is a modern infrastructure as code platform that allows you to use familiar programming languages to build, deploy, and manage cloud infrastructure. The Pulumi Cloud REST API enables programmatic access to manage organizations, stacks, deployments, environments, policy packs, webhooks, and o…
  api_count: 2
  score_band: thin
  score_composite: 43.4
  shared: 1
- slug: spacelift
  name: Spacelift
  description: Spacelift is an infrastructure-as-code (IaC) orchestration platform that combines AI-assisted deployments, GitOps pipelines, and policy-as-code governance. It supports Terraform, OpenTofu, Pulumi, CloudFormation, Kubernetes, and Ansible. Key features include drift detection, OPA-based policies, sel…
  api_count: 1
  score_band: thin
  score_composite: 39.6
  shared: 1
- slug: ansible
  name: Ansible
  description: Ansible is an open-source IT automation platform developed by Red Hat that provides agentless configuration management, application deployment, cloud provisioning, and orchestration. Using YAML-based playbooks and an SSH-native architecture, Ansible automates infrastructure at scale without requiri…
  api_count: 4
  score_band: thin
  score_composite: 39.0
  shared: 1
- slug: microsoft-bicep
  name: Microsoft Bicep
  description: Microsoft Bicep is a domain-specific language (DSL) that uses declarative syntax to deploy Azure resources. It provides a transparent abstraction over ARM templates and offers a more concise syntax, improved type safety, and better support for modularity and code reuse.
  api_count: 4
  score_band: thin
  score_composite: 38.1
  shared: 1
- slug: puppet
  name: Puppet
  description: Puppet provides infrastructure automation and configuration management for hybrid and cloud environments. Puppet Enterprise exposes a collection of service APIs (Orchestrator, RBAC, Node Classifier, Code Manager, Activity, Status, Inventory, Value) that enable programmatic management of nodes, user…
  api_count: 9
  score_band: thin
  score_composite: 36.1
  shared: 1
- slug: env0
  name: Env0
  description: env0 is an infrastructure-as-code automation platform providing cost estimation, policy enforcement, and self-service environments for Terraform, OpenTofu, Pulumi, CloudFormation, and Kubernetes workloads.
  api_count: 1
  score_band: thin
  score_composite: 35.8
  shared: 1
- slug: scalable-infrastructure
  name: Scalable Infrastructure
  description: A subject-matter collection covering APIs, tools, and platforms for building and managing scalable cloud infrastructure. This topic encompasses compute, storage, networking, container orchestration, infrastructure as code (IaC), monitoring, and the major cloud providers (AWS, Azure, GCP, DigitalOce…
  api_count: 10
  score_band: thin
  score_composite: 34.7
  shared: 1
related:
- slug: boycott-israeli-consumer-goods-dataset
  name: Boycott Israeli Consumer Goods Dataset
  shared: 1
repo: https://github.com/api-evangelist/configuration-language
overview: 'Configuration Language on the [APIs.io](https://apis.io/) network is a curated area collecting 9 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including Configuration Language, Cribl, Kustomize, Carvel, Amazon Secrets Manager, AWS CloudFormation, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Boycott Israeli Consumer Goods Dataset. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
