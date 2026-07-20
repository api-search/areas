---
layout: area
slug: dns
name: DNS
description: DNS (Domain Name System) is the distributed naming system that translates human-readable domain names (like example.com) into the numerical IP addresses computers use to…
area_url: https://dns.apievangelist.com
area_host: dns.apievangelist.com
icon: https://dns.apievangelist.com/icon-thumb.png
provider_count: 27
providers:
- slug: shodan
  name: Shodan
  description: Shodan is the world's first search engine for Internet-connected devices. It continuously crawls the public Internet to build a searchable database of servers, IoT devices, industrial control systems, routers, webcams, databases, and any other host that exposes a service. Shodan provides REST, Stre…
  api_count: 5
  score_band: exemplar
  score_composite: 70.9
  shared: 1
- slug: cloudflare
  name: Cloudflare
  description: Cloudflare is a global network designed to make everything you connect to the Internet secure, private, fast, and reliable.
  api_count: 54
  score_band: strong
  score_composite: 69.7
  shared: 1
- slug: google-cloud-dns
  name: Google Cloud DNS
  description: Google Cloud DNS is a scalable, reliable, and managed authoritative Domain Name System (DNS) service running on the same infrastructure as Google. It provides low-latency, high-availability DNS serving with 100% uptime SLA, supporting both public and private DNS zones for domain name resolution.
  api_count: 1
  score_band: strong
  score_composite: 60.5
  shared: 1
- slug: completedns
  name: CompleteDNS
  description: CompleteDNS is a DNS research platform that tracks nameserver modifications and domain drops, with over twenty years of history and billions of recorded changes. The CompleteDNS API exposes domain-scoped lookups that return the chronological history of nameserver changes, drop events, and parking s…
  api_count: 2
  score_band: developing
  score_composite: 58.5
  shared: 1
- slug: amazon-cloud-map
  name: Amazon Cloud Map
  description: Amazon Cloud Map is a cloud resource discovery service that maintains an updated registry of application resources and their locations. Define custom names for application resources and use Cloud Map to dynamically discover service dependencies with integrated health checking and automatic updates.
  api_count: 1
  score_band: developing
  score_composite: 58.4
  shared: 1
- slug: amazon-route53-resolver
  name: Amazon Route 53 Resolver
  description: Amazon Route 53 Resolver provides DNS resolution for hybrid cloud environments, enabling DNS queries between your VPCs and on-premises networks. It allows you to configure DNS forwarding rules, manage resolver endpoints, and set up conditional forwarding to resolve domain names across your hybrid i…
  api_count: 1
  score_band: developing
  score_composite: 58.1
  shared: 1
- slug: infoblox
  name: Infoblox
  description: Infoblox is a networking and cybersecurity company providing DDI (DNS, DHCP, and IPAM) solutions and protective DNS-layer security services. Its product portfolio spans the Universal DDI suite for unified hybrid and multi-cloud network services, NIOS DDI for on-premises deployments, NIOS-X as a Ser…
  api_count: 17
  score_band: developing
  score_composite: 56.7
  shared: 1
- slug: frostbyte
  name: Frostbyte
  description: Free API platform for developers and AI agents — 40+ services including IP Geolocation, Crypto Prices, Screenshots, DNS, Scraping, Code Execution. Free tier of 200 credits with no signup; USDC on Base top-ups via x402 for higher volume.
  api_count: 7
  score_band: thin
  score_composite: 44.5
  shared: 1
- slug: coredns
  name: CoreDNS
  description: CoreDNS is a CNCF graduated DNS server written in Go that serves as the default DNS service for Kubernetes clusters. It is flexible and extensible through a plugin architecture, supporting DNS-based service discovery, forwarding, caching, and integration with etcd, Kubernetes, and other backends. C…
  api_count: 4
  score_band: thin
  score_composite: 43.3
  shared: 1
- slug: hetzner
  name: Hetzner
  description: Hetzner Online is a German hosting provider offering cloud servers, dedicated servers, and domain services. Hetzner provides a Cloud API for programmatic management of cloud resources, as well as a DNS API for managing DNS zones and records.
  api_count: 2
  score_band: thin
  score_composite: 43.1
  shared: 1
- slug: cpanel
  name: cPanel
  description: cPanel is a web-based control panel that provides a graphical interface and automation tools to simplify the management of web hosting services. cPanel exposes a family of HTTP APIs (UAPI, WHM API 1, and the legacy cPanel API 2) for automating account, domain, email, database, DNS, and server-wide…
  api_count: 3
  score_band: thin
  score_composite: 42.4
  shared: 1
- slug: bunny-net
  name: Bunny.net
  description: Bunny.net is a content-delivery and edge platform offering a global CDN, edge storage, video streaming, DNS, image optimisation, edge scripting, and WAF / security shielding. The Bunny.net Core Platform REST API at api.bunny.net manages account-level resources - Pull Zones, Storage Zones, DNS Zones…
  api_count: 16
  score_band: thin
  score_composite: 41.8
  shared: 1
- slug: unstoppable-domains
  name: Unstoppable Domains
  description: Web3 domain name service providing REST APIs for resolving crypto domain names, managing NFT domains, reverse lookups, cross-chain address resolution, domain registration, and DNS management across 150+ TLDs on multiple blockchains.
  api_count: 4
  score_band: thin
  score_composite: 41.7
  shared: 1
- slug: nacos
  name: Nacos
  description: Nacos is an easy-to-use dynamic service discovery, configuration, and service management platform from Alibaba for building cloud-native applications, supporting Dubbo, gRPC, Spring Cloud RESTful, and Kubernetes services.
  api_count: 1
  score_band: thin
  score_composite: 36.7
  shared: 1
