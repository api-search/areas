---
layout: area
slug: chat
name: Chat
description: Topic-level profile capturing the Chat API category in the API Evangelist network. This profile defines a reference vocabulary and a generic OpenAPI shape for chat APIs that manage conversations, messages, and participants, and is used as a baseline when cataloguing chat platform APIs (such as Slack, Discord, Microsoft Teams, Twilio Conversations, and conversational AI platforms) into the broader catalogue.
tags:
- Chat
- Conversational AI
- Conversations
- Customer Support
- Messaging
- Real-time
resource_count: 1
provider_count: 285
resources:
- name: Reference Chat API
  description: Reference REST API shape for chat platforms covering conversation lifecycle (create/list/get), message send and history, participant management, and typing indicator events. Intended as a vocabulary and OpenAPI baseline for cataloguing concrete chat platform APIs.
  url: https://github.com/api-evangelist/chat
  tags:
  - Chat
  - Conversations
  - Messaging
  properties:
  - type: OpenAPI
    url: openapi/chat-reference-openapi.yml
  - type: Spectral
    url: spectral/chat-spectral.yml
providers:
- slug: chat
  name: Chat
  description: Topic-level profile capturing the Chat API category in the API Evangelist network. This profile defines a reference vocabulary and a generic OpenAPI shape for chat APIs that manage conversations, messages, and participants, and is used as a baseline when cataloguing chat platform APIs (such as Slac…
  api_count: 1
  score_band: thin
  score_composite: 32.0
  shared: 6
- slug: synapse
  name: Synapse
  description: Synapse is the reference Matrix homeserver implementation maintained by Element (formerly by the Matrix.org Foundation). Written in Python and Rust, it implements the Matrix open standard for secure, decentralized real-time communication. Synapse powers thousands of deployments worldwide and provid…
  api_count: 4
  score_band: developing
  score_composite: 45.0
  shared: 3
- slug: ada-cx
  name: Ada
  description: Ada (formerly Ada Support) is an AI customer service automation platform that resolves customer questions across chat, email, voice, and social channels using a generative AI agent grounded in a customer's knowledge sources. Ada exposes REST APIs for managing conversations, end users, knowledge sou…
  api_count: 8
  score_band: thin
  score_composite: 41.4
  shared: 3
- slug: google-business-messages
  name: Google Business Messages
  description: The Google Business Messages API enables agents to send messages, create events, and manage customer satisfaction surveys within conversations. It allows businesses to communicate with customers directly through Google entry points such as Search and Maps.
  api_count: 1
  score_band: thin
  score_composite: 38.9
  shared: 3
- slug: chatwoot
  name: Chatwoot
  description: Chatwoot is an open-source customer support and omni-channel messaging platform that provides REST APIs for managing conversations, contacts, agents, teams, labels, and integrating customer communication workflows. It supports live chat, email, WhatsApp, Facebook, Instagram, Telegram, SMS, and more…
  api_count: 3
  score_band: thin
  score_composite: 38.1
  shared: 3
- slug: liveperson
  name: LivePerson
  description: LivePerson is a leading provider of conversational AI and digital customer engagement technology. Their platform enables enterprises to design, deploy, and manage AI-powered messaging, voice, and agent-assisted conversations across web, mobile, and social channels, with a comprehensive suite of RES…
  api_count: 9
  score_band: thin
  score_composite: 31.7
  shared: 3
- slug: slack
  name: Slack
  description: Slack is a cloud-based team collaboration platform that provides chat, file sharing, and integrations with other tools and services.
  api_count: 39
  score_band: strong
  score_composite: 66.5
  shared: 2
- slug: novu
  name: Novu
  description: Novu is the open-source notification infrastructure for developers. A single REST API and workflow engine route a triggered event across in-app inbox, email, SMS, push, chat (Slack / Discord / MS Teams / WhatsApp) and custom channels — with subscriber preferences, topics, digest, snooze, and full w…
  api_count: 5
  score_band: strong
  score_composite: 65.1
  shared: 2
- slug: knock-app
  name: Knock
  description: Knock is notifications infrastructure as a service — a product and customer messaging platform you use to power transactional, lifecycle, broadcast, and in-product messaging across email, SMS, push, in-app, in-app guides, chat (Slack / Discord / Teams / WhatsApp), and outbound webhooks. Knock expos…
  api_count: 14
  score_band: strong
  score_composite: 62.7
  shared: 2
- slug: vapi-ai
  name: Vapi
  description: Vapi is a San Francisco-based voice AI platform that lets developers build real-time, low-latency voice agents over phone, web, and SIP. It orchestrates three modular components — a transcriber (STT), an LLM, and a voice (TTS) — into a sub-700ms voice-to-voice pipeline, with first-class support for…
  api_count: 15
  score_band: strong
  score_composite: 60.3
  shared: 2
- slug: microsoft-azure-web-pubsub
  name: Azure Web PubSub
  description: Azure Web PubSub is a fully-managed service that enables building real-time, two-way messaging applications using publish-subscribe patterns over WebSockets. It supports broadcasting messages to clients in groups, sending messages to specific connections or users, and integrating with serverless ev…
  api_count: 7
  score_band: developing
  score_composite: 58.0
  shared: 2
- slug: discord
  name: Discord
  description: Discord is a voice, video and text communication service used by hundreds of millions of people to hang out and talk with their communities and friends.
  api_count: 9
  score_band: developing
  score_composite: 54.3
  shared: 2
- slug: neuphonic
  name: Neuphonic
  description: Neuphonic is an ultra-low-latency voice AI platform specializing in real-time text-to-speech synthesis with sub-25ms latency, making it suitable for conversational AI and live applications. The platform provides both a cloud-hosted API with WebSocket streaming and Server-Sent Events (SSE), as well…
  api_count: 4
  score_band: developing
  score_composite: 49.6
  shared: 2
- slug: gladly
  name: Gladly
  description: Gladly is a San Francisco–based people-centered customer service AI platform. The Gladly Hero agent workspace unifies voice, chat, SMS, email, and social into a single, channel-agnostic conversation per Customer, while Gladly Sidekick AI handles routine resolutions, drafts replies, and hands off to…
  api_count: 8
  score_band: developing
  score_composite: 49.2
  shared: 2
- slug: telegram
  name: Telegram
  description: Telegram is a cloud-based instant messaging and voice-over-IP service that provides a comprehensive Bot API for developers to build bots, automate workflows, send notifications, and create interactive experiences on the Telegram platform. The platform supports text messages, media sharing, payments…
  api_count: 2
  score_band: developing
  score_composite: 48.0
  shared: 2
- slug: microsoft-azure-signalr
  name: Azure SignalR Service
  description: Azure SignalR Service REST API enables management of real-time web communication services. It supports creating SignalR instances, managing connections, sending messages to clients and groups, and configuring upstream endpoints for serverless real-time messaging.
  api_count: 1
  score_band: developing
  score_composite: 47.3
  shared: 2
- slug: google-chat
  name: Google Chat
  description: The Google Chat API enables building Chat apps that integrate with Google Chat. It provides RESTful access to manage Chat spaces, memberships, messages, reactions, attachments, and custom emojis. The API supports creating conversational bots, automating messaging workflows, and managing organizatio…
  api_count: 1
  score_band: developing
  score_composite: 47.3
  shared: 2
- slug: hipchat
  name: HipChat
  description: HipChat was Atlassian's team chat platform, providing persistent group chat, video, file sharing, and an extensive integration ecosystem. Atlassian discontinued HipChat Cloud, Stride, HipChat Server, and HipChat Data Center on February 15, 2019 after selling the IP to Slack in July 2018 and committ…
  api_count: 2
  score_band: developing
  score_composite: 46.7
  shared: 2
- slug: forethought
  name: Forethought
  description: Forethought is a San Francisco-based generative AI customer-support platform. Its multi-agent product suite — Solve (omnichannel resolution), Triage (ticket classification and routing), Discover (knowledge-gap detection and article generation), Assist (agentic copilot for human agents), and Agent Q…
  api_count: 2
  score_band: thin
  score_composite: 41.2
  shared: 2
- slug: microsoft-bot-framework
  name: Microsoft Bot Framework
  description: Microsoft Bot Framework provides APIs and SDKs for building conversational AI bots that work across multiple channels including Teams, Slack, and custom applications.
  api_count: 3
  score_band: thin
  score_composite: 40.8
  shared: 2
- slug: zoho-cliq
  name: Zoho Cliq
  description: Zoho Cliq is a team messaging and collaboration platform with a REST API for managing channels, bots, slash commands, message webhooks, and team communications. The API follows RESTful architecture principles with resource-oriented URLs, JSON request and response bodies, and standard HTTP verbs. It…
  api_count: 1
  score_band: thin
  score_composite: 39.9
  shared: 2
- slug: rainbow
  name: Rainbow
  description: Rainbow is a CPaaS platform from Alcatel-Lucent Enterprise (ALE) that lets developers enrich applications with chat, group chat, voice, video, file sharing, and telephony PBX features through more than 200 APIs, REST interfaces, and multi-language SDKs including Node.js, C#, iOS, and Android.
  api_count: 3
  score_band: thin
  score_composite: 39.3
  shared: 2
- slug: ably
  name: Ably
  description: Ably is a realtime messaging platform offering pub/sub, presence, push notifications, chat, LiveSync, and integrations over WebSocket and HTTP. Ably publishes its OpenAPI specifications publicly via the ably/open-specs GitHub repository, with separate specs for the Platform API (REST messaging surf…
  api_count: 2
  score_band: thin
  score_composite: 39.0
  shared: 2
- slug: missive
  name: Missive
  description: Missive is a team inbox and collaboration platform that brings email, SMS, WhatsApp, Instagram, Facebook Messenger, and live chat into one unified workspace. It provides a REST API for managing conversations, messages, contacts, labels, drafts, analytics, and automation rules, enabling teams to int…
  api_count: 1
  score_band: thin
  score_composite: 37.4
  shared: 2
related:
- slug: communication-protocols
  name: Communication Protocols
  shared: 1
repo: https://github.com/api-evangelist/chat
overview: 'Chat on the [APIs.io](https://apis.io/) network is a curated area collecting 1 resource — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including Chat, Synapse, Ada, Google Business Messages, Chatwoot, LivePerson, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Communication Protocols. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
