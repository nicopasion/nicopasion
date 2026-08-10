<div align="center">

# Hi 👋 I'm Nico

### Head of Operations · Full Stack Engineer · AI Automation

**Next.js · TypeScript · Node · Postgres · Supabase · GoHighLevel · Telephony · LLM Integration**

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=8B0101&center=true&vCenter=true&width=620&lines=I+ship+production+systems%2C+not+prototypes.;Multi-tenant+SaaS+%C2%B7+CRM+%C2%B7+Telecom+%C2%B7+Marketplaces;15+years+building.+3+years+leading+the+people+who+build." alt="Typing SVG" />

</div>

---

## 👨‍💻 About

I lead engineering and operations at a software agency, building for clients across the **United States, Canada, Puerto Rico, the UK and Southeast Asia**. Based in the Philippines, working in their timezones.

The work is **multi-tenant SaaS in production**, not demos. CRMs a sales floor lives inside all day. Telephony and billing platforms moving real money. Two-sided marketplaces with split payments. Internal tooling that has to be right the first time, because a client is already watching it.

Most of it is **not greenfield**. It is inheriting somebody else's system, finding what is quietly broken, and fixing it without taking the business offline. A lot of my best work is invisible from the outside: a payment path that stopped losing donations, an auth check that was never there, a billing rule that had been undercharging for months.

I also lead a small team across several countries, so I spend as much time on specs, reviews and incident write-ups as I do on code.

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

