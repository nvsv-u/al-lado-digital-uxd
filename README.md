# To the Digital Side (Al Lado Digital)
User Experience Design for *To the Digital Side* (*Al Lado Digital* in Spanish)

## Index

- [1. Introduction](#1-introduction)
  - [1.1. The Problem](#11-the-problem)
  - [1.2. Our Solution](#12-our-solution)
- [2. Team & Roles](#2-team--roles)
- [3. Strategy](#3-strategy)
  - [3.1. Value Proposition Canvas](#31-value-proposition-canvas)
  - [3.2. UX Personas](#32-ux-personas)
  - [3.3. Benchmarking](#33-benchmarking)
- [4. Scope](#4-scope)
  - [4.1. Customer Journey Map](#41-customer-journey-map)
- [5. Annex](#5-annex)

---

## 1. Introduction

### 1.1. **The Problem**

> I need to book a doctor's appointment online this week, and my family lives in another city.
> I don't want to give my passwords to a stranger.
> How will I know the errand was actually completed?

Many everyday errands have moved to online channels, and older adults depend on a relative being available to complete them. Peer facilitators and volunteers exist in senior citizens' clubs and municipalities, but coordination is informal and gets lost along the way.

The challenge is well-defined and verifiable: **match a specific need with someone who can help, schedule the meeting, and record whether the errand was resolved**, building trust without exposing the requester's sensitive data.

---

### 1.2. **Our Solution**

**To the Digital Side** (*Al Lado Digital*) is a platform that pairs older adults with trusted peer facilitators or volunteers to complete online errands together: in person, at an agreed time, with confirmation of the outcome, and **without sharing passwords with anyone**.

#### 🤝 **Matching and Scheduling**

- The older adult states the errand and when they are available
- Matching with a **verified** facilitator or volunteer
- Integrated scheduling: date, time and place of the meeting

#### 🔒 **Guided In-Person Assistance**

- The person types their own passwords; the volunteer only accompanies them
- Verified profiles within a limited, known support network

#### ✅ **Traceability**

- A log to verify and mark the **status of each errand**
- Peace of mind through clear, recorded confirmations

#### ♿ **Simple and Accessible Interface**

- Large text, short steps and no long forms

---

## 2. Team & Roles

Vicente Contreras - Project Manager

Nelson Sandoval - UX/UI Designer

Arturo Rivas - UX Researcher / Analyst

---

## 3. Strategy

### 3.1. Value Proposition Canvas

*How we aligned the needs of older adults with our solution*

**Customer segment:** older adults who need to complete errands online and do not always have someone available to help them.

**Identified gaps:**

- **Trust:** the risk of exposing sensitive data or passwords to a stranger.
- **Dependence:** constant reliance on relatives being available.
- **Coordination:** informal arrangements that get lost, causing missed appointments and postponed care.
- **Uncertainty:** not knowing whether the errand was actually completed.

**How the solution responds:**

- **Pain relievers:** passwords are never shared, volunteers have verified profiles, and the support network is limited and known.
- **Gain creators:** peace of mind through recorded confirmations, and the chance to complete the errand on their own with guided assistance.

![Value Proposition Canvas](./assets/value-proposition-canvas-en.png)

***

### 3.2. **UX Personas**

*Our personas represent the four key roles in the ecosystem: the older adult who requests help, two volunteers with different profiles, and the municipal coordinator. They are proto-personas based on team assumptions, to be validated through interviews.*

---

👥🔹 **Celia Márquez** — Requester, 74, retired  
*"My children live far away and I don't want to bother them every time I need to book an appointment. If someone from the club goes with me, I'll do it myself, but I'm not giving my passwords to just anyone."*

👥🔹 **Roberto Pérez** — Volunteer and club peer facilitator, 67, retired  
*"I learned to use the government portal on my own. If you give me a simple app without so many hoops, I'm happy to go with the other club members to get their things done."*

👥🔹 **Andrés Rivera** — Municipal coordinator, 40  
*"I can't rely on volunteers' good memory. I need to see on a screen how many seniors are waiting for help today and who is taking care of them."*

👥🔹 **Sofía Morales** — Volunteer and student, 24  
*"I have the whole Friday afternoon free to help, but in the WhatsApp group I get lost among so many messages and I don't know who needs which errand or what time to go."*

---

![UX Persona 1](./assets/ux-personas-1.png)

![UX Persona 2](./assets/ux-personas-2.png)

![UX Persona 3](./assets/ux-personas-3.png)

![UX Persona 4](./assets/ux-personas-4.png)

***

### 3.3. Benchmarking

To identify best practices and opportunities for improvement in the design of *To the Digital Side*, we analyzed three existing tools that cover the problem space: older adults completing everyday errands online.

#### Tools analyzed:

- 🎯 **Direct competitor and design reference:** *Espacio Mayor* (Fundación Conecta Mayor UC). A free app that brings procedures, certificates, benefits and public services for older adults into one place. It guides users to those services with simple language, step-by-step tutorials, large text and clear buttons.
- 🧩 **Complementary:** *App Mayor* (Fundación Conecta Mayor UC). An Android app that makes the smartphone easier for older adults, with large buttons, shortcuts to common apps and direct access to ChileAtiende (video call and phone).
- ⚖️ **Analogous:** *ChileAtiende*. The State's service portal, used here through its mobile website. It handles the same kinds of procedures, but for the general population.

All three were analyzed on **October 3, 2026**: Espacio Mayor v0.0.48, App Mayor v2.2.9 and the ChileAtiende mobile website.

#### How we analyzed them

The analysis follows the **four-action model** (Increase, Include, Reduce, Remove). For each tool, we recorded **"the good"** and **"the bad"**, each backed by an annotated screenshot and, for the problems, a usability heuristic.

- **Increase:** large buttons and text, cards with an image and a short description, and a step indicator when booking.
- **Include:** a bottom bar with labeled icons, a one-tap direct call, visible assisted alternatives, and **human support at the moment the user reaches the ClaveÚnica sign-in**, which is what our proposal adds.
- **Reduce:** small text, long paths to reach a service, truncated titles, and small web text inside an app.
- **Remove:** colors with no consistent meaning, leaving for an external site without warning, and discovering that a service is closed only after entering it.

> The tools we analyzed help older adults on their own, through simplified interfaces or through the State's service channels (video call, call center and branches). None of them offers guided help from a trusted peer who accompanies the person while they type their own passwords, and that is the gap *To the Digital Side* addresses.

![Benchmarking](./assets/benchmark-en.png)

📄 For the complete analysis with annotated screenshots, see the [benchmark document](docs/benchmark-en.pdf).

---

## 4. Scope

### 4.1. Customer Journey Map

We combined the persona **Celia Márquez** with the features of the project to map how she would experience the service, from hearing about it to asking for help again.

**Scenario:** book a doctor's appointment online this week, with help from a club volunteer and without handing over her passwords.

The map follows five stages:

- 🔍 **Awareness:** she hears about the service at her senior citizens' club.
- 🤔 **Consideration:** she checks that the people are verified and trustworthy.
- ✅ **Decision:** she creates her profile and states the errand she needs.
- 🤝 **Delivery & Use:** she meets her facilitator or volunteer, types her own passwords and completes the errand.
- 💬 **Loyalty & Advocacy:** she checks the status of the errand, asks for help again and tells her club peers.

For each stage, the map covers the customer's activities, goals, touchpoints, emotions, pains and the solutions in *To the Digital Side*, as well as the business goal, KPIs, organisational activities, responsible parties and technology systems behind it.

> The emotions and indicators are hypotheses based on proto-personas, to be validated with real users.

![Customer Journey Map](./assets/customer-journey-v3-en.png)

---

## 5. Annex

This section provides direct access to the documents delivered for each project phase.

### 3. Strategy Documents
- 📄 **[Value Proposition Canvas](docs/value-proposition-canvas--en.pdf)**  
 Pains, gains and jobs of our customer segment, and how our value proposition responds to them
- 📄 **[UX Personas](docs/ux-personas-en.pdf)**  
 Complete personas with profiles, frustrations, goals, interests and quotes
- 📄 **[Benchmark](docs/benchmark-en.pdf)**  
 Analysis of Espacio Mayor, App Mayor and ChileAtiende, with annotated screenshots and a four-action matrix

### 4. Scope Documents
- 📄 **[Customer Journey Map](docs/customer-journey-en.pdf)**  
 Journey of the persona Celia Márquez across five stages, with her pains and the solutions in *To the Digital Side*

---
