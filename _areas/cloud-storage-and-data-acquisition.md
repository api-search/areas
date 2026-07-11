---
layout: area
slug: cloud-storage-and-data-acquisition
name: Cloud Storage and Data Acquisition
description: Cloud Storage and Data Acquisition is a topic profile in the API Evangelist Network covering APIs and tooling for ingesting, moving, and persisting bulk and streaming data into cloud-resident storage. It groups object storage services, data-lake foundations, managed ingestion pipelines, change-data-capture connectors, transfer appliances, and data-broker APIs that provide source material for cloud-storage workloads. The topic is intended as an entry point for developers and architects evaluating how data lands in cloud storage from on-premises systems, SaaS APIs, IoT devices, public data sources, and partner exchanges.
tags:
- Bulk Transfer
- Change Data Capture
- Cloud Storage
- Data Acquisition
- Data Ingestion
- Data Lake
- ETL
- Object Storage
- Pipelines
- Streaming
resource_count: 6
provider_count: 217
resources:
- name: Object Storage Surface
  description: The object-storage surface includes Amazon S3, Google Cloud Storage, and Azure Blob Storage REST APIs. These APIs provide the canonical landing zone for cloud data acquisition and are the most common targets for ingestion pipelines.
  url: https://aws.amazon.com/s3/
  tags:
  - Object Storage
  - REST
  properties:
  - type: Documentation
    url: https://docs.aws.amazon.com/AmazonS3/latest/API/Welcome.html
  - type: Documentation
    url: https://cloud.google.com/storage/docs/json_api/v1
  - type: Documentation
    url: https://learn.microsoft.com/en-us/rest/api/storageservices/blob-service-rest-api
- name: Streaming Ingest Surface
  description: The streaming-ingest surface covers Amazon Kinesis Data Streams, Google Cloud Pub/Sub, and Azure Event Hubs. These services ingest high-volume event streams and make them durable for downstream landing into object storage and analytics systems.
  url: https://aws.amazon.com/kinesis/data-streams/
  tags:
  - Pub/Sub
  - Real-time
  - Streaming
  properties:
  - type: Documentation
    url: https://docs.aws.amazon.com/kinesis/latest/APIReference/
  - type: Documentation
    url: https://cloud.google.com/pubsub/docs/reference/rest
  - type: Documentation
    url: https://learn.microsoft.com/en-us/rest/api/eventhub/
- name: Managed Ingestion Pipelines
  description: Managed ingestion pipelines such as AWS Glue, Google Cloud Dataflow, and Azure Data Factory expose REST APIs for orchestrating extract-transform-load and extract-load-transform jobs that land source data in cloud storage.
  url: https://aws.amazon.com/glue/
  tags:
  - Data Pipelines
  - ETL
  - Managed
  properties:
  - type: Documentation
    url: https://docs.aws.amazon.com/glue/latest/webapi/Welcome.html
  - type: Documentation
    url: https://cloud.google.com/dataflow/docs/reference/rest
  - type: Documentation
    url: https://learn.microsoft.com/en-us/rest/api/datafactory/
- name: Change Data Capture Connectors
  description: Change Data Capture connectors (Debezium, AWS DMS, Fivetran, Striim) replicate row-level changes from operational databases to cloud storage and warehouses, providing a low-latency feed for analytics and data-lake hydration.
  url: https://debezium.io/
  tags:
  - CDC
  - Connectors
  - Replication
  properties:
  - type: Documentation
    url: https://debezium.io/documentation/
  - type: Documentation
    url: https://docs.aws.amazon.com/dms/
- name: Bulk Transfer Services
  description: Bulk transfer services (AWS DataSync and Snow family, Google Storage Transfer Service, Azure Data Box) move large datasets from on-premises and edge locations into cloud storage over network or via offline appliances.
  url: https://aws.amazon.com/datasync/
  tags:
  - Bulk Transfer
  - Migration
  - Offline
  properties:
  - type: Documentation
    url: https://docs.aws.amazon.com/datasync/latest/userguide/API_Reference.html
  - type: Documentation
    url: https://cloud.google.com/storage-transfer/docs/reference/rest
  - type: Documentation
    url: https://learn.microsoft.com/en-us/azure/databox/
- name: Data Marketplaces
  description: Data marketplaces and open-data registries expose third-party datasets through REST APIs, subscription delivery, and shared buckets. They are an increasingly common acquisition channel for cloud-storage data lakes.
  url: https://aws.amazon.com/data-exchange/
  tags:
  - Datasets
  - Marketplace
  - Open Data
  properties:
  - type: Documentation
    url: https://aws.amazon.com/data-exchange/
  - type: Documentation
    url: https://cloud.google.com/marketplace
  - type: Open Data Registry
    url: https://registry.opendata.aws/
