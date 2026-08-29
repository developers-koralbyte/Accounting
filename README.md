# Koralbyte Group Website

Static HTML/CSS/JS site for Koralbyte Group (no build step, no framework).

## Pages

- `koralbyte-group-home.html` — homepage
- `koralbyte-advisory.html` — Advisory hub (glance list, capability cards, browse-by-country)
- `koralbyte-advisory-malaysia.html` — Malaysia service page
- `koralbyte-advisory-indonesia.html` — Indonesia service page
- `koralbyte-ventures.html` — Cocoa + Koralbyte Studios
- `koralbyte-about.html` — narrative About page
- 35 individual service pages (`koralbyte-malaysia-*.html`, `koralbyte-indonesia-*.html`), one per service in the confirmed taxonomy, linked from the two country hub pages.

## Design system

Generated and persisted with the `ui-ux-pro-max` skill (see `.claude/skills/ui-ux-pro-max/`); full spec in `design-system/koralbyte-group/MASTER.md`. Pattern: Trust & Authority + Conversion. Style: Accessible & Ethical (Minimalism/Swiss-adjacent).

- Colors (CSS variable names unchanged from the previous system, values updated): Ink navy `#0F172A` (`--ink`), Ink-2 `#1E293B` (`--ink-2`), Paper `#F8FAFC` (`--paper`), Paper-2 `#E8ECF1` (`--paper-2`), Steel `#334155` (`--steel`, secondary), Sky `#38BDF8` (`--sky`, tertiary), Accent `#0369A1` (`--coral` variable name kept, now the blue CTA/accent color — no longer coral).
- Type: Plus Jakarta Sans (display and body), JetBrains Mono (eyebrows/labels/stats, unchanged).
- Motion: calm animated gradient mesh in hero sections, respects `prefers-reduced-motion` (unchanged).
- Nav: the "Advisory Services" item is a mega-menu (pure CSS hover/focus-within) covering Malaysia and Indonesia only. Touch/tap fallback for mobile is a known open item.

**Note on the accent color:** the previous design system used one warm coral accent (`#E55C4F`) against cool navy/blue tones. The persisted `ui-ux-pro-max` design system for this product category ("B2B Service" / "Trust & Authority") returned an all-cool-tone palette instead — a blue accent/CTA color rather than a contrasting warm one. This is a deliberate, database-driven choice for this pattern, but it is the single most visible departure from the previously client-approved identity. Easy to swap back to a warm accent (e.g. `#A16207` gold, also matched during the search) if preferred — it's one value (`--coral`) across all 42 pages.

## Known open items

1. Mobile nav fallback — the mega-menu is hover-only right now; needs a tap-friendly version for touch devices.
2. Advisory hub page consistency — the "At a Glance" list and 11 capability cards on `koralbyte-advisory.html` describe services in general terms, written before the site was narrowed to Malaysia/Indonesia only. Whether to keep this as a broad overview above the per-country detail, or cut it down to match the two-country scope exactly, is still open.
3. Contact details are placeholders and not yet confirmed.
4. The homepage and About page still reference a 6/7-country footprint ("Southeast Asia, North America, and Europe", "7 legal entities in 6 countries") from a client content update, inconsistent with the 3-country footprint (Malaysia HQ, Canada, Indonesia) used elsewhere on the site. Not touched in this pass since it's content, not styling.