- slug: openprovider
  name: Openprovider
  description: 'Openprovider is a wholesaler of Internet services and products with a unique platform from which you can find and manage all the products you need: domains, new gTLDs, SSL certificates, licenses for Plesk and Virtuozzo, spam filters, and more.'
  api_count: 1
  score_band: thin
  score_composite: 35.9
  shared: 1
- slug: quantcdn
  name: QuantCDN
  description: QuantCDN is an edge delivery, static site hosting, and cloud applications platform that lets teams generate, host, and maintain static and dynamic versions of their websites with a global CDN, WAF, edge functions, key-value storage, AI inference, and DNS management.
  api_count: 1
  score_band: thin
  score_composite: 34.3
  shared: 1
- slug: godaddy
  name: GoDaddy
  description: GoDaddy is a domain registrar and web hosting company offering REST APIs for domain registration, DNS management, certificates, shopper accounts, subscriptions, aftermarket auctions, and abuse reporting.
  api_count: 9
  score_band: thin
  score_composite: 34.1
  shared: 1
- slug: gandi
  name: Gandi
  description: Gandi is a domain name registrar and web hosting provider. The Gandi v5 Public API exposes domain management, LiveDNS, certificates, email, organization, billing, and hosting capabilities for programmatic use.
  api_count: 8
  score_band: thin
  score_composite: 33.0
  shared: 1
- slug: networkcalc
  name: NetworkCalc
  description: NetworkCalc provides a free RESTful API platform for monitoring and managing business networks and domains. Public APIs include a subnet calculator, DNS tools, security tools, encoder, and binary converter, with additional authenticated APIs for alerts, authorization, domains, reports, and subnets.
  api_count: 1
  score_band: thin
  score_composite: 32.4
  shared: 1
- slug: dnsimple
  name: DNSimple
  description: DNSimple is a domain management and DNS hosting service that provides users with a simple and easy way to manage their domain names and DNS settings. With DNSimple, users can register new domain names, transfer existing ones, and easily update DNS records to point their domains to the desired serve…
  api_count: 1
  score_band: thin
  score_composite: 31.1
  shared: 1
- slug: namesilo
  name: NameSilo
  description: NameSilo is a domain registrar and web services provider offering domain registration, hosting, email, and SSL solutions. NameSilo exposes a Domain API enabling programmatic domain search, registration, and management via HTTPS GET requests with XML or JSON responses, plus an MCP server for AI agen…
  api_count: 1
  score_band: emerging
  score_composite: 29.6
  shared: 1
- slug: dns-check
  name: DNS Check
  description: DNS Check is a domain DNS monitoring service that lets teams monitor, share, and troubleshoot DNS records across multiple record types (A, AAAA, CNAME, MX, NS, PTR, SOA, SPF, SRV, TXT). The platform detects unresponsive name servers, incorrect IP addresses, missing or duplicated records, SPF record…
  api_count: 1
  score_band: emerging
  score_composite: 22.7
  shared: 1
- slug: dns-coffee
  name: DNS Coffee
  description: DNS Coffee collects, analyzes, and archives changes to root zone files provided by various top-level domains (TLDs), offering one of the most comprehensive views of the current state of the Domain Name System (DNS). By continuously tracking these changes, DNS Coffee uncovers valuable trends over ti…
  api_count: 1
  score_band: emerging
  score_composite: 20.5
  shared: 1
- slug: pi-hole
  name: Pi-hole
  description: Pi-hole is an open source network-wide DNS sinkhole that blocks ads, tracking, and unwanted domains across all devices on a local network without requiring per-device software. It runs on lightweight hardware such as Raspberry Pi and offers a web admin interface plus a REST API (introduced in v6 vi…
  api_count: 1
  score_band: emerging
  score_composite: 20.5
  shared: 1
- slug: domscan
  name: DomScan
  description: Domain intelligence API for domain availability, DNS, WHOIS/RDAP, valuation, security checks, email posture, social handle checks, and monitoring workflows. Offers REST API, machine-readable contracts, a hosted MCP server, and llms.txt.
  api_count: 1
  score_band: emerging
  score_composite: 17.4
  shared: 1
- slug: cloudflare-com
  name: Cloudflare.com
  description: cloudflare-com is an alias profile for Cloudflare. The canonical company profile lives at the cloudflare repository in the API Evangelist Network; this entry exists so that the ".com" form of the brand resolves into the same canonical record. Cloudflare's developer surface includes a single unified…
  api_count: 1
  score_band: emerging
  score_composite: 16.9
  shared: 1
- slug: verisign
  name: VeriSign
  description: VeriSign is a major US corporation and Fortune 1000 company. The VeriSign API provides programmatic access to its platform services, data, and integrations for enterprise customers and partners.
  api_count: 1
  score_band: emerging
  score_composite: 15.9
  shared: 1
related:
- slug: network
  name: Network
  shared: 2
- slug: security
  name: Security
  shared: 2
- slug: scraping
  name: Scraping
  shared: 1
- slug: internet-of-things
  name: Internet of Things
  shared: 1
- slug: search
  name: API Evangelist Search
  shared: 1
- slug: containers
  name: Containers
  shared: 1
overview: 'DNS is one of the API Evangelist areas on the [APIs.io](https://apis.io/) network — a focused corner of the API landscape. The full area lives at [dns.apievangelist.com](https://dns.apievangelist.com).


  27 providers on the network work in this area, including Shodan, Cloudflare, Google Cloud DNS, CompleteDNS, Amazon Cloud Map, Amazon Route 53 Resolver, and 21 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Network, Security, Scraping, and Internet of Things. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
