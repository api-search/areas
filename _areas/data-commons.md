---
layout: area
slug: data-commons
name: Data Commons
description: Data Commons is an open knowledge graph initiative led by Google that aggregates and harmonizes the world's public data into a single graph, making global statistical data simple to explore, query, and integrate through REST, Python, BigQuery, web component, and MCP interfaces.
tags:
- Data Commons
- Knowledge Graph
- Open Data
- Public Data
- Statistics
resource_count: 6
provider_count: 533
resources:
- name: Data Commons REST API V2
  description: HTTP REST interface for retrieving statistical observations, exploring the Data Commons knowledge graph, and resolving entities to Data Commons IDs (DCIDs). Returns structured JSON data covering variables, places, and observations.
  url: https://docs.datacommons.org/api/rest/v2/
  tags:
  - Knowledge Graph
  - REST
  - Statistics
  properties:
  - type: Documentation
    url: https://docs.datacommons.org/api/rest/v2/
  - type: API Keys
    url: https://apikeys.datacommons.org
  - type: Reference
    url: https://docs.datacommons.org/api/
  - type: OpenAPI
    url: openapi/data-commons-openapi.yml
- name: Data Commons Python Client
  description: Official Python client library that wraps the Data Commons REST API with native Pandas DataFrame support for analytical workflows and notebook integration.
  url: https://docs.datacommons.org/api/python/v2/
  tags:
  - Pandas
  - Python
  - SDK
  properties:
  - type: Documentation
    url: https://docs.datacommons.org/api/python/v2/
  - type: PyPI
    url: https://pypi.org/project/datacommons-client/
- name: Data Commons Google Sheets
  description: Custom Google Sheets functions that pull Data Commons statistical data directly into spreadsheets without requiring an API key.
  url: https://docs.datacommons.org/api/sheets/
  tags:
  - Google Sheets
  - Spreadsheets
  properties:
  - type: Documentation
    url: https://docs.datacommons.org/api/sheets/
- name: Data Commons Web Components
  description: Drop-in JavaScript/HTML web components for embedding Data Commons charts, maps, rankings, and visualizations in any website.
  url: https://docs.datacommons.org/api/web_components/
  tags:
  - JavaScript
  - Visualization
  - Web Components
  properties:
  - type: Documentation
    url: https://docs.datacommons.org/api/web_components/
- name: Data Commons BigQuery
  description: SQL access to Data Commons through Google BigQuery enabling complex analytical queries and joins with private datasets.
  url: https://docs.datacommons.org/api/bigquery.html
  tags:
  - BigQuery
  - SQL
  properties:
  - type: Documentation
    url: https://docs.datacommons.org/api/bigquery.html
- name: Data Commons MCP Server
  description: Model Context Protocol server that lets AI agents query Data Commons conversationally, surfacing variables, places, and observations through natural language tools.
  url: https://docs.datacommons.org/api/mcp/
  tags:
  - AI Agents
  - MCP
  - Natural Language
  properties:
  - type: Documentation
    url: https://docs.datacommons.org/api/mcp/
  - type: API Keys
    url: https://apikeys.datacommons.org
providers:
- slug: data-commons
  name: Data Commons
  description: Data Commons is an open knowledge graph initiative led by Google that aggregates and harmonizes the world's public data into a single graph, making global statistical data simple to explore, query, and integrate through REST, Python, BigQuery, web component, and MCP interfaces.
  api_count: 6
  score_band: thin
  score_composite: 38.4
  shared: 5
- slug: agricultural-statistics-service
  name: Agricultural Statistics Service
  description: The National Agricultural Statistics Service (NASS) is an agency of the United States Department of Agriculture (USDA) whose mission is to support the United States, its agricultural sector, and rural communities by providing accurate, objective, and meaningful statistical information and services.…
  api_count: 4
  score_band: developing
  score_composite: 55.1
  shared: 2
- slug: wikidata
  name: Wikidata
  description: Wikidata is a free, collaborative, multilingual knowledge graph hosted by the Wikimedia Foundation. It provides structured linked data for Wikipedia and other Wikimedia projects, as well as a public platform for anyone to read and edit. Wikidata exposes several APIs including a Wikibase REST API fo…
  api_count: 5
  score_band: developing
  score_composite: 52.4
  shared: 2
- slug: wikipedia
  name: Wikipedia / MediaWiki
  description: 'Wikipedia is the free, multilingual online encyclopedia operated by the non-profit Wikimedia Foundation. The platform exposes its content and structured data through several public APIs: the original MediaWiki Action API (action=query|edit|parse|upload), the MediaWiki Core REST API (page CRUD, sear…'
  api_count: 5
  score_band: developing
  score_composite: 47.4
  shared: 2
