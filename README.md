# Awesome AI-Powered Executive Dashboards

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[日本語版はこちら / Japanese](README.ja.md)

A curated list of useful **AI-powered executive dashboards**, BI copilots, decision-intelligence platforms, open-source analytics stacks, KPI frameworks, and related tools — for leaders, FP&A, people analytics, and data teams who need governed metrics and actionable insights (not vaporware demos).

## Contents

- [AI BI platforms & copilots](#ai-bi-platforms--copilots)
- [Open-source dashboards & analytics](#open-source-dashboards--analytics)
- [Metrics layers & semantic models](#metrics-layers--semantic-models)
- [People analytics & HCM](#people-analytics--hcm)
- [Fraud & anomaly detection](#fraud--anomaly-detection)
- [Process intelligence & digital twins](#process-intelligence--digital-twins)
- [FP&A & enterprise planning](#fpa--enterprise-planning)
- [KPI frameworks & decision intelligence](#kpi-frameworks--decision-intelligence)
- [Reading & reports](#reading--reports)
- [Contributing](#contributing)

---

## AI BI platforms & copilots

Enterprise BI and analytics products with natural-language Q&A, generative report help, proactive metric digests, or agentic insights grounded in governed models.

- [Microsoft Power BI Copilot](https://learn.microsoft.com/en-us/power-bi/create-reports/copilot-introduction) - Generative AI in Power BI / Fabric for chat-with-data, report summaries, narrative visuals, and DAX assistance (capacity + admin enablement required).
- [Tableau Pulse](https://www.tableau.com/products/tableau-pulse) - Personalized, AI-driven metric insights and digests (Slack, email, Teams, mobile) on a governed metrics layer; included with Tableau Cloud.
- [ThoughtSpot Spotter](https://www.thoughtspot.com/product/spotter) - Search- and agent-first analytics: natural-language questions mapped to a governed semantic layer with verifiable queries.
- [Looker Conversational Analytics (Gemini)](https://docs.cloud.google.com/looker/docs/conversational-analytics-overview) - Natural-language exploration grounded in LookML semantic models for consistent metric answers.
- [Qlik Answers](https://www.qlik.com/us/products/qlik-answers) - Agentic assistant over Qlik analytics (and unstructured knowledge bases) with explainability and citations.
- [Omni Analytics](https://omni.co/) - Modern BI with a governed semantic layer and AI-assisted querying for shared metric definitions.
- [Domo](https://www.domo.com/) - Cloud BI / dashboard platform with AI features for exploration and operational reporting.
- [Zoho Analytics (Ask Zia)](https://www.zoho.com/analytics/) - SME-friendly BI with natural-language asking and automated insights.

---

## Open-source dashboards & analytics

Self-hostable or open-core tools for executive and operational dashboards; prefer official docs / project sites.

- [Apache Superset](https://superset.apache.org/) - Apache-2.0 data exploration and dashboard platform (SQL Lab, 40+ viz types, semantic datasets). ([GitHub](https://github.com/apache/superset))
- [Metabase](https://www.metabase.com/) - Approachable open-source BI with dashboards, alerts, embedding, and AI querying (Metabot); self-host or Cloud. ([GitHub](https://github.com/metabase/metabase))
- [Lightdash](https://www.lightdash.com/) - Agentic / dbt-native BI: governed metrics and dashboards shipped through Git, CLI, and MCP. ([GitHub](https://github.com/lightdash/lightdash))
- [Evidence](https://evidence.dev/) - Code-first, SQL + Markdown reporting that builds static, shareable data apps. ([GitHub](https://github.com/evidence-dev/evidence))
- [Grafana](https://grafana.com/oss/grafana/) - Open observability and dashboarding stack; useful for real-time operational / IoT executive views. ([GitHub](https://github.com/grafana/grafana))
- [Redash](https://redash.io/) - SQL-to-visualization and dashboard sharing (community-maintained lineage). ([GitHub](https://github.com/getredash/redash))

---

## Metrics layers & semantic models

Governed metric definitions are what make AI copilots trustworthy for executives — define once, query everywhere.

- [dbt Semantic Layer / MetricFlow](https://docs.getdbt.com/docs/build/about-metricflow) - Define metrics in YAML; MetricFlow generates consistent SQL across tools and consumers.
- [LookML](https://cloud.google.com/looker/docs/what-is-lookml) - Looker's modeling language: dimensions, measures, and explores as the source of truth for Conversational Analytics.
- [Microsoft Power BI semantic models](https://learn.microsoft.com/en-us/power-bi/connect-data/service-datasets-understand) - Shared models (and AI preparation guidance) that Copilot and reports query consistently.
- [Cube](https://cube.dev/) - Headless semantic layer / metrics API for embedding analytics in apps and AI agents. ([GitHub](https://github.com/cube-js/cube))

---

## People analytics & HCM

Workforce metrics, org design, and people risk as executive dashboard inputs.

- [Visier](https://www.visier.com/) - People analytics platform with AI-assisted workforce insights and planning.
- [Workday](https://www.workday.com/) - Cloud HCM with embedded analytics and predictive people insights.
- [ChartHop](https://www.charthop.com/) - Org charts, headcount planning, and workforce analytics for people leaders.
- [Lattice](https://lattice.com/) - Performance, engagement, and people data often rolled into leadership scorecards.

---

## Fraud & anomaly detection

ML / AI systems that feed risk and integrity signals into executive and control dashboards.

- [Fraud.net](https://www.fraud.net/) - AI platform for real-time fraud and risk detection across transactions and accounts.
- [Sumsub Anomaly Detection](https://docs.sumsub.com/docs/ai-powered-anomaly-detection) - Identity / KYC-oriented AI anomaly detection in verification flows.
- [Feedzai](https://www.feedzai.com/) - Enterprise AI for financial crime and fraud risk scoring (banking / payments).
- [Glassbox](https://www.glassbox.com/) - Digital experience analytics with anomaly detection (acquired Anodot's business monitoring tech).

---

## Process intelligence & digital twins

Process mining, simulation, and twin-style views that explain *why* operational KPIs moved.

- [Celonis](https://www.celonis.com/) - Process mining / process intelligence platform for discovering bottlenecks and automation opportunities.
- [iGrafx Process360 Live](https://www.igrafx.com/) - Process digital twin and BPM platform for modeling, simulation, and continuous improvement.
- [Simio](https://www.simio.com/) - Discrete-event simulation and digital-shadow style operational models.
- [AVEVA Digital Twin](https://www.aveva.com/en/solutions/digital-transformation/digital-twin/) - Industrial digital twin integrating engineering, operations, and performance data.
- [Skan AI](https://www.skan.ai/) - Process discovery / intelligence from desktop and system activity (task mining lineage).

---

## FP&A & enterprise planning

Planning, forecasting, and scenario tools that back board and executive financial dashboards.

- [Anaplan](https://www.anaplan.com/) - Connected planning platform with ML-assisted forecasting and scenario modeling.
- [Workday Adaptive Planning](https://www.workday.com/en-us/products/adaptive-planning/overview.html) - Cloud FP&A with AI-assisted forecasting and what-if planning.
- [Vena](https://www.venasolutions.com/) - Excel-native FP&A with AI-assisted planning workflows.
- [IBM Planning Analytics](https://www.ibm.com/products/planning-analytics) - TM1-based planning and AI forecasting for enterprise FP&A.
- [Pigment](https://www.pigment.com/) - Modern business planning platform used for finance and operational scenarios.

---

## KPI frameworks & decision intelligence

How to choose and structure the 5–12 metrics executives actually use — independent of any vendor UI.

- [Balanced Scorecard Institute](https://balancedscorecard.org/) - Classic strategy-map / BSC methodology for balanced financial and non-financial KPIs.
- [OKR resources (WhatMatters / Google re:Work)](https://rework.withgoogle.com/intl/en/guides/set-goals-with-okrs/) - Practical OKR guidance for pairing outcome goals with ongoing KPI monitoring.
- [ClearPoint — Executive dashboard examples](https://www.clearpointstrategy.com/blog/executive-dashboard-examples) - Practical patterns: few metrics, each with owner, target, trend, and decision context.
- [Decision Intelligence (Gartner glossary)](https://www.gartner.com/en/information-technology/glossary/decision-intelligence) - Framing for connecting data, analytics, and decision workflows (vendor-neutral glossary entry).

---

## Reading & reports

Durable primers and vendor/docs explainers (prefer evergreen guides over one-off press).

- [What Are AI Dashboards? — ThoughtSpot](https://www.thoughtspot.com/data-trends/dashboard/ai-dashboard) - Enterprise-oriented overview of AI dashboards vs. static reporting.
- [Copilot for Power BI overview — Microsoft Learn](https://learn.microsoft.com/en-us/power-bi/create-reports/copilot-introduction) - Official capability and requirement notes for Power BI Copilot.
- [Tableau Pulse product page](https://www.tableau.com/products/tableau-pulse) - Official Pulse capabilities (metrics, digests, Enhanced Q&A).
- [PwC AI predictions](https://www.pwc.com/us/en/tech-effect/ai-analytics/ai-predictions.html) - Annual enterprise AI outlook useful for leadership context.
- [How to Use AI for Financial Forecasting — NetSuite](https://www.netsuite.com/portal/resource/articles/financial-management/financial-forecast-ai.shtml) - FP&A-oriented AI forecasting primer.
- [How Digital Twins Are Changing Operational Efficiency — Skan AI](https://www.skan.ai/blogs/how-digital-twins-are-changing-operational-efficiency) - Process / twin angle for operational dashboards.

---

## Contributing

Contributions welcome — open a pull request to add a resource, fix a broken link, or suggest a category.

Prefer **durable official / docs URLs**, short blurbs, and products that are shipping. Avoid vaporware and affiliate-only landing pages. Keep product names; mark open-source or language/region when helpful. Update both `README.md` and `README.ja.md` when you can.

## License

[Apache License 2.0](LICENSE)
