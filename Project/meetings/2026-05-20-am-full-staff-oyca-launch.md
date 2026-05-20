---
title: "Full Staff Meeting — OYCA Project Launch"
date: 2026-05-20
time: "AM"
location: The Ready Room, 123 Prosperity Way, Asheville, NC
type: Full Staff Meeting
present:
  - Aaron Henderson (Creative Director & Founding President)
  - Pam Simpson (President)
  - Lila (CEO)
  - Terry (Project Manager & Lead Developer)
  - Kate (Web Designer)
  - Rebecca (HR Director)
  - Martha (Genealogy Research Lead)
  - Jen Connelly (Game Designer & Narrative Lead)
  - Candice Moreau (Executive Assistant & Office Administrator)
  - Sara Johansen (Executive Assistant & Office Administrator)
  - Sue Thompson (Developer)
preceding: null
description: "Aaron announces OYCA (Own Your Computer Again), a new THG Media open source project to boost worldwide Linux adoption. Team workshopped the mission statement, reviewed the brochure, and approved full project setup."
status: complete
minutes_by: Sara Johansen
---

# Full Staff Meeting — OYCA Project Launch

**Date:** May 20, 2026 (AM)
**Location:** The Ready Room
**Minutes by:** Sara Johansen

---

## Overview

Aaron announced a new THG Media open source project: **OYCA (Own Your Computer Again)** at ownyourcomputeragain.org. The project's mission is to boost worldwide Linux adoption through a marketing website that serves as the accessible front door to Linux for non-technical users. Aaron presented a completed brochure site (HTML + PDF) and the team reviewed, workshopped the mission statement, and approved the full project buildout.

---

## Agenda & Discussion

### 1. Standing Project Updates (Pre-OYCA)

