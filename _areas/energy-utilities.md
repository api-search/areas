---
layout: area
slug: energy-utilities
name: Energy and Utilities
description: Energy and Utilities is a topic profile in the API Evangelist Network cataloging the API surfaces that move data across the modern electricity, gas, and water value chain. It indexes utility data integration APIs, grid and wholesale market operator APIs, federal energy data programs, renewable energy research APIs, weather APIs that drive grid demand and solar forecasting, EV charging interoperability protocols, and the Green Button family of customer energy data standards. The repo provides a baseline catalog plus shared semantics (JSON Schema, JSON-LD, vocabulary, examples) for the meter reading / energy data point that ties every one of these surfaces together.
tags:
- Energy
- Utilities
- Electricity
- Grid
- Smart Meter
- Meter Data
- Green Button
- Demand Response
- DERMS
- EV Charging
- ISO/RTO
- Renewable Energy
- Solar
- Wind
- Weather
- Open Data
resource_count: 9
provider_count: 663
resources:
- name: Utility Data Integration APIs
  description: Third-party platforms that authenticate against retail electric, gas, and water utilities to retrieve customer meter, interval, and billing data on behalf of a consumer or business. These APIs collapse the thousands of US utility back-office systems into a single REST surface, typically aligned with the Green Button s…
  url: https://utilityapi.com/
  tags:
  - Utility Data
  - Meter Data
  - Billing Data
  - Green Button
  - Authorization
  properties:
  - type: Documentation
    url: https://utilityapi.com/docs
  - type: Documentation
    url: https://docs.bayou.energy/
  - type: Documentation
    url: https://docs.arcadia.com/
  - type: OpenAPI
    url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/openapi/utilityapi-openapi.yml
  - type: Reference
    url: https://www.arcadia.com/arc
- name: ISO and RTO Wholesale Market APIs
  description: Independent System Operators and Regional Transmission Organizations publish locational marginal prices, load forecasts, generation mix, ancillary services awards, and capacity market data through public data portals and (where available) REST APIs. These are the primary sources for wholesale electricity market data i…
  url: https://oasis.caiso.com/
  tags:
  - Wholesale Market
  - LMP
  - Grid Operator
  - Load Forecast
  - Ancillary Services
  properties:
  - type: Documentation
    url: https://www.caiso.com/library/oasis-technical-specifications
  - type: Documentation
    url: https://developer.ercot.com/
  - type: Reference
    url: https://apiexplorer.ercot.com/
  - type: Documentation
    url: https://dataminer2.pjm.com/
  - type: Reference
    url: https://data-exchange.misoenergy.org/
  - type: Reference
    url: https://www.iso-ne.com/isoexpress/
- name: EIA Open Data API
  description: The U.S. Energy Information Administration publishes time-series data covering electricity, natural gas, petroleum, coal, nuclear outages, renewables, and international energy through APIv2. Datasets are organized by major energy category and accessed with an api.data.gov key.
  url: https://www.eia.gov/opendata/
  tags:
  - Open Data
  - Federal
  - Electricity
  - Natural Gas
  - Petroleum
  - Time Series
  properties:
  - type: Documentation
    url: https://www.eia.gov/opendata/documentation.php
  - type: Signup
    url: https://www.eia.gov/opendata/register.php
  - type: Reference
    url: https://www.eia.gov/opendata/browser/
- name: NREL Developer Network APIs
  description: The National Renewable Energy Laboratory exposes a developer network of REST APIs covering solar resource (NSRDB, PVWatts), wind resource, alternative fuel stations, utility rates (URDB), transportation, buildings, and geothermal data. Authentication uses an api.data.gov key shared with other federal data programs.
  url: https://developer.nrel.gov/
  tags:
  - Renewable Energy
  - Solar
  - Wind
  - Utility Rates
  - Alternative Fuel
  properties:
  - type: Documentation
    url: https://developer.nrel.gov/docs/
  - type: Signup
    url: https://developer.nrel.gov/signup/
  - type: Reference
    url: https://nsrdb.nrel.gov/
- name: Weather APIs for Grid and Solar
  description: Weather APIs that feed grid-demand modelling, renewable generation forecasts, and outage operations. Includes the National Weather Service public API (no authentication, GeoJSON), OpenWeather solar irradiance and panel-output products, and commercial providers offering historical and predictive weather data used by ut…
  url: https://api.weather.gov/
  tags:
  - Weather
  - Solar Irradiance
  - Forecast
  - GeoJSON
  - Grid Demand
  properties:
  - type: Documentation
    url: https://www.weather.gov/documentation/services-web-api
  - type: Documentation
    url: https://openweathermap.org/api/solar-energy-prediction
  - type: Documentation
    url: https://openweathermap.org/api/one-call-3