providers:
- slug: cloud-storage-and-data-acquisition
  name: Cloud Storage and Data Acquisition
  description: Cloud Storage and Data Acquisition is a topic profile in the API Evangelist Network covering APIs and tooling for ingesting, moving, and persisting bulk and streaming data into cloud-resident storage. It groups object storage services, data-lake foundations, managed ingestion pipelines, change-data…
  api_count: 6
  score_band: minimal
  score_composite: 15.9
  shared: 10
- slug: estuary-flow
  name: Estuary Flow
  description: Estuary Flow is a real-time data movement and transformation platform combining streaming infrastructure, a runtime, and an open-source ecosystem of connectors. It supports change data capture (CDC), SaaS integration, database replication, streaming lakehouse, and real-time analytics pipelines. Use…
  api_count: 4
  score_band: thin
  score_composite: 34.2
  shared: 3
- slug: backblaze
  name: Backblaze
  description: Backblaze is a cloud storage and data backup provider offering B2 Cloud Storage - a low-cost, S3-compatible object storage service. Backblaze provides both a native B2 API and an S3-compatible API, enabling developers to build applications that store unlimited data at a fraction of major cloud prov…
  api_count: 2
  score_band: strong
  score_composite: 61.2
  shared: 2
- slug: amazon-s3
  name: Amazon S3
  description: Amazon Simple Storage Service (S3) is an object storage service offering industry-leading scalability, data availability, security, and performance.
  api_count: 3
  score_band: developing
  score_composite: 58.7
  shared: 2
- slug: amazon-redshift
  name: Amazon Redshift
  description: Amazon Redshift is a fast, fully managed cloud data warehouse that makes it simple and cost-effective to analyze all your data using standard SQL and your existing Business Intelligence (BI) tools.
  api_count: 3
  score_band: developing
  score_composite: 52.6
  shared: 2
- slug: azure-blob-storage
  name: Azure Blob Storage
  description: Microsoft Azure Blob Storage is a service for storing large amounts of unstructured object data, such as text or binary data, that can be accessed from anywhere in the world via HTTP or HTTPS.
  api_count: 3
  score_band: developing
  score_composite: 51.1
  shared: 2
- slug: microsoft-azure-blob-storage
  name: Azure Blob Storage
  description: Microsoft Azure Blob Storage is a service for storing large amounts of unstructured object data, such as text or binary data, that can be accessed from anywhere in the world via HTTP or HTTPS.
  api_count: 3
  score_band: developing
  score_composite: 51.1
  shared: 2
- slug: google-cloud-datastream
  name: Google Cloud Datastream
  description: Google Cloud Datastream is a serverless change data capture (CDC) and replication service that allows you to synchronize data across heterogeneous databases, storage systems, and applications reliably and with minimal latency.
  api_count: 1
  score_band: developing
  score_composite: 50.4
  shared: 2
- slug: aws-s3
  name: Amazon S3 API
  description: Amazon Simple Storage Service (S3) is an object storage service offering industry-leading scalability, data availability, security, and performance for storing and retrieving any amount of data.
  api_count: 1
  score_band: developing
  score_composite: 48.9
  shared: 2
- slug: gcp-cloud-storage
  name: Google Cloud Storage
  description: Object storage service offering high durability, availability, and scalability for storing and accessing data on Google Cloud Platform.
  api_count: 2
  score_band: developing
  score_composite: 46.8
  shared: 2
- slug: pure-storage
  name: Pure Storage
  description: Pure Storage is an American publicly traded technology company specializing in all-flash data storage hardware and software products. The company provides enterprise data storage platforms including FlashArray, FlashBlade, and Pure1 fleet management, along with Portworx for Kubernetes data services…
  api_count: 4
  score_band: developing
  score_composite: 45.8
  shared: 2
- slug: warpstream
  name: WarpStream
  description: WarpStream is a diskless, Apache Kafka-compatible data streaming platform built directly on top of cloud object storage such as S3, GCP, and Azure. It eliminates the need for local disks, brokers to rebalance, and ZooKeeper, delivering Kafka compatibility through a single, stateless Go binary deplo…
  api_count: 1
  score_band: thin
  score_composite: 42.8
  shared: 2
- slug: apache-flume
  name: Apache Flume
  description: Apache Flume is a distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log and event data. It provides a simple and flexible architecture based on streaming data flows with pluggable sources, channels, and sinks, plus a REST monitoring AP…
  api_count: 2
  score_band: thin
  score_composite: 42.4
  shared: 2
