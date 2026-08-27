# Koralbyte Group Website

Static HTML/CSS/JS site for Koralbyte Group (no build step, no framework).

## Pages

- `koralbyte-group-home.html` — homepage
- `koralbyte-advisory.html` — Advisory hub (glance list, capability cards, browse-by-country)
- `koralbyte-advisory-malaysia.html` — Malaysia service page
- `koralbyte-advisory-indonesia.html` — Indonesia service page
- `koralbyte-ventures.html` — Cocoa + Koralbyte Studios
- `koralbyte-about.html` — narrative About page

## Design system

- Colors: Ink navy `#1D2A3D`, Ink-2 `#243449`, Paper `#F6F9FB`, Paper-2 `#EAEFF3`, Steel `#33678A`, Sky `#78A6C9`, Coral `#E55C4F` (single accent, used sparingly).
- Type: Space Grotesk (display), Inter (body), JetBrains Mono (eyebrows/labels/stats).
- Motion: calm animated gradient mesh in hero sections, respects `prefers-reduced-motion`.
- Nav: the "Advisory Services" item is a mega-menu (pure CSS hover/focus-within) covering Malaysia and Indonesia only. Touch/tap fallback for mobile is a known open item.

## Known open items

1. Mobile nav fallback — the mega-menu is hover-only right now; needs a tap-friendly version for touch devices.
2. Advisory hub page consistency — the "At a Glance" list and 11 capability cards on `koralbyte-advisory.html` describe services in general terms, written before the site was narrowed to Malaysia/Indonesia only. Whether to keep this as a broad overview above the per-country detail, or cut it down to match the two-country scope exactly, is still open.
3. Contact details are placeholders and not yet confirmed.
4. Individual service sub-pages don't exist yet; each country page is one long page with anchored category sections.
