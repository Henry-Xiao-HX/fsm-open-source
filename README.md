# FSM Open Source Landscape

A community-maintained catalog of open-source contributions across the financial services industry.

## Overview

Financial services firms engage with open source in two distinct ways:

**Maintaining public repositories** — firms like JP Morgan Chase, Goldman Sachs, Morgan Stanley, Capital One, Visa, American Express, and PayPal actively publish and maintain first-party GitHub organizations with production-grade open-source projects. These range from design systems and data tooling to security scanners and payment SDKs.

**Participating in FINOS** — the [Fintech Open Source Foundation (FINOS)](https://www.finos.org/) is the primary industry foundation for collaborative open-source in financial services. Many institutions — including those with limited public GitHub activity — contribute through FINOS-hosted projects, working groups, and Special Interest Groups (SIGs). FINOS membership tiers (Platinum, Gold, Silver, Associate) reflect the depth of institutional commitment.

Some firms, such as Bank of America, Wells Fargo, State Street, and Vanguard, contribute predominantly at the foundation level rather than through standalone repositories.

### Most Relevant FINOS Projects

| Project | Lead Contributors | Description |
|---|---|---|
| [Legend](https://github.com/finos/legend) | Goldman Sachs, BofA, State Street | End-to-end data management and governance platform |
| [FDC3](https://github.com/finos/FDC3) | Citi, Morgan Stanley, Wells Fargo, PNC | Open standard for financial desktop interoperability |
| [Common Domain Model (CDM)](https://github.com/finos/common-domain-model) | DTCC, State Street, ISDA | Machine-readable data model for financial products and trades |
| [Common Cloud Controls (CCC)](https://github.com/finos/common-cloud-controls) | Citi, BofA, Wells Fargo | Consistent cyber controls taxonomy across public cloud providers |
| [Morphir](https://github.com/finos/morphir) | Morgan Stanley | Business logic modeling that compiles to multiple targets |
| [Perspective](https://github.com/finos/perspective) | JP Morgan Chase | High-performance streaming data visualization on WebAssembly |
| [CALM (Architecture as Code)](https://github.com/finos/architecture-as-code) | Prudential | Machine-readable architecture language and modeling standard |

---

## JP Morgan Chase

- [Perspective](https://github.com/finos/perspective) — High-performance streaming data visualization engine built on WebAssembly
- [Salt Design System](https://github.com/jpmorganchase/salt-ds) — Production design system providing accessible React components for financial applications
- [Jupyter FS](https://github.com/jpmorganchase/jupyter-fs) — JupyterLab file system extension for unified browsing across cloud and remote storage
- [nbcelltests](https://github.com/jpmorganchase/nbcelltests) — Cell-by-cell unit testing and linting framework for Jupyter Notebooks
- [Phantom](https://github.com/jpmorganchase/phantom) — Cryptographic engine and privacy-preserving computation framework
- [PADL](https://github.com/jpmorganchase/padl) — Pipeline Abstraction for Deep Learning
- [Regular Table](https://github.com/jpmorganchase/regular-table) — Virtual scrolling high-performance table web component
- [Fusion](https://github.com/jpmorganchase/fusion) — Federated data access and API layer for financial datasets
- [DataQuery SDK](https://github.com/jpmorganchase/dataquery-sdk) — Client SDK for querying structured financial data at scale

## Goldman Sachs

- [FINOS Legend](https://github.com/finos/legend) — End-to-end data management and governance platform
- [gs-quant](https://github.com/goldmansachs/gs-quant) — Python toolkit for quantitative finance and portfolio risk management (~13k stars)
- [Reladomo](https://github.com/goldmansachs/reladomo) — Enterprise ORM framework with temporal querying and high-concurrency support
- [Obevo](https://github.com/goldmansachs/obevo) — Database deployment and migration tool for enterprise DBMS architectures
- [jDMN](https://github.com/goldmansachs/jdmn) — Decision Model and Notation (DMN) implementation for financial business rules
- [Eclipse Collections](https://github.com/eclipse/eclipse-collections) — High-performance Java collections framework (donated to Eclipse Foundation)

## Morgan Stanley

- [Testplan](https://github.com/morganstanley/testplan) — Enterprise multi-tier integration and performance testing framework
- [Morphir](https://github.com/finos/morphir) — Business logic modeling tool that compiles to multiple targets
- [Hobbes](https://github.com/morganstanley/hobbes) — High-performance in-process memory allocator and query engine for C++ (~1.2k stars)
- [Xpedite](https://github.com/morganstanley/Xpedite) — Ultra-low-latency profiling and performance analysis tool
- [ComposeUI](https://github.com/morganstanley/ComposeUI) — Desktop application integration and interoperability framework
- [MSML](https://github.com/morganstanley/MSML) — Machine learning library for quantitative research and time series modeling
- Open Resource Broker — HPC cluster orchestration broker for large-scale financial compute jobs *(repo not publicly available)*
- [FDC3 Web](https://github.com/morganstanley/fdc3-web) — Web implementation of the FDC3 financial desktop interoperability standard

## CitiGroup

- [FINOS FDC3](https://github.com/finos/FDC3) — Open standard for financial desktop interoperability
- [Common Cloud Controls (CCC)](https://github.com/finos/common-cloud-controls) — Consistent taxonomy and cyber controls across public cloud providers
- [Citi OSPO Program & Tools](https://github.com/Citi/citi-ospo) — Open Source Program Office policies and compliance tooling
- [OQC-PINN](https://github.com/citi/oqc-pinn) — Quantum physics-informed neural networks and quantum computing exploration

## American Express

- [Jest Image Snapshot](https://github.com/americanexpress/jest-image-snapshot) — Visual regression testing plugin for Jest (~3.9k stars)
- [EarlyBird](https://github.com/americanexpress/earlybird) — High-throughput secret scanning tool for source code repositories (~700 stars)
- [Synapse](https://github.com/americanexpress/synapse) — Lightweight Java messaging and API orchestration framework
- [React Albus](https://github.com/americanexpress/react-albus) — Declarative component library for building multi-step forms and checkout funnels
- [SimpleMli](https://github.com/americanexpress/simplemli) — Lightweight machine-learning inference framework
- [Jest JSON Schema](https://github.com/americanexpress/jest-json-schema) — JSON Schema matcher for Jest test assertions
- [Fetchye](https://github.com/americanexpress/fetchye) — React data-fetching hook with caching and suspense support

## Capital One

- [VulnHunter](https://github.com/capitalone/vulnhunter) — AI agentic vulnerability remediation and automated code security analysis (~1k stars)
- [DataProfiler](https://github.com/capitalone/DataProfiler) — ML-powered library to profile and detect sensitive data types in datasets (~1.6k stars)
- [DataComPy](https://github.com/capitalone/datacompy) — Pandas and Spark dataframe comparison tool for regression testing data pipelines (~650 stars)
- [Rubicon ML](https://github.com/capitalone/rubicon-ml) — Logging and reproducibility framework for model training workflows
- [Stratum Observability](https://github.com/capitalone/Stratum-Observability) — Distributed systems tracing and telemetry for high-throughput microservices
- [Locopy](https://github.com/capitalone/locopy) — Python library for loading and unloading data to Amazon Redshift and Snowflake
- [Edgetest](https://github.com/capitalone/edgetest) — Automated dependency upgrade compatibility testing tool

## Mastercard International

- [Terraform Provider REST API](https://github.com/Mastercard/terraform-provider-restapi) — Terraform provider for declarative IaC management of RESTful APIs
- [PKCS#11 Tools](https://github.com/Mastercard/pkcs11-tools) — HSM management and PKCS#11 cryptographic integration toolkit
- [Client Encryption Java](https://github.com/Mastercard/client-encryption-java) — Cryptographic payload encryption library supporting JWE/JWS
- [Developers Agent Toolkit](https://github.com/Mastercard/developers-agent-toolkit) — AI agent toolkit for building financial assistants using Mastercard APIs
- [Open Banking US OpenAPI](https://github.com/Mastercard/open-banking-us-openapi) — OpenAPI specification for Mastercard Open Banking in the United States
- [OAuth2 Client Java](https://github.com/Mastercard/oauth1-signer-java) — OAuth 1.0a signing library for Mastercard API authentication
- [Flow](https://github.com/Mastercard/flow) — Structured interaction testing framework for distributed systems

## PayPal

- [PayPal JS](https://github.com/paypal/paypal-js) — Official JavaScript client SDK loader for PayPal Checkout and payment methods
- [PayPal Checkout Components](https://github.com/paypal/paypal-checkout-components) — Cross-framework web component library for payment flows and smart buttons
- [PayPal Server SDKs](https://github.com/paypal/PayPal-TypeScript-Server-SDK) — Multi-language backend SDKs for processing orders, authorizations, and webhooks
- [PayPal REST API Specifications](https://github.com/paypal/paypal-rest-api-specifications) — OpenAPI specifications for all PayPal REST APIs
- [PayPal Android SDK](https://github.com/paypal/paypal-android) — Native Android SDK for in-app payment flows
- [PayPal iOS SDK](https://github.com/paypal/paypal-ios) — Native iOS SDK for in-app payment flows

## Visa

- [Visa Vulnerability Agentic Harness (VVAH)](https://github.com/visa/visa-vulnerability-agentic-harness) — Agentic security scanner and vulnerability remediation test harness
- [Trusted Agent Protocol](https://github.com/visa/trusted-agent-protocol) — Open protocol standard for verified autonomous agent commerce
- [Visa Chart Components (VCC)](https://github.com/visa/visa-chart-components) — Accessible, internationalized data visualization library
- [Nova React](https://github.com/visa/nova-react) — Core React component library and accessibility framework
- [Nova Angular](https://github.com/visa/nova-angular) — Angular component library aligned to Visa design system

## Jack Henry

- [Kafka4s](https://github.com/banno/kafka4s) — Functional Scala client and streaming toolkit for Apache Kafka
- [Jack Henry Design System](https://github.com/Banno/jack-henry-design-system) — Accessible web components for digital banking and member onboarding
- [Vault4s](https://github.com/banno/vault4s) — Pure-functional Scala library for HashiCorp Vault secrets management
- [Web Component Router](https://github.com/Banno/web-component-router) — Client-side routing library for web component applications
- [Gordon](https://github.com/Banno/Gordon) — Developer tooling and scaffolding utilities for community-bank platforms

## GEICO

- [TuxTape](https://github.com/geico/tuxtape) — Linux kernel live-patching and memory introspection utility
- [TuxWrangler](https://github.com/geico/tuxwrangler) — Automated Linux OS provisioning and configuration orchestration agent
- [Cassandra SQL](https://github.com/geico/cassandra-sql) — SQL query layer and analytics tooling for Apache Cassandra

## Global Payments

- [Global Payments Java SDK](https://github.com/globalpayments/java-sdk) — Java payment processing SDK for card acceptance and tokenization
- [Global Payments PHP SDK](https://github.com/globalpayments/php-sdk) — PHP SDK for multi-channel payment processing and device integration
- [Global Payments Node SDK](https://github.com/globalpayments/node-sdk) — Node.js SDK for payment processing and gateway integration
- [Global Payments .NET SDK](https://github.com/globalpayments/dotnet-sdk) — .NET SDK for payment acceptance and e-commerce integration
- [GlobalPayments.js](https://github.com/globalpayments/globalpayments-js) — Browser-side JavaScript library for secure card capture and tokenization

## Worldpay

- [Worldpay Access Checkout SDKs](https://github.com/Worldpay/access-checkout-android) — Mobile and server SDKs for e-commerce checkout and 3DS authentication
- [Worldpay Magento 2](https://github.com/Worldpay/Worldpay-Magento2-CG) — Payment integration plugin for Magento 2 commerce platforms
- [CNP SDK for Java](https://github.com/Worldpay/cnp-sdk-for-java) — Card-not-present transaction processing SDK for Java
- [PayFac MP SDK .NET](https://github.com/Worldpay/payfac-mp-sdk-dotnet) — Payment facilitator merchant provisioning SDK for .NET

## Fiserv

- [Fiserv Tap to Pay SDKs](https://github.com/Fiserv/ch-ttp-androidsdk) — Contactless payment acceptance SDKs for Android and iOS

## State Farm

- CLAWS — Command Line AWS security and IAM credential management utility *(repo not publicly available)*
- TheThingStore — Distributed configuration and metadata key-value store for cloud automation *(repo not publicly available)*
- [Terratest Helpers](https://github.com/StateFarmIns/terratest-helpers) — Reusable Go testing helpers for Terraform infrastructure validation
- [Terraform AWS Default Log Retention](https://github.com/StateFarmIns/terraform-aws-default-log-retention) — Terraform module enforcing CloudWatch log retention policies

## Progressive

- [Kherkin](https://github.com/Progressive-Insurance/kherkin) — Kotlin-native BDD Gherkin test automation library for mobile and API testing
- [Need CLA](https://github.com/Progressive-Insurance/need-cla) — GitHub Action for managing Contributor License Agreements
- [Oculr Ngx](https://github.com/Progressive-Insurance/oculr-ngx) — Angular analytics and event-tracking instrumentation library
- [Log Data Contracts](https://github.com/Progressive-Insurance/log-data-contracts) — Schema definitions and contracts for structured application logging

## USAA

- [Vogel](https://github.com/usaa/vogel) — Actuarial machine learning and risk-modeling algorithms
- [Sonar Quality Gates](https://github.com/USAA/sonar-quality-gates) — SonarQube quality gate enforcement plugin for CI pipelines
- [Reactive DB Bridge](https://github.com/USAA/reactive-db-bridge) — Reactive Streams bridge for blocking JDBC database drivers
- [Powerup Assemblyline](https://github.com/USAA/powerup-assemblyline) — Automated pipeline orchestration and configuration assembly utility

## Northwestern Mutual

- [Grammes](https://github.com/northwesternmutual/grammes) — Gremlin graph database driver for Go
- [Regent](https://github.com/northwesternmutual/regent) — Lightweight declarative business rules evaluation engine

## BNY Mellon

- BNY Data on Chain — Framework for publishing financial asset reference data to blockchain networks *(repo not publicly available)*

## Fidelity

- Virgil — Infrastructure automation and developer environment orchestrator *(repo not publicly available)*

## Experian

- Experian Address Validation SDKs — Data validation and real-time postal address cleansing libraries *(repo not publicly available)*

## Automatic Data Processing (ADP)

- Reportizer — Automated payroll and benefits report aggregation and validation utility *(repo not publicly available)*

## The Travelers Companies

- [KubUI](https://github.com/travelers/kubui) — Lightweight Kubernetes cluster management interface and UI dashboard

## Bank of America

> **Note:** Bank of America is a **FINOS Platinum member** (the highest membership tier), giving them a significant open-source foundation footprint that is not fully reflected by first-party GitHub organization activity alone.

- [FINOS Common Cloud Controls (CCC)](https://github.com/finos/common-cloud-controls) — Co-contributor to the industry taxonomy and cyber controls standard for public cloud providers
- [FINOS Legend](https://github.com/finos/legend) — Contributor to the end-to-end data management and governance platform; BofA engineers are listed among Legend committers
- [FINOS FDC3](https://github.com/finos/FDC3) — Participant in the FDC3 desktop interoperability standard working group
- [FINOS Symphony](https://github.com/finos/symphony-wdk) — Founding contributor to the Symphony messaging platform ecosystem before it became independently governed
- FINOS Working Groups — Active participant in multiple FINOS Special Interest Groups (SIGs) including the Open Financial Data SIG and the Innersource SIG

## Wells Fargo

> **Note:** Wells Fargo is a **FINOS member** with documented participation in multiple FINOS working groups. Their direct GitHub org (`github.com/WellsFargo`) has historically had limited public repositories.

- [FINOS FDC3](https://github.com/finos/FDC3) — Participant in the FDC3 desktop interoperability standard working group
- [FINOS Legend](https://github.com/finos/legend) — Contributor to the Legend data management platform
- [FINOS Common Cloud Controls (CCC)](https://github.com/finos/common-cloud-controls) — Participant in the cloud controls taxonomy working group
- FINOS Open Financial Data SIG — Active member of the Open Financial Data Special Interest Group

## State Street

> **Note:** State Street is a **FINOS member** and active participant in multiple financial industry open-source initiatives. Their contribution footprint is primarily through foundation-level projects rather than a standalone GitHub organization.

- [FINOS Common Domain Model (CDM)](https://github.com/finos/common-domain-model) — Co-contributor to the industry-standard machine-readable data model for financial products and trades
- [FINOS Legend](https://github.com/finos/legend) — Contributor to the Legend data governance platform
- [FINOS Open Financial Data SIG](https://github.com/finos/open-financial-data) — Active participant in the Open Financial Data Special Interest Group
- FINOS Innersource SIG — Participant in innersource best-practices working group

## Northern Trust

> **Note:** Northern Trust operates a confirmed GitHub organization at [`NorthernTrustOpen`](https://github.com/NorthernTrustOpen) and is a **FINOS member** with documented working group participation.

- [NorthernTrustOpen GitHub Org](https://github.com/NorthernTrustOpen) — Confirmed first-party GitHub organization publishing open-source tooling
- [FINOS Open Financial Data SIG](https://github.com/finos/open-financial-data) — Active participant in the Open Financial Data Special Interest Group
- FINOS Working Groups — Participant in FINOS compliance and regulatory reporting working groups

## MetLife

> **Note:** MetLife operates a confirmed GitHub organization at [`github.com/MetLife`](https://github.com/MetLife) with active public repositories.

- [Banzai Pipeline Operator](https://github.com/MetLife/banzai-pipeline-operator) — Kubernetes operator for CI/CD pipeline management built on the Banzai Cloud stack
- [MetLife GitHub Org](https://github.com/MetLife) — Confirmed first-party GitHub organization with multiple public infrastructure and tooling repositories

## Allstate

> **Note:** Allstate operates a confirmed GitHub organization at [`github.com/allstate`](https://github.com/allstate) with public repositories, primarily focused on internal developer tooling.

- [Haystack](https://github.com/ExpediaDotCom/haystack) — Distributed tracing and anomaly detection platform (Allstate engineers are known upstream contributors)
- [Allstate GitHub Org](https://github.com/allstate) — Confirmed first-party GitHub organization with public tooling repositories

## Charles Schwab

> **Note:** Charles Schwab is a **FINOS associate member** with participation in financial industry open-source working groups. Direct first-party GitHub presence is limited.

- FINOS Working Groups — Associate-level FINOS membership with participation in compliance and data working groups
- Linux Foundation — Participant in Linux Foundation financial services initiatives

## PNC Financial Services

> **Note:** PNC is a **FINOS member** with documented participation in FINOS working groups. A first-party GitHub org exists but public repository activity is minimal.

- [FINOS FDC3](https://github.com/finos/FDC3) — Participant in the FDC3 desktop interoperability working group
- FINOS Working Groups — Member-level participation in FINOS regulatory reporting and open data SIGs

## Intercontinental Exchange (ICE) / NYSE

> **Note:** ICE/NYSE is a **FINOS member** and participates in financial data standards bodies. Their open-source footprint is concentrated in financial data standards work rather than direct GitHub org activity.

- [FINOS Financial Objects SIG](https://github.com/finos/financial-objects) — Participant in the Financial Objects Special Interest Group for standardizing financial instrument representations
- [FINOS Open Financial Data SIG](https://github.com/finos/open-financial-data) — Contributor to market data standardization efforts
- FIX Protocol / FDC3 Standards — Active participant in financial industry connectivity standards bodies

## The Vanguard Group

> **Note:** Vanguard is a **FINOS member** with documented participation in open-source financial data and compliance working groups. Their primary contribution channel is foundation-level rather than first-party GitHub activity.

- FINOS Open Financial Data SIG — Participant in open financial data standardization
- FINOS Working Groups — Member-level participation in compliance and regulatory reporting working groups

## TIAA

> **Note:** TIAA (Teachers Insurance and Annuity Association) is a **FINOS member** and participates in multiple FINOS Special Interest Groups focused on financial data and regulatory standards.

- FINOS Open Financial Data SIG — Active participant in the Open Financial Data Special Interest Group
- FINOS Working Groups — Member-level participation in regulatory compliance and data standardization working groups

## Nationwide

> **Note:** Nationwide operates a GitHub organization at [`github.com/nationwide`](https://github.com/nationwide) with some public repositories. Foundation-level membership is not confirmed at the Platinum/Gold tier.

- [Nationwide GitHub Org](https://github.com/nationwide) — First-party GitHub organization with limited public repository activity in developer tooling

## Truist

> **Note:** Truist (formed from the BB&T and SunTrust merger) has a small verified GitHub presence. Foundation-level open-source participation is in early stages relative to the institution's size.

- [Truist GitHub Org](https://github.com/Truist) — Confirmed first-party GitHub organization; currently minimal public repository activity
- Linux Foundation — Participant observer in Linux Foundation financial services working groups

## FIS (Fidelity Information Services)

> **Note:** FIS (not to be conflated with Fidelity Investments or Fidelity International) operates a GitHub organization and has made open-source contributions primarily in payments and banking infrastructure tooling.

- FIS GitHub Org — Note: FIS and Fiserv are distinct companies and should not be conflated; FIS has a limited public GitHub presence under `github.com/FIS-Global` for select developer tooling
- Payments industry standards — Participant in ISO 20022 and Open Banking API standards bodies

## Depository Trust & Clearing (DTCC)

- [Common Domain Model (CDM)](https://github.com/finos/common-domain-model) — Industry-standard machine-readable data model for financial products and trades

> **Note:** DTCC's broader foundation and standards contributions (FINOS, ISO 20022) may exceed their direct GitHub footprint. This entry reflects the CDM project co-stewardship.

## Prudential

- [FINOS CALM](https://github.com/finos/architecture-as-code) — Common Architecture Language and Modeling standard for machine-readable architecture diagrams

---

## No Verified Public Open-Source Footprint

For the following financial service entities, no substantial, verifiable first-party GitHub presence or foundation membership was identified in current research. This does not indicate an absence of open-source consumption or upstream contribution — many institutions contribute through internal InnerSource programs, upstream committer activity to Apache/CNCF projects, or participation in proprietary consortium arrangements not visible in public records.

| Financial Service Entity | Research Note |
|---|---|
| Aegon / TransAmerica | No verified first-party org; apparent `aegonplatform` GitHub result is unrelated to the insurer |
| Ameriprise | No verified first-party footprint; no confirmed FINOS or Linux Foundation membership identified |
| Auto-Owners Insurance | No verified first-party footprint; private mutual insurer with no known public OSS program |
| Unum Group | No verified footprint; prominent `unum-cloud` GitHub org is a separate, unrelated AI company |
| Westfield | No verified first-party footprint; regional P&C insurer with no known public OSS presence |
| Alight | No public repositories; corporate ownership of apparent GitHub account unverified |
| Comerica / Fifth Third | Comerica account has no public repos; Fifth Third GitHub result was confirmed third-party |
| Federal Home Loan | Entity is ambiguous — the FHLBank system comprises 11 independent regional banks; no consolidated OSS footprint |
| FNBO (First National Bank of Omaha) | No verified first-party footprint; private bank with no confirmed public GitHub or foundation membership |
| Huntington National Bank | No confirmed public GitHub activity; no verified FINOS or Linux Foundation membership |
| KeyBank | No confirmed public GitHub activity; no verified foundation membership identified |
| US Bank (U.S. Bancorp) | No verified first-party GitHub repositories; no confirmed FINOS membership identified |
| US Federal Reserve Board (FRB) | The FRB publishes economic research tools (e.g. FRB/US model) but no consolidated corporate OSS org; FRED API client repos are third-party |
| Zions Bank | Obvious `zions` GitHub account is not established as the corporate banking entity |
| Navy Federal Credit Union | No verified first-party footprint; member-owned credit union with no known public OSS program |
| First Citizens BancShares | No verified first-party footprint; growth via acquisition (SVB assets) has not produced a public OSS presence |
| M&T Bank | No verified first-party footprint; no confirmed foundation membership identified |
| Regions Financial | No confirmed public GitHub activity; no verified FINOS or Linux Foundation membership |
| American International Group (AIG) | No verified first-party footprint; no confirmed FINOS or Linux Foundation membership identified |
| Brown Brothers Harriman | No verified first-party footprint; private partnership structure limits public OSS program visibility |
| Chubb | Obvious `chubb` GitHub user appears unrelated to the global insurer |
| Hanover Insurance | No verified first-party footprint; regional commercial insurer with no known public OSS program |
| New York Life Insurance | No confirmed public GitHub activity; mutual insurer structure limits public OSS visibility |

---

*For institutions marked above, the recommended next step is foundation-level diligence: FINOS participant lists, Linux Foundation member projects, Apache committer domains, CNCF maintainer records, and OpenSSF working groups. Many large banks and insurers contribute significantly through these channels without maintaining prominent first-party GitHub organizations.*
