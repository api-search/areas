---
layout: area
slug: linux-server
name: Linux Server
description: Linux Server is a topic catalog covering management, administration, and monitoring interfaces used to operate Linux servers in production. It organizes references to systemd, cockpit, the Linux audit framework, package managers (apt, dnf, rpm), configuration management and provisioning tooling, and remote administration protocols commonly used on Linux servers.
tags:
- Infrastructure
- Linux
- Server
- System Administration
- DevOps
resource_count: 7
provider_count: 253
resources:
- name: systemd
  description: System and service manager for Linux, providing process supervision, socket activation, journaled logging, and a D-Bus management API.
  url: https://systemd.io/
  tags:
  - Service Management
  - Init
  - D-Bus
  properties:
  - type: Documentation
    url: https://www.freedesktop.org/software/systemd/man/
  - type: Reference
    url: https://www.freedesktop.org/wiki/Software/systemd/dbus/
  - type: SourceCode
    url: https://github.com/systemd/systemd
- name: Cockpit
  description: Web-based graphical interface for Linux server administration, providing tools for managing services, storage, networking, and accounts.
  url: https://cockpit-project.org/
  tags:
  - Administration
  - Web UI
  - Remote
  properties:
  - type: Documentation
    url: https://cockpit-project.org/documentation.html
  - type: SourceCode
    url: https://github.com/cockpit-project/cockpit
- name: Linux Audit
  description: The Linux audit subsystem and userspace tools for tracking security-relevant events on a Linux server.
  url: https://github.com/linux-audit/audit-documentation
  tags:
  - Security
  - Auditing
  - Compliance
  properties:
  - type: Documentation
    url: https://github.com/linux-audit/audit-documentation/wiki
  - type: SourceCode
    url: https://github.com/linux-audit/audit-userspace
- name: APT
  description: The Advanced Package Tool used by Debian, Ubuntu, and derivatives for installing, upgrading, and removing software packages.
  url: https://wiki.debian.org/Apt
  tags:
  - Package Management
  - Debian
  - Ubuntu
  properties:
  - type: Documentation
    url: https://manpages.debian.org/bookworm/apt/apt.8.en.html
- name: DNF
  description: The Dandified YUM package manager used on Fedora, RHEL, CentOS Stream, and related distributions.
  url: https://dnf.readthedocs.io/
  tags:
  - Package Management
  - Fedora
  - RHEL
  properties:
  - type: Documentation
    url: https://dnf.readthedocs.io/en/latest/
  - type: SourceCode
    url: https://github.com/rpm-software-management/dnf
- name: OpenSSH
  description: The de facto standard suite for secure remote login, command execution, and file transfer on Linux servers.
  url: https://www.openssh.com/
  tags:
  - Remote Access
  - Security
  - SSH
  properties:
  - type: Documentation
    url: https://www.openssh.com/manual.html
  - type: SourceCode
    url: https://github.com/openssh/openssh-portable
- name: systemd-journald
  description: The systemd journal daemon, providing structured, indexed logs for the Linux server with a query API via journalctl and libsystemd.
  url: https://www.freedesktop.org/software/systemd/man/systemd-journald.service.html
  tags:
  - Logging
  - Observability
  properties:
  - type: Documentation
    url: https://www.freedesktop.org/software/systemd/man/systemd-journald.service.html
providers:
- slug: linux-server
  name: Linux Server
  description: Linux Server is a topic catalog covering management, administration, and monitoring interfaces used to operate Linux servers in production. It organizes references to systemd, cockpit, the Linux audit framework, package managers (apt, dnf, rpm), configuration management and provisioning tooling, an…
  api_count: 7
  score_band: minimal
  score_composite: 23.8
  shared: 5
- slug: new-relic
  name: New Relic
  description: New Relic provides observability platform APIs for monitoring, analyzing, and optimizing your entire software stack with real-time insights into applications, infrastructure, and customer experience.
  api_count: 17
  score_band: exemplar
  score_composite: 74.7
  shared: 2
