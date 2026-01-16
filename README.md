# realtime-stock-analytics

This project showcases a complete end‑to‑end data solution built in Microsoft Fabric, covering ingestion, transformation, modeling, and interactive reporting. The goal was to design a scalable, modular, and production‑ready analytics pipeline that processes intraday stock market data as well as daily historical data and delivers near real‑time insights through a Power BI dashboard.

The work was developed in a Fabric Test Workspace without Git integration, which required a fully manual export of all available assets. To preserve transparency and reproducibility, the repository includes exported notebooks, SQL logic, screenshots of the pipeline and Lakehouse structure, and a demo video of the final dashboard.

## Key Features
- Lakehouse Architecture (Bronze → Silver → Gold)  
Clean, layered design ensuring traceability, reproducibility, and separation of concerns.

- Deployment Pipeline (Dev → Test → Prod)  
Designed a modular promotion flow with deployment rules to ensure stage specific lakehouse connections and parameters .

- Automated Data Pipelines  
Modular ingestion and transformation logic, including deduplication, schema validation, and MERGE‑based upserts.

- Data Quality Foundations  
Checks for table existence, schema consistency, null handling and duplicates.

- Semantic Model for Analytics  
Well‑structured star schema with clear relationships, optimized for performance and maintainability.

- Interactive Power BI Dashboard  
Near Real‑time Intraday tab, common stock KPIs, trend analysis, and filtering options.



## Demo & Screenshots
The repository includes:

- A video walkthrough of the dashboard

- Screenshots of the Dashboard, Lakehouse, pipelines, and semantic model

- Exported code and logic for full transparency

## Learnings & Next Steps
This project strengthened my expertise in:

-- Designing scalable Lakehouse architectures

-- Building modular Fabric pipelines

-- Implementing clean semantic models 

## Future improvements could include:

CI/CD integration via GitHub or Azure DevOps

Expanded Data Quality rules

Additional data sources and predictive analytics
