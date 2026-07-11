---
layout: area
slug: c-sharp
name: C#
description: C# is a modern, object-oriented programming language developed by Microsoft as part of the .NET platform. It is used for building Windows applications, web services, games (via Unity), and enterprise software, offering strong typing, garbage collection, and rich framework support. The C# language is defined by a standardized specification and implemented by the Roslyn compiler, with packages distributed via NuGet and running on the .NET runtime.
tags:
- .NET
- C#
- Microsoft
- Programming Language
- Topic
- Roslyn
- NuGet
- Dotnet
- Language
resource_count: 5
provider_count: 117
resources:
- name: C# Language
  description: 'The C# language itself: syntax, semantics, type system, and standard library conventions. Maintained by Microsoft with a formal ECMA-334 specification and modern features such as records, pattern matching, async/await, and nullable reference types.'
  url: https://learn.microsoft.com/en-us/dotnet/csharp/
  tags:
  - C#
  - Programming Language
  - Microsoft
  properties:
  - type: Website
    url: https://learn.microsoft.com/en-us/dotnet/csharp/
  - type: Documentation
    url: https://learn.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/
  - type: Language Reference
    url: https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/
  - type: Language Specification
    url: https://learn.microsoft.com/en-us/dotnet/csharp/specification/
- name: Roslyn (.NET Compiler Platform)
  description: Roslyn is the open-source .NET compiler platform that provides C# and Visual Basic compilers with rich code analysis APIs, enabling custom analyzers, refactorings, and tooling.
  url: https://github.com/dotnet/roslyn
  tags:
  - Compiler
  - Roslyn
  - Open Source
  properties:
  - type: GitHub
    url: https://github.com/dotnet/roslyn
  - type: Documentation
    url: https://learn.microsoft.com/en-us/dotnet/csharp/roslyn-sdk/
- name: .NET Runtime
  description: The .NET runtime hosts and executes C# programs, providing the CLR, base class libraries, garbage collection, and cross-platform support for Windows, Linux, and macOS.
  url: https://github.com/dotnet/runtime
  tags:
  - Runtime
  - Dotnet
  - Open Source
  properties:
  - type: GitHub
    url: https://github.com/dotnet/runtime
  - type: Download
    url: https://dotnet.microsoft.com/download
  - type: Documentation
    url: https://learn.microsoft.com/en-us/dotnet/core/
- name: NuGet Package Manager
  description: NuGet is the package manager for .NET, providing a central registry of open-source and commercial libraries distributed as packages for use in C# and other .NET projects. NuGet exposes a documented HTTP API for package discovery and publishing.
  url: https://www.nuget.org
  tags:
  - Package Manager
  - NuGet
  - Registry
  properties:
  - type: Website
    url: https://www.nuget.org
  - type: Documentation
    url: https://learn.microsoft.com/en-us/nuget/
  - type: API
    url: https://learn.microsoft.com/en-us/nuget/api/overview
  - type: GitHub
    url: https://github.com/NuGet
- name: ASP.NET Core
  description: ASP.NET Core is the cross-platform web framework for C#, used to build web applications, APIs, and real-time services on the .NET runtime.
  url: https://learn.microsoft.com/en-us/aspnet/core
  tags:
  - Web Framework
  - ASP.NET
  properties:
  - type: Documentation
    url: https://learn.microsoft.com/en-us/aspnet/core
  - type: GitHub
    url: https://github.com/dotnet/aspnetcore
providers:
- slug: c-sharp
  name: C#
  description: C# is a modern, object-oriented programming language developed by Microsoft as part of the .NET platform. It is used for building Windows applications, web services, games (via Unity), and enterprise software, offering strong typing, garbage collection, and rich framework support. The C# language i…
  api_count: 5
  score_band: minimal
  score_composite: 24.5
  shared: 9
- slug: microsoft-nuget
  name: Microsoft NuGet
  description: NuGet is the package manager for .NET, hosted by Microsoft. It provides APIs for searching, downloading, publishing, and managing .NET packages through the NuGet Gallery and private feeds.
  api_count: 1
  score_band: thin
  score_composite: 40.0
  shared: 3
