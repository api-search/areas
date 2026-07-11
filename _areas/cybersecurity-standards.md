---
layout: area
slug: cybersecurity-standards
name: Cybersecurity Standards
description: Cybersecurity Standards captures the public, machine-readable, and reference frameworks that establish best practices for protecting information systems, networks, software, and data from cyber threats. The landscape is anchored by U.S. National Institute of Standards and Technology (NIST) publications such as the Cybersecurity Framework (CSF) 2.0, SP 800-53 controls, SP 800-171 controls for controlled unclassified information, the Risk Management Framework (RMF), and the Secure Software Development Framework (SSDF SP 800-218); the international ISO/IEC 27001 / 27002 information security management standard family; the Center for Internet Security (CIS) Critical Security Controls and Benchmarks; the OWASP Top 10 and ASVS for application security; PCI DSS for payment data; HITRUST CSF for healthcare; SOC 2 trust services criteria; and FedRAMP / StateRAMP for cloud authorization. This index aggregates authoritative URLs, machine-readable artifacts (e.g., OSCAL), and cross-references for organizations building or auditing cybersecurity programs.
tags:
- CIS Controls
- Compliance
- CSF
- Cybersecurity
- FedRAMP
- Frameworks
- HIPAA
- HITRUST
- Information Security
- ISO 27001
- ISO 27002
- NIST
- NIST 800-171
- NIST 800-218
- NIST 800-53
- OSCAL
- OWASP
- PCI DSS
- Risk Management
- SOC 2
- SSDF
- Standards
resource_count: 10
provider_count: 299
resources:
- name: NIST Cybersecurity Framework (CSF) 2.0
  description: The NIST Cybersecurity Framework 2.0 is a voluntary risk-based framework organizing cybersecurity activities into six core functions (Govern, Identify, Protect, Detect, Respond, Recover) with categories and subcategories. NIST publishes informative references and quick-start guides mapping CSF to other standards.
  url: https://www.nist.gov/cyberframework
  tags:
  - CSF
  - Framework
  - NIST
  - Risk Management
  properties:
  - type: Documentation
    url: https://www.nist.gov/cyberframework
  - type: Publication
    url: https://doi.org/10.6028/NIST.CSWP.29
  - type: QuickStartGuides
    url: https://www.nist.gov/cyberframework/quick-start-guides
  - type: InformativeReferences
    url: https://www.nist.gov/cyberframework/informative-references
- name: NIST SP 800-53 Security and Privacy Controls
  description: NIST Special Publication 800-53 Revision 5 catalogs security and privacy controls for information systems and organizations. Used as the basis of FedRAMP authorizations and Risk Management Framework implementations. Available in machine-readable OSCAL format.
  url: https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final
  tags:
  - Controls
  - FedRAMP
  - NIST
  - OSCAL
  - RMF
  properties:
  - type: Documentation
    url: https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final
  - type: OSCALContent
    url: https://github.com/usnistgov/oscal-content
  - type: ControlBaselines
    url: https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/release-search
- name: NIST SP 800-171 Protecting CUI
  description: NIST SP 800-171 specifies requirements for protecting Controlled Unclassified Information (CUI) in non-federal systems. Forms the basis of CMMC (Cybersecurity Maturity Model Certification) for the U.S. defense industrial base.
  url: https://csrc.nist.gov/publications/detail/sp/800-171/rev-3/final
  tags:
  - CMMC
  - CUI
  - DIB
  - NIST
  properties:
  - type: Documentation
    url: https://csrc.nist.gov/publications/detail/sp/800-171/rev-3/final
  - type: Assessment
    url: https://csrc.nist.gov/publications/detail/sp/800-171a/rev-3/final
- name: NIST SP 800-218 Secure Software Development Framework (SSDF)
  description: NIST SP 800-218 defines the Secure Software Development Framework (SSDF), a set of high-level secure-development practices referenced by U.S. Executive Order 14028 and procurement attestations.
  url: https://csrc.nist.gov/publications/detail/sp/800-218/final
  tags:
  - NIST
  - Secure Development
  - SSDF
  properties:
  - type: Documentation
    url: https://csrc.nist.gov/publications/detail/sp/800-218/final
- name: ISO/IEC 27001 Information Security Management
  description: ISO/IEC 27001 is the international standard for information security management systems (ISMS). The 2022 revision aligns Annex A controls with the ISO/IEC 27002:2022 catalog. Certification is performed by accredited bodies.
  url: https://www.iso.org/standard/27001
  tags:
  - Certification
  - ISMS
  - ISO 27001
  - ISO 27002
  properties:
  - type: Documentation
    url: https://www.iso.org/standard/27001
  - type: ISO27002
    url: https://www.iso.org/standard/75652.html
