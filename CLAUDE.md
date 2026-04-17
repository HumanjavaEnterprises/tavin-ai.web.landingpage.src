# CLAUDE.md — tavin-ai.web.landingpage.src

## What This Is
Landing page for Tavin AI at `tavin.ai`. "Meet Tavin" — an approachable single-page introduction to VoxRelay's AI voice agent. Positioned as a character/personality page, not a technology brand. A prospect who just got a call from Tavin and wants to know "who called me?" should land here and feel reassured.

## Hosting
GitHub Pages from `docs/` on `main` branch. Custom domain `tavin.ai` via CNAME.

## Stack
- Static HTML, CSS — no JS, no build step
- Inter font from Google Fonts
- Dark mode via `prefers-color-scheme`
- Mobile-first, WCAG AA
- Plausible analytics (`data-domain="tavin.ai"`)

## Relationship to VoxRelay
Tavin is the voice agent behind VoxRelay. This page introduces Tavin by name and links to `voxrelay.ca` for the business product. It is NOT a separate product — it's a face for the same platform.

## Conventions
- No frameworks, no build tools
- Accessibility first (aria-labels, reduced-motion)
- All assets in `/docs`
- No Co-Authored-By lines

## Related Repos
- `voxrelay.web.landingpage.src` — VoxRelay marketing site (voxrelay.ca)
- `voxrelay.bizdocs.src` — product strategy, voice scripts, use cases
- `voxrelay.srvr.voicellm.src` — the sovereign voice engine Tavin runs on
- `tavin-ai.srvr.mcp.src` — Tavin AI companion MCP server
