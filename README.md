<div align="center">

<img src="./logo.svg" alt="Command Center logo" width="120" />

# **Command Center by Mannat AI**

### *The CIA of Real Estate Execution.*

**Control · Intelligence · Action** — the AI-powered CRM that runs a UAE brokerage every day. Battle-tested at a live Dubai brokerage. Now available to yours.

[**Live Demo →**](https://c2.mannatai.com/) · [**hello@mannatai.com**](mailto:hello@mannatai.com)

</div>

---

## In one sentence

Command Center is a real-estate-native CRM, marketing console, and public property website — bundled, AI-augmented, and deployed on **infrastructure dedicated to you**, not a shared SaaS pool.

---

## 🧭 Built on the CIA principle

Command Center isn't a CRM in the traditional sense — it's an execution system. Every feature serves one of three pillars:

### 🎯 Control
Every lead, every agent, every campaign, every property — visible and governable from one place. **No more platform hopping. No more blind management.** You see what's happening and you decide what happens next.

### 🧠 Intelligence
AI-powered lead scoring. AI-powered agent performance ranking. Smart analytics across every channel. **Your decisions are powered by signals, not gut feel.**

### ⚡ Action
The system drives the next step — auto-assignments, proactive nudges, one-click "Sync Now" publishing, smart follow-up reminders. **Execution, not passive storage.**

*This is what we mean by **"The CIA of Real Estate Execution."***

---

## How Command Center is different

We built this from the ground up for real estate teams. Four things make it unique:

### 🤖 AI-Powered Lead Scoring
Our AI analyzes every lead based on behavior, engagement, and property interest. **Hot leads get flagged immediately.** Your agents focus on prospects ready to buy — not tire-kickers.

### 🏆 Gamified Agent Performance (KRA)
We turned performance tracking into a game. **Agents earn points for activities, compete on leaderboards, and hit targets.** The result? A motivated team that actually wants to perform.

### 📥 All Leads in One Place
Connect **Facebook, Instagram, LinkedIn, and Google Ads.** Every lead flows directly into Command Center. **No more platform hopping. No more missed opportunities.** Management sees the full picture in one dashboard.

### 💬 Built-in AI Assistant
Stuck on something? **Ask our AI chatbot.** It knows the platform inside out and provides instant answers 24/7 — no support ticket, no waiting.

---

## 🔐 Your data lives on dedicated infrastructure — your choice of deployment

This is the part that nobody else in our price band offers:

**We deploy Command Center on a VPS dedicated to your brokerage.** Your database. Your Redis. Your storage. Your subdomain. Fully isolated — your records are never pooled into a shared multi-tenant database with another brokerage's.

### 🅰️ Two ways to deploy — you pick

|  | **Bring Your Own Cloud** | **Mannat-Managed** |
|---|---|---|
| Who owns the VPS account | **You.** Your Hostinger / AWS / DigitalOcean / etc. | Mannat AI's account — dedicated to you |
| Who pays the cloud bill | You — directly to your cloud provider | Included in your monthly Mannat invoice |
| Who deploys & maintains | Mannat AI (we get deploy access; revocable any time) | Mannat AI end-to-end |
| Data residency choice | Anywhere your cloud provider operates | UAE-region or Frankfurt (PDPL-permissible) |
| Portable on exit | ✅ Yes — keep the VPS, the data, the stack | ✅ Yes — full export + migration assistance |
| Cost transparency | Direct cloud invoice; predictable | Bundled — one line item from Mannat |
| Best for | Brokerages who want maximum data sovereignty + cost visibility | Brokerages who want zero infra touch |

**Both options give you:**

- ✅ **Dedicated, isolated instance** — separate DB, separate Redis, separate Docker stack
- ✅ **No multi-tenant data pooling** — ever
- ✅ **Portable on exit** — no export ticket, no 90-day hostage, no "enterprise tier" required just to leave
- ✅ **PDPL-aware** by design
- ✅ **Revocable Mannat access** — you can pause our deploy keys at any time

**The trade with a multi-tenant SaaS (HubSpot, Salesforce, Zoho):** their database, their rules, their export policy, their pricing changes, their AI training datasets. **With Command Center:** your dedicated infrastructure, your data, your terms.

## Why we built this

UAE brokerages run on five separate tools that don't talk to each other: a generic CRM, a portal listing on Bayut/PF, WhatsApp for client chats, Excel for commissions, and a static website a freelancer built two years ago. Every handoff between them leaks leads, breaks attribution, and burns agent hours.

Command Center collapses those five into one operational stack, designed around how UAE real estate actually works — RERA permits, Trakheesi numbers, off-plan vs. ready inventory, India inbound, WhatsApp-first communication, and the reality that the public listing site is part of the product, not a separate project.

It's been running a live UAE brokerage in production since 2025. Every feature in the live demo is one a working agent uses every week.

---

## See it live

> 🚀 **Public demo launching shortly at [c2.mannatai.com](https://c2.mannatai.com/).** While we finalize the sandbox tenant, email [hello@mannatai.com](mailto:hello@mannatai.com) for instant access — we'll send credentials within one business day.

**When you log in, this is the 5-minute tour we'd suggest:**
1. **Workspace → Home** — the daily-driver dashboard an agent sees first thing in the morning.
2. **Leads → Lead Control Tower** — the funnel, the live lead list, click any lead to see the timeline.
3. **Leads → Lead Control Tower → Funnel** — visual lead journey across stages.
4. **Panel → Properties** — the inventory that powers the public website.
5. **Analytics → Ad Center** — campaign performance from Meta Lead Ads end-to-end.
6. **Performance → My Scores** — AI-scored agent performance (look for the AI badge).

The demo dataset is sanitized — none of the leads, agents, or properties are real clients.

---

## What's inside (live today)

Command Center is organized into seven modules. Every module below is live in the demo — nothing on this list is a mockup.

### 🎯 Lead Control Tower
The heart of the product — every lead from every source in one funnel.

- **Live lead list** with role-aware visibility (agents see their own, managers see their teams)
- **Visual lead journey** across configurable stages, with stage-time analytics
- **Lead Funnel** dashboard — conversion rates between stages, drop-off detection
- **Multi-source lead capture** — **Facebook & Instagram Lead Ads**, **LinkedIn Lead Gen Forms**, **Google Ads** lead forms — all flow directly into one funnel with full source attribution. Plus automated ad-spend → cost-per-lead → cost-per-deal analytics pulled into Ad Center, so management sees the full ROI picture in one place.
- **CSV/Excel import** with column mapping and UAE phone-format preset
- **Phone validation** — bulk check and format correction
- **Auto-assignment rules** — route new leads to the right agent automatically
- **Bulk operations** — archive, reassign, tag, export
- **Meeting scheduler** integrated with lead timeline
- **Activity Stream** — every touchpoint (call, message, note) on every lead
- **PWA push notifications** — new lead pings agent's phone even when the app is closed

### 🏠 Property Panel
Your inventory — wired directly into your public website.

- **All Properties / Off-plan / Ready** — three tabs, one model, RERA-aware
- **Off-plan project pages** — auto-generated marketing pages at `/projects/[slug]` on your public site with stunning lead-magnet templates
- **Developer linking** — properties auto-attribute to their developer; developer pages show active inventory counts
- **Hot Deals** — promoted properties surfaced on homepage + dedicated `/hot-deals` band
- **EOI (Expressions of Interest)** — capture interest on off-plan units before launch
- **Communities** — neighborhood landing pages
- **Blogs** — long-form content for SEO
- **Media library** — uploads served via dedicated media subdomain
- **Marketing tab** — push campaigns to your inventory

### 🌐 Public Property Website — Run It Without a Developer
Yes — **your brokerage's public website is included**. Not an add-on, not a separate project.

The big idea: your sales team updates the website. **No developer. No agency. No tickets.** Add a property in Command Center → it's live on your site in minutes.

- **Website Sync panel** *(Settings → Website Sync)* — one-click "Sync Now" button pushes your latest properties, blogs, hot deals, and content to the live site. Auto-sync on a schedule (every 15 min up to 24 h). Test connection, view sync logs, download a ZIP, or "Generate only" to preview before publishing.
- **Lives at your custom domain** on your own dedicated VPS
- **Server-rendered**, SEO-optimized, Core Web Vitals green
- **Snapshot architecture** — public site reads from a refresh-every-5-minutes cache, so it stays live even if the CRM is briefly offline
- **Public API key system** — third-party integrations (your own apps, partners) pull a sanitized property feed
- **SEO settings panel** — meta titles/descriptions, structured data, robots.txt, sitemap split (properties, projects, blogs, communities) — all editable inside Command Center, no code
- **India-investor layer** — ₹ INR pricing alongside AED, gated India-investor guide PDF, WhatsApp UTM-tracked CTAs, dedicated investor strip
- **WhatsApp deep-link CTAs** on every property
- **Saved-search alerts** — visitors save a search; the system emails them when matching listings appear

### 💼 Deals
Every deal an agent works, end-to-end.

- **Deal Register** — every active deal with stage, value, agent, expected close
- **Performance Insights** — close rates, average deal size, time-to-close by agent / property type / source
- **Developer Analytics** — which developers convert, average commission, deal volume by developer
- Commission tracking by deal

### 🏆 Performance & KRA
What your team is actually doing — and how well.

- **Daily Activities (KRA)** — calls made, meetings booked, properties shown, follow-ups completed
- **My Dashboard** — each agent's personal KPI view
- **Pipeline Dashboard** — pipeline health visualization with conversion forecasting
- **Team Overview** — manager view of every direct report's activity
- **Team Leaderboard** — gamified ranking, monthly resets
- **My Scores** — 🤖 **AI-powered agent scoring** that ranks pipeline hygiene and activity performance
- **Leaderboard** — public scoreboard across the brokerage

### 📊 Analytics & Ad Center
Spend money, see what came back.

- **Analytics Hub** — single dashboard tying lead-spend to deal-close
- **Ad Center** — campaign-level performance: cost-per-lead, cost-per-qualified-lead, cost-per-deal, by source
- **Marketing Analytics** — email-campaign opens/clicks/replies, WhatsApp click-throughs, organic vs paid mix
- **Marketing Hub Email channel** — rich email composer, branded email shell, configurable Branding tab, marketing-image uploads
- **Lead-source ROI** — drill down to any source and see what it actually produces

### ⚙️ Workspace
The daily operational layer.

- **Home** — start-of-day briefing for agents
- **Command Center Board** — Kanban-style lead board across the funnel
- **WorkItems** — agent task list, manager assignment
- **Activity Stream** — org-wide timeline of every action
- **Signals** — proactive nudges that surface what needs attention next
- **DMS** — integrated document management
- **Agents directory** — every team member, role, contact
- **Network** — connections, referral tracking
- **PWA mobile app** — installs to homescreen on iOS/Android, full offline-capable shell, push notifications

### 🛡️ Settings
The operator's panel — comprehensive, role-gated to admins.

- **Users / Teams** — role-based access (admin, manager, agent, viewer)
- **Lead Sources** — define and configure every source the org uses
- **Lead Notification Recipients** — wire who gets pinged for which leads
- **Scoring** — configure AI-scoring weights for agent performance
- **Public API** — manage API keys for your public website + partners
- **Integrations** — Facebook & Instagram Lead Ads, LinkedIn Lead Gen Forms, Google Ads, Zoho, Google Workspace, custom OAuth providers
- **SEO Indexing** — robots, sitemaps, meta-tag overrides for the public website
- **Security** — 2FA enforcement, session management, **"Revoke all sessions"** kill-switch for offboarding
- **Login Audit** — every successful + failed login, by user, IP, device
- **Notification Audit** — every push/email/SMS the system sent
- **Website Sync** — manual cache-bust for the public site
- **Display Tokens** — auth tokens for kiosk/display-mode read-only views
- **Organization** — branding, contact info, legal entity details

---

## Built for UAE — not adapted to it

This is what separates Command Center from a generic CRM with a "real estate template":

| Need | What Command Center does |
|---|---|
| **RERA / Trakheesi permits** | First-class fields on every listing, validated, surfaced in the public site footer + schema.org markup |
| **Off-plan vs. ready** | Two distinct flows, two distinct page templates, two distinct sitemaps |
| **AED + ₹ pricing** | Native dual-currency layer for India-inbound investors, configurable FX |
| **WhatsApp-first comms** | Deep-link CTAs everywhere, click-to-chat with prefilled lead context, UTM-attributed |
| **Bayut / Property Finder** | Inventory export feed available as an add-on |
| **Indian investor funnel** | Gated India-guide PDF, ₹ price layer, India-specific landing strip, full UTM attribution back to source |
| **Golden Visa eligibility** | Surface AED-2M+ properties as visa-eligible automatically |
| **Compliance-aware copy** | UAE PDPL-aware data handling baked in |

---

## 🛡️ Security by design — not by checkbox

We don't treat security as a feature. **It's the foundation.** Every layer of Command Center ships secure by default — not bolted on, not optional, not behind an enterprise upsell.

- **Dedicated infrastructure** — your data lives on a VPS dedicated to you. Never pooled with another brokerage's. *(See the deployment-model section above.)*
- **UAE PDPL-aware** — data handling designed for UAE privacy law from day one
- **Authentication** — JWT + refresh tokens, Zoho SSO, Google SSO, password + email
- **2FA enforceable org-wide** — TOTP-based, admin-controlled
- **Role-based access** — admin, manager, agent, viewer; row-level visibility on leads
- **Audit logging** — every login (success + fail), every notification sent, every privileged action
- **Instant offboarding** — revoke all sessions for any user in ≤ 15 minutes — built-in kill-switch
- **Encryption** — at rest and in transit
- **OAuth domain allowlists** — restrict SSO to your company domains only
- **Continuous monitoring** with alerting on every customer instance
- **Disaster recovery** — encrypted offsite backups with restore drills *(rolling out Q3 2026)*

---

## What's coming — AI roadmap

The AI roadmap is on the public site so prospects know where this is going. Anything labeled **🔮 Coming** is not in the live demo today.

**Phase 1 — Quick wins (Q3 2026)**
- 🟢 **AI agent scoring** — *live now, see Performance → My Scores*
- 🔮 AI lead summary — one-paragraph "what does this lead want, what's next" generated from notes + chat history
- 🔮 AI reply drafts — draft replies in the agent's voice, agent edits before sending
- 🔮 Smart follow-up reminders — "You haven't talked to Lead X in 5 days — here's a suggested message"
- 🔮 Natural-language search — *"Show me 3BR in JBR under 2M with sea view added this month"* → translates to filters
- 🔮 Duplicate-lead detection on creation
- 🔮 Auto-tag property photos (kitchen, master bedroom, sea view)

**Phase 2 — Real-estate-specific (Q4 2026 / Q1 2027)**
- 🔮 AI property descriptions from photos + specs (EN/AR)
- 🔮 WhatsApp lead-capture bot — 24/7 qualification, hands off to human at the right moment
- 🔮 Document parsing — Ejari, MOU, passport, trade license → auto-extract fields
- 🔮 Multilingual translation — EN ↔ AR ↔ RU ↔ ZH
- 🔮 AI property-to-buyer matching

**Phase 3 — Strategic (2027+)**
- 🔮 Predictive pricing — list price recommendation from comps
- 🔮 Pipeline forecasting
- 🔮 AI voice agent for after-hours inbound calls
- 🔮 AI-generated marketing assets — listing → Instagram post + Facebook ad + WhatsApp broadcast

---

## Pricing

> **Launch pricing — locked for the first 10 customers, subject to change for general availability.**

### One-time setup — **AED 3,000 – 8,000**
Includes provisioning your dedicated instance, subdomain, SSO setup, CSV import of your existing leads/properties, branding (logo, colors, custom subdomain), 1-hour onboarding call, and 1-hour team training.

### Monthly per-seat (tiered)

| Tier | Agents | Per agent / month | Includes |
|---|---|---|---|
| **Starter** | 1–5 | **AED 99** | Core CRM, leads, properties, reports, hot deals |
| **Growth** | 6–20 | **AED 79** | Everything in Starter + analytics hub, custom branding, email integration |
| **Brokerage** | 20+ | **AED 59** | Everything in Growth + public API, dedicated subdomain, priority support, SLA |

**Monthly floor: AED 499** so single-agent shops still get a viable footprint.

### Add-ons

| Add-on | Price | Notes |
|---|---|---|
| **WhatsApp Business API** | AED 200/mo | High-demand in UAE |
| **Public Property Website** | AED 800/mo | Our flagship differentiator — your full website included |
| **Custom domain** (`crm.yourbrand.ae`) | AED 150/mo | nginx + cert config included |
| **Bayut / Property Finder feed** | AED 300/mo | XML feed export |
| **Zoho/Google/Microsoft SSO** | AED 500 one-time | Workspace configuration |
| **Mannat-hosted plan** *(alternative to your-own-VPS)* | from AED 400/mo | We provide and operate the VPS end-to-end |
| **AI features bundle** *(when launched)* | AED 50/agent/mo | Tier 1 + Tier 2 AI features |

### How we compare

| | Global SaaS CRMs *(HubSpot / Salesforce / Zoho)* | UAE-local broker CRMs | **Command Center** |
|---|---|---|---|
| Real-estate-native fields | Template / configuration | Varies | **Built-in** |
| UAE specifics (RERA, Trakheesi, AED, India funnel) | Add via customization | Sometimes | **Native** |
| Public property website | Sold separately | Rarely included | **Included** |
| AI in daily workflow | Expensive add-on | Rarely | **Roadmap built around it** |
| Data residency | Their data centers | Their cloud | **Your VPS** |
| Multi-tenant data pool | Yes | Often | **Never — dedicated instance** |
| Portable on exit | Export request | Export request | **Take the VPS, walk away** |

*Detailed breakdown shared on request — email us for a structural comparison tailored to your current stack.*

---

## Who's behind this

**[Mannat AI](https://mannatai.com)** is a software product company building practical AI-enabled tools for real-world businesses. Command Center is our flagship — the product that runs a live UAE real-estate brokerage every day.

**Envisioned and led by IIT-Kanpur alumni** — engineering rigor from one of India's premier institutes, combined with on-the-ground UAE real-estate operational experience.

Battle-tested in production since 2025. Every feature shipped because a working agent needed it — not because a product manager imagined it.

---

## Get started

1. **Try the demo.** Login at [c2.mannatai.com](https://c2.mannatai.com/) with the credentials above. Click around. Break things — it's a sandbox.
2. **Email us.** [hello@mannatai.com](mailto:hello@mannatai.com) — tell us your brokerage size, agent count, current tools. We'll send a tailored 20-minute walkthrough and a pricing quote.
3. **Onboard in 7 days.** Setup → SSO → data import → training → live. We do the lift; you do the selling.

<div align="center">

### [▶ Open the live demo](https://c2.mannatai.com/) · [📧 hello@mannatai.com](mailto:hello@mannatai.com)

</div>

---

<sub>© 2026 Mannat AI. Command Center is a product of Mannat AI. Pricing and roadmap subject to change. UAE-based, UAE-built.</sub>
