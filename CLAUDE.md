# SolveNow Landing Page — Project Context

## What Is This
Company landing page for SolveNow (`solvenow.in`). Static HTML — no backend, no build step.

## Pages
- `index.html` — Company homepage (solvenow.in)
- `virasat.html` — Virasat product page (solvenow.in/virasat)

## Hosting
- **Cloudflare Pages** (free tier) — auto-deploys from GitHub on push to `main`
- **Domain:** `solvenow.in` + `www.solvenow.in`
- **DNS:** Cloudflare (nameservers: anuj.ns.cloudflare.com + harmony.ns.cloudflare.com)

## Deploy
Push to `main` branch → Cloudflare Pages auto-builds and deploys (~30 seconds).

## Local Development
Just open `index.html` in a browser. No build tools needed.

## Key Rules
- This project is **completely independent** from all product repos (Virasat, NitiGo, Inventra)
- No shared infrastructure — separate git, separate hosting, separate deployment
- If a product goes down or is sold, this site stays up
- Keep it static HTML — no frameworks, no build steps, no dependencies

## GitHub
- **Org:** Solvenow20206
- **Repo:** solvenow.in

## Related Projects (separate repos)
- **Virasat** — Family Financial Safety Net (`virasat.solvenow.in`)
- **Inventra** — Asset Lifecycle Management
- **NitiGo** — Policy Governance Platform
