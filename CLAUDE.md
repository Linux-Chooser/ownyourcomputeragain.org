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
| Pam | Feels Director, coordination | `~/.claude/team/staff/pam.md` |
| Martha | Feels review (secondary after Pam) | `~/.claude/team/staff/martha.md` |

### Production Gate

Nothing ships to production without Pam's approval. She reviews every page, every piece of copy, every design choice through the lens of "how would this make someone feel?" Martha is secondary approval after Pam, ensuring the site feels right to people who aren't technical.

### Guiding Principle

> Always put yourself in the person's shoes and ask: how would I feel when finding and reading this page?

This is the northern star for every decision on this project.

---

## Technical Stack

- **Framework:** Hugo 0.155.2 (extended, pinned)
- **Theme:** Custom `oyca` theme
- **Styling:** SCSS (compiled by Hugo)
- **Deployment:** GitHub Actions -> GitHub Pages
- **Approach:** Build as we go. Landing page first, then guides/resources/blog.

---

## Design System

**Palette (Light Theme):**
| Token | Hex | Usage |
|-------|-----|-------|
| ink | #FAFAF7 | Background (warm cream) |
| ink-2 | #F3F0EA | Card/section backgrounds (warm stone) |
| bone | #2C2C2E | Primary text (soft charcoal) |
| bone-dim | #5D5550 | Secondary text (warm gray, 7:1 contrast) |
| amber | #E8943A | Decorative accent (buttons, large headings, glows) |
| amber-text | #9E6516 | Amber safe for small text (4.8:1 contrast) |
| amber-deep | #C47A1E | Hover accent |
| mint | #5B9A78 | Decorative accent (dots, glows) |
| mint-text | #3D7A58 | Sage safe for small text (5.1:1 contrast) |
| line | rgba(44,44,46,.16) | Borders (visible on light backgrounds) |

**Accessibility Floor:** All text meets WCAG AA (4.5:1 minimum). Minimum font size .85rem (~13.6px) for labels.

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
