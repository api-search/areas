---
layout: area
slug: data-format
name: Data Format
description: Data Format covers the syntactic conventions used to represent, exchange, and persist information. The landscape spans text formats (JSON, XML, YAML, CSV, TOML), binary formats (Protocol Buffers, Avro, Parquet, ORC, MessagePack, BSON, CBOR, Arrow), and schema languages and IDLs that govern how those formats are validated and evolved.
tags:
- Binary Formats
- Data Format
- Data Serialization
- Interchange
- Text Formats
resource_count: 0
provider_count: 4
resources: []
providers:
- slug: avro
  name: Apache Avro
  description: Apache Avro is a data serialization system that provides rich data structures, a compact binary format, and container files for storing persistent data. Avro uses JSON for defining data types and protocols, and serializes data in a compact binary format.
  api_count: 1
  score_band: thin
  score_composite: 30.9
  shared: 1
- slug: protocol-buffers
  name: Protocol Buffers
  description: Protocol Buffers (Protobuf) is Google's language-neutral, platform-neutral, extensible mechanism for serializing structured data. It defines a schema language for specifying message structures in .proto files, which are compiled into efficient binary wire format code for multiple programming langua…
  api_count: 1
  score_band: thin
  score_composite: 30.9
  shared: 1
- slug: json
  name: JSON
  description: JSON (JavaScript Object Notation) is a lightweight, text-based, language-independent data interchange format that uses human-readable text to represent structured data as key-value pairs and arrays. JSON is standardized by RFC 8259 (December 2017), which obsoletes RFC 7159 (2014) and RFC 4627 (2006…
  api_count: 1
  score_band: minimal
  score_composite: 26.8
  shared: 1
- slug: parquet
  name: Apache Parquet
  description: APIs and tools for working with Apache Parquet, the open source columnar storage format for efficient analytics workloads. This index covers the format specification along with the major language implementations.
  api_count: 6
  score_band: minimal
  score_composite: 22.4
  shared: 1
related: []
repo: https://github.com/api-evangelist/data-format
overview: 'Data Format on the [APIs.io](https://apis.io/) network is a curated area collecting 0 resources — specifications, tools, and documentation — for this subject.


  Providers on the network working in this area include Apache Avro, Protocol Buffers, JSON, and Apache Parquet — each links out to that provider''s APIs, schemas, and governance artifacts.'
---
