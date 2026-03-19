Description
Nexus Ultra is a modern, scalable web platform engineered for high performance, seamless user experience, and rapid deployment. Built with a clean architecture and optimized workflows, it integrates cutting-edge frontend technologies with efficient backend services to deliver a robust digital ecosystem.
Deployed on Netlify for continuous integration and lightning-fast global delivery, Nexus Ultra emphasizes responsiveness, security, and maintainability. The platform is designed to support dynamic content, modular components, and future-ready enhancements, making it ideal for startups, enterprises, and experimental projects alike.# Nexus Ultra Platforms — Full-Stack AI Code Generator

> **Nexus Ultra Platforms · nisarllc206-sys**
> [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
> [![Node.js](https://img.shields.io/badge/Node.js-18%2B-green)](https://nodejs.org)
> [![Claude](https://img.shields.io/badge/AI-Claude%20Sonnet-blueviolet)](https://anthropic.com)
> [![GPT-4o](https://img.shields.io/badge/AI-GPT--4o-orange)](https://openai.com)
> [![Version](https://img.shields.io/badge/version-2.0.0-cyan)](package.json)

Automatically generate production-ready, well-commented code for the entire **Nexus Ultra Platforms** ecosystem — a full-stack AI SaaS system covering Android, Web PWA, Node.js backend, Google AdMob monetization, AI services, and marketing automation.

---

## Architecture Overview

```
┌─────────────────────────────────────────────────────────────────┐
│                   NEXUS ULTRA PLATFORMS                         │
│                                                                 │
│  ┌───────────────────────┐   ┌───────────────────────────────┐  │
│  │  MODULE 1 · ANDROID   │   │  MODULE 2 · WEB PWA           │  │
│  │  AI PDF Super Toolkit │   │  Nexus Ultra SaaS Platform    │  │
│  │  Kotlin · MVVM · MD3  │   │  Next.js 14 · App Router      │  │
│  │  AdMob · AI · OCR     │   │  Admin · Builder · Marketing  │  │
│  └──────────┬────────────┘   └──────────────┬────────────────┘  │
│             │                               │                   │
│             └──────────────┬────────────────┘                   │
│                            ▼                                    │
│  ┌──────────────────────────────────────────────────────────┐   │
│  │          MODULE 3 · UNIFIED BACKEND                      │   │
│  │          Fastify / Node.js · REST + GraphQL              │   │
│  │  Auth · Sites · AI Routes · Email · Billing · Affiliate  │   │
│  │  PostgreSQL · Redis · ClickHouse · Pinecone · BullMQ     │   │
│  └──────────────┬────────────────┬────────────────┬─────────┘   │
│                 ▼                ▼                ▼             │
│  ┌────────────────┐  ┌─────────────────┐  ┌──────────────────┐  │
│  │  MODULE 4      │  │  MODULE 5       │  │  MODULE 6        │  │
│  │  ADMOB &       │  │  AI SERVICES    │  │  MARKETING       │  │
│  │  MONETIZATION  │  │  Website Gen    │  │  Social Sched.   │  │
│  │  AdSense       │  │  Chatbot RAG    │  │  Email Drip      │  │
│  │  Affiliate     │  │  SEO Engine     │  │  Affiliate Prog. │  │
│  └────────────────┘  └─────────────────┘  └──────────────────┘  │
└─────────────────────────────────────────────────────────────────┘
```

---

## What Gets Generated

```
output/
├── android/
│   └── app/src/main/
│       ├── java/com/nexusultra/pdftoolkit/
│       │   ├── MainActivity.kt
│       │   ├── viewmodel/DashboardViewModel.kt
│       │   ├── viewmodel/PdfViewModel.kt
│       │   ├── ai/AIModule.kt
│       │   ├── ocr/OCRScanner.kt
│       │   ├── ads/AdManager.kt
│       │   ├── qr/QRGenerator.kt
│       │   ├── media/MediaConverter.kt
│       │   ├── filemanager/FileManager.kt
│       │   ├── network/NetworkModule.kt
│       │   └── repository/ToolRepository.kt
│       ├── res/layout/activity_main.xml
│       └── AndroidManifest.xml
│   ├── build.gradle.kts
│   └── settings.gradle.kts
│
├── web/
│   ├── app/
│   │   ├── layout.tsx
│   │   ├── (dashboard)/dashboard/page.tsx
│   │   ├── (builder)/builder/[siteId]/page.tsx
│   │   ├── (marketing)/page.tsx
│   │   ├── (marketing)/pricing/page.tsx
│   │   ├── (marketing)/affiliate/page.tsx
│   │   └── (admin)/admin/page.tsx
│   ├── components/
│   │   ├── ads/AdUnit.tsx
│   │   └── dashboard/AdRevenue.tsx
│   ├── stores/builder.ts
│   └── tailwind.config.ts
│
├── backend/
│   ├── src/
│   │   ├── server.js
│   │   ├── routes/auth.js
│   │   ├── routes/sites.js
│   │   ├── routes/ai.js
│   │   ├── routes/email.js
│   │   ├── routes/billing.js
│   │   ├── routes/affiliate.js
│   │   ├── services/AnalyticsService.js
│   │   ├── services/AIWebsiteGenerator.js
│   │   ├── services/ChatbotService.js
│   │   ├── services/SocialScheduler.js
│   │   ├── queue/aiWorker.js
│   │   ├── config/monetization.js
│   │   └── email/templates/welcome.html
│   ├── db/schema.sql
│   └── docker-compose.yml
│
├── admob/
│   ├── ADMOB_SETUP.md
│   └── AdManagerFull.kt
│
└── generation-summary.json
```

---

## Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/nisarllc206-sys/Ai-pdf-super-toolkit
cd Ai-pdf-super-toolkit

# 2. Install dependencies
npm install

# 3. Configure environment
cp .env.example .env
# Open .env and add at minimum: ANTHROPIC_API_KEY

# 4. (Optional) Initialise editable prompt files
npm run prompts:init

# 5. Generate all code
npm run generate:all
```

---

## Available Scripts

| Script | Provider | Module | Description |
|---|---|---|---|
| `generate:all` | Claude | All 6 modules | Generate the complete platform |
| `generate:android` | Claude | Android | AI PDF Toolkit Kotlin app |
| `generate:web` | Claude | Web | Next.js 14 web platform |
| `generate:backend` | Claude | Backend | Fastify API, DB schema, Docker |
| `generate:admob` | Claude | AdMob | AdMob guide + full Kotlin impl |
| `generate:marketing` | Claude | Marketing | Social scheduler, email, affiliate |
| `generate:root` | Claude | Root | README, package.json, .env.example |
| `generate:all:gpt` | GPT-4o | All | Same, using OpenAI GPT-4o |
| `generate:claude` | Claude | All | Alias for `generate:all` |
| `generate:openai` | GPT-4o | All | Alias for `generate:all:gpt` |
| `verbose` | Claude | All | Full logging of every file path |
| `dry-run` | Claude | All | Preview tasks without writing files |
| `prompts:init` | — | — | Create editable `prompts/*.txt` files |
| `clean` | — | — | Delete all output files |
| `dev:all` | — | — | Run web + backend dev servers |

You may also control execution via environment variables directly:

```bash
API_PROVIDER=openai MODULE=backend VERBOSE=true node generator.js
```

---

## Customising Prompts

Every generation task has a corresponding key (e.g. `android_main`, `web_builder`, `backend_auth`). Run `npm run prompts:init` to create a `prompts/` folder with one `.txt` file per task. Edit any file and the generator will use your custom prompt instead of the built-in default. This lets you adjust code style, add specific business logic, or change architecture decisions without modifying `generator.js`.

---

## Environment Variables

| Group | Key | Description | Required |
|---|---|---|---|
| Generator | `API_PROVIDER` | `anthropic` or `openai` | Yes |
| Generator | `MODULE` | Which module to generate | No (default: all) |
| AI Keys | `ANTHROPIC_API_KEY` | Claude API key | Yes (for Claude) |
| AI Keys | `OPENAI_API_KEY` | OpenAI API key | Yes (for GPT-4o) |
| AdMob | `ADMOB_APP_ID` | AdMob application ID | Android |
| AdMob | `ADMOB_*_AD_UNIT_ID` | Ad unit IDs (5 types) | Android |
| AdSense | `ADSENSE_PUBLISHER_ID` | AdSense publisher ID | Web |
| Database | `DATABASE_URL` | PostgreSQL connection string | Backend |
| Database | `REDIS_URL` | Redis connection string | Backend |
| Database | `CLICKHOUSE_*` | ClickHouse analytics DB | Backend |
| Database | `PINECONE_*` | Vector DB for chatbot | Backend |
| Auth | `JWT_ACCESS_SECRET` | 64-char random hex | Backend |
| Payments | `STRIPE_SECRET_KEY` | Stripe secret key | Backend |
| Payments | `STRIPE_PRICE_*` | 7 Stripe price IDs | Backend |
| Email | `RESEND_API_KEY` | Resend API key | Backend |
| Storage | `AWS_S3_BUCKET` | S3 bucket name | Backend |
| Social | `TWITTER_API_KEY` | Twitter API v2 key | Marketing |
| Social | `LINKEDIN_CLIENT_ID` | LinkedIn app client ID | Marketing |
| Social | `META_APP_ID` | Facebook/Instagram app | Marketing |
| Affiliate | `PAYPAL_CLIENT_ID` | PayPal payout credentials | Backend |

See `.env.example` for the complete reference including Android build config variables.

---

## Deployment

**Web (Next.js)** — Deploy to Vercel:
```bash
cd output/web && npx vercel --prod
```

**Backend (Fastify)** — Run locally with Docker Compose:
```bash
cd output/backend && docker-compose up -d
```
Or deploy to Railway / Render with a single `railway up` command.

**Android** — Open `output/android/` in Android Studio. Generate a signed release APK or AAB, then upload to Google Play Console.

---

## GitHub


87417e6f7964dfd2e478f4e08262d14b6ed4685d
---

## License

MIT © 2024 Nexus Ultra Platforms