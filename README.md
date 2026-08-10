# 👋 Hi, I'm Prasanna Sriram

# Enterprise Risk & GRC Leader | ERM, TPRM & Cybersecurity Governance | TPM-Style Program Delivery

## About Me

I lead enterprise risk and GRC programs the way a technical program manager runs a delivery roadmap: with scope, milestones, cross-functional accountability, and executive reporting cadence, not just spreadsheets and policy documents. For 8+ years, I've owned IT risk, third-party risk, and cybersecurity governance programs end-to-end across telecom billing, banking/fintech, accounting/payroll platforms, SaaS startups, and nonprofits, reporting through governance chains that reach CISO, CFO, Risk Committee, and Board/Audit Committee levels.

I've run IPO-readiness IAM/SOX remediation programs coordinating teams of up to 12 engineers and auditors, built and defended third-party risk assessments across vendor portfolios of 50–75+, and led independent cybersecurity maturity engagements that reframed security gaps as revenue and growth risk for founders and boards. I design and automate the analytics behind these programs myself (SQL, Python, and Power BI) from three-way revenue reconciliations and vendor risk scoring engines to NIST CSF maturity models and continuous controls monitoring dashboards.

What sets me apart is the ability to move fluidly between building the technical control (a SQL check, a Python risk score, a Power BI dashboard) and defending it in front of an auditor, a CISO, or a Board Audit Committee. I treat risk and compliance as a growth enabler - connecting security posture to enterprise sales enablement, funding eligibility, and audit readiness, rather than a pure cost-of-doing-business function. I'm currently deepening my expertise in cloud security architectures and AI governance/risk frameworks, and building portfolio projects that simulate exactly those problem spaces.

---

## Highlights

- Owned end-to-end delivery of an enterprise IAM and SOX compliance program as part of company-wide **IPO readiness**, leading a cross-functional team of 12 infrastructure, security, engineering, and audit stakeholders, achieving 100% MFA adoption for privileged accounts within 3 months and cutting non-compliance risk by 40%.
- Designed and led a risk-based **Third-Party Risk Management (TPRM) program covering 50–75+ vendors**, building a weighted inherent-risk scoring engine, ISO 27001 Annex A/SOC 2-mapped control library, and risk tiering model taking a startup from zero vendor visibility to a defensible, audit-ready program.
- Built an automated 3-way reconciliation (UMS, Billing, GL) using SQL and Python that recovered ~30% of previously missed premium-service telecom revenue while generating continuous SOX audit evidence.
- Led a **NIST CSF-aligned cybersecurity maturity assessment** for a banking software startup, using Python/Pandas to convert structured interviews into quantitative maturity scores, and reframed security gaps as enterprise due-diligence and revenue risk for the CEO and Board of Directors.
- Served as the client's independent assurance lead on a **third-party technology risk assessment** for a critical PII-processing vendor, directing a 7-person cross-functional team and reporting risk heat maps and residual risk through a Risk Committee → CISO → Engineering Leadership governance chain.
- Implemented PCI DSS-compliant encryption and payment-data monitoring across legacy billing systems, eliminating unencrypted cardholder data and strengthening billing-workflow compliance.
- Replaced shared credentials with role-based access for a nonprofit handling donor and beneficiary PII, implementing logging and approval workflows that materially reduced audit and privacy risk while protecting grant/funding eligibility.

---

## 🔧 Tech Stack

- **Risk, Compliance & Governance:** SOX ITGC, SOC 2 (Type I & II), ISO 27001 Annex A, PCI DSS, NIST Cybersecurity Framework, NIST AI RMF, ISO/IEC 42001, GDPR, DPDP, FCRA, COBIT, Enterprise Risk Management (ERM), Third-Party Risk Management (TPRM), Vendor Risk Management, Control Design, RCSA, Risk Assessments & Risk Registers, Risk Appetite & KRI Design, Issue & Incident Management, Three Lines of Defense
- **Identity & Access Controls:** Identity & Access Management (IAM), Least-Privilege Access Design, User Access Reviews, Segregation of Duties (SoD), Privileged Access Monitoring, MFA Rollout & Coverage Tracking, Role-Based Access Control (RBAC), Identity Governance (IGA)
- **Data, Analytics & Automation:** SQL (Advanced), Python (Advanced: Pandas, scikit-learn, automation scripts), Power BI (Advanced: DAX, dashboards, alerts), Automated Reconciliation, Exception Monitoring, Risk Dashboards & KPIs, Automated Evidence Collection, Continuous Controls Monitoring (CCM)
- **Program & Delivery Leadership:** TPM-style program governance, hybrid Agile delivery, cross-functional stakeholder management (up to 30-person ecosystems), audit relationship ownership, executive & Board/Audit Committee reporting
- **Tools & Platforms:** Microsoft 365 (SharePoint, Power Automate, Excel risk engines), Microsoft Forms, Notion, Azure API Management, Microsoft Entra ID, Azure Key Vault, Azure Monitor / Log Analytics, Ganges BPM, TFS / Azure DevOps, ETL Pipelines, Network Configuration Monitoring Tools, Log & Change Tracking Systems
- **Security & Cloud Direction:** Cloud Security Architecture, Cloud IAM, Privileged Access, AI Governance & Model Risk, Risk Analytics, Continuous Monitoring
- **Databases:** MS SQL Server, PostgreSQL, MongoDB, Firebase
- **Operating Systems:** Windows, Linux
- **Other Tools:** Git, GitHub, Heroku

