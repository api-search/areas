---
layout: area
slug: high-tech
name: High Tech
description: High Tech indexes the APIs, data services, and reference artifacts that power the electronics, semiconductor, hardware, and IoT industries. The landscape covers electronic component data and distribution (Octopart / Nexar, Digi-Key, Mouser, Arrow Electronics, Avnet, Newark / element14), ECAD and PCB design data (SnapEDA, Ultra Librarian, Altium 365 via Nexar Design), hardware lifecycle and IoT device management (AWS IoT, Azure IoT Hub, Particle, Golioth), bill-of-materials and component-search workflows used across hardware product engineering, and the authoritative manufacturer data that anchors a component record (manufacturer part number, manufacturer, datasheet, lifecycle status, RoHS / REACH compliance, real-time inventory and pricing across distributors). This index captures the canonical providers, the shape of a component record as JSON Schema, a JSON-LD context aligning with schema.org Product / Offer / Organization, and the domain vocabulary used across the high-tech component supply chain.
tags:
- Arrow Electronics
- Availability
- Bill of Materials
- BoM
- Component Data
- Datasheets
- Digi-Key
- Distributors
- ECAD
- Electronic Components
- Electronics
- Footprints
- Hardware
- High Tech
- IoT
- Lifecycle
- Manufacturer Part Number
- Manufacturers
- Mouser
- MPN
- Nexar
- Octopart
- PCB Design
- Pricing
- RoHS
- Semiconductors
- SnapEDA
- Supply Chain
- Symbols
- Ultra Librarian
resource_count: 12
provider_count: 278
resources:
- name: Octopart / Nexar Supply API
  description: Nexar Supply (formerly Octopart API v4) is a GraphQL API that aggregates electronic component data from manufacturers and distributors worldwide. Returns parts, manufacturers, sellers, offers, datasheets, lifecycle status, compliance, and CAD models for tens of millions of MPNs. Free Evaluation plan up to 100 matched…
  url: https://nexar.com/api
  tags:
  - Component Data
  - Distributors
  - GraphQL
  - Nexar
  - Octopart
  - Supply Chain
  properties:
  - type: Documentation
    url: https://nexar.com/api
  - type: Portal
    url: https://portal.nexar.com/
  - type: Pricing
    url: https://nexar.com/api/compare-plans
  - type: GraphQLEndpoint
    url: https://api.nexar.com/graphql
  - type: GraphQL
    url: graphql/high-tech-graphql.md
- name: Digi-Key Product Information API
  description: Digi-Key's developer portal exposes a suite of OAuth 2.0 APIs including Product Information V4 (search by MPN, description, manufacturer, category), Quote, Ordering, Order Status, Order Management, MyLists, Supply Chain, Product Change Notifications, and Barcode. Sandbox and production environments separated; supports…
  url: https://developer.digikey.com/products
  tags:
  - Digi-Key
  - Distributors
  - OAuth
  - Ordering
  - Product Information
  properties:
  - type: Documentation
    url: https://developer.digikey.com/products
  - type: Portal
    url: https://developer.digikey.com/
  - type: OAuthAuthorization
    url: https://api.digikey.com/v1/oauth2/authorize
  - type: OAuthToken
    url: https://api.digikey.com/v1/oauth2/token
- name: Mouser Electronics Search API
  description: Mouser Electronics exposes a REST Search API (SearchByPartNumber, SearchByKeyword, SearchByManufacturer), a Cart API, and an Order API. Authentication uses a per-application API key issued through Mouser's developer portal. Responses include MouserPartNumber, ManufacturerPartNumber, Manufacturer, Description, DataShee…
  url: https://www.mouser.com/api-search/
  tags:
  - API Key
  - Distributors
  - Mouser
  - REST
  - Search
  properties:
  - type: Documentation
    url: https://www.mouser.com/api-search/
  - type: Portal
    url: https://www.mouser.com/api-hub/
  - type: OrderAPI
    url: https://www.mouser.com/api-order/
- name: Arrow Electronics Pricing & Availability API
  description: Arrow Electronics provides a Pricing & Availability API and an Order API. Responses returned as JSON (XML available). Partners request an authorization key through Arrow's developer onboarding. A Quote API is marked "Coming soon".
  url: https://developers.arrow.com/api/
  tags:
  - Arrow Electronics
  - Distributors
  - Ordering
  - Pricing
  - REST
  properties:
  - type: Documentation
    url: https://developers.arrow.com/api/
  - type: Portal
    url: https://developers.arrow.com/
