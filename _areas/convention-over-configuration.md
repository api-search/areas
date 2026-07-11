---
layout: area
slug: convention-over-configuration
name: Convention Over Configuration
description: Convention over Configuration (CoC) is a software design principle that prefers sensible defaults and standard patterns over explicit, repetitive configuration. Frameworks that adopt CoC reduce the number of decisions a developer must make to start a new project while still allowing overrides for non-standard cases. CoC was popularized by Ruby on Rails but predates Rails, drawing on UI principles like the principle of least astonishment and conventions in JavaBeans, Maven, and other Java ecosystems. The principle continues to shape modern frameworks such as Spring Boot, Next.js, Astro, Phoenix, Ember, Hugo, and Remix.
tags:
- Conventions
- Design Principle
- Frameworks
- Software Design
resource_count: 5
provider_count: 27
resources:
- name: Ruby on Rails
  description: Ruby on Rails is the framework that popularized convention over configuration. By default, an ActiveRecord model named Sale maps to a sales table, controllers map to RESTful resources, and the directory layout under app/ implies wiring without explicit configuration files.
  url: https://rubyonrails.org/
  tags:
  - Active Record
  - Rails
  - Ruby
  properties:
  - type: Documentation
    url: https://rubyonrails.org/doctrine
  - type: Reference
    url: https://guides.rubyonrails.org/getting_started.html
- name: Spring Boot
  description: Spring Boot is the convention-over-configuration evolution of the Spring Framework. Auto-configuration detects classpath dependencies and wires beans automatically, starter dependencies bundle common stacks, and standard application.yml properties shape behavior with sensible defaults.
  url: https://spring.io/projects/spring-boot
  tags:
  - Auto-Configuration
  - Java
  - Spring
  properties:
  - type: Documentation
    url: https://docs.spring.io/spring-boot/index.html
  - type: Reference
    url: https://spring.io/projects/spring-boot
- name: Apache Maven
  description: Apache Maven introduced a strict project layout (src/main/java, src/test/java, target/) and a convention-driven build lifecycle. A pom.xml that declares dependencies and a parent POM is enough for most Java projects to compile, test, package, and deploy.
  url: https://maven.apache.org/
  tags:
  - Build
  - Java
  - Maven
  properties:
  - type: Documentation
    url: https://maven.apache.org/guides/introduction/introduction-to-the-pom.html
  - type: Reference
    url: https://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout.html
- name: Next.js
  description: Next.js exemplifies convention over configuration in modern web frameworks. The pages and app directory conventions auto-generate routes, file-based layouts, error boundaries, loading UI, and API routes without explicit router configuration.
  url: https://nextjs.org/
  tags:
  - Next.js
  - React
  - Web
  properties:
  - type: Documentation
    url: https://nextjs.org/docs
  - type: Reference
    url: https://nextjs.org/docs/app/building-your-application/routing
- name: Hugo Static Site Generator
  description: Hugo defines content, layouts, archetypes, and partials by directory convention. A content/posts directory yields a section with a list page and per-post pages without explicit routing configuration.
  url: https://gohugo.io/
  tags:
  - Go
  - Hugo
  - Static Sites
  properties:
  - type: Documentation
    url: https://gohugo.io/documentation/
  - type: Reference
    url: https://gohugo.io/getting-started/directory-structure/
providers:
- slug: convention-over-configuration
  name: Convention Over Configuration
  description: Convention over Configuration (CoC) is a software design principle that prefers sensible defaults and standard patterns over explicit, repetitive configuration. Frameworks that adopt CoC reduce the number of decisions a developer must make to start a new project while still allowing overrides for n…
  api_count: 5
  score_band: minimal
  score_composite: 22.1
  shared: 4
- slug: vert-x
  name: Vert.x
  description: Eclipse Vert.x is a toolkit for building reactive applications on the JVM, providing support for multiple languages including Java, JavaScript, Groovy, Ruby, and Kotlin with an event-driven, non-blocking architecture. Part of the Eclipse Foundation under the Eclipse Public License 2.0. Vert.x follo…
  api_count: 7
  score_band: developing
  score_composite: 48.2
  shared: 1