- name: EV Charging Interoperability Protocols
  description: Open protocols that govern communication between EV charging stations, charging management systems, and roaming hubs. OCPP is the charger-to-back-office protocol from the Open Charge Alliance. OCPI is the back-office-to-back-office roaming protocol. ISO 15118 handles vehicle-to-charger plug-and-charge. These specifica…
  url: https://openchargealliance.org/protocols/open-charge-point-protocol/
  tags:
  - EV Charging
  - OCPP
  - OCPI
  - Roaming
  - Smart Charging
  properties:
  - type: Documentation
    url: https://openchargealliance.org/protocols/open-charge-point-protocol/
  - type: Documentation
    url: https://evroaming.org/ocpi-protocol/
  - type: Repository
    url: https://github.com/ocpi/ocpi
  - type: Repository
    url: https://github.com/openchargealliance
- name: OpenADR Demand Response
  description: OpenADR is an open, two-way information exchange model and Smart Grid standard for automating demand response and orchestrating distributed energy resources. The OpenADR Alliance publishes profile specifications, schema files, sample payloads, and test plans for utilities, aggregators, and DER vendors. OpenADR 3.0 is…
  url: https://www.openadr.org/
  tags:
  - Demand Response
  - DER
  - Smart Grid
  - Standard
  properties:
  - type: Documentation
    url: https://www.openadr.org/specification
  - type: Reference
    url: https://www.openadr.org/openadr-30