- slug: amazon-web-services-aws
  name: Amazon Web Services (AWS)
  description: Amazon Web Services offers reliable, scalable, and inexpensive cloud computing services. Free to join, pay only for what you use.
  api_count: 90
  score_band: developing
  score_composite: 56.9
  shared: 2
- slug: ibm
  name: IBM
  description: A collection of IBM's public APIs and developer resources.
  api_count: 56
  score_band: developing
  score_composite: 54.7
  shared: 2
- slug: vagrant
  name: Vagrant
  description: Vagrant, by HashiCorp, is a tool for building and managing virtualized development environments. Their developer platform provides APIs and SDKs for interacting with Vagrant Cloud and the HCP Vagrant Box Registry, enabling automation of box lifecycle management, plugin development, and integration…
  api_count: 4
  score_band: developing
  score_composite: 50.8
  shared: 2
- slug: rackspace-technology
  name: Rackspace Technology
  description: Rackspace Technology is a multicloud solutions provider offering managed services, professional services, and consulting across cloud infrastructure, applications, data, AI, and cybersecurity. The company operates as a trusted operator of the full stack from governed private cloud to AI in producti…
  api_count: 11
  score_band: developing
  score_composite: 49.0
  shared: 2
- slug: netdata
  name: Netdata
  description: Netdata is a real-time infrastructure monitoring and observability platform that collects per-second metrics from physical servers, virtual machines, cloud deployments, Kubernetes clusters, and IoT devices. It provides a REST API for querying metrics, alerts, and configuration on individual nodes (…
  api_count: 2
  score_band: developing
  score_composite: 47.0
  shared: 2
- slug: kubernetes-operators
  name: Kubernetes Operators
  description: Kubernetes Operators are a method of packaging, deploying, and managing Kubernetes applications that extend the Kubernetes API to create, configure, and manage instances of complex applications on behalf of a Kubernetes user.
  api_count: 6
  score_band: developing
  score_composite: 45.3
  shared: 2
- slug: render
  name: Render
  description: Render is a cloud platform for building and running applications and websites with automatic Git-based deployments. It provides managed infrastructure for web services, static sites, background workers, cron jobs, private services, PostgreSQL databases, Redis/Key-Value stores, and persistent disks.…
  api_count: 1
  score_band: thin
  score_composite: 44.9
  shared: 2
- slug: nomad
  name: HashiCorp Nomad
  description: HashiCorp Nomad is a flexible workload orchestrator that enables organizations to deploy and manage containers, legacy applications, and batch jobs across any infrastructure. The Nomad developer platform provides a comprehensive HTTP API, official SDKs, and tooling for automating job scheduling, cl…
  api_count: 4
  score_band: thin
  score_composite: 43.6
  shared: 2
- slug: hashicorp-vault
  name: HashiCorp Vault
  description: HashiCorp Vault is a secrets management tool that provides secure storage, access control, and distribution of tokens, passwords, certificates, and encryption keys. It provides a unified interface to any secret while providing tight access control and recording a detailed audit log.
  api_count: 1
  score_band: thin
  score_composite: 43.0
  shared: 2
- slug: docker
  name: Docker
  description: Docker is a platform for developers and sysadmins to build, share, and run applications in containers, packaging code and dependencies together for consistent deployment across environments.
  api_count: 1
  score_band: thin
  score_composite: 39.2
  shared: 2
- slug: hashicorp
  name: HashiCorp
  description: HashiCorp is the infrastructure cloud company, helping organizations automate multi-cloud and hybrid environments with Infrastructure Lifecycle Management and Security Lifecycle Management. Their suite of products includes Vault, Terraform, Nomad, Consul, Vagrant, Boundary, and Packer.
  api_count: 6
  score_band: thin
  score_composite: 39.1
  shared: 2
- slug: ubuntu
  name: Ubuntu
  description: Collection of APIs and services provided by Canonical for Ubuntu and related products. Includes the Snap Store API for package management, Launchpad API for project hosting and bug tracking, Ubuntu Security CVE API for vulnerability intelligence, and enterprise services including Ubuntu Pro, MAAS,…
  api_count: 8
  score_band: thin
  score_composite: 39.1
  shared: 2
- slug: hcp
  name: HashiCorp Cloud Platform
  description: HashiCorp Cloud Platform (HCP) is a fully managed platform for HashiCorp products including Vault, Consul, Packer, Boundary, Waypoint, and Terraform. HCP provides a unified set of APIs for managing infrastructure, secrets, service networking, and image pipelines across cloud and on-premises environ…
  api_count: 5
  score_band: thin
  score_composite: 37.4
  shared: 2
- slug: scalability
  name: Scalability
  description: A subject-matter collection covering APIs, tools, frameworks, and data sources related to application scalability, infrastructure scaling, performance optimization, and elastic resource management. This topic spans cloud provider auto-scaling, event-driven autoscaling (KEDA), load balancing, databa…
  api_count: 7
  score_band: thin
  score_composite: 35.4
  shared: 2
- slug: flightcontrol
  name: Flightcontrol
  description: Flightcontrol deploys applications to your own AWS account with a Heroku-like developer experience. It provisions and manages AWS infrastructure from a flightcontrol.json config-as-code file and exposes an HTTP management API for triggering deployments, managing environments, services, environment…
  api_count: 4
  score_band: thin
  score_composite: 34.7
  shared: 2
- slug: railway
  name: Railway
  description: The Railway public API is built with GraphQL and is the same API that powers the Railway dashboard, providing automation for projects, services, deployments, environments, volumes, and CI/CD workflows on the Railway platform.
  api_count: 1
  score_band: thin
  score_composite: 32.2
  shared: 2
- slug: ca
  name: CA Technologies (Broadcom)
  description: CA Technologies (originally Computer Associates) was a major enterprise software vendor focused on infrastructure management, DevOps, security, and mainframe software. It was acquired by Broadcom in November 2018 and its products are now part of Broadcom's Enterprise Software Division, including La…
  api_count: 6
  score_band: thin
  score_composite: 31.4
  shared: 2
- slug: civil-infrastructure-platform
  name: Civil Infrastructure Platform
  description: The Civil Infrastructure Platform (CIP) is a Linux Foundation collaborative project that builds an industrial-grade open source base layer for civil infrastructure systems such as transportation, power generation and distribution, building and city management, industrial control, and healthcare equ…
  api_count: 5
  score_band: minimal
  score_composite: 28.4
  shared: 2
- slug: shell-scripting
  name: Shell Scripting
  description: A collection of APIs and resources for Shell Scripting development, including utilities, documentation, and tools.
  api_count: 5
  score_band: minimal
  score_composite: 27.7
  shared: 2
- slug: facets
  name: Facets
  description: Facets is a platform engineering and infrastructure automation platform that unifies provisioning, deployment, and configuration into a single declarative model for governed, secure, and self-serve cloud operations. The Facets Control Plane exposes a REST API for managing blueprints, environments,…
  api_count: 1
  score_band: minimal
  score_composite: 25.6
  shared: 2
- slug: kamal-deploy
  name: Kamal
  description: Kamal is an open-source deployment tool from 37signals (DHH / Basecamp) for deploying containerized web applications to any infrastructure — bare metal, cloud VMs, or a mix — with zero-downtime rolling restarts. Originally built for Rails apps, Kamal works with any web application that can be packa…
  api_count: 2
  score_band: minimal
  score_composite: 18.1
  shared: 2
- slug: jfrog
  name: JFrog
  description: JFrog provides universal DevOps solutions for software supply chain automation and security, offering a unified platform for managing binaries, securing the software supply chain, and automating DevOps workflows.
  api_count: 15
  score_band: strong
  score_composite: 66.4
  shared: 1
related:
- slug: linuxunix
  name: Linux/Unix System
  shared: 1
- slug: cloud
  name: Cloud
  shared: 1
repo: https://github.com/api-evangelist/linux-server
overview: 'Linux Server on the [APIs.io](https://apis.io/) network is a curated area collecting 7 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including Linux Server, New Relic, Amazon Web Services (AWS), IBM, Vagrant, Rackspace Technology, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Linux/Unix System and Cloud. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
