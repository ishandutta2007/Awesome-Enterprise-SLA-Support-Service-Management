# Awesome-Enterprise-SLA-Support-Service-Management

## Top Enterprise SLA & Support Service Management Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on ITIL Service Delivery, SLA Tracking & Self-Hosted Service Desks*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise SLA & Support Service Management**. These tools help organizations deliver IT and business services with measurable commitments—covering everything from incident and request management with SLA tracking to self-service portals and service catalogs.

**Examples** include ServiceNow, Jira Service Management, Freshservice, BMC Helix, SolarWinds Service Desk, SysAid, GLPI, and Znuny (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted service management, open-source ITSM with SLA tracking, and community-driven service desks—ideal for organizations seeking data sovereignty and avoiding per-agent or per-fulfiller SaaS pricing. The open-source landscape is genuinely functional: **GLPI** provides a complete ITIL service desk with SLA tracking and asset management , **Znuny** offers audit-proof ticket management with SLA foundations , and **heidsoft/itsm** delivers an AI-native platform with BPMN orchestration and CMDB .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global IT Service Management (ITSM) and enterprise support services market is estimated at **$14.8B to $17.6B in 2026** (growing at an estimated ~14–16% CAGR from ~$13B in 2025). The sector exhibits a **moderately fragmented, tier-concentrated market dynamic**: top-tier enterprise mega-vendors (led by ServiceNow, followed by Atlassian and BMC) dominate core high-end enterprise ITIL workloads, while an expansive long tail of agile mid-market SaaS providers and specialized ESM/departmental point solutions compete across SMB, regional, and vertical niches.

## SaaS/Hosted Platforms

| Product | Company Scale (Revenue / Valuation) | Pricing (Starting Tier) | Free Tier / Trial Limits | Description |
|---------|------------------------------------|------------------------|--------------------------|-------------|
| **[ServiceNow](https://www.servicenow.com/)** | **~$105B Market Cap** (~$15.4B TTM Revenue) | **$70/fulfiller/month** (Foundation/Standard entry tier, billed annually; quote-based) | **Free Personal Developer Instance (PDI)** (1 developer instance, non-production; requires login every 10 days or reclaimed after 90 days of age) | Full ITIL practice benchmark with CMDB, service catalogs, incident/change management, and enterprise-grade generative AI/AIOps. |
| **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)** | **~$37B Market Cap** (~$6.6B TTM Revenue) | **$20/agent/month** (Standard plan; $25/agent/month on monthly billing) | **Free forever plan**: Up to 3 agents, unlimited customer requestors, 2 GB file storage, 100 email notifications/day (also offers a 14-day free trial for Standard/Premium tiers) | ITIL-aligned service desk tailored for engineering and Atlassian-native environments, including SLA tracking, incident swarming, and Rovo AI. |
| **[SolarWinds Service Desk](https://www.solarwinds.com/)** | **~$3.2B Market Cap** (~$797M TTM Revenue) | **$39/technician/month** (Essentials plan, billed annually) | **30-day free trial**: Full access to Premier tier features, ITAM/CMDB capabilities, unlimited ticket requestors, no credit card required | Cloud-based ITSM with integrated asset management, incident resolution workflows, and SLA breached-risk alerts. |
| **[Freshservice](https://www.freshworks.com/freshservice/)** | **~$3.2B Market Cap** (~$903M TTM Revenue) | **$19/agent/month** (Starter plan billed annually, or $29/month-to-month; Growth tier with full SLA management starts at $49/agent/month) | **14-day free trial**: Unrestricted access to Enterprise features, unlimited agents during evaluation, no credit card required | AI-powered IT service desk powered by Freddy AI, featuring multi-department ESM support, incident workflows, and SLA rule engines. |
| **[BMC Helix](https://www.bmc.com/)** | **~$2.2B Annual Revenue** (Private, owned by KKR) | **$115/named user/month** (Entry Service Desk tier via enterprise quote/G-Cloud frameworks) | **30-day enterprise Proof of Concept (PoC) / custom guided trial**: Scoped dedicated environment upon sales request, plus interactive on-demand sandbox demos (no self-serve free forever plan) | Enterprise ServiceOps and ITIL platform leveraging HelixGPT, advanced CMDB discovery, automated root-cause analysis, and business workflow orchestration. |
| **[SysAid](https://www.sysaid.com/)** | **~$30M ARR** (Private, raised $30M from IGP) | **$89/agent/month** (Professional AI plan, billed annually) | **30-day free trial**: Full feature access to AI agents, asset discovery, and ticket management workflows, no credit card required | AI-first IT service desk delivering generative ticket summarization, zero-trust departmental separation, asset tracking, and automated SLA escalation. |

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
