# Awesome-Log-Analytics-Dashboards

# Awesome-Log-Analytics-Dashboards

## Top Log Analytics & Dashboards Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Log Exploration, Visualization & Self-Hosted Analytics Platforms*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Log Analytics & Dashboards**. These tools transform raw log data into searchable, visual insight—enabling teams to investigate incidents, monitor system health, and build dashboards that surface anomalies before they become outages.



**Examples** include Splunk, Datadog, Sumo Logic, Elastic Cloud, Loggly, Coralogix, Mezmo, Humio, Better Stack, and Kibana (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding per-GB ingestion fees, and controlling the visualization layer. The open-source landscape is anchored by **Kibana** (the Elastic Stack visualization standard), **Grafana** (the universal dashboard platform), **OpenObserve** (the full observability platform with built-in dashboards), and **Graylog** (the mature log management platform with integrated dashboards), with **SigNoz** and **Quickwit** serving OpenTelemetry-native and object-storage-native needs respectively.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



| Product | Description | Pricing | Free Tier Limit | Company Size (Revenue/Valuation) |

| :--- | :--- | :--- | :--- | :--- |

| **[Splunk](https://www.splunk.com/)** | Enterprise log analytics standard with SPL for correlation, dashboards, and SIEM. | Splunk Cloud Platform: **$150–$225/GB/day** list (negotiated $100–$180/GB/day); Splunk Enterprise self-hosted: **$1,800–$2,700/GB/day** annual list. | **Splunk Free**: 500 MB/day indexing, single instance, no alerting or user authentication. 60-day Enterprise Trial available. | **~$3.5B+ revenue** (Cisco-owned; publicly traded pre-acquisition). |

| **[Datadog](https://www.datadoghq.com/)** | Full observability platform with logs integrated alongside metrics, traces, and dashboards. | Logs billed separately for ingest and indexing; overage at **50% premium**. Indexed logs approximately **$0.10/GB** plus event-based indexing fees. | **Infrastructure Free**: Up to 5 hosts with 1-day metric retention. Does **not** include log management. | **$3.672B TTM revenue** (ending March 31, 2026) . |

| **[Sumo Logic](https://www.sumologic.com/)** | Cloud-native log analytics with security and observability dashboards. | List pricing **$100–$180/GB/day**. Flex pricing available at **$3.14/TB scanned** with zero ingest cost. | **60-day free trial** with full access to self-service plans. No permanent free tier. | **~$301M revenue**; **$1.19B valuation** (2026) . |

| **[Elastic Cloud](https://www.elastic.co/cloud/)** | Managed Elasticsearch, Kibana dashboards, and full-text search. | **Standard**: $99/month; **Gold**: $114/month; **Platinum**: $131/month; **Enterprise**: $184/month (based on 120 GB storage/2 zones). | **14-day free trial** on Elastic Cloud. Self-managed Elasticsearch/Kibana is free (basic tier). | **~$1.74B revenue** (FY2026, ending April 2026) . |

| **[Loggly (SolarWinds)](https://www.loggly.com/)** | Cloud log management with search and dashboards, part of SolarWinds observability suite. | Starting at **$79/month**. Tiered by volume (1 GB/day to 20+ GB/day). | **Loggly Free**: 200 MB/day ingestion, 7-day retention, single user. | Part of **SolarWinds** (private, PE-owned). Exact Loggly revenue not disclosed. |

| **[Coralogix](https://coralogix.com/)** | Observability platform with TCO-based pricing and AI-assisted analytics. | **1 unit = $1.50** usage. Logs: High priority **0.75 units/GB**, Medium **0.32/GB**, Low **0.12/GB**. | **Coralogix Free**: 1 GB/day logs, 3 days retention, 1 user. | **~$100M revenue**; **$1.6B valuation** (Series F, June 2026) . |

| **[Mezmo (LogDNA)](https://www.mezmo.com/)** | Log management with live tail, parsing, and alerting. | Starting at **$10/month** for basic plans; scales with volume. | **Mezmo Free**: 50 MB/day, 3-day retention, 1 user. | **$60M total funding**; ARR growth 2.6x (as of Series C). Revenue not publicly disclosed . |

| **[Humio (CrowdStrike)](https://www.humio.com/)** | Streaming log management with unlimited ingest plans and fast search. | Humio Cloud: **~$778/year** for 1 GB/day subscription (Band 6). Enterprise pricing via CrowdStrike. | **Humio Community Edition**: 16 GB/day ingest, 7-day retention, free for self-hosted. | Part of **CrowdStrike** (public). Humio standalone estimated **$5M–$10M revenue** . |

| **[Better Stack Logs](https://betterstack.com/logs)** | Developer-friendly log management with dashboards and alerting. | **Free**: 3 GB/month each of logs/traces/events, 3-day retention. **Nano bundle**: $30–$105/month for 40 GB each; **Micro**: $120–$420/month. | **Free plan**: 3 GB/month each of logs, traces, and web events, retained 3 days. | Private; revenue not disclosed. |

| **[Graylog Cloud](https://www.graylog.org/)** | Mature enterprise log management with security correlation and dashboards. | **Cloud Operations**: $1,250/month for 10 GB/day; **Cloud Security**: $1,550/month for 10 GB/day. | **Graylog Open**: Free self-hosted, unlimited logs (requires infrastructure). **Cloud**: 30-day free trial. | Private; revenue not disclosed. |



## Open-Source GitHub Projects



- **[Grafana](https://github.com/grafana/grafana)** [![GitHub Stars](https://img.shields.io/github/stars/grafana/grafana?style=social&color=white)](https://github.com/grafana/grafana/stargazers)  

  **The universal dashboard platform.** ~72.7k stars . Connects to virtually any data source—Loki, Elasticsearch, Prometheus, ClickHouse, Postgres—and renders unified dashboards. Best for teams that want one visualization layer across logs, metrics, and traces regardless of backend.



- **[Kibana](https://github.com/elastic/kibana)** [![GitHub Stars](https://img.shields.io/github/stars/elastic/kibana?style=social&color=white)](https://github.com/elastic/kibana/stargazers)  

  **The Elastic Stack visualization standard.** ~19.2k–19.4k stars . Your window into Elasticsearch—search, dashboards, visualizations, and Canvas for pixel-perfect reports. Tightly coupled to Elasticsearch as the data backend. Best for teams already using Elasticsearch who want the most mature log exploration UI with Lens for drag-and-drop visualization.



- **[OpenObserve](https://github.com/openobserve/openobserve)** [![GitHub Stars](https://img.shields.io/github/stars/openobserve/openobserve?style=social&color=white)](https://github.com/openobserve/openobserve/stargazers)  

  **The full observability platform with built-in dashboards.** ~20.4k+ stars . AGPL-3.0 licensed. Covers logs, metrics, traces, LLM observability, and Synthetics with a visual query builder and dashboard panels. Best for teams wanting an all-in-one platform without assembling Kibana + Grafana + separate backends.



- **[SigNoz](https://github.com/SigNoz/signoz)** [![GitHub Stars](https://img.shields.io/github/stars/SigNoz/signoz?style=social&color=white)](https://github.com/SigNoz/signoz/stargazers)  

  **The OpenTelemetry-native observability platform.** ~12.2k stars . Combines logs, metrics, and traces in a unified UI with ClickHouse storage and built-in dashboards. Best for teams standardized on OpenTelemetry that want a single backend and visualization layer for all telemetry signals.



- **[Quickwit](https://github.com/quickwit-oss/quickwit)** [![GitHub Stars](https://img.shields.io/github/stars/quickwit-oss/quickwit?style=social&color=white)](https://github.com/quickwit-oss/quickwit/stargazers)  

  **The object-storage-native search engine.** ~9.9k stars . Sub-second full-text search on 100TB+ datasets with 10x TCO reduction vs Elasticsearch in one migration case study. Includes a built-in UI for log exploration. Best for teams prioritizing search performance and cost efficiency over dashboard richness.



- **[Graylog](https://github.com/Graylog2/graylog2-server)** [![GitHub Stars](https://img.shields.io/github/stars/Graylog2/graylog2-server?style=social&color=white)](https://github.com/Graylog2/graylog2-server/stargazers)  

  **The mature enterprise log management platform.** **License note**: Graylog Open is distributed under **SSPL** (Server Side Public License)—not OSI-approved open-source; more accurately described as open-core or source-available . Integrated search, dashboards, alerting, and stream processing. Graylog 7.0 adds Asset Events, Vulnerability Scan Support, and MCP Tools for LLM interaction. Best for enterprises needing security correlation and asset intelligence alongside log analytics.



### Additional Strong Open-Source Options



- **OpenSearch Dashboards** — The Apache 2.0 fork of Kibana, paired with OpenSearch. Best for teams needing Elasticsearch-compatible visualization without Elastic's licensing restrictions.

- **Loki + Grafana** — Label-indexed log aggregation paired with Grafana dashboards. Best for cost-efficient log analytics within an existing Grafana/Prometheus stack.

- **Apache Superset** — General-purpose BI and dashboard platform that can connect to log databases. Best for teams wanting log analytics alongside business intelligence dashboards in one tool.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **Pricing scales dramatically with volume**: Splunk at 200 GB/day can cost $120,000–$200,000 annually; Graylog Cloud at the same volume is $5,000–$6,500/month. Model your actual ingest before committing.

- **Free tiers are for evaluation, not production**: Splunk Free lacks alerting; Datadog Free excludes logs; Sumo Logic and Elastic offer trials only. Verify limits before relying on free plans.

- **Graylog Open is SSPL-licensed**: not OSI-approved open-source. The free tier covers basic log aggregation and alerts; SIEM features (search filtering, log archiving, anomaly detection, compliance reports) are in the paid Graylog Security tier .

- **Company size data varies in reliability**: Public company revenues (Datadog, Elastic) are from official filings. Private company figures (Coralogix, Sumo Logic) are from funding databases and may lag. Loggly and Mezmo revenue is not publicly disclosed—they are parts of larger parent companies or have limited funding disclosures .

- **Open-source visualizers still require infrastructure**: Kibana, Grafana, and OpenObserve all need servers, storage, and maintenance—free software is not free operations.



---



**Made for SREs, platform engineers, and developers building observability dashboards.**  

Let's make log analytics more open, visual, and appropriately scoped.
