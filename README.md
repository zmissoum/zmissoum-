# 👋 Hey, I'm Zakaria

**CRM Architect & Product Builder**  
Helping enterprises migrate between Salesforce and Dynamics 365 | Building the missing infrastructure for CRM transformations

---

## 🚀 My CRM Product Suite

I don't just consult — I build production-grade tools that automate what's currently done manually.

### [Colvio](https://github.com/zmissoum/colvio) - Free & Open-Source ⭐
**The Salesforce Inspector for Dynamics 365**

The missing browser-native tool for D365 consultants, admins, and developers.

**6,200 lines of code** • **11 functional modules** • **Production-ready** • **Chrome Extension**

🔍 **Key Features:**
- **Data Explorer**: Visual query builder with 4 modes (Builder, OData, FetchXML, SQL→FetchXML translator)
- **Virtual Scrolling**: 60fps performance on 10,000+ records
- **Security Audit**: Flag 30+ sensitive privileges, role-based access control
- **Data Loader**: CSV/Excel import with auto-mapping and lookup resolution
- **Metadata Browser**: Navigate entities, fields, OptionSets with ease
- **Users Monitor**: Identify unused licenses, export comprehensive reports
- **Translation Manager**: Edit field labels in multiple languages

**Tech Stack**: React 18, TypeScript, Chrome Extension Manifest V3, Dataverse Web API, FetchXML

**Impact**: First browser-native tool covering exploration + import + audit + metadata for Dynamics 365