- name: Avnet Developer APIs
  description: Avnet provides distributor APIs for part search, pricing, availability, and order management, primarily for established partner accounts.
  url: https://www.avnet.com/
  tags:
  - Avnet
  - Distributors
  - Pricing
  properties:
  - type: Website
    url: https://www.avnet.com/
- name: Newark / element14 API
  description: Newark and element14 (Premier Farnell) expose component search and pricing data via partner APIs for hardware engineers and maker communities.
  url: https://www.newark.com/
  tags:
  - Distributors
  - element14
  - Newark
  properties:
  - type: Website
    url: https://www.newark.com/
- name: SnapEDA Symbols & Footprints API
  description: SnapEDA is a library of free CAD models for electronic components — schematic symbols, PCB footprints, and 3D models — keyed off manufacturer part numbers. Used by PCB design tools to auto-resolve CAD assets for a BoM.
  url: https://www.snapeda.com/home/
  tags:
  - 3D Models
  - ECAD
  - Footprints
  - PCB Design
  - SnapEDA
  - Symbols
  properties:
  - type: Website
    url: https://www.snapeda.com/home/
- name: Ultra Librarian ECAD API
  description: Ultra Librarian (an EMA Design Automation service) publishes symbols, footprints, and 3D models for over 16 million components, with integrations to major ECAD tools.
  url: https://www.ultralibrarian.com/
  tags:
  - 3D Models
  - ECAD
  - Footprints
  - Symbols
  - Ultra Librarian
  properties:
  - type: Website
    url: https://www.ultralibrarian.com/
- name: Altium 365 / Nexar Design API
  description: Nexar Design exposes Altium 365 workspace data — components, nets, MCAD geometry, and positional data — via GraphQL for programmatic access to PCB designs.
  url: https://nexar.com/api
  tags:
  - Altium 365
  - Design
  - GraphQL
  - Nexar
  - PCB Design
  properties:
  - type: Documentation
    url: https://nexar.com/api
- name: AWS IoT Core
  description: AWS IoT Core provides device registry, MQTT message broker, device shadow, jobs, and rules engine for connected hardware at scale. Anchors the AWS IoT family (Device Management, Device Defender, Events, FleetWise, Greengrass, SiteWise, TwinMaker).
  url: https://aws.amazon.com/iot-core/
  tags:
  - AWS
  - Device Management
  - IoT
  - MQTT
  properties:
  - type: Documentation
    url: https://docs.aws.amazon.com/iot/
- name: Microsoft Azure IoT Hub
  description: Azure IoT Hub provides bi-directional device-to-cloud and cloud-to-device messaging, device twins, direct methods, and device provisioning service (DPS).
  url: https://azure.microsoft.com/en-us/products/iot-hub/
  tags:
  - Azure
  - Device Twins
  - IoT
  - MQTT
  properties:
  - type: Documentation
    url: https://learn.microsoft.com/en-us/azure/iot-hub/
- name: Particle Device Cloud API
  description: Particle provides a Device Cloud REST API plus webhooks for managing cellular and Wi-Fi connected hardware, firmware OTA, and variable / function / event APIs against devices.
  url: https://docs.particle.io/reference/cloud-apis/api/
  tags:
  - Device Cloud
  - IoT
  - OTA
  - Particle
  - REST
  - Webhooks
  properties:
  - type: Documentation
    url: https://docs.particle.io/reference/cloud-apis/api/
providers:
- slug: high-tech
  name: High Tech
  description: High Tech indexes the APIs, data services, and reference artifacts that power the electronics, semiconductor, hardware, and IoT industries. The landscape covers electronic component data and distribution (Octopart / Nexar, Digi-Key, Mouser, Arrow Electronics, Avnet, Newark / element14), ECAD and PC…
  api_count: 12
  score_band: minimal
  score_composite: 14.8
  shared: 30
- slug: texas-instruments
  name: Texas Instruments
  description: Texas Instruments is an American technology company that designs and manufactures semiconductors and various integrated circuits for industrial, automotive, personal electronics, communications equipment, and enterprise systems markets. TI provides a developer API portal at api-portal.ti.com offeri…
  api_count: 2
  score_band: developing
  score_composite: 48.1
  shared: 3