---

## 📁 Featured Projects

### [AuroraPay - Product Risk Analytics for Real-Time Payments](https://github.com/prasanna-sriram/aurorapay-product-risk-case-study)

A second-line ERM case study for a fictional national real-time payments rail (inspired by Interac), built to show how a Product Risk Lead challenges a payments product rather than just reports on it. I designed a product-aligned risk taxonomy and 12-item risk register across five themes: outages, fraud, technology/access, third-party, and regulatory exposure, then generated and analyzed ~100K synthetic transactions in Python/pandas to compute KRIs on fraud rates, incident severity, and open High/Critical issues. The Power BI dashboards and executive risk paper surfaced that a smaller payment rail carried disproportionately higher fraud risk, and that privileged-access gaps and vendor-resilience shortfalls were the structural amplifiers behind it, resulting in prioritized, time-bound remediation recommendations written from a genuine second-line challenge perspective.

**Skills demonstrated:** ERM and product-aligned risk frameworks, risk registers and appetite statements, Python/pandas analytics, KRI design, Power BI dashboarding, executive risk storytelling.

### [Continuous IT GRC Monitoring for SaaS Platforms - SOX ITGC Automation](https://github.com/prasanna-sriram/netwave-grc-monitoring)

An automated GRC monitoring pipeline built for a fictional SaaS company, designed to replace slow, inconsistent manual access reviews with a repeatable, audit-evidenced control-testing process. I designed a relational schema in SQL Server, wrote parameterized SQL checks to detect excessive privileges, dormant privileged accounts, terminated users retaining access, missing MFA, unapproved configuration changes, and segregation-of-duties conflicts, then built a Python evidence runner (pyodbc/pandas) that executes those checks, stamps audit metadata, and writes dated, auditor-ready CSV evidence with run manifests, even when a check returns zero findings. The results feed a four-page Power BI report (executive overview, access governance, change management/SoD, and a department-level drillthrough) designed to support periodic access reviews and management reporting, and the architecture is built to extend directly into cloud IAM (AWS/Azure/GCP) monitoring.

**Skills demonstrated:** SQL Server schema design and control-check logic, Python audit-evidence automation, Power BI/DAX reporting, SOX ITGC and access governance concepts, segregation-of-duties analysis.

### [Enterprise Risk, Fraud Analytics & AI-Driven Fraud Detection Framework - Canadian Payments](https://github.com/prasanna-sriram/payments-risk-360)

A second-line ERM framework simulating how a Canadian payments network monitors resilience across four connected workstreams: credit risk, intraday liquidity risk, fraud risk, and AI-driven fraud detection. I built a logistic-regression PD-style model to score participant/merchant distress and concentration risk, simulated intraday liquidity flows under baseline and stressed scenarios with time-to-breach thresholds, designed rules-based fraud KRIs on card-level velocity and amount data, and trained an explainable logistic-regression fraud-scoring model with feature importance for second-line challenge. All four workstreams roll up into an integrated Power BI executive dashboard, supported by RCSA-style documentation and a regulatory alignment note mapped to OSFI, Bank of Canada PPS, and RPAA expectations, directly demonstrating the quantitative risk modeling and AI-explainability skillset increasingly expected in 2026 ERM roles.

**Skills demonstrated:** PD-style credit risk scoring, intraday liquidity stress testing, fraud KRI design, scikit-learn model building and explainability, Power BI executive dashboarding, RCSA and Three Lines of Defence framing, regulatory alignment mapping.

---

## 🧠 What I’m Working On

I'm currently building two portfolio projects that push into the areas I'm actively growing: continuous compliance operations engineering and AI governance for regulated environments. Both are genuinely in progress and here's where they actually stand today.

### [Security Compliance Operations Engine - ISO 27001, SOC 2 Type II, PIPEDA & TPRM (In Progress)](https://github.com/prasanna-sriram/northstar-compliance-operations-engine)

