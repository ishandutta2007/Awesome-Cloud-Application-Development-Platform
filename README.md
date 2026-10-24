# Awesome-Cloud-Application-Development-Platform

## Top Cloud Application Development Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Low-Code Builders, Enterprise PaaS & Self-Hosted Application Platforms*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Application Development Platforms**. These tools enable teams to build, deploy, and scale custom applications—internal tools, customer portals, and workflow apps—using visual builders, pre-built connectors, and managed infrastructure rather than starting from scratch.



**Examples** include Adobe App Builder, Retool, Mendix, OutSystems, Microsoft Power Apps, Appian, Quickbase, and open-source leaders like Appsmith, Budibase, and ToolJet (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding per-user or per-credit SaaS fees, and controlling the application runtime. The open-source landscape is anchored by **Appsmith** (the most widely adopted Retool alternative), **Budibase** (the all-in-one platform with built-in database), and **ToolJet** (the enterprise-focused builder), with **Windmill** serving developer-first script-to-UI workflows and **NocoDB** providing Airtable-style database frontends.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global cloud application and low-code development platform market is estimated at approximately **$37 billion to $48 billion** (scaling towards $50B+ with a ~25–30% CAGR), driven by enterprise digital transformation, developer shortages, and agentic AI app generation. The market structure is **moderately concentrated**—anchored at the top tier by major software giants and enterprise suites (e.g., Microsoft Power Apps, Siemens Mendix, OutSystems, Appian), complemented by a diverse, fragmented ecosystem of developer-first builders, specialized database workflow tools, and open-source alternatives.

## SaaS/Hosted Platforms

| Product | Description | Valuation / Revenue Scale | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Power Apps](https://powerapps.microsoft.com/)** | Microsoft's enterprise low-code platform deeply integrated into Microsoft 365, Power Platform, Azure, and Dataverse. | ~$3.9T Market Cap (Microsoft) | **$20/user/month** (Power Apps Premium for unlimited apps); or **$5/user/app/month** (Power Apps per-app subscription). | **No permanent production free tier**. Offers a 30-day free trial and a permanent **Developer Plan** strictly limited to 1 user for non-production development/learning. |
| **[Adobe App Builder](https://developer.adobe.com/app-builder/)** | Serverless extensibility framework for building custom cloud-native apps that extend Adobe Experience Platform, Commerce, and Workfront. | ~$105B Market Cap (Adobe) | **Pack-based annual licensing**; base deployments typically start at ~$15,000–$30,000/year (or bundled in qualifying Adobe Commerce/AEM cloud contracts). Standard Pack includes 6M GB-s compute, 24M events, 10TB CDN, 1TB file storage. | **No permanent free tier**. Enterprise trial sandbox access provided upon request via Adobe Developer Sales (strictly capped for non-production/staging: 200MB state storage, 0 PII data). |
| **[Mendix](https://www.mendix.com/)** | Enterprise-grade low-code application development platform designed for complex multi-experience enterprise applications. | ~$150B Market Cap (Parent Siemens AG / Acquired for $730M) | **Basic**: **€52.50/month** (~$57/month, up to 5 named users per app). **Standard**: starts at **€840/month** (~$915/month). | **Free Edition (Forever Free)**: 1 deployed cloud app, up to 0.5 GiB (512 MB) database storage, 1 GiB file storage; app sleeps after 1 hour of inactivity. |
| **[OutSystems](https://www.outsystems.com/)** | High-performance enterprise low-code development platform supporting mission-critical web and mobile systems. | ~$4.3B–$9.5B Valuation (~€500M+ ARR) | Starts at **$36,300/year** (billed annually, ~$3,025/month for entry-level enterprise deployment). | **Free Edition (Forever Free)**: 1 app environment (dev/test/prod combined), up to 100 end users, and 1 GB shared database storage. |
| **[Retool](https://retool.com/)** | Developer-centric visual development environment for building internal web apps, dashboards, and automated workflows. | ~$3.2B Valuation (~$120M ARR) | **Team**: **$10/builder/month + $5/end-user/month**. **Business**: **$50/builder/month + $15/end-user/month**. | **Free Plan (Forever Free)**: Up to 5 users, 500 workflow runs/month, 5 GB Retool Database storage, and 20 AI agent hours/month. |
| **[Appian](https://appian.com/)** | Enterprise low-code process automation platform combining workflow orchestration, data fabric, and AI-driven document processing. | ~$3.1B Market Cap (NASDAQ: APPN, ~$600M ARR) | Standard entry tiers start at **$75/user/month** (typically requires annual agreement with a 100-user baseline enterprise minimum). | **Community Edition (Forever Free)**: 1 dedicated developer environment, limited to 1 user for non-production prototyping and learning. |
| **[Quickbase (Pave)](https://www.quickbase.com/)** | No-code work management and operational application platform connecting operational data with business workflows. | ~$1.0B Valuation (~$215M ARR) | **Team Plan**: starts at **$35/user/month** (billed annually; subject to baseline platform contract minimums). | **Free Trial**: **30-day free trial** with access to Team features and up to 100 credits; no permanent free tier. |
| **[Caspio](https://www.caspio.com/)** | No-code relational database and business application builder with zero per-user licensing fees. | ~$120M Estimated Revenue | **Team Plan**: starts at **$300/month** (billed annually at $3,600/year, includes unlimited application users and 50,000 data records). | **Free Trial**: **14-day free trial** with full platform features and testing capacity; no permanent free tier. |

## Open-Source GitHub Projects



- **[Appsmith](https://github.com/appsmithorg/appsmith)** [![GitHub Stars](https://img.shields.io/github/stars/appsmithorg/appsmith?style=social&color=white)](https://github.com/appsmithorg/appsmith/stargazers)  

  **The most widely adopted open-source Retool alternative.** Build admin panels, dashboards, and CRUD apps by dragging widgets and connecting to 25+ databases and any REST API. **Features**: JavaScript anywhere, Git sync for version control, granular RBAC, audit logs, and self-hosting via Docker/Kubernetes. **Cloud pricing**: Free for up to 5 users; Business $15/user/month; Enterprise $2,500 for 100 users. **Community Edition** is free to self-host with no user limits. Best for teams wanting a mature, well-documented builder with the broadest data source coverage.



- **[Budibase](https://github.com/Budibase/budibase)** [![GitHub Stars](https://img.shields.io/github/stars/Budibase/budibase?style=social&color=white)](https://github.com/Budibase/budibase/stargazers)  

  **The all-in-one platform with built-in database.** Combines an internal DB (or connects to external sources), drag-and-drop app builder, automation engine, and AI agent builder in one package. **Features**: 40+ pre-built components, workspace management, user roles, and SSO on paid tiers. **Cloud pricing**: Free (1 creator, 50k DB rows); Premium $49/mo (1 creator, 250k rows); Business $299/mo (3 creators, 500k rows). **Self-hosted** is free with no creator limits. Best for teams wanting a single platform covering database, UI, and automation without stitching tools together.



- **[ToolJet](https://github.com/ToolJet/ToolJet)** [![GitHub Stars](https://img.shields.io/github/stars/ToolJet/ToolJet?style=social&color=white)](https://github.com/ToolJet/ToolJet/stargazers)  

  **The enterprise-focused builder with strong data source coverage.** Connects to PostgreSQL, MySQL, MongoDB, Snowflake, BigQuery, S3, and any REST/GraphQL API. **Features**: visual app builder with 50+ widgets, JavaScript code support, multi-page apps, granular permissions, and audit logs. **Self-hosted** Community Edition is free with no user limits. Best for teams needing a polished UI builder with enterprise features and broad database support.



- **[Windmill](https://github.com/windmill-labs/windmill)** [![GitHub Stars](https://img.shields.io/github/stars/windmill-labs/windmill?style=social&color=white)](https://github.com/windmill-labs/windmill/stargazers)  

  **The developer-first platform turning scripts into UIs.** Write logic in Python, TypeScript, Go, Bash, or SQL; Windmill auto-generates UIs, APIs, and workflows. **Features**: Git-based deployment, VS Code extension, secrets management, and self-hosting via Docker/Helm. **License**: AGPL-3.0 for core; enterprise features under commercial license. Best for engineering teams that want to build internal tools by writing code, not dragging widgets.



- **[NocoDB](https://github.com/nocodb/nocodb)** [![GitHub Stars](https://img.shields.io/github/stars/nocodb/nocodb?style=social&color=white)](https://github.com/nocodb/nocodb/stargazers)  

  **The Airtable alternative for existing databases.** Turns any Postgres, MySQL, SQLite, or SQL Server database into a spreadsheet-like interface with forms, galleries, and kanban views. **Features**: REST APIs auto-generated, webhooks, and role-based access. **Self-hosted** is free and open-source. Best for teams wanting a familiar spreadsheet UI over their existing data without migrating it.



### Additional Strong Open-Source Options



- **Baserow** — Open-source Airtable alternative with a modern UI. Spreadsheet-database hybrid with views, formulas, and API access. Self-hosted via Docker is free. Best for teams wanting a polished Airtable-like experience they can host themselves.

- **Directus** — Database-first headless CMS and data platform that wraps any SQL database with a no-code admin UI. Best for teams that want an instant admin panel over an existing schema.

- **Appwrite** — Self-hosted backend-as-a-service with database, auth, storage, and functions. Best for teams building internal tools that need a backend layer alongside the UI.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **Pricing models vary dramatically**: Retool charges per builder plus per internal user; Power Apps charges per user or per app; Caspio charges by records with **no per-user fees** ; Adobe App Builder uses resource packs rather than seats . Model your actual usage pattern before committing.

- **Free tiers are for evaluation, not production**: Retool Free caps at 5 users and 500 workflow runs ; Power Apps Developer Plan is explicitly non-production; OutSystems Free limits to 100 end users; Caspio offers only a 14-day trial .

- **Adobe App Builder is not a standalone low-code builder**: it's an extensibility framework for Adobe solutions, licensed in resource packs rather than seats . Only relevant if you're already in the Adobe ecosystem.

- **Open-source platforms still require infrastructure**: Appsmith, Budibase, and ToolJet all need servers, databases, and maintenance—free software is not free operations.



---



**Made for operations teams, internal tool builders, and developers who want to ship applications without writing full frontend code.**  

Let's make cloud application development more open, appropriately priced, and self-hostable.
