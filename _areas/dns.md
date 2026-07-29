---
layout: area
slug: dns
name: DNS
description: DNS (Domain Name System) is the distributed naming system that translates human-readable domain names (like example.com) into the numerical IP addresses computers use to…
area_url: https://dns.apievangelist.com
area_host: dns.apievangelist.com
icon: https://dns.apievangelist.com/icon-thumb.png
provider_count: 41
providers:
- slug: shodan
  name: Shodan
  description: Shodan is the world's first search engine for Internet-connected devices. It continuously crawls the public Internet to build a searchable database of servers, IoT devices, industrial control systems, routers, webcams, databases, and any other host that exposes a service. Shodan provides REST, Stre…
  api_count: 15
  score_band: exemplar
  score_composite: 72.9
  shared: 1
- slug: cloudflare
  name: Cloudflare
  description: Cloudflare is a global network designed to make everything you connect to the Internet secure, private, fast, and reliable.
  api_count: 54
  score_band: exemplar
  score_composite: 70.3
  shared: 1
- slug: google-cloud-dns
  name: Google Cloud DNS
  description: Google Cloud DNS is a scalable, reliable, and managed authoritative Domain Name System (DNS) service running on the same infrastructure as Google. It provides low-latency, high-availability DNS serving with 100% uptime SLA, supporting both public and private DNS zones for domain name resolution.
  api_count: 4
  score_band: strong
  score_composite: 62.6
  shared: 1
- slug: infoblox
  name: Infoblox
  description: Infoblox is a networking and cybersecurity company providing DDI (DNS, DHCP, and IPAM) solutions and protective DNS-layer security services. Its product portfolio spans the Universal DDI suite for unified hybrid and multi-cloud network services, NIOS DDI for on-premises deployments, NIOS-X as a Ser…
  api_count: 21
  score_band: strong
  score_composite: 61.3
  shared: 1
- slug: amazon-route-53
  name: Amazon Route 53
  description: Amazon Route 53 is a highly available and scalable Domain Name System (DNS) web service that provides DNS routing, domain name registration, and health checking capabilities. Route 53 connects user requests to internet applications running on AWS or on-premises infrastructure, and can be used to ro…
  api_count: 3
  score_band: strong
  score_composite: 60.6
  shared: 1
- slug: amazon-route53-resolver
  name: Amazon Route 53 Resolver
  description: Amazon Route 53 Resolver provides DNS resolution for hybrid cloud environments, enabling DNS queries between your VPCs and on-premises networks. It allows you to configure DNS forwarding rules, manage resolver endpoints, and set up conditional forwarding to resolve domain names across your hybrid i…
  api_count: 63
  score_band: strong
  score_composite: 59.0
  shared: 1
- slug: completedns
  name: CompleteDNS
  description: CompleteDNS is a DNS research platform that tracks nameserver modifications and domain drops, with over twenty years of history and billions of recorded changes. The CompleteDNS API exposes domain-scoped lookups that return the chronological history of nameserver changes, drop events, and parking s…
  api_count: 2
  score_band: strong
  score_composite: 57.8
  shared: 1
- slug: amazon-cloud-map
  name: Amazon Cloud Map
  description: Amazon Cloud Map is a cloud resource discovery service that maintains an updated registry of application resources and their locations. Define custom names for application resources and use Cloud Map to dynamically discover service dependencies with integrated health checking and automatic updates.
  api_count: 3
  score_band: developing
  score_composite: 55.0
  shared: 1