- name: CIS Critical Security Controls and Benchmarks
  description: The Center for Internet Security publishes the Critical Security Controls (currently v8.1) and a library of CIS Benchmarks providing prescriptive secure configuration guidance for OSes, cloud platforms, and applications.
  url: https://www.cisecurity.org/controls
  tags:
  - Benchmarks
  - CIS
  - Configuration
  - Controls
  properties:
  - type: Documentation
    url: https://www.cisecurity.org/controls
  - type: Benchmarks
    url: https://www.cisecurity.org/cis-benchmarks
- name: OWASP Top 10 and ASVS
  description: OWASP publishes the Top 10 web application risks, the API Security Top 10, and the Application Security Verification Standard (ASVS) used as a baseline for application security reviews.
  url: https://owasp.org/Top10/
  tags:
  - API Security
  - ASVS
  - AppSec
  - OWASP
  properties:
  - type: Top10
    url: https://owasp.org/Top10/
  - type: APITop10
    url: https://owasp.org/API-Security/
  - type: ASVS
    url: https://owasp.org/www-project-application-security-verification-standard/
- name: PCI DSS Payment Card Industry Data Security Standard
  description: PCI DSS, maintained by the PCI Security Standards Council, defines requirements for organizations that store, process, or transmit cardholder data. Version 4.0.1 is the current edition.
  url: https://www.pcisecuritystandards.org/
  tags:
  - Cardholder Data
  - Payments
  - PCI DSS
  properties:
  - type: Documentation
    url: https://www.pcisecuritystandards.org/document_library/
- name: SOC 2 Trust Services Criteria
  description: SOC 2 (System and Organization Controls 2) reports are issued by AICPA-licensed auditors against the Trust Services Criteria (Security, Availability, Processing Integrity, Confidentiality, Privacy). Widely adopted by SaaS vendors.
  url: https://www.aicpa-cima.com/topic/audit-assurance/audit-and-assurance-greater-than-soc-2
  tags:
  - AICPA
  - Audit
  - SOC 2
  - Trust Services
  properties:
  - type: Documentation
    url: https://www.aicpa-cima.com/topic/audit-assurance/audit-and-assurance-greater-than-soc-2
- name: FedRAMP Federal Cloud Authorization
  description: The Federal Risk and Authorization Management Program provides a standardized approach for U.S. federal agencies to authorize cloud services, anchored on NIST SP 800-53 baselines.
  url: https://www.fedramp.gov/
  tags:
  - Cloud
  - FedRAMP
  - Federal Government
  properties:
  - type: Documentation
    url: https://www.fedramp.gov/
  - type: Marketplace
    url: https://marketplace.fedramp.gov/
providers:
- slug: cybersecurity-standards
  name: Cybersecurity Standards
  description: Cybersecurity Standards captures the public, machine-readable, and reference frameworks that establish best practices for protecting information systems, networks, software, and data from cyber threats. The landscape is anchored by U.S. National Institute of Standards and Technology (NIST) publicat…
  api_count: 10
  score_band: minimal
  score_composite: 20.8
  shared: 22
- slug: regulatory-templates
  name: Regulatory Templates
  description: Pre-built templates, frameworks, and policy libraries for meeting regulatory compliance requirements across industries and jurisdictions including GDPR, HIPAA, SOC 2, ISO 27001, PCI DSS, and more. Compliance platforms and API governance tools provide template-driven approaches to accelerate audit r…
  api_count: 4
  score_band: minimal
  score_composite: 26.9
  shared: 5
- slug: svix
  name: Svix
  description: Svix is an enterprise webhooks-as-a-service platform on the sending side of the webhook market. It provides a single API for delivering reliable, secure, low-latency webhooks at scale, with hosted UIs (Consumer App Portal), a polyglot SDK pipeline, an open source server, and adjacent products for s…
  api_count: 4
  score_band: strong
  score_composite: 68.8
  shared: 3
- slug: heidi-health
  name: Heidi Health
  description: 'Heidi Health is a Melbourne, Australia-founded AI care partner for clinicians, founded in 2019 by Dr. Tom Kelly (CEO), Waleed Mussa (CFO), and Yu Liu (CTO). The product began as an ambient AI medical scribe and now spans four capability surfaces: Scribe (real-time clinical documentation from audio)…'
  api_count: 11
  score_band: developing
  score_composite: 55.0
  shared: 3