- slug: particle
  name: Particle
  description: Particle is an integrated IoT Platform-as-a-Service that provides cellular, Wi-Fi, and Bluetooth hardware modules alongside a comprehensive cloud platform for building and managing connected devices at scale. The Particle Device Cloud exposes a REST API that enables developers to call device functi…
  api_count: 1
  score_band: developing
  score_composite: 49.1
  shared: 2
- slug: arduino
  name: Arduino
  description: Arduino is an open-source electronics platform providing hardware, software, and cloud services for IoT development. The Arduino IoT Cloud REST API enables developers to programmatically manage devices, Things, dashboards, properties, and time-series data in the Arduino Cloud ecosystem. The API use…
  api_count: 1
  score_band: developing
  score_composite: 45.9
  shared: 2
- slug: stanley-black-and-decker
  name: Stanley Black & Decker
  description: Stanley Black & Decker is a global manufacturer and marketer of hand tools, power tools, and related accessories. Through brands like DEWALT, Stanley, Craftsman, and Black+Decker, the company provides connected tool management platforms, IoT solutions, and partner integrations for jobsite productiv…
  api_count: 2
  score_band: thin
  score_composite: 40.5
  shared: 2
- slug: cypress-semiconductor
  name: Cypress Semiconductor
  description: Cypress Semiconductor was a US-based semiconductor company known for its PSoC programmable system-on-chip microcontrollers, WICED Wi-Fi and Bluetooth connectivity stacks, NOR Flash memory, CapSense capacitive touch sensing, and Traveo automotive microcontrollers. Infineon Technologies completed its…
  api_count: 7
  score_band: thin
  score_composite: 37.8
  shared: 2
- slug: analog-devices
  name: Analog Devices
  description: Analog Devices (ADI) is a global semiconductor company designing high-performance analog, mixed-signal, and digital signal processing integrated circuits for industrial, communications, automotive, and consumer markets. ADI provides developer tools through its CodeFusion Studio embedded development…
  api_count: 3
  score_band: thin
  score_composite: 32.5
  shared: 2
- slug: tive
  name: Tive
  description: Tive is a real-time supply-chain and shipment visibility platform built on cellular IoT trackers. The Tive Public API (v3) lets you programmatically create and track shipments, manage trackers/devices, pull sensor data (location, temperature, humidity, pressure, light, motion, battery), configure a…
  api_count: 5
  score_band: thin
  score_composite: 31.7
  shared: 2
- slug: arrow-electronics
  name: Arrow Electronics
  description: Arrow Electronics is a global provider of products, services, and solutions to industrial and commercial users of electronic components and enterprise computing solutions. With over 2,200 suppliers and more than 200,000 customers worldwide, Arrow serves as a vital link in the technology supply chai…
  api_count: 2
  score_band: thin
  score_composite: 31.6
  shared: 2
- slug: vishay-intertechnology
  name: Vishay Intertechnology
  description: Vishay Intertechnology is one of the world's largest manufacturers of discrete semiconductors (diodes, rectifiers, MOSFETs, optoelectronics, selected ICs) and passive electronic components (resistors, inductors, capacitors). Vishay components are used in automotive, industrial, computing, consumer,…
  api_count: 3
  score_band: minimal
  score_composite: 27.4
  shared: 2
- slug: cadence
  name: Cadence Design Systems
  description: Cadence Design Systems is a multinational electronic design automation (EDA) software and hardware company. Cadence provides tools for designing integrated circuits, systems on chips, printed circuit boards, and pharmaceutical drugs, with a portfolio that includes Virtuoso, Spectre, Genus, Innovus,…
  api_count: 1
  score_band: minimal
  score_composite: 25.1
  shared: 2
- slug: rfid
  name: RFID
  description: Radio-Frequency Identification (RFID) is an automatic identification technology that uses radio waves to read and capture information stored on a tag attached to an object. RFID powers supply chain visibility, inventory management, asset tracking, access control, and contactless payments. The RFID…
  api_count: 4
  score_band: minimal
  score_composite: 19.0
  shared: 2
- slug: now
  name: DNOW
  description: 'DNOW Inc. (NYSE: DNOW), formerly NOW Inc. and operating as DistributionNOW, is a Houston-headquartered Fortune 1000 distributor of pipe, valves, fittings (PVF), pumps and packaged, engineered process and production equipment serving the upstream, midstream, downstream energy, and industrial sectors…'
  api_count: 5
  score_band: minimal
  score_composite: 10.5
  shared: 2