- slug: akka
  name: Akka
  description: Akka is a toolkit and runtime for building highly concurrent, distributed, and resilient message-driven applications on the JVM using the actor model for Java and Scala. Maintained by Lightbend, Akka provides a comprehensive set of libraries including actors, HTTP, streams, cluster, persistence, an…
  api_count: 4
  score_band: thin
  score_composite: 43.4
  shared: 1
- slug: ruby
  name: Ruby Programming Language and Popular API Gems
  description: 'A profile of the Ruby programming language ecosystem from an API perspective: the language and its standard library HTTP surface (Net::HTTP), the rubygems.org package registry and its public v1/v2 REST API, Bundler, RBS type signatures, popular HTTP/REST client gems (Faraday, http.rb, HTTParty, Exc…'
  api_count: 15
  score_band: thin
  score_composite: 39.5
  shared: 1
- slug: test-first
  name: Test First
  description: A software development approach where tests are written before the implementation code, ensuring code quality and driving design decisions through test requirements. Test-first development is the foundational principle behind test-driven development (TDD) and behavior-driven development (BDD), wher…
  api_count: 5
  score_band: thin
  score_composite: 38.0
  shared: 1
- slug: quarkus
  name: Quarkus
  description: Quarkus is a Kubernetes-native Java framework tailored for GraalVM and OpenJDK HotSpot, designed to build cloud-native microservices and serverless applications with fast startup times and low memory footprint.
  api_count: 1
  score_band: thin
  score_composite: 36.3
  shared: 1
- slug: helidon
  name: Helidon
  description: Helidon is a collection of Java libraries from Oracle for writing microservices that run on a fast web core powered by Netty, supporting MicroProfile and reactive programming models.
  api_count: 1
  score_band: thin
  score_composite: 35.0
  shared: 1
- slug: micronaut
  name: Micronaut
  description: Micronaut is a modern JVM-based framework for building modular, easily testable microservice and serverless applications with ahead-of-time compilation and minimal memory consumption.
  api_count: 1
  score_band: thin
  score_composite: 33.7
  shared: 1
- slug: dropwizard
  name: Dropwizard
  description: Dropwizard is a Java framework for developing ops-friendly, high-performance RESTful web services, pulling together stable, mature libraries from the Java ecosystem into a simple, lightweight package.
  api_count: 1
  score_band: thin
  score_composite: 32.0
  shared: 1
- slug: encore
  name: Encore
  description: Encore is an open source development platform for building type-safe, production-ready backend applications and distributed systems. It supports Go and TypeScript, provides built-in infrastructure automation for databases, caches, pub/sub, and cron jobs, and includes a local development dashboard w…
  api_count: 2
  score_band: thin
  score_composite: 31.7
  shared: 1
- slug: flask
  name: Flask
  description: Flask is a lightweight WSGI web application framework for Python, designed to make getting started quick and easy with the ability to scale up to complex applications. It provides a simple core with Jinja2 templating and Werkzeug WSGI toolkit, and is extensible through a rich ecosystem of extension…
  api_count: 1
  score_band: minimal
  score_composite: 29.9
  shared: 1
- slug: fastify
  name: Fastify
  description: Fastify is a fast and low-overhead web framework for Node.js, designed for building high-performance APIs and microservices. It features a powerful plugin architecture, JSON Schema-based request and response validation, automatic serialization, comprehensive logging with Pino, and TypeScript suppor…
  api_count: 1
  score_band: minimal
  score_composite: 29.7
  shared: 1
- slug: hapi
  name: Hapi
  description: hapi is a rich, configuration-centric framework for building web applications and APIs in Node.js. It provides a powerful plugin system, built-in input validation with Joi, authentication strategies, caching, cookie handling, and a focus on security and reliability for enterprise-grade applications.
  api_count: 1
  score_band: minimal
  score_composite: 29.3
  shared: 1
- slug: moleculer
  name: Moleculer
  description: Moleculer is a fast, modern, and powerful microservices framework for Node.js. It provides built-in service discovery, load balancing, fault tolerance with circuit breaker, request retries, distributed event handling, and support for multiple serializers and transporters including NATS, Redis, MQTT…
  api_count: 1
  score_band: minimal
  score_composite: 29.3
  shared: 1
