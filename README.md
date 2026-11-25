# Hi, I'm Zeliha 👋

Analytics Engineer with 8+ years in e-commerce operations. I build tested,
monitored data pipelines and care about numbers people can trust.

🌐 [Portfolio](https://tutarzeliha-ctrl.github.io) · 💼 [LinkedIn](https://www.linkedin.com/in/zeliha-tutar/) · 📄 [CV](https://tutarzeliha-ctrl.github.io/assets/Zeliha_Tutar_CV.pdf)

## Featured project

**[realtime-cdc-lakehouse](https://github.com/tutarzeliha-ctrl/realtime-cdc-lakehouse)**:
PostgreSQL → Debezium → Kafka → DuckDB/Parquet → dbt → Airflow, running locally in Docker.

- **v1.0 CDC:** transactional consumer; replaying the topic from the start produced no duplicate rows (verified live).
- **v1.1 Analytics:** dbt models, SCD2 snapshot, daily status history and a reconciliation test against the source.
- **v1.2 Orchestration:** Airflow freshness and connector checks; a stopped consumer and a stopped connector both raised alerts in live tests.

## Other projects

| Project | What it shows |
| :--- | :--- |
| [sepetix-dbt-analytics](https://github.com/tutarzeliha-ctrl/sepetix-dbt-analytics) | dbt staging/mart models and tests on e-commerce data |
| [ecommerce-retention-analytics](https://github.com/tutarzeliha-ctrl/ecommerce-retention-analytics) | dbt + BigQuery retention models, snapshot and CI |
| [enterprise-data-observability](https://github.com/tutarzeliha-ctrl/enterprise-data-observability) | Airflow data quality checks, Streamlit dashboard, Slack alerts |
| [data-quality-airflow-pipeline](https://github.com/tutarzeliha-ctrl/data-quality-airflow-pipeline) | Medallion pipeline with Polars, DuckDB and quality gates |
| [agentic-data-quality](https://github.com/tutarzeliha-ctrl/agentic-data-quality) | Prototype: rule-based checks with LLM explanations |

All projects are portfolio work, built locally or on free tiers and mostly on
synthetic data. Each README lists what was tested and what was not.

## Stack

**Core:** SQL · Python · dbt · Airflow · BigQuery
**Used in projects:** PostgreSQL · Kafka · Debezium · DuckDB · Docker · PySpark · Streamlit · GitHub Actions