- slug: opendatasoft
  name: Opendatasoft
  description: Open data platform with REST APIs for accessing public datasets from 1,000+ cities and organizations, providing standard OData and JSON query interfaces. Now operating as Huwise, the platform powers 3,000+ data marketplaces and provides catalog, records, analysis, and export APIs across public port…
  api_count: 3
  score_band: thin
  score_composite: 44.4
  shared: 2
- slug: us-census-bureau
  name: US Census Bureau
  description: The U.S. Census Bureau is the federal statistical agency responsible for producing data about the American people and economy. Established in 1902 and part of the U.S. Department of Commerce, the Bureau conducts the constitutionally mandated Decennial Census every ten years and dozens of ongoing su…
  api_count: 7
  score_band: thin
  score_composite: 42.1
  shared: 2
- slug: the-bureau-of-economic-analysis
  name: The Bureau of Economic Analysis
  description: The Bureau of Economic Analysis (BEA) is an agency within the U.S. Department of Commerce that provides economic data to policymakers, businesses, and the general public. The BEA collects and analyzes a wide range of economic indicators, including gross domestic product (GDP), personal income, and…
  api_count: 1
  score_band: thin
  score_composite: 40.4
  shared: 2
- slug: eurostat
  name: Eurostat
  description: Eurostat is the statistical office of the European Union, providing free and open REST APIs for programmatic access to European statistical data covering demographics, economy, trade, agriculture, transport, environment, and dozens of other indicators across EU member states and regions.
  api_count: 5
  score_band: thin
  score_composite: 38.6
  shared: 2
- slug: united-states-census-bureau
  name: United States Census Bureau
  description: The U.S. Census Bureau is the nation's leading provider of quality data about its people and economy. The Census Bureau has been rolling out datasets via APIs, providing programmatic access to demographic, economic, housing, and social statistics. The Census Data API supports queries across dataset…
  api_count: 3
  score_band: thin
  score_composite: 38.5
  shared: 2
- slug: department-of-energy
  name: Department of Energy
  description: The U.S. Department of Energy (DOE) provides extensive open data and APIs across its national laboratories and program offices. Notable APIs are published by the Energy Information Administration (EIA) for energy statistics, the Office of Scientific and Technical Information (OSTI) for research and…
  api_count: 6
  score_band: thin
  score_composite: 38.4
  shared: 2
- slug: data-analysis-tools-bureau-of-justice-statistics
  name: Bureau of Justice Statistics Data Analysis Tools
  description: The Bureau of Justice Statistics (BJS) is the agency within the U.S. Department of Justice responsible for collecting, analysing, and disseminating crime, criminal-justice, expenditure, and victimisation data. BJS exposes selected datasets through Socrata Open Data APIs and offers interactive data…
  api_count: 2
  score_band: thin
  score_composite: 36.7
  shared: 2
- slug: unicef-data
  name: UNICEF Data
  description: UNICEF Data is the official open data platform of the United Nations Children's Fund, providing programmatic access to global child welfare statistics, health and nutrition indicators, education data, child protection metrics, MICS (Multiple Indicator Cluster Survey) results, and SDG indicators for…
  api_count: 3
  score_band: thin
  score_composite: 36.4
  shared: 2