- slug: google-cloud-assured-workloads
  name: Google Cloud Assured Workloads
  description: Google Cloud Assured Workloads enables organizations to create and manage compliance-controlled environments on Google Cloud. It provides guardrails for regulatory compliance frameworks such as FedRAMP, HIPAA, CJIS, ITAR, and others by enforcing organizational policies, data residency requirements,…
  api_count: 1
  score_band: developing
  score_composite: 51.0
  shared: 3
- slug: vanta
  name: Vanta
  description: Vanta is a trust management platform that automates security compliance for frameworks including SOC 2, ISO 27001, HIPAA, PCI DSS, and GDPR. The Vanta API enables organizations to programmatically manage their compliance posture, automate security monitoring, manage vulnerabilities, track controls,…
  api_count: 2
  score_band: developing
  score_composite: 50.0
  shared: 3
- slug: formassembly
  name: FormAssembly
  description: FormAssembly is an enterprise form and data collection platform with a REST API for managing forms, exporting submission data, handling Salesforce integrations, and building compliant data collection workflows. The API supports OAuth2 authentication and enables programmatic access to forms, respons…
  api_count: 1
  score_band: developing
  score_composite: 45.8
  shared: 3
- slug: certn-com
  name: Certn
  description: Certn is a Canadian background screening platform headquartered in Victoria, British Columbia, providing fast, FCRA / SOC 2 Type II / ISO 27001 compliant background checks for employment, tenant, and partner screening across more than 195 countries. The Certn platform delivers criminal record check…
  api_count: 4
  score_band: minimal
  score_composite: 26.9
  shared: 3
- slug: drata
  name: Drata
  description: Drata is a continuous security and compliance automation platform supporting SOC 2, ISO 27001, HIPAA, PCI DSS, GDPR, and more, with policies, evidence, and trust center. Drata exposes a public REST API plus the SafeBase Trust API (acquired) and a Custom Connections framework for evidence collection.
  api_count: 4
  score_band: minimal
  score_composite: 25.4
  shared: 3
- slug: secureframe
  name: Secureframe
  description: Secureframe automates security and privacy compliance for SOC 2, ISO 27001, HIPAA, PCI DSS, GDPR, NIST, and more. The Secureframe Public API exposes controls, frameworks, evidence, tests, personnel, and vendor data.
  api_count: 1
  score_band: minimal
  score_composite: 18.4
  shared: 3
- slug: sprinto
  name: Sprinto
  description: Sprinto is a security and compliance automation platform supporting SOC 2, ISO 27001, HIPAA, GDPR, PCI DSS, and more. Sprinto offers an API for building custom compliance and risk workflows; specific public reference docs are limited and require a customer login.
  api_count: 1
  score_band: minimal
  score_composite: 17.2
  shared: 3
- slug: tugboat-logic
  name: Tugboat Logic
  description: Tugboat Logic is a security assurance and compliance automation platform acquired by OneTrust in 2021. It supports SOC 2, ISO 27001, HIPAA, GDPR, and NIST. As of 2024, the product has been rebranded under OneTrust's Certification Automation offering; legacy Tugboat Logic APIs are not publicly docum…
  api_count: 1
  score_band: minimal
  score_composite: 16.5
  shared: 3
- slug: tufin
  name: Tufin
  description: Tufin provides security policy orchestration solutions for managing network security policies across hybrid cloud environments, including firewalls, SDN, and cloud security controls. The Tufin Orchestration Suite (TOS) includes SecureTrack for network topology and policy analysis, SecureChange for…
  api_count: 5
  score_band: developing
  score_composite: 56.5
  shared: 2
- slug: google-cloud-security-command-center
  name: Google Cloud Security Command Center
  description: Google Cloud Security Command Center (SCC) is a security and risk management platform for Google Cloud that helps organizations identify misconfigurations, vulnerabilities, and threats across their cloud assets. It provides centralized visibility into cloud resources, security findings, and complia…
  api_count: 1
  score_band: developing
  score_composite: 51.0
  shared: 2
- slug: inkit
  name: Inkit
  description: Inkit is a Secure Document Generation (SDG) platform that enables organizations to generate, sign, store, and distribute documents in total privacy. The platform provides a REST API for rendering HTML templates into PDFs, automating document workflows, and managing digital signatures at scale. Inki…
  api_count: 1
  score_band: developing
  score_composite: 47.8
  shared: 2
