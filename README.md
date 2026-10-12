# Awesome-Cloud-Business-Intelligence
# Awesome-Cloud-Business-Intelligence

# Awesome-Cloud-Business-Intelligence

# Top Cloud Business Intelligence Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Business Intelligence, Data Visualization & Self-Service Analytics*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Business Intelligence**. These tools help organizations connect to data sources, build interactive dashboards, perform ad-hoc analysis, and embed analytics into applications — enabling data-driven decision-making at scale.

**Examples** include Salesforce Analytics Cloud, Tableau Cloud, Microsoft Power BI, Looker, Domo, Sisense, Qlik Sense, ThoughtSpot, GoodData, and Sigma Computing (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom semantic layers, and open analytics pipelines — ideal for organizations seeking transparent, vendor-independent business intelligence.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Analytics Cloud (Tableau)](https://www.salesforce.com/analytics/)**  
  Salesforce's BI platform powered by Tableau. Provides AI-powered insights, dashboards, and data exploration directly integrated with Salesforce CRM data.

- **[Tableau Cloud](https://www.tableau.com/products/cloud-bi)**  
  Fully hosted analytics platform with Tableau Agent and Tableau Pulse. Features AI-powered insights delivered to Slack, Teams, and email, plus Tableau Bridge for hybrid data connectivity .

- **[Microsoft Power BI](https://powerbi.microsoft.com/)**  
  Microsoft's business analytics platform integrated with Microsoft Fabric. Features Power BI Desktop for authoring, Copilot AI assistance, and Direct Lake mode for querying OneLake without data import.

- **[Looker (Google Cloud)](https://looker.com/)**  
  Google Cloud's enterprise BI platform built on LookML, a code-based semantic modeling language. Features Git integration for version control, embedded analytics, and API-driven customization .

- **[Domo](https://www.domo.com/)**  
  Cloud-native BI and data product platform with 1,000+ connectors. Named a Leader in the 2026 Nucleus Research Value Matrix for its comprehensive functionality and usability .

- **[Qlik Sense](https://www.qlik.com/)**  
  Associative analytics platform with Qlik Sense Enterprise and Qlik Cloud Analytics. Features self-service visualization, guided analytics, and embedded analytics with open APIs .

- **[Sisense](https://www.sisense.com/)**  
  BI and analytics platform for embedded analytics. Features ElastiCube for in-memory data blending and AI-powered predictive analytics.

- **[ThoughtSpot](https://www.thoughtspot.com/)**  
  Agentic analytics platform with Spotter AI agent. Features natural language search, embedded analytics via SDK/API/MCP, and unified structured and unstructured data analysis .

- **[GoodData](https://www.gooddata.com/)**  
  Composable analytics platform with Analytics Lake infrastructure. Features Apache Iceberg and DuckDB integration, FlexConnect for custom data connectors, and multi-tenant workspace isolation.

- **[Sigma Computing](https://www.sigmacomputing.com/)**  
  Cloud-native analytics platform sitting on top of Snowflake, Databricks, and BigQuery. Features spreadsheet-like interface for business users, warehouse-native governance, and Sigma Agents for autonomous workflows .

## Open-Source GitHub Projects

- **[Apache Superset](https://github.com/apache/superset)**  
  Modern, enterprise-ready BI web application (Apache-2.0). No-code chart builder, SQL Editor, lightweight semantic layer, and support for nearly any SQL database. 40+ visualization types with a plugin-based architecture. One of the most widely adopted open-source BI platforms with 74,000+ GitHub stars .

- **[Metabase](https://github.com/metabase/metabase)**  
  Easy-to-use open-source BI tool (AGPL-3.0) for self-service analytics. Features Query Builder for non-SQL users, Metabot AI assistant, interactive dashboards, and granular permissions. Written in Clojure and runs as a single JAR file. The most popular open-source BI tool by GitHub stars, ideal for teams where non-technical users need to answer their own data questions .

- **[Redash](https://github.com/getredash/redash)**  
  Open-source data visualization and dashboarding tool (BSD-2-Clause). Query editor with schema browser, drag-and-drop visualizations, scheduled refreshes, alerts, and REST API. 28,000+ GitHub stars. Note: Acquired by Databricks in 2020, the project has had no major release since v10 (late 2021), so long-term maintenance is uncertain .

- **[Lightdash](https://github.com/lightdash/lightdash)**  
  Open-source BI tool built for dbt users (MIT). Transforms dbt models into explorable dashboards, metrics, and self-service analytics. Metrics and dimensions defined in YAML alongside dbt project, version-controlled in Git. Features CI/CD workflows for BI content and natural language query interface .

- **[Knowage](https://github.com/KnowageLabs/Knowage-Server)**  
  Full open-source suite for Business Intelligence and Analytics (AGPL-3.0) by Engineering Group. Modules include Enterprise Reporting, Smart Intelligence for self-service BI, Location Intelligence, Performance Management with KPIs, and Custom Analytics with R/Python integration. Rated 8.5/10 by LinuxLinks .

- **[Grafana](https://github.com/grafana/grafana)**  
  Open-source observability and analytics platform (AGPL-3.0). While primarily for monitoring, widely used for BI dashboards with support for SQL databases, Prometheus, and multiple data sources. Production-grade alerting and massive plugin ecosystem. 77,000+ GitHub stars .

- **[Cube.js](https://github.com/cube-js/cube)**  
  Open-source semantic layer (Apache-2.0) for building data applications. Provides headless BI infrastructure with SQL generation, caching, and API for custom analytics frontends. Serves as a universal semantic layer connecting data sources to analytics tools .

- **[DataEase](https://github.com/dataease/dataease)**  
  Open-source data visualization and analysis tool (Chinese origin, GPL-3.0). Connects to MySQL, Oracle, SQL Server, PostgreSQL, Excel, and more. Drag-and-drop interface for building visualizations without code. 13,000+ GitHub stars .

### Additional Strong Open-Source Options

- **[Trino](https://github.com/trinodb/trino)** — Distributed SQL query engine for analytics on data lakes .
- **[ClickHouse](https://github.com/ClickHouse/ClickHouse)** — Column-oriented OLAP database for real-time analytics.
- **[Apache Druid](https://github.com/apache/druid)** — Real-time analytics database for sub-second queries on streaming and batch data.
- **[Evidence](https://github.com/evidence-dev/evidence)** — Markdown-based BI where reports are `.md` files with SQL code blocks, version-controlled in Git .
- Community **dbt** packages for semantic modeling and **Streamlit** apps for custom analytics.

**Frameworks for building custom systems**: Combine **Apache Superset** or **Metabase** as the BI frontend with **Cube.js** for semantic modeling, **ClickHouse** or **Trino** for high-performance queries, **dbt** for data transformation, and **PostgreSQL** for metadata — creating a fully self-hosted, enterprise-grade BI stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Analytics data must comply with data protection regulations (GDPR, CCPA, HIPAA, etc.).
- Self-hosted open-source solutions require proper security hardening, resource provisioning, and ongoing maintenance. Budget for operational costs including upgrades, security patching, and backup management .

---

**Made for data teams, analysts, engineers, and developers building transparent analytics solutions.**  
Let's make cloud business intelligence more open, data-driven, and accessible.
