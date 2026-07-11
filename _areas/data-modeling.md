---
layout: area
slug: data-modeling
name: Data Modeling
description: Data Modeling is the discipline of designing structured representations of data to organize information, define relationships, and govern how data is stored, accessed, and managed. It spans conceptual, logical, and physical models across relational, dimensional, NoSQL, graph, and data vault paradigms, supported by standards and tools from the OMG, DAMA, Erwin, PowerDesigner, dbt, and modern data modeling platforms.
tags:
- Data Architecture
- Data Engineering
- Data Modeling
- Database Design
- Schema Design
resource_count: 0
provider_count: 18
resources: []
providers:
- slug: relational-data-modeling
  name: Relational Data Modeling
  description: Relational data modeling is a database design approach that organizes data into tables (relations) with rows and columns, establishing relationships between tables through primary and foreign keys to ensure data integrity and minimize redundancy. This index covers leading platforms, tools, and APIs…
  api_count: 4
  score_band: minimal
  score_composite: 25.4
  shared: 4
- slug: schema-design
  name: Schema Design
  description: Schema Design is the practice of defining the structure, constraints, and semantics of data models used in APIs, databases, and data exchange formats. It encompasses schema-first API design approaches, data modeling methodologies, type systems, and tooling for creating, validating, and evolving dat…
  api_count: 5
  score_band: minimal
  score_composite: 26.9
  shared: 2
- slug: databricks
  name: Databricks
  description: Collection of Databricks REST APIs for managing workspaces, clusters, jobs, and data operations.
  api_count: 57
  score_band: strong
  score_composite: 67.6
  shared: 1
- slug: azure-databricks
  name: Azure Databricks
  description: Azure Databricks is an Apache Spark-based analytics platform optimized for Microsoft Azure. It provides a collaborative workspace for data engineers, data scientists, and analysts to work together on big data and machine learning workloads.
  api_count: 39
  score_band: developing
  score_composite: 59.0
  shared: 1
- slug: microsoft-azure-databricks
  name: Azure Databricks
  description: Azure Databricks is an Apache Spark-based analytics platform optimized for Microsoft Azure. It provides a collaborative workspace for data engineers, data scientists, and analysts to work together on big data and machine learning workloads.
  api_count: 39
  score_band: developing
  score_composite: 59.0
  shared: 1
- slug: dagster
  name: Dagster
  description: Dagster is a data orchestration platform centered on software-defined assets with strong observability and testing support. It exposes a GraphQL API for programmatic interaction with Dagster instances and a REST API for reporting external asset materializations, checks, and observations from outsid…
  api_count: 2
  score_band: developing
  score_composite: 58.4
  shared: 1
- slug: databricks-asset-bundles
  name: Databricks Asset Bundles
  description: Databricks Asset Bundles (DABs) provide an infrastructure-as-code approach to managing Databricks data and AI projects. Bundles enable version control, CI/CD, deployment, and management of Databricks resources such as jobs, pipelines, apps, schemas, experiments, and model serving endpoints across w…
  api_count: 1
  score_band: developing
  score_composite: 56.7
  shared: 1
- slug: tetrascience
  name: TetraScience
  description: TetraScience is the scientific data and AI platform company behind the Tetra Scientific Data and AI Cloud — purpose-built infrastructure that liberates, replatforms, and engineers raw lab data from instruments, informatics systems, and partner organizations into FAIR, AI-native Tetra Data. The plat…
  api_count: 1
  score_band: developing
  score_composite: 51.8
  shared: 1
- slug: airflow
  name: Apache Airflow
  description: Apache Airflow is an open-source platform to programmatically author, schedule, and monitor workflows. Airflow uses directed acyclic graphs (DAGs) to manage workflow orchestration. The Airflow REST API provides programmatic access to DAGs, DAG runs, tasks, connections, variables, pools, and monitor…
  api_count: 1
  score_band: developing
  score_composite: 48.3
  shared: 1