- slug: microsoft-net
  name: Microsoft .NET
  description: Microsoft .NET is a free, cross-platform, open source developer platform for building many different types of applications. The .NET APIs and developer tools provide programmatic access to .NET runtime services, NuGet package management, project templates, and build tooling across web, mobile, desk…
  api_count: 5
  score_band: thin
  score_composite: 33.9
  shared: 3
- slug: restsharp
  name: RestSharp
  description: RestSharp is a simple REST and HTTP API client library for .NET that wraps HttpClient with a fluent API for making HTTP requests with automatic serialization and deserialization of request and response bodies. Supports JSON, XML, and CSV formats, OAuth1/OAuth2 authentication, async operations, and…
  api_count: 1
  score_band: minimal
  score_composite: 27.1
  shared: 3
- slug: polly
  name: Polly
  description: Polly is a .NET resilience and transient-fault-handling library that allows developers to express resilience strategies such as Retry, Circuit Breaker, Hedging, Timeout, Rate Limiter, and Fallback in a fluent and thread-safe manner. A .NET Foundation member project.
  api_count: 1
  score_band: minimal
  score_composite: 27.3
  shared: 2
- slug: refitter
  name: Refitter
  description: Refitter is a .NET tool and source generator that produces Refit HTTP client interfaces from OpenAPI specifications. It runs at compile time as a source generator or as a standalone CLI tool (dotnet-refitter), enabling type-safe API consumption in .NET projects. Refitter reads OpenAPI 2.0 (Swagger)…
  api_count: 2
  score_band: minimal
  score_composite: 27.1
  shared: 2
- slug: nunit
  name: NUnit
  description: NUnit is a unit-testing framework for all .NET languages. Initially ported from JUnit, the current production release has been completely rewritten with many new features and support for a wide range of .NET platforms. NUnit is a software testing framework, not a remote HTTP API service.
  api_count: 4
  score_band: minimal
  score_composite: 26.5
  shared: 2
- slug: microsoft-package
  name: Microsoft Package
  description: A collection of Microsoft package management APIs covering NuGet, Windows Package Manager (WinGet), Microsoft Store, and Azure Artifacts for managing and distributing software packages across Microsoft platforms.
  api_count: 4
  score_band: minimal
  score_composite: 25.6
  shared: 2
- slug: navision
  name: Microsoft Dynamics NAV
  description: API collection for Microsoft Dynamics NAV (formerly Navision), an enterprise resource planning (ERP) solution for small and medium-sized businesses. Dynamics NAV has evolved into Dynamics 365 Business Central, which provides modern REST, OData, and SOAP web services for business data integration.
  api_count: 7
  score_band: strong
  score_composite: 63.4
  shared: 1
- slug: socket-dev
  name: Socket
  description: Socket is a developer-first supply-chain security platform that protects applications from malicious dependencies, vulnerable packages, license risk, and software-supply-chain attacks across npm, PyPI, Go, Maven, Cargo, NuGet, RubyGems, and other open-source ecosystems. Socket ships a hosted API, C…
  api_count: 15
  score_band: strong
  score_composite: 63.0
  shared: 1
- slug: microsoft-azure-functions
  name: Microsoft Azure Functions
  description: Azure Functions is a serverless compute platform from Microsoft Azure enabling event-driven code execution triggered by HTTP requests, timers, queues, blobs, and other Azure services. The Azure Functions management API provides programmatic access to function app lifecycle management, deployment, c…
  api_count: 2
  score_band: strong
  score_composite: 61.8
  shared: 1
- slug: microsoft-office-365
  name: Microsoft Office 365
  description: A collection of APIs provided by Microsoft Office 365 for productivity, collaboration, and enterprise services.
  api_count: 17
  score_band: strong
  score_composite: 60.8
  shared: 1
- slug: microsoft-outlook
  name: Microsoft Outlook
  description: Microsoft Outlook is a personal information manager and email client that is part of the Microsoft Office suite. It provides email, calendar, contact management, task management, and other productivity features.
  api_count: 10
  score_band: developing
  score_composite: 59.3
  shared: 1
