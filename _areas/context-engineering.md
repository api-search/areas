---
layout: area
slug: context-engineering
name: Context Engineering
description: Context engineering is the practice of curating the information that large language models receive at inference time so that the model can perform a task reliably and cost-effectively. It treats the context window as a finite attention budget and looks for the smallest set of high-signal tokens that maximize the likelihood of the desired outcome. Context engineering subsumes and extends prompt engineering, system prompts, tool design, retrieval, agent loops, structured note taking, compaction, and multi-agent decomposition. It is a foundational discipline for building production AI agents and assistants.
tags:
- Agents
- AI
- Anthropic
- Compaction
- Context Window
- LLM
- Memory
- Prompt Engineering
- RAG
- Tools
resource_count: 5
provider_count: 505
resources:
- name: Effective Context Engineering for AI Agents
  description: Anthropic's engineering guide to context engineering, framing context as a finite attention budget and walking through system prompts, tool design, few-shot examples, just-in-time retrieval, compaction, structured note taking, and multi-agent architectures.
  url: https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents
  tags:
  - Anthropic
  - Best Practices
  - Engineering
  properties:
  - type: Documentation
    url: https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents
  - type: Reference
    url: https://docs.anthropic.com/en/docs/agents-and-tools/agent-best-practices
- name: Retrieval-Augmented Generation (RAG)
  description: RAG is a context engineering pattern that augments LLM prompts with passages retrieved at inference time from a vector store, search index, or knowledge base. RAG keeps facts outside the model and is one of the most widely used context engineering techniques.
  url: https://arxiv.org/abs/2005.11401
  tags:
  - Embeddings
  - Knowledge Base
  - RAG
  - Retrieval
  properties:
  - type: Specification
    url: https://arxiv.org/abs/2005.11401
  - type: Reference
    url: https://docs.llamaindex.ai/
  - type: Reference
    url: https://python.langchain.com/docs/concepts/rag/
- name: Prompt Engineering
  description: Prompt engineering is the discipline of crafting model instructions and examples to guide model behavior. Prompt engineering remains a sub-discipline of context engineering and includes techniques like role prompting, chain-of-thought, few-shot examples, and structured output formats.
  url: https://www.promptingguide.ai/
  tags:
  - Few-Shot
  - Instructions
  - Prompting
  properties:
  - type: Documentation
    url: https://www.promptingguide.ai/
  - type: Reference
    url: https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview
  - type: Reference
    url: https://platform.openai.com/docs/guides/prompt-engineering
- name: Agentic Loops and Tool Use
  description: 'Agentic loops are iterative reasoning patterns in which an LLM plans, calls tools, observes results, and refines its plan. Tool design is a central context engineering concern: tools must be token-efficient, have minimal overlap, and include clear, motivating descriptions.'
  url: https://docs.anthropic.com/en/docs/build-with-claude/tool-use/overview
  tags:
  - Agents
  - Function Calling
  - ReAct
  - Tool Use
  properties:
  - type: Documentation
    url: https://docs.anthropic.com/en/docs/build-with-claude/tool-use/overview
  - type: Reference
    url: https://platform.openai.com/docs/guides/function-calling
  - type: Reference
    url: https://arxiv.org/abs/2210.03629
- name: Long-Horizon Context Strategies
  description: Long-horizon strategies handle conversations and tasks that exceed the context window. Techniques include compaction (summarizing history into a smaller representation), structured note taking (persistent external memory), and multi-agent decomposition where sub-agents handle bounded subtasks and return condensed summ…
  url: https://www.anthropic.com/news/contextual-retrieval
  tags:
  - Compaction
  - Long Context
  - Memory
  - Multi-Agent
  properties:
  - type: Documentation
    url: https://www.anthropic.com/news/contextual-retrieval
  - type: Reference
    url: https://www.anthropic.com/research/swe-bench-sonnet
  - type: Reference
    url: https://github.com/microsoft/autogen
providers:
- slug: context-engineering
  name: Context Engineering
  description: Context engineering is the practice of curating the information that large language models receive at inference time so that the model can perform a task reliably and cost-effectively. It treats the context window as a finite attention budget and looks for the smallest set of high-signal tokens tha…
  api_count: 5
  score_band: minimal
  score_composite: 23.3
  shared: 10
- slug: cognee
  name: Cognee
  description: Cognee is an open-source AI memory and knowledge graph platform that enables developers to build persistent, structured memory for AI agents and LLM applications. The platform provides a REST API and Python/TypeScript SDKs for ingesting documents and data from 28+ sources, processing them through a…
  api_count: 1
  score_band: thin
  score_composite: 36.9
  shared: 5