- slug: conceptnet
  name: ConceptNet
  description: ConceptNet is a freely available multilingual knowledge graph that gives computers access to common-sense knowledge. It represents over 13 million links between concepts across 100+ languages, drawing from crowd-sourced resources (Open Mind Common Sense, Wiktionary), expert-created resources (WordN…
  api_count: 1
  score_band: thin
  score_composite: 34.0
  shared: 2
- slug: bureau-of-transportation-statistics
  name: Bureau of Transportation Statistics
  description: The Bureau of Transportation Statistics (BTS), part of the Department of Transportation (DOT) is the preeminent source of statistics on commercial aviation, multimodal freight activity, and transportation economics, and provides context to decision makers and the public for understanding statistics…
  api_count: 3
  score_band: thin
  score_composite: 32.7
  shared: 2
- slug: dol
  name: Department of Labor
  description: The U.S. Department of Labor provides REST APIs exposing over 200 datasets covering employment statistics, H-1B and foreign labor visa data, OSHA inspections and enforcement, wage and hour violations, job openings, union reports, workforce development data, mine safety, and Bureau of Labor Statisti…
  api_count: 8
  score_band: thin
  score_composite: 30.1
  shared: 2
- slug: department-of-justice
  name: Department of Justice
  description: The U.S. Department of Justice (DOJ) is the federal executive department responsible for enforcing the law and defending the interests of the United States. DOJ exposes a portfolio of public APIs and data feeds including the DOJ News API for press releases, speeches, and blog entries from the Offic…
  api_count: 5
  score_band: minimal
  score_composite: 28.7
  shared: 2
- slug: department-of-labor
  name: Department of Labor
  description: The U.S. Department of Labor (DOL) is the federal department that fosters, promotes, and develops the welfare of wage earners, job seekers, and retirees, improves working conditions, advances opportunities for profitable employment, and assures work-related benefits and rights. DOL exposes a portfo…
  api_count: 5
  score_band: minimal
  score_composite: 28.7
  shared: 2
- slug: dbpedia
  name: DBpedia
  description: DBpedia is a community project that extracts structured data from Wikipedia and publishes it as Linked Open Data on the Web. It provides a SPARQL endpoint, a Lookup Service for entity resolution, a Spotlight API for text annotation, a Live endpoint for real-time Wikipedia data, and Linked Data acce…
  api_count: 6
  score_band: minimal
  score_composite: 22.7
  shared: 2
- slug: wiktionary
  name: Wiktionary
  description: Wiktionary is the free, collaborative multilingual dictionary project of the Wikimedia Foundation, the dictionary sibling of Wikipedia. Programmatic access is exposed through the MediaWiki Action API at en.wiktionary.org/w/api.php, the older Wikimedia REST API at en.wiktionary.org/api/rest_v1/ (whi…
  api_count: 3
  score_band: developing
  score_composite: 59.7
  shared: 1
- slug: scryfall
  name: Scryfall
  description: Scryfall is the most comprehensive free Magic - The Gathering card database. The Scryfall API exposes Cards (search, autocomplete, named, random, collection, by various IDs), Sets, Rulings, Symbology, Catalogs, Bulk Data downloads, and card-object Migrations. The service is community-funded (Patreo…
  api_count: 1
  score_band: developing
  score_composite: 57.4
  shared: 1
- slug: sportmonks
  name: Sportmonks
  description: Sportmonks is a Dutch sports data provider (Deventer, Netherlands) delivering developer-friendly REST APIs for football/soccer, cricket, and motorsport (Formula 1). The platform serves 30,000+ active users and 20,000+ developers building livescore portals, fantasy games, betting platforms, sports m…
  api_count: 4
  score_band: developing
  score_composite: 55.3
  shared: 1
- slug: u-s-bureau-of-labor-statistics
  name: U.S. Bureau of Labor Statistics
  description: The U.S. Bureau of Labor Statistics (BLS) is the principal federal statistical agency responsible for measuring labor market activity, working conditions, and price changes in the U.S. economy. BLS collects, processes, analyzes, and disseminates statistical data on employment, unemployment, inflati…
  api_count: 1
  score_band: developing
  score_composite: 53.9
  shared: 1
- slug: stackexchange
  name: Stack Exchange
  description: Stack Exchange is the network of Q&A communities founded by Joel Spolsky and Jeff Atwood and headlined by Stack Overflow, the largest community of software developers on the web. The Stack Exchange API v2.3 (api.stackexchange.com) is a single, read-mostly HTTP/JSON interface that spans 180+ Q&A sit…
  api_count: 2
  score_band: developing
  score_composite: 53.2
  shared: 1
- slug: google-knowledge-graph
  name: Google Knowledge Graph Search
  description: The Google Knowledge Graph Search API allows developers to search for entities (people, places, things) in the Google Knowledge Graph and retrieve structured data about them in JSON-LD format conforming to schema.org standards. Results include names, descriptions, images, and detailed descriptions…
  api_count: 1
  score_band: developing
  score_composite: 53.0
  shared: 1
related:
- slug: boycott-israeli-consumer-goods-dataset
  name: Boycott Israeli Consumer Goods Dataset
  shared: 1
- slug: energy-utilities
  name: Energy and Utilities
  shared: 1
repo: https://github.com/api-evangelist/data-commons
overview: 'Data Commons on the [APIs.io](https://apis.io/) network is a curated area collecting 6 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including Data Commons, Agricultural Statistics Service, Wikidata, Wikipedia / MediaWiki, Opendatasoft, US Census Bureau, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Boycott Israeli Consumer Goods Dataset and Energy and Utilities. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
