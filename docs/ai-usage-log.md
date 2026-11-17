# AI Usage Log: To the Digital Side (Al Lado Digital)

**Milestone:** Hito 1, Main Interfaces
**Maintained by:** Nelson Sandoval (UX/UI Designer), who consolidates the declarations of every member
**Last updated:** 2026-11-16

> **How to read this log.** Each entry says which AI tool was used, by whom, for what, what it produced and, most importantly, **what the team decided to do with the output and why**. AI output is treated as a draft: nothing in this repository is accepted just because a tool generated it. The decisions can be traced to documents in this repository (benchmark, interface evolution sheet, navigation flow).

---

## 1. Declaration by member

| Member | Role | AI tools used | Artifacts where AI assisted |
|---|---|---|---|
| Vicente Contreras | Project Manager | Claude (Anthropic) | Team-level entries AI-02 to AI-08 (shared project account) |
| Nelson Sandoval | UX/UI Designer | Claude (Anthropic) and Gemini (Google) | AI-01 (Gemini, generic wireframe kit, not used as screens) and the team-level entries AI-02 to AI-08 (shared project account) |
| Arturo Rivas | UX Researcher / Analyst | Claude (Anthropic) | Team-level entries AI-02 to AI-08 (shared project account) |

The sessions with Claude were run from the team's shared project account, so entries AI-02 to AI-08 are declared at team level and are not split by member. Gemini was used for AI-01.

---

## 2. Entries

### AI-01 · Generic wireframe kit (start of Delivery 3)

| Field | Detail |
|---|---|
| **Date** | The kit files are dated 2026-10-07 and were added to the project Drive on 2026-10-15 |
| **Tool** | Gemini (a Python script that generated SVG files) |
| **Used by** | Nelson Sandoval |
| **What was asked** | A starting kit of low-fidelity SVG wireframes. The files in the Drive folder are 18 mobile screens (360×640), web variants and a component sheet |
| **What the AI produced** | A generic app kit: splash, onboarding, login, feed, dashboard, search, list, detail, profile, settings, notifications, **chat**, **cart / checkout**, bottom sheet and states. Gray rectangles, no text and no brand |
| **Decisions** | **Not used as the project's screens.** The kit was a generic app and several of its patterns do not belong to our product. The final set (A1 to D2) has **no feed, no cart or checkout and no chat**: a one-tap call ("Hablar con una persona", A1m) replaces the chat so we do not recreate the confusion of WhatsApp groups that our personas complain about. The low-fidelity wireframes in this repository are the team's own work |
| **Verification** | The final screens were designed from the navigation flow and the benchmark, and every screen has real Spanish content. Their codes and names are listed in [`screen-names.md`](screen-names.md) |

### AI-02 · Project context document and UX plan for Delivery 3

| Field | Detail |
|---|---|
| **Date** | 2026-10-21 |
| **Tool** | Claude (Anthropic), from the team's project |
| **Used by** | Team (shared project account) |
| **What was asked** | To review the Drive folder "Proyecto UX" (Deliveries 1 and 2), consolidate the project in one document and propose a plan for the navigation flow and wireframes |
| **What the AI produced** | A consolidation of what had been delivered (Canvas, personas, benchmark, journey), a glossary of unified terms, and a **proposal**: an information architecture, three navigation flows, an inventory of 24 screens and a MoSCoW prioritization |
| **Decisions** | The team **did not adopt the proposal as it was**. The final design differs from it in three ways: (1) **Sign-up was left out of the wireframes** (the proposal had a three-step registration). The access method is still undecided and the core value we test does not depend on it (see the scope, section 4.1). (2) **Volunteers propose a meeting** from the requests of their own network, instead of the coordinator assigning them as the proposal said, so the coordinator's dashboard is a follow-up tool (D1, D2). (3) **20 screens instead of 24**, grouped into one main and two secondary flows, because the course asks for a bounded scope |
| **Verification** | The facts in the document were checked against the files in Drive. The proposals were labeled as proposals and not as findings. The final screen list was checked against [`screen-names.md`](screen-names.md) |

