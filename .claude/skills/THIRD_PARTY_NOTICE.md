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

## MIT License

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
