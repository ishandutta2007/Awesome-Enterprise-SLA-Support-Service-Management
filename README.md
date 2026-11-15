# Awesome-Enterprise-SLA-Support-Service-Management

# Top Enterprise SLA & Support Service Management Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on ITIL Service Delivery, SLA Tracking & Self-Hosted Service Desks*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise SLA & Support Service Management**. These tools help organizations deliver IT and business services with measurable commitments—covering everything from incident and request management with SLA tracking to self-service portals and service catalogs.

**Examples** include ServiceNow, Jira Service Management, Freshservice, BMC Helix, SolarWinds Service Desk, SysAid, GLPI, and Znuny (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted service management, open-source ITSM with SLA tracking, and community-driven service desks—ideal for organizations seeking data sovereignty and avoiding per-agent or per-fulfiller SaaS pricing. The open-source landscape is genuinely functional: **GLPI** provides a complete ITIL service desk with SLA tracking and asset management , **Znuny** offers audit-proof ticket management with SLA foundations , and **heidsoft/itsm** delivers an AI-native platform with BPMN orchestration and CMDB .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[ServiceNow](https://www.servicenow.com/)** | **The enterprise ITSM benchmark.** Full ITIL practice coverage with CMDB, discovery, and AIOps. **IRM Standard ($125/operator/month)** for risk; ITSM pricing is quote-only and scales with fulfiller seats . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)** | **Most accessible enterprise ITSM for Atlassian shops.** Premium: **~$55/agent/month**. **Free tier: 3 agents, unlimited customers**. SLA management, request types, and knowledge base included. | Premium: **~$55/agent/month**; Free: 3 agents | **Free**: 3 agents, unlimited customers, 2 GB storage |
| **[Freshservice](https://www.freshworks.com/freshservice/)** | AI-powered IT service management with Freddy AI. SLA tracking, service catalog, and multi-department ESM. | Quote-only (tiered by agents) | **14-day free trial**; no permanent free tier |
| **[BMC Helix](https://www.bmc.com/)** | Enterprise ITSM with AIOps and automation. **HelixGPT** for AI-assisted service management. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[SolarWinds Service Desk](https://www.solarwinds.com/)** | ITSM with **$39/technician/month** pricing. Includes incident, problem, change, and asset management. | **$39/technician/month** | **30-day full-featured trial** |
| **[SysAid](https://www.sysaid.com/)** | AI-powered ITSM with zero-trust data segregation for multi-department ESM. | Quote-only (tiered by agents) | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[GLPI](https://github.com/glpi-project/glpi)** | [![Stars](https://img.shields.io/github/stars/glpi-project/glpi?style=social&color=white)](https://github.com/glpi-project/glpi/stargazers) | **The most complete open-source ITIL service desk with SLA tracking and asset management.** PHP/MySQL. **Trusted by 100,000+ organizations** worldwide . **ITIL Service Desk** with incident, request, problem, and change management; **SLA tracking** for response and resolution targets; **CMDB** and asset inventory with agentless network discovery; **service catalog** for standardized requests; and a **plugin architecture** for extensibility . **Best for organizations wanting a proven, full-featured ITSM platform** with SLA management and asset lifecycle tracking in one self-hosted package . |
| **[Znuny](https://github.com/znuny/Znuny)** | [![Stars](https://img.shields.io/github/stars/znuny/Znuny?style=social&color=white)](https://github.com/znuny/Znuny/stargazers) | **Audit-proof open-source ticket management (LTS fork of OTRS Community Edition).** GPL-3.0. **Communications are unchangeable**—all modifications documented with who/what/when for regulatory compliance. **SLA foundations** for response and resolution targets. **SAML authentication** added in v7.3.1 . **Best for IT service management and regulated environments** requiring immutable audit trails . |
| **[heidsoft/itsm](https://github.com/heidsoft/itsm)** | [![Stars](https://img.shields.io/github/stars/heidsoft/itsm?style=social&color=white)](https://github.com/heidsoft/itsm/stargazers) | **AI-native open-source ITSM platform with BPMN orchestration and CMDB.** Apache-2.0. **Covers tickets, incidents, problems, changes, service requests, service catalogs, SLA, CMDB, and knowledge** . **AI is embedded into triage, summarization, and workflow recommendations**—degradable and auditable . **Multi-tenant** for MSP and SaaS modes. **Status: v1.6.x production hardening phase**—validate before production . **Best for organizations wanting a modern, AI-native ITSM foundation** with BPMN orchestration. |
| **[OTRS (OTOBO)](https://github.com/rotheross/otobo)** | [![Stars](https://img.shields.io/github/stars/rotheross/otobo?style=social&color=white)](https://github.com/rotheross/otobo/stargazers) | **Open-source ticketing and ITSM system forked from OTRS.** **ITSM add-on packages are free**—CMDB, service catalog, and process management included. **Production servers need 8–16 GB RAM** . Vendor support from €3,900/year. **Best for IT teams wanting OTRS-style service desk** with optional commercial support. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Frappe Helpdesk](https://github.com/frappe/helpdesk)** | [![Stars](https://img.shields.io/github/stars/frappe/helpdesk?style=social&color=white)](https://github.com/frappe/helpdesk/stargazers) | **Modern open-source customer service platform with SLA-driven ticket management.** Built on Frappe framework. **SLA monitoring tool for defining and tracking response time targets**; auto-assignment by priority/type/team/workload; **unlimited agents with no seat fees**; customer sync with ERPNext . **Best for organizations already on Frappe/ERPNext** wanting service management with ERP integration . |
| **[Libredesk](https://github.com/abhinavxd/libredesk)** | [![Stars](https://img.shields.io/github/stars/abhinavxd/libredesk?style=social&color=white)](https://github.com/abhinavxd/libredesk/stargazers) | **Omnichannel support management with SLA breach monitoring.** Go-based, single binary. **Monitors response time targets and triggers notifications when conversations risk breaching SLAs**. AI customer support automation for generating responses . **Best for teams wanting a lightweight, modern support desk** with SLA awareness . |

**Frameworks for building custom systems**: Choose **GLPI** for the most complete open-source ITIL service desk with SLA tracking, CMDB, and asset management , **Znuny** for audit-proof ticket management in regulated environments , or **heidsoft/itsm** for an AI-native platform with BPMN orchestration —all without per-agent or per-fulfiller pricing.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- SLA and service management platforms handle employee PII, service requests, and potentially sensitive incident data; enforce role-based access, audit logging, and compliance with applicable data protection regulations.
- **Enterprise ITSM pricing is quote-only and scales per-agent.** **Jira Service Management** offers a genuine free tier (3 agents) and Premium at ~$55/agent/month—the most accessible enterprise option . **SolarWinds Service Desk publishes $39/technician/month** with a 30-day trial . **Open-source ITSM is genuinely mature**: **GLPI** is the most complete with SLA tracking, CMDB, and asset management trusted by 100,000+ organizations . **Znuny** provides audit-proof ticketing for regulated environments . **heidsoft/itsm** is the most ambitious modern option but is still in **production hardening phase**—validate before production . **Validate whether you need full ITIL service management (GLPI, ServiceNow) or focused ticket management (Znuny, Libredesk)** before committing.

---

**Made for IT service managers, support operations teams, and organizations building service delivery infrastructure.**  
Let's make enterprise SLA and support service management more open, measurable, and accountable.