- slug: filebase
  name: Filebase
  description: Filebase is an S3-compatible object storage and IPFS pinning platform that combines familiar cloud storage APIs with decentralized, blockchain-backed infrastructure. Developers can store, manage, and pin files to IPFS using standard S3 tooling, a dedicated IPFS Pinning Service API, and an IPFS RPC…
  api_count: 4
  score_band: thin
  score_composite: 42.2
  shared: 2
- slug: talend
  name: Talend
  description: Talend (now part of Qlik) provides data integration, quality, and API management capabilities through cloud-native APIs for ETL, data pipelines, and application integration. The Qlik Talend Cloud platform exposes REST APIs for orchestrating tasks and plans, executing data integration jobs, managing…
  api_count: 6
  score_band: thin
  score_composite: 41.9
  shared: 2
- slug: apache-seatunnel
  name: Apache SeaTunnel
  description: Apache SeaTunnel is a high-performance, distributed data integration platform that supports real-time and batch data synchronization. It provides a connector API with support for over 100 data sources and sinks.
  api_count: 1
  score_band: thin
  score_composite: 41.8
  shared: 2
- slug: cloudflare-r2
  name: Cloudflare R2
  description: Cloudflare R2 is S3-compatible object storage with zero egress fees. It provides both an S3-compatible REST API and a Cloudflare API for managing buckets, objects, and storage policies at global scale. R2 offers a generous free tier including 10 GB storage, 1 million Class A operations, and 10 mill…
  api_count: 2
  score_band: thin
  score_composite: 41.5
  shared: 2
- slug: flatfile
  name: Flatfile
  description: Flatfile is a data exchange platform that helps teams import, transform, validate, and collaborate on file-based data. The Flatfile API provides programmatic access to spaces, workbooks, sheets, records, files, documents, jobs, events, agents, environments, users, guests, and related primitives for…
  api_count: 1
  score_band: thin
  score_composite: 38.3
  shared: 2
- slug: apache-nifi
  name: Apache NiFi
  description: Apache NiFi is a dataflow management system designed to automate the flow of data between systems. It provides a web-based user interface for designing, controlling, and monitoring data flows with real-time operational control, data provenance tracking, and support for hundreds of processors. NiFi…
  api_count: 3
  score_band: thin
  score_composite: 33.1
  shared: 2
- slug: apache-beam
  name: Apache Beam
  description: Apache Beam is a unified, open-source programming model developed by the Apache Software Foundation for defining both batch and streaming data processing pipelines. It provides a portable API layer that lets developers write pipeline logic once in Java, Python, or Go and deploy it to multiple execu…
  api_count: 2
  score_band: thin
  score_composite: 32.7
  shared: 2
- slug: kafka-connect
  name: Kafka Connect
  description: Kafka Connect is a tool for scalably and reliably streaming data between Apache Kafka and other systems. It makes it simple to quickly define connectors that move large collections of data into and out of Kafka.
  api_count: 1
  score_band: thin
  score_composite: 31.9
  shared: 2
- slug: wasabi
  name: Wasabi
  description: Wasabi Hot Cloud Storage is an S3-compatible object storage service offering a REST API that mirrors the Amazon S3 API for storing, retrieving, and managing objects and buckets. Wasabi provides always-consistent storage at lower cost than hyperscale providers, with no egress fees, no API request fe…
  api_count: 4
  score_band: thin
  score_composite: 30.1
  shared: 2
- slug: delta-lake
  name: Delta Lake
  description: Delta Lake is a graduated project of the Linux Foundation AI & Data Foundation providing an open source storage framework for building Lakehouse architectures. Originally contributed by Databricks, it adds reliability, quality, and performance to data lakes with ACID transactions, schema enforcemen…
  api_count: 3
  score_band: minimal
  score_composite: 25.2
  shared: 2
- slug: cloud-storage
  name: Cloud Storage
  description: Cloud Storage is a topic profile in the API Evangelist Network covering the major cloud and S3-compatible object, file, and block storage APIs. The topic indexes the canonical hyperscaler offerings (Amazon S3, Google Cloud Storage, Azure Blob Storage) alongside S3-compatible alternatives (Wasabi, B…
  api_count: 11
  score_band: minimal
  score_composite: 15.9
  shared: 2
related:
- slug: cloud-storage
  name: Cloud Storage
  shared: 2
repo: https://github.com/api-evangelist/cloud-storage-and-data-acquisition
overview: 'Cloud Storage and Data Acquisition on the [APIs.io](https://apis.io/) network is a curated area collecting 6 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including Cloud Storage and Data Acquisition, Estuary Flow, Backblaze, Amazon S3, Amazon Redshift, Azure Blob Storage, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Cloud Storage. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