- slug: dust-tt
  name: Dust
  description: Dust is a Paris-based enterprise AI platform for building, deploying, and operating teams of AI agents that have shared context across a company's knowledge and tools. Dust positions itself as the platform for "AI Operators" — the people who design, govern, and continuously improve agentic workflow…
  api_count: 9
  score_band: developing
  score_composite: 59.3
  shared: 4
- slug: vectara
  name: Vectara
  description: Vectara is a Retrieval Augmented Generation (RAG) as a service platform that provides grounded generative AI for enterprises. The API-first platform exposes a unified REST API v2 for managing corpora, ingesting documents, performing semantic and hybrid search, generating answers with hallucination…
  api_count: 7
  score_band: developing
  score_composite: 52.7
  shared: 4
- slug: amazon-bedrock
  name: Amazon Bedrock
  description: Amazon Bedrock is a fully managed AWS service that makes high-performing foundation models from leading AI companies available through a unified API for building generative AI applications. It supports text and image generation, conversational AI, model customization and fine-tuning, retrieval-augm…
  api_count: 4
  score_band: developing
  score_composite: 50.5
  shared: 4
- slug: pydantic-ai
  name: PydanticAI
  description: PydanticAI is an open-source, model-agnostic Python agent framework built by the Pydantic team, designed to bring the ergonomic, type-safe design philosophy of FastAPI to production-grade generative AI application development. It provides structured outputs, dependency injection, and first-class su…
  api_count: 2
  score_band: developing
  score_composite: 46.4
  shared: 4
