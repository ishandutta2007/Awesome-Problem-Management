# Awesome-Problem-Management

## Top Problem Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Root Cause Analysis, Known Error Management & Incident Recurrence Prevention*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Problem Management**. These tools enable IT teams to move beyond incident firefighting—identifying recurring issues, performing structured root cause analysis (RCA), documenting known errors and workarounds, and driving permanent fixes that reduce incident volume and business impact.



**Examples** include ServiceNow Problem Management, Jira Service Management, BMC Helix ITSM, Freshservice, Cherwell Service Management, Ivanti Service Manager, ManageEngine ServiceDesk Plus, SysAid, HaloITSM, and Zendesk (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosted ITSM with problem management capabilities—ideal for organizations building sovereign problem management infrastructure without per-agent licensing lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ServiceNow Problem Management](https://www.servicenow.com/)**  

  Enterprise problem management on the Now Platform with structured lifecycle (New → Assess → Root Cause Analysis → Fix in Progress → Resolved → Closed); links multiple incidents to a single problem, uses CMDB dependency views for blast radius analysis, supports known error documentation, and drives RCA to safer changes .



- **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)**  

  Problem management capabilities for grouping incidents into problems, accelerating root cause analysis, and documenting workarounds to minimize incident impact; note that advanced problem management moved to Premium and Enterprise plans as of October 2024 .



- **[BMC Helix ITSM](https://www.bmc.com/)**  

  ITIL-compliant problem management with **Problem Solver** that automatically detects recurring incidents and creates problem candidate clusters for investigation; includes AI-powered chat, root cause analysis, and recommended resolutions; 26.2 release adds Post Incident Reviews (PIR) with PDF export for audit .



- **[Freshservice](https://www.freshworks.com/freshservice/)**  

  ITIL-aligned problem management for isolating problems, linking to existing or past incidents, performing timeline-based root cause analysis, and minimizing business disruptions through structured workflows .



- **[Cherwell Service Management](https://www.cherwell.com/)**  

  Problem management with lifecycle workflow phases, Quick Info Tile showing status/priority/linked incident thresholds, known error submission to portal, workaround documentation to knowledge base, and automation processes for notifications and ownership assignment .



- **[Ivanti Service Manager](https://www.ivanti.com/)**  

  Problem Management package that configures the platform to address root causes by analyzing incidents, with knowledge management integration to share information and speed future incident resolution .



- **[ManageEngine ServiceDesk Plus](https://www.manageengine.com/products/service-desk/)**  

  ITIL-certified problem management with Zia AI predicting potential problems by grouping similar incidents, visual RCA workflows (including Five Whys), CMDB-integrated dependency analysis, and known error repository for sharing workarounds .



- **[SysAid](https://www.sysaid.com/)**  

  AI-first problem management with Copilot and AI Agents suggesting potential root causes from historical data, recommending workarounds from knowledge base, highlighting affected assets via CMDB, auto-prioritizing by severity, and predicting problem recurrence .



- **[HaloITSM](https://www.haloitsm.com/)**  

  ITIL-aligned problem management with smart-link escalation of request types to problems, attaching multiple incidents to a problem with one-click updates, full activity traceability for audit, and knowledge base sharing of resolutions .



- **[Zendesk](https://www.zendesk.com/)**  

  Problem ticket type for tracking issues with multiple affected users; supports linking incidents to problems, views and triggers for problem notification, and workflow configuration for problem lifecycle management .



## Open-Source GitHub Projects



- **[heidsoft ITSM](https://github.com/heidsoft/itsm)**  

  AI-native open-source ITSM platform (Apache-2.0) with dedicated **Problem Management** flow: Recurring incidents → Problem → Known Error → Knowledge publication → RAG; includes BPMN workflow engine, CMDB, SLA management, and AI-embedded triage and recommendations; Docker-deployable with Go backend and Next.js frontend .



- **[iTop](https://github.com/Combodo/iTop)**  

  Complete open-source ITIL-aligned ITSM platform with problem management as a core ITIL process; integrates with CMDB for impact analysis, supports known error documentation and workaround management, and provides REST API for automation; AGPL-3.0 licensed.



- **[Znuny](https://github.com/znuny/Znuny)**  

  Open-source ITSM and helpdesk platform (OTRS fork) with problem management capabilities through ticket type configuration and escalation workflows; supports linking incidents to problems, SLA tracking, and knowledge base integration for known errors; GPL-3.0 licensed.



- **[Frappe Helpdesk](https://github.com/frappe/helpdesk)**  

  100% open-source ticket management with customizable ticket types that can be configured for problem tracking; includes knowledge base integration, SLA rules, and auto-assignment; built on Frappe Framework and Docker-deployable.



### Additional Strong Open-Source Options



- **osTicket** — Widely used open-source support ticket system that can be configured with help topics for problem tracking and linked incidents for smaller teams.

- **Helpy** — Open-source customer support platform with knowledge base and community forums that can serve as known error documentation repositories.

- **Faveo Helpdesk** — Open-source helpdesk with workflow automation and SLA management that can be adapted for problem lifecycle tracking.



**Frameworks for building custom systems**: Combine **heidsoft ITSM** for AI-assisted problem detection and RAG-powered known error retrieval, **iTop** for ITIL-aligned problem management with CMDB integration, and **Znuny** for ticket-based problem escalation with SLA tracking in a self-hosted problem management stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Problem management platforms handling incident and root cause data must comply with applicable regulations and organizational data governance policies.

- Self-hosted open-source solutions vary in problem management depth—heidsoft ITSM and iTop offer dedicated ITIL problem workflows, while others require configuration to enable problem tracking.

- Verify license terms for commercial use; heidsoft ITSM uses Apache-2.0, iTop uses AGPL-3.0, and Znuny uses GPL-3.0.



---



**Made for IT service managers, problem coordinators, service desk analysts, and SRE teams.**  

Let's make problem management more open, root-cause-driven, and recurrence-aware.