Simulating the operating model of a Senior Security Compliance Engineer at a fictional cloud-native digital bank, this project is being built incrementally with working scripts and validated outputs rather than static placeholders. 

**Built so far:** a full compliance data layer (controls, evidence, policies, risks, vendors, privacy requests); five Python automation scripts covering evidence-freshness checks, policy review tracking, remediation aging, control-effectiveness summaries, and DSAR SLA monitoring; a risk-scoring engine that ranks and flags high-severity overdue risks for a management-review report; a vendor-tiering engine that scored and tiered all 35 vendors, flagged 14 as High tier and caught 4 cases of tier drift a static spreadsheet would have missed; and a PIPEDA-aligned DSAR/privacy operations module with a six-stage intake-to-closure workflow. 

**Still to come:** the Power BI dashboard (executive, control-ops, risk, vendor, and privacy views) and the final audit-evidence index and customer-facing security review pack.

### [AI Governance and Controls Program - Enterprise AI Gateway (MeridianBank) (In Progress)](https://github.com/prasanna-sriram/ai-governance-controls-gateway)
Simulating the work of an AI Governance & Controls Lead standing up governance for a fictional bank's internal GenAI gateway, mapped to the NIST AI RMF and ISO/IEC 42001. The objective is to show governance enforced mechanically at a platform layer (Azure API Management, Entra ID, Key Vault, Azure Monitor) rather than through annual policy attestation. 

**Built so far:** the first three AI standards (model approval, human oversight, logging/retention) fully drafted. 

**Still to come:** finishing the agentic-guardrails and acceptable-use standards, building the full Obligation → Control → Evidence mapping table, provisioning the Azure enforcement layer and RBAC roles, designing the AI use case/agent registry and its Python validation script, building the policy-exception/TRM deviation tracker, assembling the examiner-readiness evidence package, and building the final Power BI governance dashboard.

---

## Collaboration

Open to collaborating on:
- ERM and second-line risk analytics projects
- GRC automation and continuous controls monitoring
- Third-party/vendor risk management tooling
- Cybersecurity maturity and cloud security compliance projects
- AI risk and governance initiatives

 Reach out via [LinkedIn](https://www.linkedin.com/in/prasanna-sriram/) or open an issue on any of the repos above.

<details>
<summary>📦 Additional Projects (click to expand)</summary>

These earlier projects reflect foundational SQL, Python, and Power BI analytics work built while developing the risk-analytics skillset behind the featured projects above.

- **[Global COVID-19 Data Analysis with SQL and Tableau](https://github.com/prasanna-sriram/covid19-global-data-analysis)** - Analyzed global COVID-19 data using SQL to uncover trends in infection, death rates, and vaccination progress, with time series and geographic insights. *Skills: SQL, Data Cleaning, Aggregations, Joins, Time Series Analysis.*
- **[Tech Job Market Trends Analysis with Python, Web Scraping, and Power BI](https://github.com/prasanna-sriram/tech-jobs-survey-analysis)** - Used APIs, web scraping, and survey data to identify top tech skills, job locations, and salary trends, visualized in Python and Power BI. *Skills: Python, Pandas, API Access, Web Scraping, Data Visualization.*
- **[Box Office Revenue Drivers Analysis with Python](https://github.com/prasanna-sriram/movie-revenue-analysis)** - Analyzed movie data to find correlations between budget, votes, and revenue, with data cleaning and feature engineering. *Skills: Python, Pandas, EDA, Feature Engineering, Correlation Analysis.*
- **[Coffee Sales Analysis for Retail Performance Optimization](https://github.com/prasanna-sriram/coffee-sales-analysis)** - Built a Power BI dashboard analyzing coffee shop sales, orders, and quantities sold for dynamic revenue tracking. *Skills: Power BI, DAX, Power Query, KPI Design.*
- **[HR Data Analytics Dashboard for Workforce Insights](https://github.com/prasanna-sriram/hr-data-analysis)** - Built a Power BI dashboard analyzing promotions, retention risk, job satisfaction, and gender balance. *Skills: Power BI, DAX, Data Modeling, Executive Reporting.*
- **[Real Estate Data Cleaning & Transformation using SQL for Nashville Housing](https://github.com/prasanna-sriram/nashville-housing-data)** - Cleaned and transformed real estate data using SQL, handling nulls, address parsing, and deduplication. *Skills: SQL, Data Cleaning, Window Functions, ETL Logic.*

</details>

---

## 📫 Let’s Connect!

- 💼 [LinkedIn](https://www.linkedin.com/in/prasanna-sriram/)  

---
