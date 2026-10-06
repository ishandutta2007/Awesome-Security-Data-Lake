# Awesome-Security-Data-Lake

## Top Security Data Lake Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Security Data Lakes, Detection Engineering & Self-Hosted Analytics*  

**Last updated: October 2026**



This repository tracks notable **commercial security data lake platforms** and **open-source projects** that centralize security telemetry at petabyte scale for threat detection, investigation, and compliance. These tools combine data lake storage economics with SIEM analytical capabilities.



**Examples** include Amazon Security Lake, Snowflake Cybersecurity, Google Chronicle, Microsoft Sentinel, Panther Labs, Databricks Lakehouse Security, Devo Platform, Splunk Enterprise Security, Elastic Security, and Sumo Logic Cloud SIEM (the category leaders).



**Open-source emphasis**: Security data lakes are anchored by **Apache Iceberg** as the open table format, **Trino** and **Apache Spark** for federated queries, and **Matano** as the serverless AWS-native security lake. **OpenSearch Security Analytics** and **Wazuh** provide SIEM capabilities, while **Sigma** enables portable detection rules. **DuckDB** brings in-process analytics, and **Apache Druid**/**Apache Pinot** handle real-time OLAP. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Amazon Security Lake](https://aws.amazon.com/security-lake/)**  

  **AWS's security data lake service** — automatically centralizes security data from AWS, SaaS, and on-premises sources into OCSF format . **Built on S3 and Iceberg** — pay for storage only . **The reference for cloud-native security data lakes** . **Best for AWS-native security analytics** .



- **[Snowflake Cybersecurity](https://www.snowflake.com/)**  

  **Security analytics on Snowflake** — centralize security data with Snowflake's elastic compute . **Best for Snowflake users** .



- **[Google Chronicle](https://cloud.google.com/chronicle)**  

  **Google's cloud-native security analytics** — petabyte-scale with UDM normalization and YARA-L . **Best for massive-scale security analytics** .



- **[Microsoft Sentinel](https://azure.microsoft.com/en-us/products/microsoft-sentinel)**  

  **Microsoft's cloud SIEM with data lake capabilities** — integrated with Azure and Microsoft 365 . **Best for Microsoft-centric organizations** .



- **[Panther Labs](https://panther.com/)**  

  **Cloud-native SIEM with data lake architecture** — detection-as-code with Python rules . **Best for modern security teams** .



- **[Databricks Lakehouse Security](https://www.databricks.com/)**  

  **Security analytics on Databricks lakehouse** — Delta Lake and ML for threat detection . **Best for Databricks users** .



- **[Devo Platform](https://www.devo.com/)**  

  **Cloud-native security analytics** — real-time ingestion and hot storage . **Best for high-volume security data** .



- **[Splunk Enterprise Security](https://www.splunk.com/en_us/products/enterprise-security.html)**  

  **The enterprise SIEM standard** — mature UEBA and correlation . **Best for large SOCs** .



- **[Elastic Security](https://www.elastic.co/security)**  

  **SIEM and EDR on Elastic Stack** . **Best for Elastic ecosystem users** .



- **[Sumo Logic Cloud SIEM](https://www.sumologic.com/solutions/cloud-siem/)**  

  **Cloud-native SIEM** — automated threat detection . **Best for cloud-first organizations** .



## Open-Source GitHub Projects



### Security Data Lake Platforms



- **[Matano](https://github.com/matanolabs/matano)**  

  **The leading open-source serverless security data lake for AWS**, Apache-2.0 licensed . **Security data lake in your AWS account** — ingest petabytes of logs, store in **Apache Iceberg Parquet files on S3** . **Detection-as-code in Python** — manage rules in Git with test, code review, and audit lifecycle . **No vendor lock-in** — query directly from AWS Athena, Snowflake, etc. . **Fully serverless (Lambda, S3, SQS)** with Rust for performance . **The de facto open-source Amazon Security Lake alternative** . **Best for AWS-native security data lakes** .



- **[OpenSearch Security Analytics](https://github.com/opensearch-project/OpenSearch)**  

  **Apache 2.0 licensed fork of Elasticsearch/Kibana** . **Security Analytics includes Sigma rules, alerting, and anomaly detection at no cost** . **The open-source alternative to Elastic Security** . **Best for open-source SIEM with Sigma rules** .



- **[Wazuh](https://github.com/wazuh/wazuh)**  

  **The leading open-source security platform with SIEM and XDR capabilities**, GPLv2 licensed with **16,646+ GitHub stars** . **Native HIDS, FIM, rootkit detection, vulnerability detection, and 1,000+ MITRE ATT&CK rules** . **OpenSearch is the default backend** — Apache 2.0 licensed . **Best for log aggregation, detection, and compliance** .



### Table Formats & Query Engines



- **[Apache Iceberg](https://github.com/apache/iceberg)**  

  **The open table format for security data lakes**, Apache-2.0 licensed with **6,000+ GitHub stars** . **Schema evolution, time travel, and hidden partitioning** . **The de facto standard for security data lakes** — used by Amazon Security Lake and Matano . **Best for lakehouse architectures** .



- **[Delta Lake](https://github.com/delta-io/delta)**  

  **Open table format with ACID transactions**, Apache-2.0 licensed . **Reliable data lakes with schema enforcement** . **Best for Databricks and Spark** .



- **[Apache Hudi](https://github.com/apache/hudi)**  

  **Transactional data lake platform**, Apache-2.0 licensed . **Upserts, deletes, and incremental processing** . **Best for streaming security data** .



- **[Trino](https://github.com/trinodb/trino)**  

  **Federated SQL query engine**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Query across 50+ data sources** including Iceberg, Delta Lake, and security tools . **Best for federated security analytics** .



- **[Apache Spark](https://github.com/apache/spark)**  

  **Unified analytics engine**, Apache-2.0 licensed with **39,000+ GitHub stars** . **Batch and stream processing for security data** . **Best for large-scale security analytics** .



- **[DuckDB](https://github.com/duckdb/duckdb)**  

  **In-process analytical database**, MIT licensed with **20,000+ GitHub stars** . **"SQLite for analytics"** — query Parquet and Iceberg locally . **Best for embedded security analytics** .



### Detection & Threat Analysis



- **[Sigma](https://github.com/SigmaHQ/sigma)**  

  **Open standard for detection rules**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Vendor-neutral detection rules** — convert to any SIEM . **The de facto standard for detection-as-code** . **Best for portable detection rules** .



- **[MISP](https://github.com/MISP/MISP)**  

  **Open-source threat intelligence platform**, AGPL-3.0 licensed with **5,000+ GitHub stars** . **Share, store, and correlate threat indicators** . **Best for threat intelligence sharing** .



- **[OpenCTI](https://github.com/OpenCTI-Platform/opencti)**  

  **Open-source cyber threat intelligence platform**, Apache-2.0 licensed . **Structured threat intelligence with STIX/TAXII** . **Best for CTI management** .



- **[TheHive](https://github.com/TheHive-Project/TheHive)**  

  **Open-source incident response platform**, AGPL-3.0 licensed . **Case management, collaboration, and task tracking** . **Best for SOC case management** .



- **[Cortex](https://github.com/TheHive-Project/Cortex)**  

  **Open-source observable analysis engine**, AGPL-3.0 licensed . **Analyze observables with 100+ analyzers** . **Best for automated observable analysis** .



### Network & Endpoint Telemetry



- **[Zeek](https://github.com/zeek/zeek)**  

  **Network security monitor**, BSD-3-Clause licensed . **Rich network metadata and file extraction** . **Best for network visibility** .



- **[Suricata](https://github.com/OISF/suricata)**  

  **Network IDS/IPS/NSM**, GPL-2.0 licensed . **Deep packet inspection with TLS** . **Best for network detection** .



- **[Velociraptor](https://github.com/Velocidex/velociraptor)**  

  **Endpoint monitoring and digital forensics**, Apache-2.0 licensed . **Query endpoints at scale with VQL** . **Best for threat hunting and DFIR** .



- **[osquery](https://github.com/osquery/osquery)**  

  **SQL-powered operating system instrumentation**, Apache-2.0 licensed with **22,000+ GitHub stars** . **Query endpoints like a database** . **Best for endpoint visibility** .



### Additional Strong Open-Source Options



- **Apache Druid** — Real-time analytics database .

- **Apache Pinot** — Real-time distributed OLAP .

- **ClickHouse** — Columnar analytical database .

- **Apache Doris** — Real-time analytical database .

- **StarRocks** — High-performance analytical database .

- **Elasticsearch** — Search and analytics engine .

- **Graylog** — Log management with SIEM .

- **Security Onion** — Network security monitoring .

- **Chainsaw** — Windows event log hunting .

- **RITA** — Network threat hunting .



**Frameworks for building custom security data lakes**: Combine **Apache Iceberg** for open table format on S3 . Use **Matano** for serverless AWS-native security data lake with detection-as-code . Deploy **Trino** or **Apache Spark** for federated queries across security data . Choose **Wazuh** or **OpenSearch Security Analytics** for SIEM capabilities . Integrate **Sigma** for portable detection rules . Use **MISP** or **OpenCTI** for threat intelligence . Deploy **TheHive** + **Cortex** for incident response . Note that true enterprise security data lakes with managed infrastructure, curated threat intelligence, and vendor-supported SLAs (Amazon Security Lake, Snowflake, Chronicle) remain primarily commercial territory; open-source stacks provide strong table formats, query engines, and detection frameworks that require integration for complete security analytics.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Security data lakes process sensitive security telemetry and may contain PII. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.

- **Open-source security data lakes have hidden costs** — engineering overhead, detection coverage gaps, and higher false-positive rates increase analyst triage time . A senior security engineer dedicated to security analytics costs more than many commercial licenses .

- **Storage costs dominate security data lakes** — Iceberg and Parquet on S3 provide 10-100x lower storage costs than traditional SIEM . However, query costs and compute requirements must be factored in .

- **Detection rules require tuning** — Sigma and Wazuh rules produce false positives. Plan for log-only mode before production blocking .

- The open-source ecosystem provides strong table formats, query engines, and detection frameworks, but **managed infrastructure, curated threat intelligence, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for security engineers, SOC teams, and organizations seeking security data lake sovereignty.**  

Let's make security data lakes more open, transparent, and cost-effective.