- slug: alteryx
  name: Alteryx
  description: Alteryx is an analytics automation platform that enables data analysts and scientists to break data barriers, deliver insights, and experience the thrill of getting to the answer faster.
  api_count: 7
  score_band: developing
  score_composite: 48.2
  shared: 1
- slug: microsoft-fabric
  name: Microsoft Fabric
  description: Microsoft Fabric is a unified analytics platform that brings together data engineering, data science, real-time analytics, and business intelligence. It provides REST APIs for managing workspaces, lakehouses, warehouses, data pipelines, notebooks, and other Fabric items.
  api_count: 2
  score_band: developing
  score_composite: 48.1
  shared: 1
- slug: snowplow
  name: Snowplow
  description: Snowplow is a behavioral data platform that enables organizations to collect, process, and model granular event-level data from web, mobile, and server-side sources, providing a data pipeline for analytics and AI use cases. The platform uses a schema-first approach with self-describing JSON events…
  api_count: 2
  score_band: developing
  score_composite: 47.4
  shared: 1
- slug: vineyard
  name: Vineyard
  description: Vineyard (v6d) is an in-memory immutable data manager developed under CNCF TAG-Storage. It provides efficient zero-copy data sharing across distributed systems for big data analytics, machine learning, and data-intensive workflows. Vineyard enables seamless object sharing between computation engine…
  api_count: 2
  score_band: thin
  score_composite: 43.0
  shared: 1
- slug: soda-co
  name: Soda
  description: Soda is an AI-native, fully automated data quality platform that helps data engineering and analytics teams define data quality checks, scan datasets, monitor data freshness, and manage data quality incidents. The Soda Cloud REST API enables programmatic access to trigger scans, retrieve check resu…
  api_count: 1
  score_band: thin
  score_composite: 41.5
  shared: 1
- slug: holistics
  name: Holistics
  description: Holistics is a self-service business intelligence and analytics platform built around code-based data modeling (AML - Analytics Modeling Language), Git version control, and a SQL/dataset semantic layer. Its REST API lets teams query datasets and reports, export data to CSV/JSON/XLSX, trigger data i…
  api_count: 5
  score_band: thin
  score_composite: 34.9
  shared: 1
- slug: mage-ai
  name: Mage
  description: Mage is an open-source data pipeline tool for building, running, and managing data pipelines from transformer, data loader, and data exporter blocks. The self-hosted Mage app exposes a REST API for triggering pipeline runs and managing pipelines, blocks, pipeline runs, and schedules; Mage Pro is th…
  api_count: 4
  score_band: thin
  score_composite: 33.8
  shared: 1
- slug: cloudera
  name: Cloudera
  description: Cloudera is a hybrid data platform company offering the Cloudera Data Platform (CDP) for data engineering, data warehousing, machine learning, streaming, and operational data. The platform exposes multiple REST APIs including the CDP Public Cloud Control Plane API for managing environments, datalak…
  api_count: 6
  score_band: minimal
  score_composite: 27.1
  shared: 1
- slug: lakehouse-architecture
  name: Lakehouse Architecture
  description: Lakehouse Architecture is a data architecture paradigm that combines the best features of data lakes and data warehouses, providing ACID transactions, schema enforcement, and governance on low-cost storage with support for both business intelligence and machine learning workloads.
  api_count: 1
  score_band: minimal
  score_composite: 20.0
  shared: 1
related:
- slug: data-models
  name: Data Models
  shared: 3
- slug: database-normalization
  name: Database Normalization
  shared: 2
- slug: database-schema-design
  name: Database Schema Design
  shared: 2
- slug: schema-design
  name: Schema Design
  shared: 2
- slug: data-warehouse-schemas
  name: Data Warehouse Schemas
  shared: 1
repo: https://github.com/api-evangelist/data-modeling
overview: 'Data Modeling on the [APIs.io](https://apis.io/) network is a curated area collecting 0 resources — specifications, tools, and documentation — for this subject.


  18 providers on the network work in this area, including Relational Data Modeling, Schema Design, Databricks, Azure Databricks, Azure Databricks, Dagster, and 12 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Data Models, Database Normalization, Database Schema Design, and Schema Design. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
