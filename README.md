# Xun (Eddie) Luo

Data engineer finishing an M.S. in Computer Science at Northeastern University (Seattle, Dec 2026), with a B.A. in Economics from Baylor. I build data pipelines, warehouses and dashboards, and GenAI agents that work on top of data. Most recently a **Business Intelligence Engineer Intern at Amazon**.

**Open to new-grad Data Engineer, BI Engineer and Analytics Engineer roles.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-xun--luo-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/xun-luo-a96b56372/)
[![Email](https://img.shields.io/badge/Email-xunluo1234%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:xunluo1234@gmail.com)

## Experience

**Amazon, Business Intelligence Engineer Intern** (Global Transportation Services, Jun to Sep 2026)

- Built an automated evaluation framework for a GenAI supply-chain agent. It runs 600+ question-answer test cases and feeds an agent-health dashboard. Parallel workers cut evaluation time from 5 to 8 hours down to about 20 minutes.
- Scheduled the evaluations on ECS Fargate with AWS CDK and EventBridge, stored the results in S3 and queried them in place with Glue and Athena.
- Connected 20+ BI dashboards to the agent through MCP-based tools and skills, and wrote the onboarding SOPs other teams use to connect their own data.

## Tech stack

| Area | Tools |
|---|---|
| Languages | Python, SQL, Java, C |
| Data engineering | Spark / PySpark, dbt, Airflow, Databricks, Snowflake, Delta Lake, Redshift |
| Cloud | AWS (S3, Glue, Athena, ECS Fargate, CDK, EventBridge), Azure (Databricks, ADLS Gen2) |
| BI | Power BI, Amazon QuickSight, Tableau, Excel |
| AI and tooling | GenAI agents, MCP, LangGraph, FastAPI, Docker, Git, Claude Code |

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| [query-agent](https://github.com/xunluo776/query-agent) | Ask questions about your data in plain English: a LangGraph agent writes SQL and runs it through a config-driven MCP server with read-only, row-capped and time-limited queries. Chat sessions, SQL-error retry and CSV download, running in three Docker containers | Python, MCP, LangGraph, Gemini, FastAPI, Streamlit, Docker Compose |
| [superstore-databricks-dbt-project](https://github.com/xunluo776/superstore-databricks-dbt-project) | End-to-end lakehouse: Auto Loader ingestion into Bronze, dbt models and snapshots into a Silver/Gold star schema, then Power BI analysis of growth, segments and discount vs. margin | Databricks, dbt, Delta Lake, PySpark, Power BI |
| [Daily-Pricing-ETL-Pipeline](https://github.com/xunluo776/Daily-Pricing-ETL-Pipeline) | Daily pricing ETL on Azure: HTTP, streaming and reference-database ingestion, Delta transforms, SCD Type 1 and Type 2 dimensions, and a reporting fact table | Azure Databricks, ADLS Gen2, PySpark, Delta |
| [bitcoin-airflow-pipeline](https://github.com/xunluo776/bitcoin-airflow-pipeline) | Daily Airflow DAG that ingests into Snowflake, then runs dbt Silver/Gold models and tests through Astronomer Cosmos | Airflow (Astro), Snowflake, dbt, Docker |
| [data-warehouse-project](https://github.com/xunluo776/data-warehouse-project) | SQL Server warehouse that merges CRM and ERP sources: Bronze bulk loads, Silver cleansing procedures, Gold star-schema views and data-quality checks | T-SQL, SQL Server |
| [supply-chain-powerbi](https://github.com/xunluo776/supply-chain-powerbi) | Power BI dashboards for supply-chain KPIs: revenue and margin, carrier delays, lead times and disruption risk | Power BI, star schema |
| [campushub](https://github.com/xunluo776/campushub) | Full-stack booking app for campus rooms and equipment, with double-booking protection, an OpenAPI contract, an 80% test-coverage gate and a CI job that asks an LLM to patch failing tests | TypeScript, Express, MongoDB, React, GitHub Actions |
| [nlp-ship-of-theseus-project](https://github.com/xunluo776/nlp-ship-of-theseus-project) | Team research project measuring how much meaning and how many named entities survive repeated paraphrasing, across 7 paraphrasers and 7 datasets | Python, spaCy, PyTorch, Transformers |

## Education

- **Northeastern University**, M.S. Computer Science (Seattle, expected Dec 2026), GPA 3.77
- **Baylor University**, B.A. Economics, minor in Business Administration, GPA 3.8

**Certification:** AWS Certified Cloud Practitioner (CLF-C02)
