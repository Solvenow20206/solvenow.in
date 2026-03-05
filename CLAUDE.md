# SolveNow Landing Page — Project Context

## What Is This
Company landing page for SolveNow (`solvenow.in`). Static HTML with animated UI — no backend, no build step.

## Pages
- `index.html` — Company homepage (solvenow.in)
- `virasat.html` — Virasat product page (solvenow.in/virasat)

## Design & Animations
Both pages use a consistent animated design system (all vanilla CSS + JS, no libraries):
- **Animated gradient** hero backgrounds (shifting indigo/violet/navy)
- **Floating geometric shapes** (CSS keyframe animations)
- **Glass-morphism navbar** — transparent at top, blur backdrop on scroll
- **Scroll-triggered reveals** — IntersectionObserver-based fade/slide animations
- **Animated counters** — numbers count up with eased animation on scroll
- **3D tilt** on product/pricing cards (CSS perspective + JS mousemove)
- **Timeline** with filling line and scaling step numbers
- **Floating particles** in CTA sections (JS-generated)
- **Text cycling** in index.html hero ("real problems" → "your family" → "your business")
- **Color palette:** `--navy: #0f172a`, `--indigo: #4f46e5`, `--violet: #7c3aed`
- **Font:** Inter (Google Fonts), weights 400–900

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
- All CSS is inlined in `<style>` tags, all JS is inlined in `<script>` tags
- Mobile responsive at 768px and 480px breakpoints

## GitHub
- **Org:** Solvenow20206
- **Repo:** solvenow.in

## Related Projects (separate repos)
- **Virasat** — Family Financial Safety Net (`virasat.solvenow.in`)
- **Inventra** — Asset Lifecycle Management
- **NitiGo** — Policy Governance Platform
