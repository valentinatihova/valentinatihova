<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" width="100%" alt="Valentina Tihova, Data & MarTech Architect. Salesforce Data Cloud and customer data platforms for banking, telecom and retail.">
</picture>

I design and build customer data platforms for regulated industries: the layer where a bank's customer data is unified, segmented and turned into the right message on the right channel. Eight years across banking, telecom and retail. Since 2025 I lead Salesforce Data Cloud and Marketing Cloud implementations end to end, from the data model to production support.

### In production

- **Moved a bank with 30M+ retail customers to a new CDP in six months.** Campaigns, segments and data migrated from a legacy decisioning engine and Oracle to PostgreSQL and Tarantool; five complex flows re-implemented on the new stack.
- **Took a retail bank's Salesforce Data Cloud from an empty org to live activation.** About 30 data streams and DMOs, identity resolution, calculated insights and 10 segments feeding cross-channel journeys.
- **Designed custom Viber, SMS and push channels** between Marketing Cloud and a bank's notification platform, and led the incident response when the callback contract changed, tracing the loss down to individual sends.
- **Built Kafka monitoring for campaign triggers** that detects failures and restarts campaigns automatically.
- **Shipped 15+ real-time decisioning cases**: offer recalculation, card issuance, instalment products and transactional triggers, from brief to production.

### Open source and products

| Project | What it solves | Status |
|---|---|---|
| **[data360-autodoc](https://github.com/valentinatihova/data360-autodoc)** | Generates a data dictionary, field mappings, an ERD and a diffable JSON snapshot for any Salesforce Data Cloud org. Replaces days of hand-written documentation on every implementation. | [![PyPI](https://img.shields.io/pypi/v/data360-autodoc?label=PyPI&color=37486F)](https://pypi.org/project/data360-autodoc/) MIT |
| **[Suspicious opens in SFMC](https://valentinatihova.com/article/sfmc-false-opens)** | Flags machine-generated email opens using Marketing Cloud Data Views, so engagement reports count people, not security scanners that open mail seconds after delivery. | Method and SQL published |
| **SFMC Campaign Ops Analytics** | Measures campaign lead time, rework and handoffs from Journey Builder audit logs, as an app inside Marketing Cloud. | In discovery |

### Writing

- [Data Cloud documentation should not be written by hand](https://valentinatihova.com/article/data-cloud-metadata-apex) (May 2026). Apex callouts to the Data Cloud REST API that turn stream inventory, mappings and DMO relationships into reproducible documentation.
- [When open rate lies: detecting suspicious opens in SFMC](https://valentinatihova.com/article/sfmc-false-opens) (April 2026). SQL on Data Views and send timing that separates human opens from scanner traffic.
- [How we build a day: baby feeding clock](https://valentinatihova.com/article/feeding-clock-in-a-day) (April 2026). A 24-hour circular chart that shows feed volume and timing in one view.

### Toolbox

**Customer data:** Salesforce Data Cloud (Data 360), Marketing Cloud Engagement (Journey Builder, Automation Studio, AMPscript, SSJS), CDP and real-time decisioning engines<br>
**Engineering:** SQL (Oracle, PostgreSQL), Python, Apex, REST APIs, Kafka, Airflow, Docker, Kubernetes<br>
**Analytics:** Azure Databricks, Power BI, Tableau

### Contact

[valentinatihova.com](https://valentinatihova.com) · [LinkedIn](https://www.linkedin.com/in/valentina-tihova/) · [valentina.tikhova1@gmail.com](mailto:valentina.tikhova1@gmail.com)
