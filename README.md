# Python Backend, Data Pipelines & Workflow Automation Portfolio

### Aayush Agrawal — Python Backend & Data Engineer
Pune, India (Available for US/UK/EU overlap) | `aayush.satna94@gmail.com`  | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aayush-agrawal-dev)

I build reliable Python backends, automated ETL/scraping pipelines, real-time alert engines, and zero-maintenance internal business tools that eliminate manual bottlenecks.

---

### Core Technical Stack
* **Languages & Frameworks:** Python, FastAPI, Django, Flask, SQL, Google Apps Script
* **Data & Streaming:** PostgreSQL, TimescaleDB, MySQL, SQLite, Apache Kafka, NATS (JetStream), Pandas
* **Automation & Infrastructure:** REST APIs, Webhooks, Telegram Bots, Docker, Kubernetes, Jenkins, AWS, Linux

---

### Selected Systems & Automation Case Studies

#### 1. Real-Time Market Scanner & Instant Telegram Alert Engine
* **Problem:** Manually monitoring intraday price breakouts and logging session metrics across multiple instruments caused missed entries and delayed execution.
* **Solution:** Engineered a Python-based Opening Range Breakout (ORB) scanner that polls market feeds in real time, evaluates breakout thresholds, deduplicates events, logs structured session metrics, and dispatches instant alerts to Telegram.
* **Architecture:** `Market Data Feed` $\rightarrow$ `Python Rule Engine` $\rightarrow$ `State Deduplication` $\rightarrow$ `Telegram Bot API + Cloud Ledger`
* **Impact:** Sub-minute notification delivery with zero manual chart monitoring.

#### 2. Automated Business Operations, Billing & Inventory Portal
* **Problem:** Service businesses managing daily recurring deliveries/orders via paper registers suffered from billing errors, missed pause dates, and untracked grocery/supply expenses.
* **Solution:** Built a multi-device web application and automated backend on Google Workspace (Apps Script + Sheets) featuring customer onboarding, daily attendance/delivery tracking, partial-order billing, automated invoice calculation, and expense accounting.
* **Architecture:** `Responsive Web UI` $\rightarrow$ `Apps Script REST Endpoints` $\rightarrow$ `Relational Sheet Engine` $\rightarrow$ `Automated Itemized Billing`
* **Impact:** Reduced monthly billing reconciliation from hours to one click while running at $0/month hosting cost.

#### 3. Real-Time Mobile Webhook & Automated Expense Analytics Pipeline
* **Problem:** Tracking daily digital transactions across multiple payment apps required tedious manual spreadsheet entry.
* **Solution:** Designed an event-driven webhook pipeline connecting iOS automation triggers directly to a cloud backend (`doPost`/`doGet` JSON endpoints) that categorizes transactions in real time and updates live visual analytics dashboards.
* **Architecture:** `Mobile Payment Trigger` $\rightarrow$ `JSON Webhook Payload` $\rightarrow$ `Validation & Categorization` $\rightarrow$ `Live Dashboard`
* **Impact:** 100% automated real-time expense capture with zero manual data entry.

#### 4. Fault-Tolerant High-Throughput Telemetry & ETL Pipelines (Production)
* **Problem:** Distributed IoT gateways and enterprise data systems experience intermittent network drops and schema inconsistencies that risk data loss.
* **Solution:** Built resilient Python ingestion services utilizing edge buffering, NATS JetStream, Apache Kafka, PostgreSQL, and TimescaleDB alongside automated validation and CI/CD pipelines (Docker, Jenkins, Kubernetes).
* **Impact:** Achieved 99.9% uptime across 1,000+ connected endpoints and cut API response latency by 50% (800ms $\rightarrow$ 400ms).

---

### How We Can Work Together
* **Custom Scrapers & Data Pipelines:** Clean, scheduled extraction into CSV, PostgreSQL, or Google Sheets with anti-blocking and retry logic.
* **API Integrations & Webhooks:** Connecting CRMs, payment gateways, Telegram/Slack bots, and internal databases.
* **Internal Business Tools & Dashboards:** Fast, low-cost operational portals and automated reporting workflows.

*Open to fixed-price automation builds, custom data pipelines, and ongoing backend contracts.*
