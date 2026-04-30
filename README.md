# Política de Privacidade — Port Go

Static legal pages for the **Portaria Go** app (condominium management system). Serves the privacy policy required by app stores (Google Play / App Store) and LGPD compliance.

## Tech Stack

- Plain HTML with inline CSS
- No frameworks, no build step
- Deployed via Vercel

## Running Locally

Open `index.html` directly in a browser, or use a local HTTP server:

```bash
npx serve .
```

## Deploy

Push to `main` — Vercel auto-deploys on every commit.

To deploy manually:

```bash
vercel --prod
```

## Features

- **Privacy Policy** (`index.html`, pt-BR) — covers:
  - Data collected: name, phone number, apartment/tower, FCM push token
  - Data usage: WhatsApp notifications, push notifications, doorman panel identification
  - AI assistant: semantic search via OpenAI embeddings + response generation via Anthropic (Claude) — no personal data transmitted
  - Push notifications via Firebase Cloud Messaging (Google)
  - Data sharing: Evolution API/WhatsApp, Firebase only; no data sold or rented
  - Storage: Supabase/PostgreSQL with encryption at rest/transit and Row Level Security
  - Account and data deletion: email request, 7-business-day SLA
  - User rights under LGPD (Brazilian data protection law)
  - Security measures: HTTPS/TLS, RLS, mandatory authentication

## Folder Structure

```
politica_privacidade_port_go/
├── CLAUDE.md       # Project instructions for Claude Code
├── README.md
└── index.html      # Privacy policy page (pt-BR)
```
