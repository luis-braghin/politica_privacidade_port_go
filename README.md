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

- **Privacy Policy** (`index.html`) — covers data collection, usage, AI assistant (OpenAI + Anthropic), push notifications (FCM), data sharing, storage (Supabase/PostgreSQL), account deletion, and user rights (LGPD)

## Folder Structure

```
politica_privacidade_port_go/
├── CLAUDE.md       # Project instructions for Claude Code
├── README.md
└── index.html      # Privacy policy page (pt-BR)
```
