# CLAUDE.md -- OYCA (Own Your Computer Again)

## What This Is

OYCA is a THG Media project to boost worldwide Linux adoption through education, advocacy, and community. The website serves as the front door to Linux for people who've never considered it, making the case, showing the path, and welcoming them in.

**Domain:** ownyourcomputeragain.org
**Working directory:** `/home/wahender/My_Library/Tech/thg-media/oyca/`
**Parent:** Standing directives from the THG Media CLAUDE.md carry forward to this project.

---

## Mission

> We exist to help people worldwide reclaim ownership of their computers through education, advocacy, and community.

This is the OYCA project mission, not the THG Media company mission.

---

## Team

| Name | OYCA Role | Profile |
|------|-----------|---------|
| Lila | Technical Lead, CSS/design | `~/.claude/team/staff/lila.md` |
| Kate | Web design, front-end | `~/.claude/team/staff/kate.md` |
| Terry | Development, QA | `~/.claude/team/staff/terry.md` |
| Sue | Development, accessibility | `~/.claude/team/staff/sue.md` |
| Jen | Narrative, copy | `~/.claude/team/staff/jen.md` |
| Mandy | Data, analytics, metrics | `~/.claude/team/staff/mandy.md` |
| Pam | Coordination | `~/.claude/team/staff/pam.md` |

---

## Technical Stack

- **Framework:** Hugo 0.155.2 (extended, pinned)
- **Theme:** Custom `oyca` theme
- **Styling:** SCSS (compiled by Hugo)
- **Deployment:** GitHub Actions -> GitHub Pages
- **Approach:** Build as we go. Landing page first, then guides/resources/blog.

---

## Design System

**Palette:**
| Token | Hex | Usage |
|-------|-----|-------|
| ink | #0c0c0e | Background |
| ink-2 | #141417 | Card/section backgrounds |
| bone | #ECE7DD | Primary text |
| bone-dim | #A29C90 | Secondary text |
| amber | #F2A33C | Primary accent |
| amber-deep | #d7821a | Hover/deep accent |
| mint | #74E0AE | Secondary accent |
| line | rgba(236,231,221,.12) | Borders |

**Typography:**
- **Fraunces** (serif) -- Headlines, display text
- **Hanken Grotesk** (sans-serif) -- Body text
- **JetBrains Mono** (monospace) -- Labels, code, technical elements

---

## Build & Dev

```bash
# Local development
./start_webserver.sh

# Production build
hugo --minify --gc
```

---

## Content Pipeline

Build as we go:
1. Landing page (complete -- the brochure)
2. Getting-started guides (future)
3. Distro comparisons (future)
4. Migration walkthroughs (future)
5. Community resources (future)
6. Blog/advocacy content (future)