- slug: domaintools
  name: DomainTools
  description: DomainTools is a domain and DNS intelligence company whose APIs power threat investigation, hunting, and monitoring for security teams. Its product surface spans Iris Investigate (pivot-based domain investigation), Iris Enrich (bulk domain enrichment), and Iris Detect (brand-infringement monitoring…
  api_count: 12
  score_band: developing
  score_composite: 51.8
  shared: 1
- slug: hetzner
  name: Hetzner
  description: Hetzner Online is a German hosting provider offering cloud servers, dedicated servers, and domain services. Hetzner provides a Cloud API for programmatic management of cloud resources, as well as a DNS API for managing DNS zones and records.
  api_count: 32
  score_band: developing
  score_composite: 49.4
  shared: 1
- slug: cpanel
  name: cPanel
  description: cPanel is a web-based control panel that provides a graphical interface and automation tools to simplify the management of web hosting services. cPanel exposes a family of HTTP APIs (UAPI, WHM API 1, and the legacy cPanel API 2) for automating account, domain, email, database, DNS, and server-wide…
  api_count: 7
  score_band: developing
  score_composite: 46.2
  shared: 1
- slug: stack-machine
  name: Stack Machine
  description: StackMachine is elastic, headless infrastructure for AI applications and agents. It runs existing Node.js, Python, and PHP codebases as WebAssembly with sub-5ms cold starts and sandboxed execution for untrusted or AI-generated code, packing thousands of apps per server. The platform is driven by a…
  api_count: 1
  score_band: developing
  score_composite: 46.1
  shared: 1
- slug: tucows
  name: Tucows
  description: Tucows is one of the world's largest internet-services and domain companies. Its OpenSRS division runs a wholesale reseller platform for domain-name registration, DNS, TLS/SSL certificates and hosted email, exposed through the OpenSRS API (an XML-over-HTTPS reseller protocol) and the OpenSRS Mail A…
  api_count: 2
  score_band: developing
  score_composite: 45.8
  shared: 1
- slug: d3
  name: D3
  description: D3 is a crypto-infrastructure company building the internet's domain layer, tokenized. Through its Doma Protocol, D3 brings ICANN domain names on-chain as tokenized name assets and unlocks "DomainFi" — programmable DNS, fractionalized domain tokens, an on-chain marketplace, and agentic commerce. De…
  api_count: 2
  score_band: developing
  score_composite: 45.1
  shared: 1
- slug: dnsfilter
  name: DNSFilter
  description: DNSFilter is an AI-powered DNS security and content-filtering platform that protects organizations from cyber threats and unwanted content at the DNS layer. Its machine-learning engine blocks malicious domains — phishing, malware, ransomware, and botnet command-and-control — often before they appea…
  api_count: 45
  score_band: developing
  score_composite: 44.8
  shared: 1
- slug: frostbyte
  name: Frostbyte
  description: Free API platform for developers and AI agents — 40+ services including IP Geolocation, Crypto Prices, Screenshots, DNS, Scraping, Code Execution. Free tier of 200 credits with no signup; USDC on Base top-ups via x402 for higher volume.
  api_count: 10
  score_band: developing
  score_composite: 43.1
  shared: 1
- slug: coredns
  name: CoreDNS
  description: CoreDNS is a CNCF graduated DNS server written in Go that serves as the default DNS service for Kubernetes clusters. It is flexible and extensible through a plugin architecture, supporting DNS-based service discovery, forwarding, caching, and integration with etcd, Kubernetes, and other backends. C…
  api_count: 5
  score_band: developing
  score_composite: 42.2
  shared: 1
- slug: bunny-net
  name: Bunny.net
  description: Bunny.net is a content-delivery and edge platform offering a global CDN, edge storage, video streaming, DNS, image optimisation, edge scripting, and WAF / security shielding. The Bunny.net Core Platform REST API at api.bunny.net manages account-level resources - Pull Zones, Storage Zones, DNS Zones…
  api_count: 26
  score_band: thin
  score_composite: 41.7
  shared: 1
- slug: nacos
  name: Nacos
  description: Nacos is an easy-to-use dynamic service discovery, configuration, and service management platform from Alibaba for building cloud-native applications, supporting Dubbo, gRPC, Spring Cloud RESTful, and Kubernetes services.
  api_count: 6
  score_band: thin
  score_composite: 40.7
  shared: 1
- slug: unstoppable-domains
  name: Unstoppable Domains
  description: Web3 domain name service providing REST APIs for resolving crypto domain names, managing NFT domains, reverse lookups, cross-chain address resolution, domain registration, and DNS management across 150+ TLDs on multiple blockchains.
  api_count: 33
  score_band: thin
  score_composite: 39.7
  shared: 1
- slug: quantcdn
  name: QuantCDN
  description: QuantCDN is an edge delivery, static site hosting, and cloud applications platform that lets teams generate, host, and maintain static and dynamic versions of their websites with a global CDN, WAF, edge functions, key-value storage, AI inference, and DNS management.
  api_count: 38
  score_band: thin
  score_composite: 37.3
  shared: 1
- slug: spaceship
  name: Spaceship
  description: Spaceship is a domain registrar and domain marketplace offering domain registration, DNS management, WHOIS privacy protection, and a SellerHub resale marketplace with SafePay escrow. Its public REST API (https://spaceship.dev/api, v1) exposes 40 operations across domain management, availability, se…
  api_count: 10
  score_band: thin
  score_composite: 36.2
  shared: 1
- slug: openprovider
  name: Openprovider
  description: 'Openprovider is a wholesaler of Internet services and products with a unique platform from which you can find and manage all the products you need: domains, new gTLDs, SSL certificates, licenses for Plesk and Virtuozzo, spam filters, and more.'
  api_count: 35
  score_band: thin
  score_composite: 36.0
  shared: 1
- slug: gandi
  name: Gandi
  description: Gandi is a domain name registrar and web hosting provider. The Gandi v5 Public API exposes domain management, LiveDNS, certificates, email, organization, billing, and hosting capabilities for programmatic use.
  api_count: 17
  score_band: thin
  score_composite: 34.7
  shared: 1
- slug: godaddy
  name: GoDaddy
  description: GoDaddy is a domain registrar and web hosting company offering REST APIs for domain registration, DNS management, certificates, shopper accounts, subscriptions, aftermarket auctions, and abuse reporting.
  api_count: 7
  score_band: thin
  score_composite: 33.4
  shared: 1
- slug: dnsimple
  name: DNSimple
  description: DNSimple is a domain management and DNS hosting service that provides users with a simple and easy way to manage their domain names and DNS settings. With DNSimple, users can register new domain names, transfer existing ones, and easily update DNS records to point their domains to the desired serve…
  api_count: 7
  score_band: thin
  score_composite: 33.3
  shared: 1
- slug: datum
  name: Datum
  description: Datum is an open source network cloud built for AI, founded in 2024 and backed by $13.6M from Amplify Partners, CRV, Encoded Ventures, Cervin Ventures, Ex/Ante, Step Function, and Vine Ventures, and founded by Zac Smith and Jacob Smith (ex-Equinix, Packet). Datum gives AI-native developers and alte…
  api_count: 1
  score_band: thin
  score_composite: 33.1
  shared: 1
- slug: networkcalc
  name: NetworkCalc
  description: NetworkCalc provides a free RESTful API platform for monitoring and managing business networks and domains. Public APIs include a subnet calculator, DNS tools, security tools, encoder, and binary converter, with additional authenticated APIs for alerts, authorization, domains, reports, and subnets.
  api_count: 5
  score_band: thin
  score_composite: 33.0
  shared: 1
- slug: virtualmin
  name: Virtualmin
  description: Virtualmin is an open-source web hosting control panel for Linux and BSD, built on top of Webmin, that lets administrators and resellers manage websites, virtual servers, DNS, email, FTP, databases, SSL certificates, WordPress and more from a single interface. Distributed as a community GPL edition…
  api_count: 1
  score_band: thin
  score_composite: 32.1
  shared: 1
- slug: dns-check
  name: DNS Check
  description: DNS Check is a domain DNS monitoring service that lets teams monitor, share, and troubleshoot DNS records across multiple record types (A, AAAA, CNAME, MX, NS, PTR, SOA, SPF, SRV, TXT). The platform detects unresponsive name servers, incorrect IP addresses, missing or duplicated records, SPF record…
  api_count: 2
  score_band: emerging
  score_composite: 27.9
  shared: 1
related:
- slug: security
  name: Security
  shared: 2
- slug: network
  name: Network
  shared: 1
- slug: scraping
  name: Scraping
  shared: 1
- slug: search
  name: API Evangelist Search
  shared: 1
- slug: containers
  name: Containers
  shared: 1
- slug: deployment
  name: Deployment
  shared: 1
overview: 'DNS is one of the API Evangelist areas on the [APIs.io](https://apis.io/) network — a focused corner of the API landscape. The full area lives at [dns.apievangelist.com](https://dns.apievangelist.com).


  30 providers on the network work in this area, including Shodan, Cloudflare, Google Cloud DNS, Infoblox, Amazon Route 53, Amazon Route 53 Resolver, and 24 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Security, Network, Scraping, and API Evangelist Search. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
