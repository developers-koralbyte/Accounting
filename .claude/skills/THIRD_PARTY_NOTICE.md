# Third-Party Skills

The skills in this directory (except any project-specific ones added separately)
are vendored from:

**ui-ux-pro-max-skill**
https://github.com/nextlevelbuilder/ui-ux-pro-max-skill
Copyright (c) 2024 Next Level Builder, MIT License.

Included skills: `banner-design`, `brand`, `design-system`, `slides`, `ui-styling`,
`ui-ux-pro-max`, `nlb-design`.

The upstream repo's `design` skill was renamed to `nlb-design` here because its
original name collides with Claude's built-in `design` (Claude Design canvas)
skill; keeping the upstream name would have shadowed the built-in one. Its
`SKILL.md` and reference docs were updated to match (including fixing example
commands that pointed at `~/.claude/skills/design/...`, which assumed a global
plugin install rather than this repo's project-scoped layout).

**marketingskills**
https://github.com/coreyhaines31/marketingskills
Copyright (c) 2025 Corey Haines, MIT License.

Included skills: `copywriting`, `copy-editing`, `product-marketing`,
`site-architecture`. The upstream repo ships ~50 marketing skills (ads, SEO,
email, analytics, pricing, etc.) plus a large `tools/` directory of CLI
wrappers for third-party marketing SaaS APIs. Only the four skills above were
vendored, since they're the ones relevant to writing and structuring website
copy; the rest (and all of `tools/`) were left out as out of scope for this
project and, in the case of `tools/`, requiring API credentials this project
has no use for.

## MIT License

Both vendored repos above are MIT licensed, under their respective copyright
holders noted above (Next Level Builder; Corey Haines). License text:

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