- slug: letta
  name: Letta
  description: Letta (formerly MemGPT) is a stateful AI agents platform built around long-term memory, tool execution, and multi-agent coordination. The Letta REST API exposes 239 endpoints across 36 public resource categories — agents, memory blocks, archival memory, sources (RAG), custom tools (sandboxed/client…
  api_count: 3
  score_band: thin
  score_composite: 41.2
  shared: 4
- slug: ai21-labs
  name: AI21 Labs
  description: AI21 Labs is an enterprise foundation-model company best known for the Jamba family of open-weight hybrid Mamba/Transformer models and AI21 Maestro, a dynamic planning system that orchestrates tools, retrieval, and validated output during inference. The platform exposes a Bearer-token REST API at a…
  api_count: 8
  score_band: minimal
  score_composite: 29.3
  shared: 4
- slug: vapi-ai
  name: Vapi
  description: Vapi is a San Francisco-based voice AI platform that lets developers build real-time, low-latency voice agents over phone, web, and SIP. It orchestrates three modular components — a transcriber (STT), an LLM, and a voice (TTS) — into a sub-700ms voice-to-voice pipeline, with first-class support for…
  api_count: 15
  score_band: strong
  score_composite: 60.3
  shared: 3
- slug: exa-ai
  name: Exa
  description: Exa is a web search API and AI research platform built specifically for LLMs and agents — semantic and keyword search across the open web with token-efficient highlights, structured outputs, sub-200ms latency tiers, and verticals for code, companies, news, people, research, and financials. The plat…
  api_count: 7
  score_band: developing
  score_composite: 57.2
  shared: 3
- slug: plandex
  name: Plandex
  description: Plandex is an open-source, terminal-based AI coding agent designed to take on large, multi-step software development tasks across many files in real world codebases. Written in Go and released under the MIT license, Plandex builds and executes long-running "plans" — durable, branchable units of wor…
  api_count: 1
  score_band: developing
  score_composite: 53.8
  shared: 3
- slug: unify-ai
  name: Unify
  description: Unify is an LLM routing and model gateway platform that enables developers to access 100+ large language model providers through a single unified REST API and API key. The platform dynamically routes each prompt to the optimal model based on user-defined preferences across quality, speed, and cost…
  api_count: 1
  score_band: developing
  score_composite: 49.2
  shared: 3
- slug: smithery-ai
  name: Smithery
  description: Smithery is an MCP server registry and hosting platform that lets developers discover, publish, and connect to Model Context Protocol servers from any AI agent. The platform combines a public registry of thousands of community MCP servers with a managed gateway that handles OAuth, credential storag…
  api_count: 2
  score_band: developing
  score_composite: 47.7
  shared: 3
- slug: llamaparse
  name: LlamaParse
  description: 'LlamaParse is an enterprise document parsing and AI pipeline platform from LlamaIndex that converts complex PDFs, Office files, and 130+ document formats into LLM-ready structured outputs. The platform offers six composable products under a single API key: Parse (agentic OCR), Extract (structured d…'
  api_count: 4
  score_band: developing
  score_composite: 47.5
  shared: 3
- slug: chroma
  name: Chroma
  description: Chroma (Chroma DB) is an open-source AI-native embedding database designed to make it easy to build LLM applications by providing storage, retrieval, and management for vector embeddings, full-text search, regex search, and multi-modal retrieval (text, image, audio). Distributed under the Apache 2.…
  api_count: 4
  score_band: developing
  score_composite: 46.8
  shared: 3
- slug: opik
  name: Opik
  description: Opik is an open-source LLM evaluation, testing, and tracing platform developed by Comet ML that enables developers to debug, evaluate, and monitor LLM applications, RAG systems, and agentic workflows. The platform provides a REST API for logging traces and spans, running automated evaluations with…
  api_count: 1
  score_band: developing
  score_composite: 46.3
  shared: 3
- slug: unstructured
  name: Unstructured
  description: Unstructured is a document parsing and pre-processing platform that provides a REST API for ingesting PDFs, HTML, DOCX, images, and more than 50 other file formats, transforming them into clean structured JSON chunks ready for RAG pipelines and LLM applications. The platform offers partitioning, en…
  api_count: 2
  score_band: thin
  score_composite: 43.4
  shared: 3
- slug: langflow
  name: Langflow
  description: Langflow is an open-source low-code visual builder for AI agents, RAG pipelines, and LangChain-based workflows. It pairs a drag-and-drop React Flow frontend with a FastAPI backend that exposes every flow as a REST API, an MCP server, and an OpenAI-compatible Responses endpoint. Components are edita…
  api_count: 13
  score_band: thin
  score_composite: 42.5
  shared: 3
- slug: osmapi
  name: osmAPI
  description: osmAPI is a unified AI gateway that routes requests to OpenAI, Anthropic, Google, and 14+ LLM providers through a single API. Drop-in compatible with the OpenAI SDK, it provides smart routing, streaming, function calling, web search, response healing, embeddings, audio, and realtime endpoints.
  api_count: 4
  score_band: thin
  score_composite: 42.3
  shared: 3
- slug: glean
  name: Glean
  description: Glean is an AI-powered work assistant and enterprise search platform that connects to a company's apps and data sources to provide unified search, generative answers, and autonomous agents grounded in enterprise knowledge. Glean exposes a Client API for end-user features (search, chat, agents, answ…
  api_count: 8
  score_band: thin
  score_composite: 40.1
  shared: 3
- slug: inkeep
  name: Inkeep
  description: Inkeep is an AI support and agent platform for documentation and products. Its developer platform exposes an OpenAI-compatible RAG / chat completions API over your own content, an Analytics API for logging conversations, feedback, and events, and an Agents / management surface for building and oper…
  api_count: 3
  score_band: thin
  score_composite: 36.6
  shared: 3
- slug: promptlayer
  name: PromptLayer
  description: PromptLayer is a prompt engineering, prompt management, and LLM observability platform. Its REST API logs and tracks LLM requests, manages a versioned prompt registry with release labels, ingests OpenTelemetry-style spans and traces, and runs evaluations and datasets so teams can monitor, debug, an…
  api_count: 4
  score_band: thin
  score_composite: 35.8
  shared: 3
- slug: linkup-so
  name: Linkup
  description: Linkup is a production-grade web search and answer API for AI agents and LLMs. Its /search endpoint grounds model responses in real-time web context, returning ranked results, sourced answers with citations, or structured output, plus /fetch for clean LLM-ready markdown, an async /research endpoint…
  api_count: 4
  score_band: thin
  score_composite: 35.3
  shared: 3
- slug: klu-ai
  name: Klu
  description: Klu (klu.ai) is an LLM app platform for designing, deploying, evaluating, and observing prompt-driven AI applications. The Klu Engine exposes a REST API at https://api.klu.ai/v1 (Bearer API key) where an Action encapsulates a prompt template, model config, context (RAG), and output parsing, and is…
  api_count: 5
  score_band: thin
  score_composite: 34.4
  shared: 3
related: []
repo: https://github.com/api-evangelist/context-engineering
overview: 'Context Engineering on the [APIs.io](https://apis.io/) network is a curated area collecting 5 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including Context Engineering, Cognee, Dust, Vectara, Amazon Bedrock, PydanticAI, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.'
---