### AI-03 · Rubric transcription and compliance review

| Field | Detail |
|---|---|
| **Date** | 2026-11-04 |
| **Tool** | Claude (Anthropic) |
| **Used by** | Team (shared project account) |
| **What was asked** | To put the Hito 1 rubric in a Markdown file, review the Drive folders and the repository against it, and estimate the evaluation |
| **What the AI produced** | A rubric checklist, a gap analysis and a prioritized list: missing AI Usage Log, scope not delimited, four personas instead of three, placeholders left in the interfaces |
| **Decisions** | The team accepted the findings that matched the rubric text and acted on them (see AI-04). The score estimate is a planning aid only and is not claimed anywhere in the repository |
| **Verification** | The findings were compared with the rubric text, with the files in Drive and with a clone of this repository (every README link resolved to an existing file, except the link to this log, which did not exist yet) |

### AI-04 · README restructuring

| Field | Detail |
|---|---|
| **Date** | 2026-11-04 |
| **Tool** | Claude (Anthropic) |
| **Used by** | Team (shared project account) |
| **What was asked** | To change the README so that it meets the rubric |
| **What the AI produced** | A draft of the new README sections: UX Elements table (1.3), scope definition with traceability (4.1), three personas (3.2), synthetic benchmark table and restrictions (3.3), the written interface evolution in English (7.2) |
| **Decisions** | (1) **Three personas** drive the design, to match the course requirement. The fourth (Sofía) has the same role as Roberto and moved to the Annex. (2) **One main and two secondary flows**, grouping the 20 existing screens without changing any wireframe. (3) The text says openly that the personas are proto-personas **not yet validated with interviews**. (4) The AI's wording about how the benchmark was done was **replaced** by the wording already in the repository, because the AI's version described a method that no project file confirms. (5) The note about placeholders in the high-fidelity screens was **kept** while the published PDF and PNGs still contained them |
| **Verification** | Screen counts (11 + 7 + 2 = 20), screen codes and Figma links were checked against [`screen-names.md`](screen-names.md) and the repository README. Every internal link was checked against the files in the repository (the link to this log was the only one pending) |

### AI-05 · Visual layout of the Strategy documents (Canvas, Personas, Benchmark, Journey Map)

| Field | Detail |
|---|---|
| **Date** | Deliveries 1 and 2 (committed 2026-10-02 and 2026-10-09) |
| **Tool** | Claude (Anthropic) |
| **Used by** | Team (shared project account) |
| **What was asked** | To generate the visual design and layout of four documents: Value Proposition Canvas, UX Personas, Benchmark and Customer Journey Map |
| **What the AI produced** | The visual design and layout of those documents (in `assets/` and `docs/`: `value-proposition-canvas-en` / `value-proposition-canvas--en.pdf`, `ux-personas-1` to `ux-personas-4` / `ux-personas-en.pdf`, `benchmark-en`, and `customer-journey-v3-en` / `customer-journey-en.pdf`) |
| **Decisions** | The **content was the team's own**: the problem and customer analysis, the persona profiles, the benchmark observations and the journey stages. The AI was used only for the visual design, and the team published the layout it accepted. The benchmark screenshots are the team's own, taken on 2026-10-03 |

### AI-06 · Iteration of the high-fidelity interfaces (Delivery 3)

| Field | Detail |
|---|---|
| **Date** | During Delivery 3 (October 2026) |
| **Tool** | Claude (Anthropic) |
| **Used by** | Team, with the Designer as owner of the HD interfaces (project roles) |
| **What was asked** | To help iterate the high-fidelity interfaces |
| **What the AI produced** | Three kinds of help: **(1)** layout and hierarchy proposals, **(2)** proposals for visual style and components, **(3)** a review of the screens against usability heuristics and accessibility. This is declared for the HD interfaces as a whole, not per screen |
| **Decisions** | The team **asked for several versions and chose among them**, and **accepted proposals with its own adjustments**. The final decisions are in section 4 |
| **Verification** | (1) Against the benchmark and the usability heuristics, recorded in the interface evolution sheet. (2) By walking through the Figma prototype, so that every arrow of the navigation flow matches a link. (3) By the Designer's visual review (contrast, sizes and consistency) |