- slug: lagom
  name: Lagom
  description: Lagom is an open source framework for building reactive microservice systems in Java and Scala, built on top of Akka and Play Framework, designed for distributed architectures.
  api_count: 1
  score_band: minimal
  score_composite: 28.5
  shared: 1
- slug: go-micro
  name: Go Micro
  description: Go Micro is a distributed systems framework for building microservices in Go, providing service discovery, load balancing, message encoding, RPC, and async messaging out of the box.
  api_count: 1
  score_band: minimal
  score_composite: 28.1
  shared: 1
- slug: kitex
  name: Kitex
  description: Kitex is a high-performance, extensible RPC framework for building microservices in Go, developed by ByteDance. It supports Thrift and Protocol Buffers serialization, provides built-in service governance features including service discovery, load balancing, circuit breaking, and retry policies, and…
  api_count: 1
  score_band: minimal
  score_composite: 27.8
  shared: 1
- slug: kratos
  name: Kratos
  description: Kratos is a Go framework for building cloud-native microservices, originally created at Bilibili. It provides built-in support for HTTP and gRPC transports, service discovery, configuration management, logging, metrics, and tracing, following a clean architecture approach with Protocol Buffers for…
  api_count: 1
  score_band: minimal
  score_composite: 27.8
  shared: 1
- slug: nestjs
  name: NestJS
  description: NestJS is a progressive Node.js framework for building efficient, reliable, and scalable server-side applications. Built with TypeScript and inspired by Angular, it provides an out-of-the-box application architecture with support for REST APIs, GraphQL, WebSockets, microservices, and CLI tooling, u…
  api_count: 1
  score_band: minimal
  score_composite: 27.8
  shared: 1
- slug: nameko
  name: Nameko
  description: Nameko is a microservices framework for Python that provides tools for building, testing, and running services. It supports RPC over AMQP, HTTP endpoints, WebSocket connections, and timer-based workers, with built-in dependency injection and a testing framework that allows services to be tested in…
  api_count: 1
  score_band: minimal
  score_composite: 27.4
  shared: 1
- slug: go-kit
  name: Go Kit
  description: Go Kit is a programming toolkit for building microservices in Go, emphasizing domain-driven design, transport-agnostic service definitions, and best practices for distributed systems.
  api_count: 1
  score_band: minimal
  score_composite: 26.2
  shared: 1
- slug: seneca
  name: Seneca
  description: Seneca is a microservices toolkit for Node.js that uses a pattern-matching approach to message handling. It provides transport independence, allowing services to communicate over HTTP, TCP, or message queues without changing business logic. Seneca emphasizes simplicity and composability through its…
  api_count: 1
  score_band: minimal
  score_composite: 25.7
  shared: 1
- slug: style-guides
  name: API Style Guides
  description: A landscape index of public API style guides published by leading technology companies and standards bodies. API style guides codify conventions for resource modeling, URI design, HTTP method use, status codes, error formats, pagination, versioning, deprecation, idempotency, hypermedia, and securit…
  api_count: 11
  score_band: minimal
  score_composite: 22.0
  shared: 1
- slug: conventions-md
  name: CONVENTIONS.md
  description: CONVENTIONS.md is a Markdown convention popularized by AI pair programming tools such as aider and adopted by AI coding agents like Cursor, Cline, and Claude Code. It documents project-specific coding standards, library preferences, naming conventions, architecture decisions, and development practi…
  api_count: 2
  score_band: minimal
  score_composite: 21.7
  shared: 1
related:
- slug: cybersecurity-standards
  name: Cybersecurity Standards
  shared: 1
repo: https://github.com/api-evangelist/convention-over-configuration
overview: 'Convention Over Configuration on the [APIs.io](https://apis.io/) network is a curated area collecting 5 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including Convention Over Configuration, Vert.x, Akka, Ruby Programming Language and Popular API Gems, Test First, Quarkus, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Cybersecurity Standards. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
