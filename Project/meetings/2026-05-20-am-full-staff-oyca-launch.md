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

## Post-Meeting Additions (Aaron & Pam, Private)

Following the full staff meeting, Aaron and Pam discussed:

- **Platform independence:** GitHub is Microsoft-owned. Identified risk if OYCA gains traction. Alternatives noted: Codeberg, Gitea (self-hosted), SourceHut. Deployment alternatives: Netlify, Cloudflare Pages. Added to backlog as "Platform Independence Plan."
- **Funding paths:** Crowdsourcing (GoFundMe, Open Collective) and grant opportunities (EFF, Linux Foundation, Software Freedom Conservancy, Mozilla Foundation) identified for future if needed.
- **MIT License** added to repository.
- **CONTRIBUTING.md** added with voice/tone guidelines, technical standards, submission process, and code of conduct.
- Both files committed to the OYCA repo.

---

### 6. Pam Designated Feels Director

Aaron designated Pam as **Feels Director** for OYCA. Nothing ships to production without her approval. Martha is secondary approval after Pam. Every page, every piece of copy, every design choice is reviewed through the lens of "how would this make someone feel?"

**Guiding Principle (North Star) codified:**

> "Always put yourself in the person's shoes and ask: how would I feel when finding and reading this page?"

**Mandy (Amanda Stevenson)** added to OYCA team for data, analytics, and metrics.

---

### 7. Light Theme Reskin

Aaron directed a full theme reskin from dark to light, based on Pam's emotional brief. Pam described five feelings the site should evoke: relief, trust, warmth, simplicity, and belonging. "Like a letter from a friend who figured it out first."

Lila executed the reskin via SCSS variable swap — all components auto-inherited new values:

| Token | Dark (Before) | Light (After) |
|-------|--------------|---------------|
| ink | #0c0c0e | #FAFAF7 (warm cream) |
| bone | #ECE7DD | #2C2C2E (soft charcoal) |
| bone-dim | #A29C90 | #5D5550 (warm gray) |
| mint | #74E0AE | #5B9A78 (sage green) |

Grain overlay removed (dark-theme technique). Welcome card replaced terminal mockup. Committed to main.

---

### 8. Vincent's Accessibility Pass

Aaron flagged contrast and font size issues on the light background. Vincent (contractor) was called in.

**Findings:**
- `$bone-dim` at 5.2:1 — technically passing but too faint at small sizes
- `$amber` on cream at 2.3:1 — fails WCAG AA entirely
- `$mint` on cream at 3.2:1 — fails for small text
- Border token at 10% opacity — essentially invisible
- Label font sizes at .72rem (11.5px) — too small for older visitors