### AI-07 · Repository review, closure plan and drafting of this log

| Field | Detail |
|---|---|
| **Date** | 2026-11-15 and 2026-11-16 |
| **Tool** | Claude (Anthropic) |
| **Used by** | Team (shared project account) |
| **What was asked** | To review the repository against the rubric, prepare a closure plan and draft the final text of this log from the team's own declarations |
| **What the AI produced** | A checklist of gaps (missing log, placeholders in the HD screens, journey without associated interfaces) and the wording of this log |
| **Decisions** | The facts in this log (who used which tool, on which artifacts and what for) were **given by the team**; the AI only wrote them down, and where the team had not said, it left the detail out instead of guessing |

### AI-08 · Cleaning the high-fidelity screens and closing the README gaps

| Field | Detail |
|---|---|
| **Date** | 2026-11-16 and 2026-11-17 |
| **Tool** | Claude (Anthropic), connected to the team's Figma file and Google Drive |
| **Used by** | Team (shared project account) |
| **What was asked** | To replace the placeholders in the high-fidelity screens, re-export them, and draft the README sections that the closure plan marked as missing |
| **What the AI produced** | **(1)** In the hi-fi Figma file, it replaced the 10 placeholder texts with the fictional values the team approved (club "Nuevo Amanecer", "Calle Ejemplo 1234, Temuco", "www.cesfam-ejemplo.cl/horas"). It also moved the bottom sheet of `A1m` 21 px down so that it reaches the bottom edge again after the text change. **(2)** It re-rendered the 10 screens that changed. It pasted them over the same positions in the three hi-fi PNG sheets, and replaced only those 10 pages in the hi-fi PDF (those pages are now images). The two "(Prototipo)" buttons were hidden only for the export and are visible again in Figma. **(3)** It drafted the English text of README 3.3 (initial exploration guide), 4.2 (journey stages and their interfaces), 5.1 (note on the volunteer lane) and 6.1 (description of the paper sketch and the table "paper sketch → wireframes") |
| **Decisions** | The team chose the fictional values and decided to keep the "(Prototipo)" buttons in Figma. It also chose to explain the placeholders of the low-fi screens in the README instead of editing that file. The paper sketch is Nelson's own work (drawn on 2026-09-30); its date was given by the team and the AI did not edit the image. The README texts only describe what the repository's own documents show; the reasons for the changes were not invented |
| **Verification** | No bracketed placeholder is left in the hi-fi Figma file, and the hi-fi PDF shows 0 matches (12 before). The three sheets and the changed PDF pages were checked visually. All anchors and file links in the README resolve. The changes were merged by the team in PR #3 |

---

## 3. Artifacts: where AI was used

| Artifact | Section | AI used? | Entry |
|---|---|---|---|
| Value Proposition Canvas | 3.1 | Yes, visual layout only | AI-05 |
| UX Personas | 3.2 | Yes, visual layout only | AI-05 |
| Benchmark (screenshots, texts and matrix) | 3.3 | Yes, visual layout only. Screenshots and observations are the team's own | AI-05 |
| Customer Journey Map | 4.2 | Yes, visual layout only | AI-05 |
| Navigation flow diagram | 5.1 | No, the team's own work | |
| Paper sketch (`assets/low-fi-paper-sketch-1.jpg`) | 6.1 | No, drawn by Nelson Sandoval. Its description in the README was drafted with the AI | AI-08 (text only) |
| Low-fi wireframes (20 screens) | 6.1 | No, the team's own work. The generic kit from AI-01 was not used | AI-01 (not used) |
| **Hi-fi wireframes (20 screens)** | 7.1 | **Yes**, iteration of the HD interfaces; placeholder replacement and re-export | AI-06, AI-08 |
| Interface evolution sheet (image and PDF page) | 7.2 | No, the team's own work | |
| Interface evolution text in the README | 7.2 | Yes, English text drafted with the AI | AI-04 |
| `docs/screen-names.md` | 5.1 | No, the team's own work | |
| README and this log | 1 to 9 | Yes | AI-02 to AI-04, AI-07, AI-08 |

