---
layout: area
slug: sdk
name: SDKs
description: A curated index of services, tooling, and open source solutions for generating API SDKs, client libraries, and code from API specifications. This collection covers SDK generation…
area_url: https://sdk.apievangelist.com
area_host: sdk.apievangelist.com
icon: https://sdk.apievangelist.com/icon-thumb.png
provider_count: 17
providers:
- slug: swagger-codegen
  name: Swagger Codegen
  description: Swagger Codegen is an open-source template-driven code generation tool that automatically generates client libraries, server stubs, and API documentation from OpenAPI Specification definitions. It supports 40+ client languages and 20+ server frameworks. Available as a CLI, Docker image, Maven/Gradl…
  api_count: 5
  score_band: strong
  score_composite: 57.6
  shared: 2
- slug: ogen
  name: Ogen
  description: 'Ogen is an Apache-2.0 OpenAPI v3 code generator for Go, maintained by the ogen-go organization. It reads an OpenAPI v3 document at build time and emits a statically typed Go client and server: code-generated JSON encoding with no reflection or interface{}, code-generated validators, a static radix…'
  api_count: 1
  score_band: thin
  score_composite: 38.1
  shared: 2
- slug: speakeasy
  name: Speakeasy
  description: Speakeasy provides an AI control plane platform that lets enterprises govern, secure, and observe AI agents, MCP servers, and Skills. The platform integrates with existing identity providers to assign permissioned identities to each agent and enforces policy in real time. It offers audit logs, comp…
  api_count: 1
  score_band: exemplar
  score_composite: 68.3
  shared: 1
- slug: apimatic
  name: APIMatic
  description: APIMatic is a developer experience platform for APIs that specializes in automated SDK generation, API documentation portal creation, specification validation and linting, and API format transformation. It supports 15+ API specification formats and generates idiomatic SDKs in 7+ programming languag…
  api_count: 5
  score_band: strong
  score_composite: 63.1
  shared: 1
- slug: liblab
  name: Liblab
  description: liblab generates and publishes type-safe, idiomatic SDKs in TypeScript, Python, Java, .NET, Go, PHP, and Terraform from OpenAPI/Swagger/Postman specs, plus MCP servers that expose those APIs to AI agents. The platform ships a CLI, hosted portal, and CI/CD GitHub Action that publish SDKs to customer…
  api_count: 13
  score_band: strong
  score_composite: 59.8
  shared: 1
- slug: fern-api
  name: Fern
  description: Fern is a developer-tools platform that turns a single API specification into idiomatic client SDKs, beautiful API documentation, and MCP servers. Given OpenAPI, AsyncAPI, gRPC/Protobuf, or Fern's own Fern Definition as input, Fern generates type-safe SDKs in TypeScript, Python, Go, Java, C#, PHP,…
  api_count: 1
  score_band: developing
  score_composite: 48.7
  shared: 1
- slug: stainless
  name: Stainless
  description: Stainless is an API developer experience platform that generates best-in-class SDKs, interactive documentation, production-ready CLI tools, MCP servers, and Terraform providers directly from an OpenAPI specification. Trusted by Anthropic, Cloudflare, Google, and OpenAI, Stainless automates the boil…
  api_count: 4
  score_band: developing
  score_composite: 47.7
  shared: 1
- slug: kiota
  name: Kiota
  description: 'Kiota is Microsoft''s open source (MIT) API client generator: a command line tool that turns any OpenAPI-described API into a strongly-typed, lightweight client in C#, Dart, Go, Java, PHP, Python, Ruby or TypeScript. It exists to remove the need to take a dependency on a different hand-written SDK f…'
  api_count: 1
  score_band: developing
  score_composite: 46.3
  shared: 1
- slug: hey-api
  name: Hey API
  description: Hey API builds open-source OpenAPI code generators and a hosted specification registry. @hey-api/openapi-ts turns an OpenAPI document into production-grade TypeScript — SDKs, types, Zod/Valibot/TypeBox validators, TanStack Query and SWR hooks, MSW and Playwright test doubles, and Fastify/NestJS/Hon…
  api_count: 1
  score_band: developing
  score_composite: 42.8
  shared: 1