**Fixes implemented:**
- `$bone-dim` darkened to #5D5550 (7:1 contrast)
- New `$amber-text` (#9E6516, 4.8:1) for small label text
- New `$mint-text` (#3D7A58, 5.1:1) for small label text
- Border opacity raised to 16%
- Minimum font size floor set at .85rem (13.6px)
- Accessibility floor documented in CLAUDE.md

---

### 9. Persona Panels Reworked

The team identified that the original four persona panels (Gamers / Developers / Artists & Creators / Everyday Users) didn't match the actual target audience. Identity-based panels excluded people who don't self-identify with those labels.

**New audience-focused panels:**

| Panel | Heading | Audience |
|-------|---------|----------|
| For / Everyday Life | It just gets out of the way. | General users, browsing, email, video calls |
| For / Your Budget | Everything you need. Nothing you owe. | Students, retirees, cost-conscious users |
| For / Your Work | A quiet, focused workspace. | Remote workers, freelancers, small business |
| For / Your Creativity | Pro tools, zero rent. | Photographers, writers, musicians, designers |

Pam's review flagged two notes: removed "Not a niche OS for techies" (unnecessary friction), added LibreOffice Writer to the creativity panel tags (writers need to see themselves). Both addressed. Pam signed off on landing page.

---

### 10. Three-Path Get-Started Page

Aaron asked the critical question: what is the actual flow for a visitor coming from Windows vs. macOS (Intel vs. Apple Silicon)?

**Team analysis identified three distinct paths:**

| Path | Experience | Approach |
|------|-----------|----------|
| Windows | Smooth, well-supported | Full 5-step guide with Secure Boot note |
| Mac (Intel) | Works with caveats | 5-step guide, WiFi/trackpad and T2 chip notes |
| Mac (Apple Silicon) | Not natively ready yet | UTM virtual machine option + Asahi Linux follow |

Lila built a path picker at the top of the get-started page — three warm cards ("choosing a door, not reading a warning label" per Vincent). Vanilla JS toggles visibility. Windows shown by default. Apple Silicon headline: "You're not left out. You're early."

Intel Mac path includes elementary OS as an alternative (designed to feel like macOS). Apple Silicon path offers UTM as a genuine way to try Linux today, not a consolation prize.

Pam signed off: "Every visitor leaves with a next step. Nobody hits a dead end."

---

### 11. Help Page & Site-Wide Get Help Button

Aaron directed: "I want a big HELP button on every page to make it clear help is just a few clicks away."

**Get Help button:** Warm amber pill in the site nav, `margin-left: auto` to push right. Appears on every page. Styled by Vincent to feel welcoming, not urgent.

**Help page** (`/help/`) organized in four lanes per Pam's framework:

| Lane | Heading | Resources |
|------|---------|-----------|
| Search for answers | "Type your question. Someone's probably already answered it." | Linux Mint Forums, Ubuntu Forums, Ask Ubuntu, It's FOSS, ArchWiki |
| Talk to someone | "Sometimes you need a human, not a search result." | r/linuxquestions, r/linux4noobs, Linux Mint Community, Ubuntu Community, Fedora Discussion |
| Watch and learn | "Some things are easier when someone shows you." | Learn Linux TV, The Linux Experiment, Chris Titus Tech, Linux Journey |
| Read the docs | "For people who like to understand how things work." | Official distro docs (5), general reference (4), free books (4) |

The "Read the docs" lane includes subsections: Official distro documentation, General Linux reference, and Free books (The Linux Command Line, Debian Administrator's Handbook, Linux From Scratch, Pro Git).

Pam signed off on all four lanes.

---

### 12. Launch

**Site deployed to production at ownyourcomputeragain.org.**

- GitHub repo: `Linux-Chooser/ownyourcomputeragain.org`
- Deployment: GitHub Actions -> GitHub Pages
- DNS: GoDaddy, four A records (GitHub IPs) + www CNAME
- CNAME file in `static/CNAME`
- 10 commits on main, clean history
- 10 pages built (home, get-started, help, plus defaults)

**Pam's launch review:**

> "We built that today. From a brochure and a mission statement to a live website with three pages, four help lanes, three platform paths, and a warm amber button that says 'we're here if you need us.' In one session."

**Site verified live and fully rendered.**

---

## Pam's Newcomer Framework

During the session, Pam articulated a framework for understanding OYCA's audience:

1. **The Fed Up** — Angry about what happened to their computer. Motivated, don't need convincing. Need a path.
2. **The Curious** — Heard about Linux somewhere, wondering. May not act today. Need a reason to bookmark.
3. **The Stuck** — Older computer, can't afford a new one. Need this to work. No plan B. "We get one shot with them."

> "Everything we build should be measured against that third person. If it works for them, it works for everyone."

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
| 7 | Screenshots/video section — "what Linux actually looks like" | Kate, Vincent | Future |
| 8 | Testimonials — real user stories | Jen | Future |
| 9 | Full accessibility audit | Sue | Next |
| 10 | Content backlog (9 items from team review) | Jen, Team | Backlog |

---

## Key Quotes

> "This doesn't look like an open source project page. This looks like a brand." — Lila

> "That's not a website. That's a narrative arc." — Jen

> "You're not asking people to figure out if Linux is for them. You're telling them it already is." — Sue

> "Nobody is standing at the front door of the alternative and saying 'come in, it's okay, we built this for you.' Until now." — Pam

> "I don't pretend to understand all the technical pieces. But I know what good storytelling looks like." — Martha

> "We are building a community that welcomes people in, not one that tests them at the door." — CONTRIBUTING.md

> "Everything we build should be measured against that third person. If it works for them, it works for everyone." — Pam

> "You're not left out. You're early." — Apple Silicon path headline

> "Like a letter from a friend who figured it out first." — Pam, on the light theme direction

---

*Minutes recorded and updated by Sara Johansen, Executive Assistant*
*THG Media — The Henderson Group*