- slug: ariba
  name: Ariba
  description: SAP Ariba provides cloud-based procurement and supply chain collaboration solutions. These APIs enable integration with Ariba's procurement, sourcing, contract management, and supplier management capabilities.
  api_count: 80
  score_band: developing
  score_composite: 47.0
  shared: 2
- slug: coalition-inc
  name: Coalition
  description: Coalition is a San Francisco–headquartered cyber insurance and active risk management provider founded in 2017 by Joshua Motta (CEO) and John Hering. Coalition pairs commercial insurance lines — Cyber, Technology Errors & Omissions, Executive Risks (D&O, EPL, Fiduciary, Crime), Miscellaneous Profes…
  api_count: 2
  score_band: thin
  score_composite: 41.1
  shared: 2
- slug: cybersecurity-and-infrastructure-security-agency
  name: Cybersecurity and Infrastructure Security Agency
  description: The Cybersecurity and Infrastructure Security Agency (CISA) is the United States federal civilian cybersecurity agency, part of the Department of Homeland Security. CISA reduces cybersecurity and physical security risk for the nation, coordinates federal civilian cyber defense, and partners with st…
  api_count: 3
  score_band: thin
  score_composite: 41.1
  shared: 2
- slug: simcorp-dimension
  name: SimCorp Dimension
  description: Investment management software solution providing APIs for portfolio management, accounting, risk management, and investment operations. SimCorp Dimension is part of the SimCorp One integrated platform, offering Web APIs, Data Distribution APIs, and Streaming APIs through the SimCorp Integration Mo…
  api_count: 6
  score_band: thin
  score_composite: 38.8
  shared: 2
- slug: regulatory
  name: Regulatory
  description: The regulatory domain encompasses compliance requirements, regulatory reporting, and governance frameworks that organizations must adhere to across industries. APIs in this space enable businesses to automate compliance workflows, track regulatory changes, submit required filings, and manage risk.…
  api_count: 4
  score_band: thin
  score_composite: 36.0
  shared: 2
- slug: daytona
  name: Daytona
  description: Daytona provides secure, elastic sandbox infrastructure for running AI-generated code, with sub-90ms sandbox creation, multi-language runtimes, and full filesystem, process, Git, and Language Server Protocol APIs. Sandboxes are stateful, snapshot-able, and deployable across US, EU, and Asia regions…
  api_count: 1
  score_band: thin
  score_composite: 33.1
  shared: 2
- slug: synthflow
  name: Synthflow
  description: Synthflow is an enterprise-ready no-code Voice AI platform for automating phone conversations at scale. The product combines a visual agent designer with in-house telephony, sub-100ms latency, and a 99.99% uptime guarantee, so businesses can build, deploy, and operate voice agents without third-par…
  api_count: 1
  score_band: thin
  score_composite: 32.4
  shared: 2
- slug: national-institute-of-standards-and-technology
  name: National Institute of Standards and Technology
  description: NIST promotes U.S. innovation and industrial competitiveness by advancing measurement science, standards, and technology in ways that enhance economic security and improve our quality of life. NIST operates the National Vulnerability Database (NVD), which provides public APIs for CVE, CVE change hi…
  api_count: 1
  score_band: thin
  score_composite: 31.6
  shared: 2
- slug: apigovernance-dev
  name: APIGovernance.Dev
  description: APIGovernance.Dev is an AI-powered API governance platform that enforces API best practices through automated reviews trained on 10,000 public APIs. It provides the API Governance Top-10 list of best practices, automated CI/CD integration, and tools to help organizations deliver consistent, industr…
  api_count: 1
  score_band: thin
  score_composite: 30.6
  shared: 2
related:
- slug: defense-in-depth
  name: Defense in Depth
  shared: 4
- slug: basel-compliance
  name: Basel Compliance
  shared: 2
- slug: convention-over-configuration
  name: Convention Over Configuration
  shared: 1
- slug: data-privacy-standards
  name: Data Privacy Standards
  shared: 1
- slug: data-quality-standards
  name: Data Quality Standards
  shared: 1
- slug: disclosure-requirements
  name: Disclosure Requirements
  shared: 1
repo: https://github.com/api-evangelist/cybersecurity-standards
overview: 'Cybersecurity Standards on the [APIs.io](https://apis.io/) network is a curated area collecting 10 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including Cybersecurity Standards, Regulatory Templates, Svix, Heidi Health, Google Cloud Assured Workloads, Vanta, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Defense in Depth, Basel Compliance, Convention Over Configuration, and Data Privacy Standards. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