- slug: shodan
  name: Shodan
  description: Shodan is the world's first search engine for Internet-connected devices. It continuously crawls the public Internet to build a searchable database of servers, IoT devices, industrial control systems, routers, webcams, databases, and any other host that exposes a service. Shodan provides REST, Stre…
  api_count: 5
  score_band: strong
  score_composite: 67.8
  shared: 1
- slug: twilio
  name: Twilio
  description: Cloud communications platform providing APIs for SMS, voice, video, and authentication services. Twilio offers 30+ APIs covering messaging, voice, video, email, identity verification, IoT connectivity, and contact center solutions. Used by over 10 million developers globally with SDKs for Node.js,…
  api_count: 35
  score_band: strong
  score_composite: 64.1
  shared: 1
- slug: soracom
  name: Soracom
  description: Soracom is a global IoT cellular connectivity and platform provider headquartered in Tokyo, founded in 2014, with regional operations in the US (Soracom Global) and EU. The platform pairs multicarrier SIMs (physical, eSIM, iSIM) across 170+ countries with a deep platform of cloud integration servic…
  api_count: 18
  score_band: strong
  score_composite: 62.9
  shared: 1
- slug: adafruit-io
  name: Adafruit IO
  description: Adafruit IO is a cloud Internet of Things platform from Adafruit Industries built for makers, hobbyists, students, and STEM educators. It provides feed-based time-series storage, drag-and-drop dashboards with 20+ visualization block types, actions/triggers for SMS/voice/email/webhook notifications,…
  api_count: 3
  score_band: strong
  score_composite: 62.1
  shared: 1
- slug: microsoft-azure-event-hubs
  name: Azure Event Hubs
  description: Azure Event Hubs is a big data streaming platform and event ingestion service that can receive and process millions of events per second. It provides a distributed stream processing platform with low latency and seamless integration with Azure data and analytics services.
  api_count: 4
  score_band: strong
  score_composite: 61.2
  shared: 1
- slug: dell-servers
  name: Dell Servers
  description: APIs for managing and monitoring Dell PowerEdge servers and infrastructure, including the iDRAC Redfish out-of-band management interface, OpenManage Enterprise centralized console and its modular, power, support, and VMware integrations, telemetry streaming, the Lifecycle Controller, RACADM, and th…
  api_count: 10
  score_band: strong
  score_composite: 60.8
  shared: 1
- slug: ariba-sourcing
  name: Ariba Sourcing
  description: SAP Ariba Sourcing provides cloud-based strategic sourcing capabilities for procurement organizations. It enables supplier collaboration, RFx management, electronic auctions, and contract management through APIs that integrate sourcing processes with enterprise systems.
  api_count: 1
  score_band: strong
  score_composite: 60.0
  shared: 1
- slug: harness
  name: Harness
  description: Harness is an AI-powered software delivery platform that automates and accelerates the entire software development lifecycle from code to production. The platform provides intelligent automation across DevOps, testing and resilience, security and compliance, and cost optimization, helping engineeri…
  api_count: 13
  score_band: strong
  score_composite: 60.0
  shared: 1
- slug: thingspeak
  name: ThingSpeak
  description: ThingSpeak is an IoT analytics platform from MathWorks that lets devices aggregate, visualize, and analyze live data streams in the cloud. Devices push telemetry to channels via a REST update endpoint or the `mqtt3.thingspeak.com` MQTT broker, and the platform layers in MATLAB Analysis for compute,…
  api_count: 12
  score_band: developing
  score_composite: 59.9
  shared: 1
- slug: dun-and-bradstreet
  name: Dun & Bradstreet
  description: Dun & Bradstreet is a leading global provider of business decisioning data and analytics, anchored by the D-U-N-S Number — a unique nine-digit identifier assigned to more than 500 million businesses worldwide. Founded in 1841 as The Mercantile Agency in New York City and now headquartered in Jackso…
  api_count: 8
  score_band: developing
  score_composite: 59.4
  shared: 1
- slug: amazon-signer
  name: Amazon Signer
  description: AWS Signer is a fully managed code-signing service to ensure the trust and integrity of your code. It manages the code-signing certificate public and private keys and enables central management and deployment of code signing certificates for Lambda functions and IoT devices.
  api_count: 1
  score_band: developing
  score_composite: 58.4
  shared: 1
related: []
repo: https://github.com/api-evangelist/high-tech
overview: 'High Tech on the [APIs.io](https://apis.io/) network is a curated area collecting 12 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including High Tech, Texas Instruments, Particle, Arduino, Stanley Black & Decker, Cypress Semiconductor, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.'
---
