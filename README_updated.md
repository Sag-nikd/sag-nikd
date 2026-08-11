<h1 align="center">Sagnik Dutta</h1>
<h3 align="center">Forward Deployed Engineer | Customer Engineer | Implementation & Deployment</h3>

<p align="center">
  United States &nbsp;|&nbsp;
  <a href="mailto:sagnikdutta.techm@gmail.com">sagnikdutta.techm@gmail.com</a> &nbsp;|&nbsp;
  <a href="https://www.linkedin.com/in/sagnik-dutta-/">LinkedIn</a>
</p>

---

## About Me

I build inside the customer's environment, not around it.

**10+ years** in customer-facing technical roles, the last three deploying enterprise healthcare software on Medicaid and Medicare managed care accounts covering **2M+ members** (BCBS-Illinois, Centene, Cook County Health).

The pattern of the work is consistent:

- Sit with carrier operations and claims teams and learn how they actually operate
- Build the integrations and Dynamics 365 configuration that make the product fit
- Write the Python, SQL, and JavaScript that closes what the product does not close
- Instrument adoption after go-live rather than treating launch as the finish line
- Hand the recurring patterns back to product and engineering as reusable capability

HIPAA, CMS, and state Medicaid constraints are design inputs I write as test cases and defend in the customer's own security review, not blockers discovered two weeks before go-live.

---

## Selected Work

### [GTM System, Outbound Revenue Pipeline](https://github.com/Sag-nikd/Gtm_System_Outbound)

`Python` `HubSpot REST API` `Pydantic` `pytest` `YAML` `Tenacity`

An end-to-end revenue pipeline across **11 staged checkpoints**: source ingestion, scoring, enrichment, two-step email validation, live CRM sync covering custom company and contact properties, deal pipeline and associations, multi-channel sequence export, and campaign health monitoring.

- **Dual-client integration pattern** (`mock_client` and `api_client`) across 6 vendor stubs, so the pipeline runs end to end on fixtures and paid interfaces activate one at a time with no refactor. Same problem shape as standing up a new customer tenant without touching core code.
- **Configuration, not forks.** Externalized scoring weights, tier thresholds, lifecycle transition rules, and per-client setup overrides in YAML.
- **Production hygiene throughout.** pytest coverage across scoring, validation, enrichment, ingestion, and CRM mapping. Retry decorators with backoff. Structured logging. A dry-run provisioning mode so first writes into a customer CRM are reversible.

### Pawsome Goods, Data Quality Pipeline

`Python` `pandas` `schema validation` `SOP documentation`

A two-stage validator and cleaner for a client product catalog, deliberately separating **detection from remediation** so data owners review flagged records before any transformation is applied. Schema and type validation, duplicate and null handling, normalization rules, and an exception report routed back to the client operations team.

Shipped with a standard operating procedure so a non-technical operator can run, interpret, and hand off the pipeline without engineering support. That handoff is the same one required when a deployment transitions from the forward deployed engineer to the customer team.

### ICP Hub, Bring-Your-Own-Key Targeting Tool

`Python` `Streamlit` `LLM APIs`

A Streamlit application that lets a team define, score, and stress-test targeting criteria against account lists using their own API keys, keeping account data and model spend inside the customer environment rather than a shared vendor tenant. That is the architecture that survives a security review at a regulated buyer.

---

## What I Have Delivered

- Cut average deployment time from **12 to 13 weeks down to 10**, roughly 20% faster time to value
- Contributed to a **25% CSAT increase** and **$5M+ in accelerated customer value**
- Ran **3 to 4 enterprise deployments per year** on 2 to 3 month cycles
- Scored **1,000+ accounts at 90% targeting accuracy**, lifting qualified pipeline 20% and cutting manual research 80%
- Built the reusable deployment kit and monitoring components adopted across engagements
- Analysis on datasets from **1K to 500K+ rows** driving customer health and adoption models
- Validated a single-day **200,000 member** campaign under load with no save loss

---

## Domain Experience

| Domain | What I worked on |
|---|---|
| **Healthcare SaaS** | Medicaid and Medicare MCO deployments, claims and eligibility data, HIPAA-regulated member engagement |
| **Insurance / Claims** | Claims and remittance reconciliation, denial root cause, enrollment feeds |
| **Marketplaces** | Merchant and partner onboarding, deployment, retention, operational analytics |
| **Education** | Systems support, internal databases, reporting |
| **Real Estate** | Client solutions, due diligence, pipeline tooling |

---

## Stack

### Languages and Data
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

### Integration
![REST](https://img.shields.io/badge/REST%20APIs-111827?style=for-the-badge)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![HL7](https://img.shields.io/badge/HL7-B91C1C?style=for-the-badge)
![FHIR](https://img.shields.io/badge/FHIR-DC2626?style=for-the-badge)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=twilio&logoColor=white)
![SFTP](https://img.shields.io/badge/SFTP%20Batch-111827?style=for-the-badge)
![Webhooks](https://img.shields.io/badge/Webhooks-111827?style=for-the-badge)

### Platform and Cloud
![Dynamics 365](https://img.shields.io/badge/Dynamics%20365-0B53CE?style=for-the-badge&logo=microsoft&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)
![HubSpot](https://img.shields.io/badge/HubSpot-FF7A59?style=for-the-badge&logo=hubspot&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Instrumentation
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Looker](https://img.shields.io/badge/Looker-4285F4?style=for-the-badge&logo=looker&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)

### Build Loop
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97706?style=for-the-badge)
![Cursor](https://img.shields.io/badge/Cursor-111827?style=for-the-badge)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)

---

## Experience Snapshot

**Senior Customer Success Engineer (Forward Deployed) / Implementation Manager, Sagitec**
Embedded on enterprise MCO deployments: integration layer across HL7, FHIR, Twilio, SFTP, and REST; JavaScript member-facing microsites carrying survey and enrollment traffic; Python and SQL against live deployment data; compliance constraints translated into platform behavior and defended in carrier-side security review.

**Customer Success Engineer, Sagitec**
Product implemented directly on the client side. Interoperability scoping and configuration, omnichannel orchestration, client-facing UAT, and the reusable deployment kit that cut time to go-live across the portfolio.

**GTM and Revenue Operations, OYO and Foodpanda**
Partner and merchant onboarding at scale, reporting infrastructure on 100K+ datapoints, and the repeatable playbooks that standardized deployment across regional teams.

---

## Certifications

- Databricks Fundamentals
- Gainsight Administrator
- Salesforce Certified Administrator
- Certified Scrum Master (CSM)
- Certified Scrum Product Owner (CSPO)

---

## Current Focus

- Forward deployed and customer engineering in regulated environments
- Healthcare interoperability: HL7, FHIR, eligibility and claims data pipelines
- Validation gates, reconciliation, and data quality as deployment infrastructure
- LLM-in-the-loop enrichment, classification, and personalization pipelines
- Handoff engineering: containerized tooling and procedures a customer team can run without me

---

## Let's Connect

Open to **Forward Deployed Engineer**, **Customer Engineer**, **Implementation Engineer**, **Solutions Engineer**, and **Technical Account Manager** roles in the United States.

<p align="center">
  <a href="https://www.linkedin.com/in/sagnik-dutta-/">LinkedIn</a> &nbsp;•&nbsp;
  <a href="mailto:sagnikdutta.techm@gmail.com">Email</a> &nbsp;•&nbsp;
  <a href="https://github.com/Sag-nikd">GitHub</a>
</p>