- slug: microsoft-power-automate
  name: Microsoft Power Automate
  description: Microsoft Power Automate is a cloud-based service that helps you create automated workflows between your favorite apps and services to synchronize files, get notifications, collect data, and automate business processes. It supports automated, instant, and scheduled cloud flows, as well as desktop f…
  api_count: 1
  score_band: developing
  score_composite: 59.3
  shared: 1
- slug: microsoft-project
  name: Microsoft Project
  description: Microsoft Project is a project management software product developed by Microsoft. It provides tools for developing plans, assigning resources to tasks, tracking progress, managing budgets, and analyzing workloads. Microsoft Project offers REST APIs via SharePoint/Project Online, a Client-Side Obje…
  api_count: 4
  score_band: developing
  score_composite: 59.0
  shared: 1
- slug: microsoft-entra
  name: Microsoft Entra
  description: Microsoft Entra (formerly Azure Active Directory) provides identity and access management services including authentication, authorization, and directory services.
  api_count: 14
  score_band: developing
  score_composite: 58.4
  shared: 1
- slug: microsoft-edge
  name: Microsoft Edge
  description: APIs and resources for Microsoft Edge browser development and integration, including the Edge Add-ons API for extension management, DevTools Protocol for browser debugging and automation, Extensions API for building browser extensions, and Web Platform APIs for progressive web app development.
  api_count: 4
  score_band: developing
  score_composite: 57.3
  shared: 1
- slug: microsoft-excel
  name: Microsoft Excel
  description: APIs for automating, integrating, and extending Microsoft Excel functionality including workbook management, data manipulation, charting, and formula execution through Microsoft Graph REST APIs.
  api_count: 3
  score_band: developing
  score_composite: 57.1
  shared: 1
- slug: azure-networking-services
  name: Azure Networking Services
  description: A comprehensive collection of Azure networking APIs for managing virtual networks, load balancers, application gateways, VPN gateways, DNS, and other networking resources in the Microsoft Azure cloud.
  api_count: 2
  score_band: developing
  score_composite: 56.5
  shared: 1
- slug: microsoft-graph
  name: Microsoft Graph
  description: Microsoft Graph is the gateway to data and intelligence in Microsoft 365. It provides a unified programmability model that you can use to access data in Microsoft 365, Windows 10, and Enterprise Mobility + Security.
  api_count: 90
  score_band: developing
  score_composite: 56.0
  shared: 1
- slug: microsoft-quantum
  name: Microsoft Azure Quantum
  description: Microsoft Azure Quantum is Microsoft's cloud quantum computing service — an open, multi-vendor platform that provides access to quantum hardware from IonQ, Quantinuum, Pasqal, and Rigetti alongside Microsoft's own Q# programming language, Quantum Development Kit (QDK), and post-layout fault-toleran…
  api_count: 5
  score_band: developing
  score_composite: 53.2
  shared: 1
- slug: microsoft-azure-active-directory
  name: Microsoft Azure Active Directory
  description: Microsoft Azure Active Directory (Azure AD), now Microsoft Entra ID, is Microsoft's cloud-based identity and access management service, which helps employees sign in and access resources.
  api_count: 10
  score_band: developing
  score_composite: 52.9
  shared: 1
- slug: azure-blob-storage
  name: Azure Blob Storage
  description: Microsoft Azure Blob Storage is a service for storing large amounts of unstructured object data, such as text or binary data, that can be accessed from anywhere in the world via HTTP or HTTPS.
  api_count: 3
  score_band: developing
  score_composite: 51.1
  shared: 1
- slug: microsoft-azure-blob-storage
  name: Azure Blob Storage
  description: Microsoft Azure Blob Storage is a service for storing large amounts of unstructured object data, such as text or binary data, that can be accessed from anywhere in the world via HTTP or HTTPS.
  api_count: 3
  score_band: developing
  score_composite: 51.1
  shared: 1
related: []
repo: https://github.com/api-evangelist/c-sharp
overview: 'C# on the [APIs.io](https://apis.io/) network is a curated area collecting 5 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including C#, Microsoft NuGet, Microsoft .NET, RestSharp, Polly, Refitter, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.'
---
