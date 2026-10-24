# Awesome-Cloud-Application-Development-Platform

# Top Cloud Application Development Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Low-Code Builders, Enterprise PaaS & Self-Hosted Application Platforms*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Application Development Platforms**. These tools enable teams to build, deploy, and scale custom applications—internal tools, customer portals, and workflow apps—using visual builders, pre-built connectors, and managed infrastructure rather than starting from scratch.

**Examples** include Adobe App Builder, Retool, Mendix, OutSystems, Microsoft Power Apps, Appian, Quickbase, and open-source leaders like Appsmith, Budibase, and ToolJet (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding per-user or per-credit SaaS fees, and controlling the application runtime. The open-source landscape is anchored by **Appsmith** (the most widely adopted Retool alternative), **Budibase** (the all-in-one platform with built-in database), and **ToolJet** (the enterprise-focused builder), with **Windmill** serving developer-first script-to-UI workflows and **NocoDB** providing Airtable-style database frontends.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- |
| **[Retool](https://retool.com/)** | The category-defining internal tool builder with AI-native app generation, workflows, and self-hosting options. | **Team**: $10/builder/mo + $5/internal user/mo. **Business**: $50/builder/mo + $15/internal user/mo. **Enterprise**: custom . | **Free**: Up to 5 users, 500 workflow runs/month, 5GB database storage, 20 agent hours/month . |
| **[Microsoft Power Apps](https://powerapps.microsoft.com/)** | Microsoft's low-code platform integrated with the Power Platform and Dataverse. | **Premium (per user)**: ~**$20/user/month** for unlimited apps and premium connectors. **Pay-as-you-go (per app)**: ~**$10/active user/app/month** . | **Nonprofit offer**: Free for up to 10 users, $2.50/user/mo for additional users . No general free tier; Developer Plan available for non-production use. |
| **[Mendix](https://www.mendix.com/)** | Enterprise low-code with multi-app support and Siemens ecosystem alignment. | **Starting price**: **€52.50/month** (~$57) per Software Advice listing . Enterprise tiers are quote-based. | **Free tier**: 1 app, limited users, Mendix Cloud hosting (specific limits not detailed in search results). |
| **[OutSystems](https://www.outsystems.com/)** | Enterprise high-performance low-code platform with full DevOps automation. | **Starting price**: **$36,300/year** (~$3,025/month) per Software Advice listings . Enterprise pricing is quote-based. | **Free tier**: 1 app, up to 100 end users, one environment (dev/test/prod combined). |
| **[Appian](https://appian.com/)** | Enterprise process automation and low-code platform with strong workflow capabilities. | **Starting price**: **$75/month** per Software Advice . Standard/Advanced/Premium tiers available; enterprise quotes vary. | **Appian Community Edition**: Free for developers, 1 app, limited users, non-production use. |
| **[Quickbase (Pave)](https://www.quickbase.com/)** | No-code platform focused on operational workflows with credit-based pricing. | **Team**: ~$120 credits/month (specific dollar amount for Team tier not shown in results). **Department**: **$300/mo** for 1,800 credits . | **Free**: 1 app, 1 builder, up to 3 users, **100 free credits** (then $20 per 100 credits) . |
| **[Caspio](https://www.caspio.com/)** | No-code database app builder with **no per-user fees**—priced by records and features. | **Team (prepaid)**: **$15/month** . Business and Enterprise tiers scale with records and add-on blocks. | **Free trial**: 14 days with full access to core features. No permanent free tier . |
| **[Adobe App Builder](https://developer.adobe.com/app-builder/)** | Extensibility framework for building custom experiences that extend Adobe solutions. | **Pack-based licensing** (1-year). Each pack includes 6M GB-seconds I/O runtime, 24M custom events, 10TB CDN egress, 1TB file storage, 10GB key-value storage, 40GB database storage . Contact Adobe for pack pricing. | **No free tier**. Available as add-on to Adobe products or standalone license . |

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
