# Agent & Agency — site preview

Static HTML preview of the Agent & Agency landing page, for internal review by the three principals (Josh, Adam, Jordan) before visual identity lock.

## What's here

- `index.html` — single-page mockup. All CSS inlined. No build step, no JS.
- `assets/` — B&W portraits for the Team section.

## Copy source of truth

Copy comes from `clients/agentandagency/messaging/landing-page-framework.md` in the working repo (not included here). Any copy change on the preview should be mirrored back there.

## Deploy

Any static host works. Tested paths:

- **GitHub Pages** — push this folder to the root of a public repo, enable Pages on `main` / `/` (root).
- **Netlify / Vercel** — drag the folder into their web UI for an instant preview URL.

The page includes `<meta name="robots" content="noindex, nofollow">` so it won't be indexed while the brand is still pre-launch.

## Status

Framework-locked copy. One outstanding decision — the contact-CTA mechanism (Calendly / form / email) — currently rendered as a `[contact email]` placeholder.
