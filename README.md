# Enterprise Digital Transformation & Data Infrastructure
**Bleve Engenharia de Incêndio** | *Information Architecture, Cloud Migration & Workflow Automation*

---

### Executive Summary

Bleve Engenharia de Incêndio is an industrial and residential fire protection engineering firm with 30 years of market presence. 

This project addresses the end-to-end digital transformation of the company’s data infrastructure. Prior to this initiative, the organization faced significant operational bottlenecks caused by decentralized local storage, lack of data standardization, and fragmented business workflows.

The core objective was to migrate local operations to a secure, centralized Microsoft 365 cloud architecture, establish data governance, and prepare the foundation for advanced analytics and automated workflows.

---

### Key Challenges

* **Data Fragmentation:** Critical business documents, design models, and project assets were stored locally on individual machines without centralized access or cloud integration.
* **Lack of Standardization:** Absence of unified file naming conventions, version control, and document structure, leading to duplicate files and outdated data usage.
* **Process Inefficiencies:** Manual communication channels lacking structured intake workflows or automated customer query management.

---

### Solution Architecture & Implementation

#### 1. Information Architecture & Access Control (SharePoint)
Structured a centralized information system categorized into five core operational directories:

* `01 - Projects by Client:` Standardized repository for active and legacy engineering projects.
* `02 - Administrative & Financial:` Restricted directory for core corporate governance.
* `03 - Templates & Standards:` Centralized repository for engineered document models.
* `04 - IT & Systems:` Infrastructure, software management, and security protocols.
* `05 - Technical Library:` Specialized technical references and engineering regulatory assets.

*Role-Based Access Control (RBAC):* Implemented granular permissions to secure sensitive financial, administrative, and technical assets while maintaining open collaboration on active project files.

#### 2. Enterprise Ecosystem Integration (Microsoft 365)
* **Domain & Security:** Deployed corporate domain identity (`@bleve.com`), multi-factor authentication (Microsoft Authenticator), and identity management.
* **Collaborative Tools:** Integrated Outlook, Teams, SharePoint, Visio, PowerPoint, and Excel Online to align cross-functional teams.
* **Business Automation:** Configured Power Automate to handle background data sync and workflow triggers.

#### 3. Communication & Data Intake Pipeline (Meta & SendPulse)
* **API Integration:** Integrated the corporate WhatsApp number directly with the Meta Business API and SendPulse platform.
* **Workflow Automation (In Progress):** Designing automated customer interaction flows to capture intake data, log query records, and streamline project requests.

---

### Business Impact & Data Foundations

* **Single Source of Truth:** Centralized 100% of corporate data, eliminating file duplication and version conflicts across teams.
* **Data Governance & Readiness:** Established clean, structured directory hierarchies and data intake protocols, laying the foundation for future Power BI dashboards and SQL reporting.
* **Security & Compliance:** Enforced identity verification and access restrictions across critical business units.

---

### Tech Stack

`Microsoft 365` · `SharePoint Architecture` · `Power Automate` · `Meta Business API` · `SendPulse` · `Information Governance`