[![Languages](https://skillicons.dev/icons?i=ts,js,python,php,html,css,bash,sql)](https://skillicons.dev)

**Frontend**

[![Frontend](https://skillicons.dev/icons?i=react,nextjs,tailwind,vite,figma)](https://skillicons.dev)

**Backend & Data**

[![Backend](https://skillicons.dev/icons?i=nodejs,express,postgres,supabase,redis,prisma,mysql)](https://skillicons.dev)

**Infrastructure**

[![Infra](https://skillicons.dev/icons?i=vercel,docker,nginx,linux,cloudflare,git,github,githubactions)](https://skillicons.dev)

</div>

### Where I'm strongest

| Area | What that means in practice | Depth |
|---|---|---|
| **Next.js / React** | App Router, RSC, server actions, multi-tenant routing and auth | ⭐⭐⭐⭐⭐ |
| **TypeScript** | Strict mode, shared types across API and client, Zod at every boundary | ⭐⭐⭐⭐⭐ |
| **Postgres** | Schema design, RLS policies, migrations, query tuning, Drizzle and Prisma | ⭐⭐⭐⭐⭐ |
| **GoHighLevel** | Agency and sub-account architecture, workflows, custom marketplace actions, Conversation AI, calendars, funnels, snapshots, API and webhook integrations | ⭐⭐⭐⭐⭐ |
| **Auth & access control** | Role hierarchies, tenant isolation, impersonation with audit trails | ⭐⭐⭐⭐⭐ |
| **Payments & billing** | Stripe, PayPal, usage metering, reconciliation, refund and clawback logic | ⭐⭐⭐⭐ |
| **Telephony** | SIP, carrier integration, call and message routing, CDR reconciliation, fraud hardening | ⭐⭐⭐⭐ |
| **LLM integration** | Anthropic and OpenAI SDKs, RAG, structured output, agent tooling | ⭐⭐⭐⭐ |
| **Testing** | Vitest, Playwright, contract tests against real schemas rather than mocks | ⭐⭐⭐⭐ |

### Also work with

![Anthropic](https://img.shields.io/badge/Anthropic_SDK-8B0101?style=flat-square&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-8B0101?style=flat-square&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-8B0101?style=flat-square&logoColor=white)
![Twilio](https://img.shields.io/badge/Twilio-8B0101?style=flat-square&logoColor=white)
![SendGrid](https://img.shields.io/badge/SendGrid-8B0101?style=flat-square&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle_ORM-8B0101?style=flat-square&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-8B0101?style=flat-square&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-8B0101?style=flat-square&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-8B0101?style=flat-square&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-8B0101?style=flat-square&logoColor=white)
![Zapier](https://img.shields.io/badge/Zapier-8B0101?style=flat-square&logoColor=white)
![Kamailio](https://img.shields.io/badge/Kamailio_SIP-8B0101?style=flat-square&logoColor=white)

### GoHighLevel, in depth

I have built on GoHighLevel from every side of it: as an agency operator, as an integration engineer against its API, and as the person migrating clients into it and out of it.

- **Agency and sub-account architecture** — white-label setup, snapshots, permission models, onboarding at volume
- **Workflows and automation** — triggers, custom values, conditional branching, and untangling the ones that quietly stopped firing
- **Custom marketplace actions** built against the GHL API, plus an **MCP server** that exposes GHL operations to AI agents as typed tools
- **Conversation AI** — booking and qualification bots running in production across a portfolio of businesses
- **Calendars** — round-robin distribution, availability rules, slot randomisation, reminder cadences
- **Funnels, forms, surveys, memberships** and course delivery
- **A2P 10DLC registration** and SMS compliance, including recovering rejected campaigns
- **Migrations** into GHL from other CRMs, and out of GHL when a client outgrows it
- **Two-way integrations** with telephony carriers, Shopify, Notion, Postgres and Zapier, Make and n8n

I have also rebuilt a CRM's agency dashboard modelled on GHL's, because I knew exactly what the client expected it to feel like.

---

## 🚀 What I've Built

Client work, so described by shape rather than by name. Around 25 systems across 22 repositories.

### SaaS platforms

| System | Stack | What it does |
|---|---|---|
| **Multi-tenant sales CRM** | Express · Drizzle · Postgres · React · Twilio | A sales floor works in it daily. Pipeline board, browser calling, SMS in and out, lead intake from third-party feeds, sub-account role model with tenant isolation, audited impersonation, per-rep coaching metrics |
| **Multi-brand marketing CRM** | Next.js · Drizzle · Postgres · SendGrid · carrier APIs | White-label workspaces, email campaign builder, SMS and MMS threads, per-workspace usage metering and billing, brand theming, mobile build |
| **Telecom provisioning and billing** | Node · Postgres · Kamailio SIP · carrier APIs | Number search and provisioning, per-message and per-minute metering, CDR reconciliation, subscription lifecycle with grace periods, toll-fraud hardening after a live incident |
| **Healthcare booking SaaS** | Next.js 16 · Supabase · Tailwind | Clinic dashboard and patient marketplace, OTP auth, appointment engine, SMS reminders, teleconsult, programmatic SEO, partner program with a commission engine and payouts |
| **Two-sided services marketplace** | Next.js · Supabase · Stripe Connect | Provider onboarding and payouts, booking flow with payment gating, quoting, in-app messaging, notification preferences, iOS app |
| **SEO / AEO / GEO scanner** | Next.js · Supabase · Anthropic SDK | Crawls a site, scores it across nine modules, generates AI fix suggestions, produces PDF reports |
| **Operations hub** | Next.js · Postgres · Drizzle | Event-driven platform unifying scattered client systems into one operational view |
| **Resort booking platform** | Next.js · Postgres | Availability, room inventory, booking and payment flow |
| **Debt payoff tracker** | Next.js · Supabase | Snowball and avalanche modelling with projections |

### Backends and internal systems

| System | Stack | What it does |
|---|---|---|
| **Certification fulfilment backend** | Node · Postgres · Shopify and CRM APIs | System of record for course sales. Allocates and emails access codes, deducts inventory, tracks attribution and ROAS, flags payment issues, feeds dashboards |
| **Operations command centre** | Next.js · Postgres · Vercel | Public progress reporting across multiple businesses, per-integration connection status, multi-currency revenue kept deliberately separate rather than summed. Ships with governance: CODEOWNERS, recorded decisions, deploy guards |
| **Revenue reporting dashboard** | Next.js · edge functions | Per-store revenue split by country and currency, proxied from the fulfilment backend, course-level sales reporting |
| **Checkout link builder** | Supabase edge functions · Shopify Admin API | Generates and manages one-off checkout links for invoiced and comped sales |
| **Ecommerce storefront and ops** | Next.js · Shopify · Postgres | Catalogue, orders, fulfilment tooling and reporting |
| **Live chat** | Node · websockets | Embedded support chat with agent handoff |

### AI and automation

| Build | Stack | What it does |
|---|---|---|
| **Voice and chat AI assistant** | Next.js · Supabase · RAG · ElevenLabs · Stripe | Answers from a private knowledge base over both text and voice, behind a live paywall, with affiliate attribution and payouts |
| **Call intelligence** | Anthropic SDK · Node | Reads meeting transcripts and returns sentiment, outcome, objections, competitor mentions and next step. Transcripts stay local, only PII-safe aggregates ship |
| **MCP server for a CRM platform** | TypeScript · MCP | Exposes CRM operations to AI agents as typed tools |
| **Conversational AI agents** | GoHighLevel · webhooks · Notion sync | Production chatbots for booking and qualification across a portfolio of businesses, with CRM and knowledge-base sync |
| **AI fix suggestions engine** | Anthropic SDK · Zod | Turns raw audit findings into ranked, actionable tasks with structured output validation |
| **Automation pipelines** | Zapier · Make · n8n · GoHighLevel | Transcript filing, membership provisioning, calendar to CRM routing, lead intake, spreadsheet sync |
| **Inbox automation** | Node · Gmail API | Bulk triage and cleanup at scale |

### Front of house

| Build | Stack | What it does |
|---|---|---|
| **Marketing sites** | Next.js · Vercel · Tailwind | Several, built and maintained. SEO foundations, JSON-LD, OG and Twitter cards, sitemaps, analytics, Core Web Vitals work |
| **Landing pages and funnels** | Next.js · GoHighLevel · Elementor | Lead capture, quiz funnels, offer pages, booking flows |
| **Booking engines** | GoHighLevel · calendars · SMS | Round-robin scheduling, availability rules, reminder sequences |
| **Brand and identity work** | Figma · Tailwind | Design systems, palettes, illustrated and photographic social sets, branded PDF deliverables |

### Diagnostics and rescue work

Some of the work I am proudest of is not a build at all.

| Case | What happened |
|---|---|
| **Silent payment loss** | A nonprofit's donations had been failing for months with no error anywhere. Found roughly half of all attempts were being dropped because every off-site payment redirect never returned. Proved it from the records rather than guessing, then closed the path |
| **Undercharged telecom billing** | Traced a large unbilled cost gap to four separate causes, including international numbers being priced as domestic. Money-affecting, and none of it was visible in the dashboards |
| **Toll fraud incident** | Shared SIP credential exposed in the browser. Led the remediation, hardened the carrier config, and rebuilt the billing path that hid it |
| **Auth holes in a live CRM** | Seven access-control defects found in production, none of them ever reported by a user. Refresh tokens reaching the browser, unauthenticated automation endpoints, cross-tenant leakage |
| **A destructive script** | Found a maintenance script with three statements missing a `WHERE` clause. Only fixtures had been lost. Wrote a guard that fails closed and wired it into every destructive script in the repo |
| **Production data audits** | Swept 57 routes with Playwright plus anonymous-role probes and found admin pages reporting success while silently changing nothing, and a cron that had never once run |

> **A note on the contribution graph.** Almost all of the above lives in **private client repositories**, so what is public here is a small fraction of the work. Happy to walk through any of it in detail.

---

## 🌱 Currently

- Building an **operations hub** that unifies scattered client systems into one event-driven platform
- Going deeper on **agentic workflows**: tool design, evals, and getting LLM output to be reliable enough to ship
- **Postgres at scale**: partitioning, query planning, and getting RLS right the first time
- Reading more **incident write-ups** than tutorials, because that is where the real lessons are

---

## 💬 How I work

- **Verify before claiming.** If I say it is fixed, I have run it. Green tests are evidence, not a feeling.
- **Fix the cause, not the symptom.** A retry that hides a race condition is a bug with better manners.
- **Write it down.** Decisions get recorded with the reasoning, so the next person is not guessing.
- **Small commits, clear messages.** Someone will read this at 2am during an outage. Probably me.

---

<div align="center">

## 📫 Get in touch

[![Email](https://img.shields.io/badge/Email-8B0101?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nicoarchelauspasion@gmail.com)

<br>

**Open to conversations about interesting systems problems.**

<img src="https://komarev.com/ghpvc/?username=nicopasion&label=Profile%20views&color=8B0101&style=flat" alt="profile views" />

</div>
