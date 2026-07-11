---
layout: area
slug: cqrs
name: CQRS
description: Command Query Responsibility Segregation (CQRS) is an architectural pattern that separates read and write operations for a data store into distinct models. Commands mutate state and produce events; queries return data optimized for the read side. CQRS is frequently combined with Event Sourcing, Domain-Driven Design (DDD), and message-based integration to scale complex domains. The pattern is most associated with Greg Young, building on Bertrand Meyer's Command-Query Separation principle, and is widely covered in writings by Martin Fowler and the Microsoft Patterns and Practices team.
tags:
- Architecture
- Command Query Responsibility Segregation
- Commands
- CQRS
- Domain-Driven Design
- Event Sourcing
- Events
- Patterns
- Queries
- Read Models
resource_count: 0
provider_count: 60
resources: []
providers:
- slug: axon-framework
  name: Axon Framework
  description: Axon Framework is a Java framework for building event-driven microservices using CQRS (Command Query Responsibility Segregation) and event sourcing patterns, providing the building blocks to implement scalable and maintainable distributed systems.
  api_count: 1
  score_band: developing
  score_composite: 48.7
  shared: 2
- slug: eventuate
  name: Eventuate
  description: Eventuate is a platform for developing transactional microservices using event sourcing and CQRS patterns, providing frameworks for managing distributed data consistency across services without two-phase commit.
  api_count: 1
  score_band: thin
  score_composite: 32.4
  shared: 2
- slug: hookdeck
  name: Hookdeck
  description: Hookdeck is a Toronto-based webhook and event-infrastructure platform. The Hookdeck Event Gateway sits between webhook senders and your services to receive, verify, queue, retry, transform, filter, route, and observe events reliably at scale. Hookdeck exposes a fully versioned REST Admin API, a CLI…
  api_count: 12
  score_band: strong
  score_composite: 63.2
  shared: 1
- slug: amazon-eventbridge
  name: Amazon EventBridge
  description: Amazon EventBridge is a serverless event bus service that makes it easy to connect your applications with data from a variety of sources. EventBridge delivers a stream of real-time data from your own applications, SaaS applications, and AWS services and routes that data to targets such as Lambda, S…
  api_count: 1
  score_band: strong
  score_composite: 60.9
  shared: 1
- slug: cdk-global
  name: CDK Global
  description: CDK Global is the dominant U.S. dealer management system (DMS) provider, serving roughly 15,000 automotive dealerships with software covering sales, F&I, fixed operations, parts, CRM, and digital retail. CDK was spun out of ADP in 2014 and acquired by Brookfield Business Partners in July 2022 for $…
  api_count: 8
  score_band: developing
  score_composite: 57.8
  shared: 1
- slug: amazon-well-architected-tool
  name: Amazon Well-Architected Tool
  description: 'The AWS Well-Architected Tool helps you review your workloads and compare them to the latest AWS architectural best practices. It provides a consistent process for evaluating architectures and implementing designs that scale over time across five pillars: operational excellence, security, reliabili…'
  api_count: 1
  score_band: developing
  score_composite: 57.5
  shared: 1
- slug: autodesk
  name: Autodesk
  description: Autodesk is a global leader in design, engineering, and entertainment software, providing cloud-connected platform APIs through Autodesk Platform Services (APS). APS APIs enable developers to build applications that access design data, automate workflows, visualize 3D models, manage construction pr…
  api_count: 33
  score_band: developing
  score_composite: 57.5
  shared: 1
- slug: wildapricot
  name: WildApricot
  description: WildApricot is a cloud-based membership management software platform designed for associations, nonprofits, and clubs. It provides tools for managing members, events, email communications, online payments, and websites. The WildApricot Admin API provides programmatic access to all platform features…
  api_count: 1
  score_band: developing
  score_composite: 56.0
  shared: 1
- slug: checkiday-national-holiday-api
  name: Checkiday - National Holiday and Event API
  description: Industry-leading Holiday and Event API by Checkiday, providing data on more than 5,000 national, international, and bizarre holidays and observances with thousands of descriptions, hashtags, images, founders, alternate names, and multi-year occurrence patterns. Routed through the apilayer marketpla…
  api_count: 1
  score_band: developing
  score_composite: 53.6
  shared: 1
- slug: honeycomb-io
  name: Honeycomb
  description: ''
  api_count: 12
  score_band: developing
  score_composite: 53.4
  shared: 1
- slug: codehooks
  name: Codehooks
  description: Codehooks is a JavaScript-native serverless backend platform that bundles a NoSQL document database, key-value store, persistent queues with workers, CRON jobs, blob storage, frontend hosting, and an automatic CRUD REST API in a single CLI-deployable runtime. Developers write small Node.js handler…
  api_count: 2
  score_band: developing
  score_composite: 51.8
  shared: 1
- slug: google-calendar
  name: Google Calendar
  description: The Google Calendar API provides RESTful access to Google Calendar data, enabling applications to create, view, and manage calendar events, access control lists, and user settings. It supports creating and managing multiple calendars, querying free/busy information, setting up push notifications fo…
  api_count: 1
  score_band: developing
  score_composite: 49.9
  shared: 1