⭐ **[Star Colvio on GitHub](https://github.com/zmissoum/colvio)** if you find it useful!

---

### [Dynovo](https://dynovo.io) - Coming Soon 🚧
**Salesforce → Dynamics 365 Migration Accelerator**

SaaS platform that automates the repetitive tasks of CRM migration, eliminating ~40% of manual work so consultants can focus on business decisions and custom code.

**Architecture**: 4-phase migration pipeline (Audit → Clean → Plan → Migrate)

📊 **S1 - Audit** (30 minutes for complete org inventory)
- **30+ metadata extractors**: Objects, fields, workflows, triggers, validation rules, security, integrations
- **Scoring engine**: 8 complexity dimensions + 6 health check axes
- **Apex code analysis**: Static analysis of custom code complexity
- **Field usage detection**: 7 data sources to identify unused fields
- **Effort estimation**: With/without Dynovo comparison
- **Outputs**: PDF executive summary, Excel workbook (15 tabs), PowerPoint deck

🧹 **S2 - Clean**
- Identifies unused objects/fields, dead metadata, orphan fields
- Generates cleanup plan with justifications
- Executes pre-migration cleanup via Metadata API

🗺️ **S3 - Plan**
- Automated SF→D365 field mapping with lookup resolution
- Schema provisioning in D365 via Web API
- Handles custom objects + standard object extensions

📦 **S4 - Migrate**
- Data extraction via Salesforce Bulk API
- Transformation layer (picklists, lookups, data types)
- Idempotent upsert loading into Dynamics 365
- Document migration (Attachments, Files) → SharePoint integration

**Target**: Consultancies, integrators (Accenture, Capgemini), enterprises with in-house teams

**Value**: Accelerates migrations, reduces risk, frees consultants for high-value work

---

### [Cerulio](https://app.cerulio.io) - Coming Soon 🚧
**Dynamics 365 → Salesforce Migration Accelerator**

SaaS platform that automates the repetitive tasks of CRM migration, eliminating ~40% of manual work so consultants can focus on business decisions, security redesign, and C# plugin rewrites.

**Architecture**: 4-phase migration pipeline (Audit → Clean → Plan → Migrate)

📊 **S1 - Audit** (~10 min for complete Dataverse inventory)
- **58 Dataverse elements scanned**: Entities, C# Plugins, Business Process Flows, Security Roles, Power Automate, Web Resources (JS), Model-driven Apps, Dashboards, Views, Forms, and more
- **Scoring engine**: 12 complexity dimensions with prioritized recommendations
- **Static analysis**: JavaScript code analysis + C# plugin anti-patterns detection
- **License analysis**: Identify active/inactive modules and optimization opportunities
- **Technical debt assessment**: GDPR compliance check, deprecated features detection
- **Outputs**: PDF executive summary, Excel workbook (6 tabs), PowerPoint deck (7 slides)
- **Languages**: French, English, Spanish

🧹 **S2 - Clean**
- Identifies empty entities, low-fill-rate attributes, inactive Classic Workflows
- Detects disabled Business Rules, unreferenced Web Resources
- **Data quality scoring** with AI-powered cleanup justifications
- Executes pre-migration cleanup to optimize scope

🗺️ **S3 - Plan**
- **Automated schema mapping**: D365 → Salesforce with SF Describe resolution
- **Security conversion**: D365 Security Roles (Business Units + CRUDAA) → Salesforce Profiles + Permission Sets
- **Process transformation**: Business Process Flows → Lightning Path + Salesforce Flow
- **ISV solution mapping**: Managed solutions → AppExchange equivalent identification
- **Schema provisioning**: Creates Salesforce schema via Metadata API

📦 **S4 - Migrate**
- Data extraction via D365 OData v4 API
- Transformation engine:
  - OptionSets: int codes → string values
  - Lookups: D365 GUIDs → Salesforce IDs
  - Statecode → Salesforce Picklist mapping
- Loading via Salesforce Bulk API 2.0 with idempotent upserts
- **Document migration**: Annotations + SharePoint + email attachments → Salesforce ContentDocument

**Standalone Audit Mode** (usable without migration):
- **Audit + Clean plan**: €990
- Audit and clean any D365 environment independently of Salesforce migration
- Perfect for health checks, technical debt assessment, pre-upgrade cleanup

**Target**: Consultancies, integrators, enterprises with in-house teams

**Value**: Accelerates migrations, reduces risk, frees consultants for high-value work

---

**Why 3 products?**

Most CRM migrations are slow, risky, and expensive because they're done manually. I'm building the missing automation infrastructure:

- **Colvio** (free, open-source) → Browser tool for daily D365 work. Proves technical capability, serves the community
- **Dynovo** (SF→D365) → Enterprise migration accelerator. 30+ extractors, reduces ~40% manual work, 30-min audit vs 2-week manual inventory
- **Cerulio** (D365→SF) → Enterprise migration accelerator. 58-element scan in ~10 min, reduces ~40% manual work, standalone audit mode (€990)

**Symmetry by design**: Both commercial products follow the same 4-phase architecture (Audit → Clean → Plan → Migrate) and deliver the same ~40% efficiency gain. Different migration directions, identical value proposition.

Together they demonstrate:
1. **Deep technical expertise** in both platforms (not surface-level consulting)
2. **Ability to ship production-grade products** (not just POCs or side projects)
3. **Understanding of real enterprise pain points** (from 9 years hands-on migration experience)

---

## 💼 What I Do Professionally

**CRM Architect** with 9 years of experience specializing in:

- 🔄 **Complex CRM Migrations**: Salesforce ↔ Dynamics 365 at enterprise scale
- 🏗️ **Solution Architecture**: Multi-cloud Salesforce, D365 + Power Platform
- 💻 **Hands-on Development**: Apex, Lightning Web Components, React, Dataverse APIs
- 🎯 **Technical Leadership**: Coordinating integrators (Accenture, Capgemini) and vendors (Microsoft)

**Recent Mission**: Lead Architect for complete Salesforce → D365 migration at TotalEnergies (Sept 2024 - Jan 2026)
- Multi-org migration, millions of records with full historical preservation
- Data migration orchestration with Accenture integration team
- Coordination across architects, IT, business stakeholders, Microsoft vendor
- Zero downtime cutover, on-time delivery

This hands-on migration experience directly informed the design of Dynovo and Cerulio — every feature solves a real pain point I encountered.

---

## 🛠️ Tech Stack

**Salesforce**  
Apex • SOQL • Lightning Web Components • Metadata API • Tooling API • Bulk API • SFDX • Copado

**Microsoft Dynamics 365**  
Dataverse • Power Platform • Web API • OData • FetchXML • C# Plugins • Model-driven Apps • Business Process Flows

**Development**  
React 18 • TypeScript • JavaScript ES6+ • Python • Chrome Extensions • Git • CI/CD

**Architecture & Integration**  
REST/SOAP APIs • Azure • OAuth 2.0 • AES Encryption • Multi-cloud • ERP/ESB/ETL integrations

**Migration & Data**  
ETL pipelines • Bulk API • Schema mapping • Data transformation • Idempotent upserts

---

## 🎓 Certifications

**Salesforce** (7 certifications)
- Data Architect ⭐
- Application Architect ⭐
- Sharing & Visibility Architect ⭐
- Platform Developer I
- App Builder
- Administrator
- Associate

**Copado** (3 certifications)
- Administrator
- Developer
- Consultant

---

## 📊 GitHub Stats

![Zakaria's GitHub Stats](https://github-readme-stats.vercel.app/api?username=zmissoum&show_icons=true&theme=radical&hide_border=true)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=zmissoum&layout=compact&theme=radical&hide_border=true)](https://github.com/zmissoum)

---

## 🌟 Product Philosophy

**Colvio** is free and open-source because I believe in giving back to the community. Zero telemetry, no data collection, no external servers. If you're a D365 consultant, star it and share it.

**Dynovo and Cerulio** are commercial SaaS products, but they're built on the same principle: **automate the boring stuff so humans can focus on the interesting problems**.

Migrations shouldn't take 6-12 months when 40% of the work is mechanical. The industry needs better tools, not more manual labor.

---

## 📫 Let's Connect

- 💼 [LinkedIn](https://linkedin.com/in/zakaria-missoum)
- 🌐 [Malt Profile](https://malt.fr/profile/zakariamissoum) (freelance consulting)
- 🔗 [Dynovo](https://dynovo.io) (SF → D365 migration)
- 🔗 [Cerulio](https://app.cerulio.io) (D365 → SF migration)
- 📧 zakaria.missoum.pro@gmail.com

---

## 🎯 Currently Working On

- 🔨 Finalizing Dynovo S1 Audit engine (30+ Salesforce metadata extractors)
- 📦 Building Cerulio S3 Plan mapper (58 D365 elements → Salesforce schema)
- 🌟 Preparing Colvio v2.0 for Chrome Web Store release
- 📚 Writing migration playbooks based on TotalEnergies experience

---

## 💡 Technical Highlights

**Custom SQL→FetchXML Parser** (Colvio)  
Built a complete tokenizer + recursive descent parser to translate SQL queries to FetchXML. Handles JOINs, WHERE clauses, aggregations, subqueries. 400+ lines of parsing logic.

**Virtual Scrolling at 60fps** (Colvio)  
Renders 10,000+ Dataverse records in browser using windowing technique with DOM recycling. Outperforms Dynamics UI by 3x.

**Idempotent Upsert Engine** (Dynovo, Cerulio)  
Handles lookup resolution, retries, and partial failures during bulk data loading. Ensures migrations can be re-run safely.

**Security Role Converter** (Cerulio)  
Maps D365 CRUDAA permissions (Create, Read, Update, Delete, Append, AppendTo) to Salesforce CRUDLS (Create, Read, Update, Delete, List, Search) + Profile + Permission Set architecture.

**Business Process Flow → Lightning Flow** (Cerulio)  
Analyzes D365 BPF structure (stages, steps, conditions) and generates equivalent Salesforce Flow definition via Metadata API.

---

## 🏆 Why This Matters

I've seen migrations fail because:
- Manual audits miss critical dependencies (costs 2+ months in rework)
- Schema mapping errors corrupt data (costs credibility + client trust)
- Security models are copy-pasted incorrectly (compliance risk)
- Document migration is treated as an afterthought (users lose files)

**Dynovo and Cerulio exist because these problems are solvable with automation.**

Consultants are expensive. They should design architectures and solve business problems, not spend weeks extracting metadata or mapping fields in Excel.

---

⭐ **If you work with Dynamics 365, check out [Colvio](https://github.com/zmissoum/colvio) — it's free and might save you hours every week.**

---