- slug: openapi-generator
  name: OpenAPI Generator
  description: OpenAPI Generator is a community-governed, Apache-2.0 open-source project that generates client libraries (SDKs), server stubs, API documentation and configuration automatically from an OpenAPI Specification (v2 and v3). Forked from Swagger Codegen in 2018 by more than 40 of that project's top cont…
  api_count: 2
  score_band: developing
  score_composite: 41.9
  shared: 1
- slug: sideko
  name: Sideko
  description: Sideko is an API tooling generation platform that turns an OpenAPI specification into a complete developer-tooling suite — SDKs in six languages (Python, TypeScript, Java, Go, C#, Rust), Model Context Protocol (MCP) servers for AI agents, on-brand documentation sites with an Automatic MCP surface,…
  api_count: 1
  score_band: developing
  score_composite: 41.9
  shared: 1
- slug: orval
  name: Orval
  description: Orval is an MIT-licensed open source code generator that turns any valid OpenAPI v3 or Swagger v2 specification into type-safe TypeScript. From one spec it emits HTTP request functions (Fetch by default, Axios optional), TanStack Query hooks for React, Vue, Svelte, Solid and Angular, SWR hooks, Ang…
  api_count: 1
  score_band: thin
  score_composite: 38.4
  shared: 1
- slug: autorest
  name: AutoRest
  description: 'AutoRest is an open source tool from Microsoft (MIT License) that generates client libraries for accessing RESTful APIs from OpenAPI specifications. It powers generation of Azure SDKs across C#, Python, Java, TypeScript, Go, PowerShell, and Swift with an extensible plugin architecture. Note: AutoRe…'
  api_count: 6
  score_band: thin
  score_composite: 36.0
  shared: 1
- slug: oapi-codegen
  name: Oapi-Codegen
  description: oapi-codegen is an open source Go code generator that produces client and server boilerplate from OpenAPI 3.0 and 3.1 specifications with support for Echo, Chi, Gin, Gorilla/Mux, Iris, Fiber, and the standard library net/http router.
  api_count: 1
  score_band: thin
  score_composite: 32.8
  shared: 1
- slug: snapser
  name: Snapser
  description: Snapser is a plug-and-play, modular backend-as-a-service platform for game studios and app developers. Instead of building infrastructure from scratch, teams assemble a backend from modular "Snaps" — managed microservices such as Authentication, Profiles, Storage, Leaderboards, Inventory, Chat, Soc…
  api_count: 0
  score_band: thin
  score_composite: 26.9
  shared: 1
- slug: nswag
  name: NSwag
  description: 'NSwag is the Swagger/OpenAPI toolchain for .NET, ASP.NET Core and TypeScript, written in C# and maintained by Rico Suter under an MIT licence. It runs the contract in both directions: generating Swagger 2.0 and OpenAPI 3.0 documents from ASP.NET (Core) controllers, Web API assemblies and plain .NET…'
  api_count: 1
  score_band: emerging
  score_composite: 25.9
  shared: 1
- slug: konfig-api
  name: Konfig
  description: Konfig is an SDK and API documentation generator that turns an OpenAPI Specification or Postman Collection into production-ready client libraries, interactive reference docs, demos, and tutorials. It generates and publishes idiomatic SDKs across TypeScript/JavaScript, Python, Java, C#, PHP, Ruby, G…
  api_count: 0
  score_band: emerging
  score_composite: 20.4
  shared: 1
provider_slugs:
- swagger-codegen
- ogen
- speakeasy
- apimatic
- liblab
- fern-api
- stainless
- kiota
- hey-api
- openapi-generator
- sideko
- orval
- autorest
- oapi-codegen
- snapser
- nswag
- konfig-api
related:
- slug: cli
  name: Command Line Interface
  shared: 4
- slug: developer-experience
  name: Developer Experience
  shared: 4
- slug: documentation
  name: Documentation
  shared: 3
- slug: design
  name: Design
  shared: 1
- slug: testing
  name: Testing
  shared: 1
overview: 'SDKs is one of the API Evangelist areas on the [APIs.io](https://apis.io/) network — a focused corner of the API landscape. The full area lives at [sdk.apievangelist.com](https://sdk.apievangelist.com).


  17 providers on the network work in this area, including Swagger Codegen, Ogen, Speakeasy, APIMatic, Liblab, Fern, and 11 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Command Line Interface, Developer Experience, Documentation, and Design. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