**Black Sheep**
- All 10 phases complete. Deck architecture final: 218 cards, 84 unique designs.
- Generator v2.0 production-ready (Lila's full rewrite, all 7 blockers cleared).
- Pipeline confirmed solid by Sue and Terry. No blockers.
- Critical path: test print, then GameCon July 7.
- Jen confirmed no structural design surprises expected; any playtest findings will be tuning only.

**Emerald Web (Observatory)**
- Timezone database live (IANA, ~95 cities). City search, Live/Set toggle, planet popovers in.
- 3 of 6 manual corrections complete (#1-3). Remaining 3 in backlog.
- Lila: functional and not ugly, shipping. Remaining corrections are polish.

**Genealogy**
- Archive reorg in good shape. CLAUDE.md, baseline, launch block set.
- Martha deep in Howell-Rhys material (William and Fran, the locket).
- Martha: "I'm close. Genuinely close this time." (The room was skeptical. Warmly.)

**People & Operations (Rebecca)**
- Morale high. Three recent hires (Sara, Sue, Candice conversion) all landed smoothly.
- Rebecca checked in with Terry on workload and vacation. Terry acknowledged the note.
- Kate flagged for upcoming discussion re: post-Black Sheep plans.

**Admin (Candice & Sara)**
- Filing current across all projects. Meeting notes archived through prior Friday.
- Vendor accounts reconciled. Room prepped at 7:45 AM.

**Personal Announcement**
- Martha and Vincent: wedding in July. The team expressed warm congratulations.

---

### 2. OYCA Announcement

Aaron revealed the purchase of the domain **ownyourcomputeragain.org** and announced a new open source project to boost worldwide Linux adoption.

**The Challenge:** Aaron asked the team to figure out what the project was. The team debated, with Lila ultimately identifying the core: Linux, and a project to help people take their computers back from proprietary, subscription-locked, cloud-dependent systems.

**Clarification:** Aaron clarified that OYCA is not a Linux distribution. It is a marketing website — an education and advocacy platform to drive Linux adoption globally.

**Lila won a HomePod** for getting closest first (identified the Linux angle in under two minutes).

---

### 3. Brochure Review

Aaron directed the team to the existing brochure at `oyca/linux-brochure.html`. The team reviewed the full 6-page design.

**Team feedback (unanimous positive):**
- **Lila:** Typography praised (Fraunces, Hanken Grotesk, JetBrains Mono). Color palette (dark/amber/mint) called out as brand-quality. "This doesn't look like an open source project page. This looks like a brand."
- **Kate:** CSS architecture clean. Responsive breakpoints well-placed. Animations subtle and effective.
- **Jen:** Narrative arc praised — "That's not a website. That's a narrative arc." Closing line ("Stop renting your computer. Start owning it.") called Superbowl-ad quality. Tapped the table twice.
- **Sue:** Persona cards identified as smartest design choice — four audiences, each answered directly. "You're not asking people to figure out if Linux is for them. You're telling them it already is."
- **Terry:** Stats section praised for being sourced and evidence-based, not hype.
- **Pam:** "Your PC isn't obsolete. Your old OS just gave up on it" identified as the emotional core. "Nobody is standing at the front door of the alternative and saying 'come in, it's okay, we built this for you.' Until now."
- **Martha:** "I know what good storytelling looks like. This does that."

---

### 4. Mission Statement Workshop

**Aaron's draft:** "Drive worldwide Linux adoption marketing web site education and assistance"

**Team workshop process:**
- Sue proposed: "Empowering people worldwide to reclaim ownership of their computers through education, advocacy, and open source."
- Terry flagged "empowering" as corporate wallpaper.
- Lila suggested "helping" over "empowering" — honest, not performative.
- Martha emphasized "reclaim" as the emotional anchor.
- Jen confirmed "reclamation" as the core narrative.
- Lila proposed declarative framing: "We exist to..."
- Sue refined final clause: "...through education, advocacy, and community."

**Approved mission statement:**

> "We exist to help people worldwide reclaim ownership of their computers through education, advocacy, and community."

**Scope:** This is the OYCA project mission, not the THG Media company mission.

---

### 5. Project Buildout — Approved

Aaron directed full web publishing treatment for OYCA:
- Hugo project with custom theme
- Git repository
- GitHub Actions deployment pipeline
- CLAUDE.md with team assignments
- Project skeleton (`skel/`) for future THG web projects
- Web publishing best practices document for the company

**Team assignments for OYCA:**

| Name | OYCA Role |
|------|-----------|
| Lila | Technical Lead, CSS/design oversight |
| Kate | Web design, front-end |
| Terry | Development, QA |
| Sue | Development, accessibility |
| Jen | Narrative, copy |
| Pam | Coordination |

---

## Deliverables Completed (Same Session)

All three deliverables were built and committed during the meeting session:

1. **OYCA Hugo Project** (`oyca/`) — 24 files. Custom `oyca` theme with SCSS extracted from brochure. Homepage template, single/list templates, deploy pipeline, dev server script, CLAUDE.md. Git repo initialized, initial commit done.

2. **Project Skeleton** (`skel/`) — 24 files. Reusable Hugo project template with placeholder system for rapid new project standup.

3. **Web Publishing Best Practices** (`Project/docs/web-publishing-best-practices.md`) — 10-section standards document covering Hugo, themes, deployment, content, git, accessibility, QA, and documentation.

---

## Post-Meeting Additions (Aaron & Pam)

Following the full staff meeting, Aaron and Pam discussed:

- **Platform independence:** GitHub is Microsoft-owned. Identified risk if OYCA gains traction. Alternatives noted: Codeberg, Gitea (self-hosted), SourceHut. Deployment alternatives: Netlify, Cloudflare Pages. Added to backlog as "Platform Independence Plan."
- **Funding paths:** Crowdsourcing (GoFundMe, Open Collective) and grant opportunities (EFF, Linux Foundation, Software Freedom Conservancy, Mozilla Foundation) identified for future if needed.
- **MIT License** added to repository.
- **CONTRIBUTING.md** added with voice/tone guidelines, technical standards, submission process, and code of conduct.
- Both files committed to the OYCA repo.

---

## Action Items

| # | Action | Owner | Status |
|---|--------|-------|--------|
| 1 | Test print for Black Sheep — critical path to GameCon July 7 | Terry, Lila | In progress |
| 2 | Remaining observatory corrections (#4-6) | Kate, Lila | Backlog |
| 3 | Kate post-Black Sheep discussion (promotion) | Pam, Aaron | Pending |
| 4 | Platform independence plan for OYCA | Pam | Backlog |
| 5 | Funding paths research (crowdsource, EFF, grants) | Pam | Backlog |
| 6 | OYCA content pipeline — first guide/resource TBD | Jen, Sue | Future |
| 7 | Hugo dev server verification for OYCA | Terry, Sue | Next |

---

## Key Quotes

> "This doesn't look like an open source project page. This looks like a brand." — Lila

> "That's not a website. That's a narrative arc." — Jen

> "You're not asking people to figure out if Linux is for them. You're telling them it already is." — Sue

> "Nobody is standing at the front door of the alternative and saying 'come in, it's okay, we built this for you.' Until now." — Pam

> "I don't pretend to understand all the technical pieces. But I know what good storytelling looks like." — Martha

> "We are building a community that welcomes people in, not one that tests them at the door." — CONTRIBUTING.md

---

*Minutes recorded by Sara Johansen, Executive Assistant*
*THG Media — The Henderson Group*