---

## 4. Decision trace for the high-fidelity artifacts

**What the AI contributed (AI-06):** layout and hierarchy proposals, proposals for visual style and components, and a review against heuristics and accessibility.

**What the team did with it (AI-06):** it asked for several versions and chose among them, and it accepted proposals with its own adjustments.

**Criteria behind the decisions.** The decisions below can be checked against four things that are documented in this repository:

1. **The password rule:** the older adult always types her own passwords (README, sections 1.2 and 7.1).
2. **The benchmark:** each change cites a problem found in Espacio Mayor, App Mayor or ChileAtiende, or a pattern that works there (README 3.3 and the [interface evolution sheet](../assets/interface-evolution-es.png)).
3. **The personas:** a low digital level (Celia), an intermediate one (Roberto) and a coordinator on a desktop (Andrés) (README 3.2).
4. **The scope:** one main flow and two secondary flows (README [4.1](../README.md#41-scope-definition)).

**Decisions, by group of screens.** They are the ones recorded in the team's own [interface evolution sheet](../assets/interface-evolution-es.png); this log does not attribute each one to the AI or to the team separately:

| Screens | What we kept | What we changed or rejected | Why (our judgment) | How we checked it |
|---|---|---|---|---|
| **Older adult, A1 to A8m** | Large shortcuts with icon and label, text-size control (A– / A+), a three-step request with a summary before sending, the reassurance about passwords on every sensitive screen | Removed the "Continue" button on step 1 (one tap advances); pre-filled the place with the person's club and a "Change" option; reduced declining a proposal to a sheet with two actions and **removed the reasons form**; added a notice before leaving for the official site | Fewer decisions and taps for a person with low digital skill (8 decisions down to 6); avoid leaving for an external site without warning, a problem we found in Espacio Mayor; clear actions with a visible "Close", as App Mayor does | Compared each screen with the annotated benchmark screenshots and Nielsen's heuristics. Decisions and taps counted by the team on the v1 and v2 screens. Walked through the Figma prototype. **Not tested with users** |
| **Volunteer, B1 to C2** | Requests from the network, one-tap outcome, three-tab bottom bar | The volunteer chooses among options **filtered by the older adult's availability**, instead of three lists (7 taps down to 4); the note on the result became **optional**; the volunteer no longer searches for or opens the official site: the older adult opens it herself | ChileAtiende only offers available days and hours, which prevents errors; keeping the password rule means the older adult must be the one who opens the site and types her own passwords | As above, plus a check of the navigation flow so that every tap has a matching link in the Figma prototype |
| **Older adult after the meeting, C3 to C4** | Confirmation by the older adult and the list of errands with status | Added "Ask again" on resolved errands, which repeats the errand without choosing it again | Espacio Mayor's favorites let people return quickly to what matters; errands are not daily, so repeating one should be easy | Compared with the benchmark; not tested with users |
| **Coordinator, D1 to D2** | Dashboard sorted by waiting time and a case history that records who, what and when, never passwords or health data | Added visible opening hours and an **alert for requests without a companion for more than 3 days**; shorter menus (no "Reports") | App Mayor's closed service with no notice is a problem; Andrés needs to see who is waiting today (persona need) | Compared with the persona's quote and the benchmark; not tested with users |
| **Component sheet and visual style** | Bottom bar with icon and label, large cards, step indicator | **One** accent color (orange), used only for the main action and the active item; everything else neutral | Color must mean the same thing on every screen; App Mayor uses the same red for unrelated actions (consistency and standards) | Compared with the benchmark and reviewed visually by the Designer. **Still to validate with real users:** whether orange stands out for low vision, whether A– / A+ is understood without explanation, and whether the older adult recognizes the official sites by name |

**What is still open.** None of the figures above has been tested with users (see README 7.2).