- slug: constant-contact
  name: Constant Contact
  description: Constant Contact is a small-business email and digital marketing platform offering email campaigns, automation, SMS, contact management, surveys, and events. The Constant Contact V3 API is a REST + JSON, OAuth2-protected service published at api.cc.email/v3 covering accounts, contacts, lists, tags,…
  api_count: 1
  score_band: developing
  score_composite: 49.5
  shared: 1
- slug: seatgeek
  name: SeatGeek
  description: SeatGeek is a live event ticketing and discovery platform that aggregates ticket inventory from multiple sources and provides a transparent, data-driven ticket buying experience. The SeatGeek Platform API gives developers access to a canonical dataset of live events including concerts, sports, and…
  api_count: 1
  score_band: developing
  score_composite: 49.3
  shared: 1
- slug: gotowebinar
  name: GoToWebinar
  description: GoToWebinar is GoTo's (formerly LogMeIn) webinar and virtual event platform. The GoToWebinar REST API lets developers create and manage webinars, organizers, registrants, attendees, sessions, panelists, co-organizers, polls, surveys, and recordings, and subscribe to real-time webhook events for reg…
  api_count: 2
  score_band: developing
  score_composite: 49.1
  shared: 1
- slug: trino
  name: Trino
  description: Trino is an open-source, distributed SQL query engine built for lightning-fast analytics over large, heterogeneous data sets. Originally forked from Presto (which emerged at Facebook), it supports ANSI-compliant SQL across a wide range of storage systems from data lakes (S3, HDFS, Iceberg) to relat…
  api_count: 1
  score_band: developing
  score_composite: 48.9
  shared: 1
- slug: google-cloud-eventarc
  name: Google Cloud Eventarc
  description: Google Cloud Eventarc is a fully managed eventing service that allows you to build event-driven architectures by routing events from Google Cloud services, SaaS applications, and custom sources to target destinations. Eventarc supports both standard and advanced editions, providing scalable, server…
  api_count: 1
  score_band: developing
  score_composite: 48.4
  shared: 1
- slug: predicthq
  name: PredictHQ
  description: PredictHQ is an AI-powered demand intelligence platform that predicts the impact of real-world events on business demand. The PredictHQ API delivers structured, deduplicated event data, machine learning features, demand forecasts, and impact analytics across categories such as concerts, sports, con…
  api_count: 1
  score_band: developing
  score_composite: 48.2
  shared: 1
- slug: ticketmaster
  name: Ticketmaster
  description: Ticketmaster is the world's largest live entertainment ticketing company, providing access to tickets for concerts, sports, theater, and other live events globally. Their developer platform offers APIs for event discovery, ticket commerce, venue data, and partner integrations, giving developers acc…
  api_count: 3
  score_band: developing
  score_composite: 48.1
  shared: 1
- slug: fathom
  name: Fathom Analytics
  description: Fathom Analytics is a privacy-first website analytics platform that provides GDPR-compliant, cookie-free analytics as an alternative to Google Analytics. The platform serves thousands of companies, including Fortune 100 enterprises and government agencies, offering simple and accurate traffic metri…
  api_count: 1
  score_band: developing
  score_composite: 47.8
  shared: 1
- slug: cvent
  name: Cvent
  description: Cvent is a leading meetings, events, and hospitality technology provider with over 4,800 employees and 22,000+ customers worldwide. The Cvent platform spans Event Cloud (event management, registration, mobile event apps, virtual and hybrid events, Attendee Hub, surveys, Diagramming, and analytics)…
  api_count: 9
  score_band: developing
  score_composite: 47.2
  shared: 1
- slug: autocad
  name: AutoCAD
  description: APIs for Autodesk AutoCAD, providing programmatic access to CAD design, drawing, and automation capabilities through Autodesk Platform Services (APS, formerly Forge) and desktop development environments including AutoLISP, ObjectARX, .NET, and JavaScript.
  api_count: 6
  score_band: developing
  score_composite: 46.2
  shared: 1
- slug: autodesk-construction-cloud
  name: Autodesk Construction Cloud
  description: Autodesk Construction Cloud (ACC) is a unified platform connecting workflows, teams, and data across the construction project lifecycle, integrating preconstruction, design collaboration, project management, and field execution tools. ACC provides REST APIs through the Autodesk Platform Services (A…
  api_count: 7
  score_band: developing
  score_composite: 46.1
  shared: 1
- slug: hopin
  name: RingCentral Events
  description: RingCentral Events (formerly Hopin) is a virtual and hybrid event management platform with REST APIs for managing organizations, events, sessions, stages, booths, registrations, attendees, tickets, reports, and data subscriptions. Acquired by RingCentral from Hopin in August 2023, the platform enab…
  api_count: 1
  score_band: developing
  score_composite: 45.9
  shared: 1
related:
- slug: circuit-breaker
  name: Circuit Breaker
  shared: 1
repo: https://github.com/api-evangelist/cqrs
overview: 'CQRS on the [APIs.io](https://apis.io/) network is a curated area collecting 0 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including Axon Framework, Eventuate, Hookdeck, Amazon EventBridge, CDK Global, Amazon Well-Architected Tool, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Circuit Breaker. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