- name: Green Button (CMD / DMD / ESPI / CDS)
  description: Green Button is the consumer energy data standard for utilities and third-party solution providers. Connect My Data (CMD) is the machine-to-machine sharing flow. Download My Data (DMD) is the user-initiated export flow. The Energy Services Provider Interface (ESPI) defines the underlying REST and Atom payloads (UsageP…
  url: https://www.greenbuttonalliance.org/
  tags:
  - Green Button
  - ESPI
  - CDS
  - Consumer Data
  - Authorization
  - OAuth2
  properties:
  - type: Documentation
    url: https://greenbuttonalliance.github.io/OpenESPI-GreenButton-API-Documentation/API/
  - type: Repository
    url: https://github.com/GreenButtonAlliance
  - type: Reference
    url: https://www.greenbuttonalliance.org/developer-resources
- name: Distributed Energy Resource Management APIs
  description: DERMS platforms aggregate, monitor, dispatch, and optimize distributed energy resources such as rooftop solar, behind-the-meter batteries, EV chargers, and controllable loads. DERMS API surfaces typically wrap OpenADR for event signaling, IEEE 2030.5 (SEP 2.0) for device-level control, and proprietary REST APIs for te…
  url: https://www.openadr.org/
  tags:
  - DERMS
  - DER
  - Aggregation
  - VPP
  - IEEE 2030.5
  properties:
  - type: Reference
    url: https://standards.ieee.org/ieee/2030.5/5897/
  - type: Reference
    url: https://www.openadr.org/openadr-30
providers:
- slug: energy-utilities
  name: Energy and Utilities
  description: Energy and Utilities is a topic profile in the API Evangelist Network cataloging the API surfaces that move data across the modern electricity, gas, and water value chain. It indexes utility data integration APIs, grid and wholesale market operator APIs, federal energy data programs, renewable ener…
  api_count: 9
  score_band: minimal
  score_composite: 20.1
  shared: 16
- slug: span-io
  name: SPAN
  description: SPAN is a San Francisco-based home energy technology company building smart electrical panels that replace traditional residential breaker boxes with a software-defined, controllable, and metered panel. SPAN Panel provides whole-home real-time power and energy metering, per-circuit monitoring and r…
  api_count: 2
  score_band: developing
  score_composite: 53.0
  shared: 5
- slug: octopus-energy
  name: Octopus Energy
  description: Octopus Energy is a UK-founded retail energy supplier and the parent of Kraken Technologies, the AI-powered energy operating system that runs both Octopus and many of the world's largest utilities. Octopus operates a free, open REST API at api.octopus.energy/v1/ that exposes the full UK product cat…
  api_count: 3
  score_band: developing
  score_composite: 47.2
  shared: 5
- slug: doe
  name: Department of Energy
  description: The U.S. Department of Energy provides REST APIs for energy consumption data, renewable energy statistics, fuel prices, electric vehicle infrastructure data, nuclear facility information, and scientific research publications. Primary API programs include the EIA Open Data API for energy time-series…
  api_count: 8
  score_band: thin
  score_composite: 38.1
  shared: 5
- slug: solcast
  name: Solcast
  description: Solcast is a solar and renewable energy data company, acquired by DNV in 2023, that provides high-resolution, satellite-derived solar irradiance, PV power, weather forecasting, and historical climate data via a developer API. Its data covers live, forecast, historical, and typical meteorological ye…
  api_count: 1
  score_band: developing
  score_composite: 50.7
  shared: 4
- slug: lunar-energy
  name: Lunar Energy
  description: Lunar Energy is a Mountain View, California-based residential clean-energy company founded in August 2020 by former Tesla Energy executive Kunal Girotra. The company designs and manufactures the Lunar System — a modular home battery (15–30 kWh, 9.6 kW continuous / 15 kW peak), Lunar Inverter, Lunar…
  api_count: 3
  score_band: thin
  score_composite: 43.7
  shared: 4
- slug: utilityapi
  name: UtilityAPI
  description: UtilityAPI collects, standardizes, and shares utility data seamlessly and securely, providing a platform for accessing energy and utility billing data, meter intervals, and authorization workflows for energy companies, cleantech firms, and developers.
  api_count: 1
  score_band: thin
  score_composite: 40.5
  shared: 4
- slug: department-of-energy
  name: Department of Energy
  description: The U.S. Department of Energy (DOE) provides extensive open data and APIs across its national laboratories and program offices. Notable APIs are published by the Energy Information Administration (EIA) for energy statistics, the Office of Scientific and Technical Information (OSTI) for research and…
  api_count: 6
  score_band: thin
  score_composite: 38.4
  shared: 4
- slug: national-energy-system-operator
  name: National Energy System Operator
  description: The National Energy System Operator (NESO) is the independent operator responsible for planning and operating Great Britain's electricity and gas networks. NESO publishes operational, market, and forecasting datasets through its Data Portal, which exposes a CKAN v3 API for programmatic access to en…
  api_count: 1
  score_band: thin
  score_composite: 30.9
  shared: 4
- slug: centerpoint-energy
  name: CenterPoint Energy
  description: CenterPoint Energy is a domestic energy delivery company that provides electric transmission and distribution, natural gas distribution, and energy services operations serving residential, commercial, and industrial customers across multiple U.S. states. Developer-facing interfaces include the Smar…
  api_count: 3
  score_band: minimal
  score_composite: 22.9
  shared: 4
- slug: enphase-energy
  name: Enphase Energy
  description: Enphase Energy is a solar microinverter and energy management company that provides the Enlighten Systems API, a REST API enabling access to solar production, battery storage, grid usage, and home energy data. The API supports monitoring at the fleet, site, and device level across Enphase IQ Microi…
  api_count: 3
  score_band: developing
  score_composite: 51.5
  shared: 3
- slug: arcadia-power
  name: Arcadia
  description: Arcadia is a clean-energy access and energy-intelligence company that operates Arc, a utility data platform giving developers programmatic access to utility bills, statements, meters, interval (15-minute) usage data, tariff rates, and provider metadata across thousands of US and international utili…
  api_count: 5
  score_band: developing
  score_composite: 47.2
  shared: 3
- slug: itron
  name: Itron
  description: 'Itron, Inc. (NASDAQ: ITRI) is a Liberty Lake, Washington–based industrial technology company providing smart-meter, grid-edge, and IoT infrastructure to electric, gas, and water utilities and cities. Itron''s self-described mission is "Creating a more resourceful world" and the company reports 7,700…'
  api_count: 8
  score_band: developing
  score_composite: 47.1
  shared: 3
- slug: eaton
  name: Eaton
  description: 'Eaton Corporation plc (NYSE: ETN) is a global intelligent-power-management company with operations across electrical, aerospace, vehicle, and eMobility segments. Its digital surface centers on Brightlayer — a software portfolio for data centers, utilities, industrial, buildings, and mobility — toge…'
  api_count: 12
  score_band: developing
  score_composite: 46.3
  shared: 3
- slug: sense
  name: Sense
  description: Sense is a ClimateTech company founded in 2013 that provides home energy intelligence through a high-resolution electrical monitoring device installed in residential electrical panels. The Sense platform captures real-time electricity usage data and uses machine learning to disaggregate power consu…
  api_count: 2
  score_band: developing
  score_composite: 46.2
  shared: 3
- slug: xcel-energy
  name: Xcel Energy
  description: 'Xcel Energy is a major U.S. electricity and natural gas utility holding company headquartered in Minneapolis, Minnesota, providing service to approximately 3.7 million electricity customers and 2.1 million natural gas customers across eight Midwestern and Western states: Colorado, Minnesota, Texas,…'
  api_count: 2
  score_band: thin
  score_composite: 42.1
  shared: 3
- slug: arcadia
  name: Arcadia
  description: Arcadia is the leading clean energy data platform that provides developers and businesses with programmatic access to utility billing data, real-time energy usage, and tariff intelligence across thousands of utility providers in the United States. The Arc Connect API enables applications to collect…
  api_count: 4
  score_band: thin
  score_composite: 41.5
  shared: 3
- slug: electricitymaps
  name: Electricity Maps
  description: Electricity Maps provides electricity grid data - carbon intensity and power production/consumption breakdown - for 200+ zones worldwide, in real time, as historical series, and as 24-72 hour forecasts. The REST API serves the same data behind the live electricity map at app.electricitymap.org, aut…
  api_count: 5
  score_band: thin
  score_composite: 36.6
  shared: 3
- slug: solar-edge
  name: SolarEdge
  description: SolarEdge Technologies provides a cloud-based Monitoring API that enables web services and third-party applications to access real-time and historical solar production data stored on the SolarEdge monitoring server. The REST API delivers site energy measurements, power flow data, inverter technical…
  api_count: 1
  score_band: thin
  score_composite: 34.6
  shared: 3
- slug: national-grid
  name: National Grid ESO
  description: National Energy System Operator (NESO) provides open data APIs for the UK electricity system, including carbon intensity forecasts, demand data, generation mix, ancillary services, balancing costs, and operational data for Great Britain's electricity network. The Carbon Intensity API delivers 96+ h…
  api_count: 2
  score_band: minimal
  score_composite: 29.9
  shared: 3
- slug: energy-charts-api
  name: Energy Charts API
  description: The Energy-Charts API, provided by Fraunhofer ISE, delivers European energy data including electricity production by source, day-ahead spot market prices, cross-border electricity trading and physical flows, grid frequency, installed capacity, and renewable energy share forecasts. It covers more th…
  api_count: 1
  score_band: minimal
  score_composite: 27.4
  shared: 3
- slug: wgl-holdings
  name: WGL Holdings
  description: WGL Holdings was an integrated energy holding company headquartered in Washington, D.C., serving over 1 million customers across the District of Columbia, Maryland, and Virginia. Its operations spanned regulated natural gas distribution (Washington Gas), retail energy marketing (WGL Energy Services…
  api_count: 4
  score_band: minimal
  score_composite: 26.1
  shared: 3
- slug: ameren
  name: Ameren
  description: Ameren Corporation is a regulated electric and natural gas utility serving customers in Missouri and Illinois. The company provides reliable energy delivery, smart grid infrastructure, and renewable energy programs. Ameren Illinois implements the Green Button Connect My Data program (Share My Usage…
  api_count: 2
  score_band: minimal
  score_composite: 20.2
  shared: 3
- slug: openweathermap
  name: OpenWeatherMap
  description: OpenWeather (operating openweathermap.org) is a global weather data platform delivering current weather, multi-horizon forecasts, historical archives, climate statistics, air pollution, solar irradiance, road risk, geocoding, and weather map tiles. Data is sourced from satellites, weather models, r…
  api_count: 12
  score_band: strong
  score_composite: 64.5
  shared: 2
related:
- slug: data-commons
  name: Data Commons
  shared: 1
- slug: boycott-israeli-consumer-goods-dataset
  name: Boycott Israeli Consumer Goods Dataset
  shared: 1
repo: https://github.com/api-evangelist/energy-utilities
overview: 'Energy and Utilities on the [APIs.io](https://apis.io/) network is a curated area collecting 9 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including Energy and Utilities, SPAN, Octopus Energy, Department of Energy, Solcast, Lunar Energy, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Data Commons and Boycott Israeli Consumer Goods Dataset. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
