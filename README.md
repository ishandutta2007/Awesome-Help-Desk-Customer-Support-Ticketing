# Awesome-Help-Desk-Customer-Support-Ticketing

# Awesome Help Desk & Customer Support Ticketing

> A curated list of top Help Desk, Customer Support, and Ticketing software — both SaaS/Hosted Platforms and Open-Source alternatives.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [HubSpot Service Hub](#hubspot-service-hub)
  - [Zendesk Support](#zendesk-support)
  - [Freshdesk](#freshdesk)
  - [HappyFox](#happyfox)
  - [Zoho Desk](#zoho-desk)
  - [Help Scout](#help-scout)
  - [SolarWinds Service Desk](#solarwinds-service-desk)
  - [Kayako](#kayako)
  - [LiveAgent](#liveagent)
  - [Front](#front)
- [Open-Source Software](#-open-source-software)
  - [Zammad](#zammad)
  - [osTicket](#osticket)
  - [FreeScout](#freescout)
  - [Chatwoot](#chatwoot)
  - [GLPI](#glpi)
  - [OTOBO](#otobo)
  - [Znuny](#znuny)
  - [Request Tracker (RT)](#request-tracker-rt)
  - [UVdesk](#uvdesk)
  - [Frappe Helpdesk](#frappe-helpdesk)
  - [Libredesk](#libredesk)
  - [HESK](#hesk)
  - [Helpdock](#helpdock)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted customer support and ticketing platforms. These are not open-source but are included as reference points for feature comparison.

### HubSpot Service Hub
Integrated with HubSpot CRM, offering ticketing, knowledge base, customer feedback, and AI tools. Ticket automation assigns requests based on agent skills. Free tier for up to 2 users; paid plans from $7/seat/month (Starter) up to $150/seat/month (Enterprise) [citation:13].

### Zendesk Support
A long-standing industry standard for customer support ticketing. Known for extensive integrations, robust reporting, and AI features at all tiers (advanced AI costs extra). Pricing typically starts around $29/month for entry-level plans, scaling significantly for larger teams .

### Freshdesk
Part of the Freshworks suite, offering a clean interface and full ITSM adherence. Includes ticket management, automation, asset tracking, and AI features (available as paid add-ons). Suitable for teams wanting an easy-to-use platform with room to grow .

### HappyFox
Beginner-friendly help desk with strong ticket organization, automation for routing, and custom reporting. Supports multichannel intake (email, chat, social, phone). Pricing starts from approximately $24/agent/month with a 14-day free trial [citation:13].

### Zoho Desk
Classic ticket queue with a free plan for up to 3 agents. Integrates seamlessly with other Zoho products. Good for small teams already within the Zoho ecosystem [citation:3].

### Help Scout
Email-first shared inbox tool with a free plan for up to 5 users. Focuses on simplicity and conversation-style support rather than complex ITIL workflows. A popular choice for small customer-facing teams [citation:3].

### SolarWinds Service Desk
IT-focused service management with asset tracking, change management, and ITIL alignment. Often compared alongside Vivantio and ManageEngine ServiceDesk Plus for mid-sized IT teams [citation:1].

### Kayako
Built for SMBs with real-time collaboration and a complete customer journey view. Pricing is quote-based rather than published per-agent rates. AI agent resolution costs approximately $1 per resolved ticket [citation:13].

### LiveAgent
Multichannel help desk with ticketing, live chat, and call center features. Known for a generous feature set at competitive price points, particularly for smaller teams [citation:13].

### Front
Shared inbox platform that treats email, chat, and messaging as collaborative conversations. Popular with operations and customer-facing teams that prioritize internal collaboration alongside external support.

---

## 🟩 Open-Source Software

Self-hosted, community-driven alternatives. All listed projects offer source code you can deploy on your own infrastructure.

### Zammad
**Stack:** Ruby on Rails / Vue | **License:** AGPL-3.0  
A modern, full-featured help desk with a clean real-time interface. Handles email, chat, phone, Telegram, Facebook, WhatsApp, and SMS in one queue. Includes knowledge base, SLAs, roles, SSO (SAML/OIDC), and audit logs in the free self-hosted edition. Built-in importers for Zendesk, Freshdesk, Kayako, and OTRS.  
**Requirements:** ~6 GB RAM minimum (plus 4 GB extra if Elasticsearch runs on the same server).  
**Best for:** Teams that want a polished, SaaS-like experience without license fees [citation:3][citation:8][citation:12].

### osTicket
**Stack:** PHP / MySQL | **License:** GPL-2.0  
One of the longest-running open-source ticketing systems. Converts emails and web forms into tickets with help topics, departments, SLA plans, canned responses, and a customer portal. Extremely stable and well-documented, though the interface looks dated compared to modern SaaS tools.  
**Best for:** Budget-conscious teams with basic email ticketing needs on inexpensive PHP hosting [citation:3][citation:8].

### FreeScout
**Stack:** PHP / MySQL | **License:** AGPL-3.0  
A lightweight, self-hosted alternative to Help Scout and Zendesk focused on shared email inboxes. Core app is free with unlimited users and mailboxes. Advanced features (knowledge base, satisfaction ratings, time tracking, WhatsApp integration) are available as paid add-on modules. Runs comfortably on 1–2 GB RAM.  
**Best for:** Small teams and technical founders who want an email-style inbox without per-seat billing [citation:3][citation:8][citation:14].

### Chatwoot
**Stack:** Ruby on Rails / Vue | **License:** MIT  
An omnichannel customer engagement platform positioned as a self-hostable Intercom/Zendesk alternative. Shared inbox covers live chat, email, WhatsApp, Facebook, Instagram, Telegram, and SMS. Includes AI Captain for triage. 28k+ GitHub stars and very active development.  
**Best for:** Conversational support across many messaging channels, not just email tickets [citation:8].

### GLPI
**Stack:** PHP / MySQL | **License:** GPL  
Combines ITIL-style ticketing (incidents, requests, problems, changes) with hardware/software inventory, license tracking, and a basic CMDB. Popular in schools, public sector, and IT departments that want one tool for both help desk and asset management.  
**Best for:** Internal IT teams that need ticketing plus asset tracking in a single free platform [citation:3].

### OTOBO
**Stack:** Perl / MariaDB/MySQL/PostgreSQL/Oracle | **License:** GPL-3.0  
A fork of OTRS maintained by Rother OSS. Continues the OTRS codebase with ITSM packages available free. Includes ticket management, service desk, incident/problem/change management, self-service portal, and knowledge management.  
**Requirements:** At least 8 GB RAM (16 GB recommended). Vendor support starts around €3,900/year.  
**Best for:** IT and service teams that want an OTRS-style service desk without license fees [citation:2][citation:5].

### Znuny
**Stack:** Perl | **License:** GPL  
Another community fork of OTRS (alongside OTOBO). Keeps the familiar queue/ticket/process model that made OTRS popular in Europe. Suits IT and service teams with structured workflows. Requires meaningful configuration effort.  
**Best for:** Organizations with existing OTRS expertise or strict ITSM process requirements [citation:3].

### Request Tracker (RT)
**Stack:** Perl / MySQL/PostgreSQL/Oracle/SQLite | **License:** GPL-2.0  
A mature, email-driven ticket tracker with extremely granular rights per queue, group, and role. Includes asset tracking and REST 2 API in core. RT 6 allows admins to rearrange ticket page layouts.  
**Note:** No official Docker image for production; SSO requires web server modules.  
**Best for:** Universities, ISPs, and IT operations teams that need detailed queue-level permissions and a full change history [citation:2][citation:3].

### UVdesk
**Stack:** PHP / Symfony / MySQL | **License:** OSL-3.0 (open core)  
Open-source help desk with ticketing, knowledge base, customer portal, and e-commerce/marketplace connectors. Unlimited agents, teams, and mailboxes in the free edition. **Caution:** No new release since v1.1.8 in September 2025; check recent activity before committing. No SSO for agents and no audit log.  
**Best for:** Small teams on PHP hosting who need email ticketing and a self-service portal [citation:2][citation:3].

### Frappe Helpdesk
**Stack:** Python / Vue.js on Frappe framework | **License:** GPL-3.0-or-later  
Built on the Frappe framework (same ecosystem as ERPNext). Features SLAs with business hours, auto-assignment by priority/type/team/workload, customer portal, and unlimited agents with no seat fees. Sign-in via Google, Microsoft, or custom OIDC through Frappe. Customer sync with ERPNext.  
**Note:** No live chat or WhatsApp channel. Self-hosting runs the full Frappe stack (MariaDB, Redis, bench).  
**Best for:** Teams already on ERPNext or Frappe who want support tickets integrated with their ERP [citation:2].

### Libredesk
**Stack:** Go | **License:** (Check repository)  
A newer open-source customer support inbox for email and live chat, written in Go as a single binary. Simpler deployment than many alternatives. Worth watching as the project matures.  
**Best for:** Teams that prefer a lightweight, Go-based binary deployment [citation:2].

### HESK
**Stack:** PHP / MySQL | **License:** (Free with paid branding removal)  
A small, quick-to-install PHP help desk suitable for shared hosting. Free to use; paid license removes branding and adds a hosted option. Good for small internal queues; lacks modern omnichannel features.  
**Best for:** Very small teams or individual departments needing a simple ticket queue on minimal infrastructure [citation:3].

### Helpdock
**Stack:** Docker / PostgreSQL / S3-compatible storage | **License:** (Check repository)  
A newer self-hosted customer support platform with ticketing, help center, live chat widget, and grounded AI. Multi-brand support, SAML/OIDC SSO, Argon2id password hashing, and importers for Zendesk/Freshdesk/Zoho Desk. Requires Docker, 2 vCPU, 4 GB RAM, and an S3 bucket.  
**Best for:** Teams wanting a modern, security-conscious self-hosted alternative with AI features and multi-brand support [citation:15].

---

## 📊 Comparison at a Glance

| Software | License | Stack | Best For | SSO (Free) | Chat/Omnichannel |
|----------|---------|-------|----------|------------|------------------|
| **Zammad** | AGPL-3.0 | Ruby/Rails | Modern UI + omnichannel | ✅ | ✅ Email, chat, WhatsApp, Telegram |
| **osTicket** | GPL-2.0 | PHP | Simple email ticketing | ❌ | ❌ Email/web only |
| **FreeScout** | AGPL-3.0 | PHP | Lightweight shared inbox | ❌ | ❌ Email-focused |
| **Chatwoot** | MIT | Ruby/Rails | Conversational support | (Check) | ✅ Full omnichannel |
| **GLPI** | GPL | PHP | IT help desk + assets | (Check) | ❌ ITIL-focused |
| **OTOBO** | GPL-3.0 | Perl | OTRS-style ITSM | ✅ | ❌ Email/portal |
| **Request Tracker** | GPL-2.0 | Perl | Granular queue permissions | ❌ (needs module) | ❌ Email-driven |
| **Frappe Helpdesk** | GPL-3.0+ | Python/Vue | ERPNext integration | ✅ (via Frappe) | ❌ |
| **UVdesk** | OSL-3.0 | PHP/Symfony | PHP hosting + portal | ❌ | ❌ |
| **Helpdock** | (Check) | Docker/PostgreSQL | Multi-brand + AI | ✅ SAML/OIDC | ✅ Live chat widget |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source help desk or ticketing tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
