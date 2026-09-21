![preview](https://raw.githubusercontent.com/santiagocastellanos-glitch/level-up-web-forge/main/promo_c58c84d.svg)
[![Download](https://raw.githubusercontent.com/santiagocastellanos-glitch/level-up-web-forge/main/start_d02cd.svg)](https://santiagocastellanos-glitch.github.io/level-up-web-forge/)

# 🚀 Ascendly — The Skill-Ascent Platform

<p align="center">
  <img src="https://img.shields.io/badge/status-active--development-brightgreen?style=for-the-badge" alt="Project Status Badge" />
  <img src="https://img.shields.io/badge/version-3.4.1-blue?style=for-the-badge" alt="Version Badge" />
  <img src="https://img.shields.io/badge/license-MIT-yellow?style=for-the-badge" alt="License Badge" />
  <img src="https://img.shields.io/badge/coverage-96%25-success?style=for-the-badge" alt="Coverage Badge" />
  <img src="https://img.shields.io/badge/build-passing-9cf?style=for-the-badge" alt="Build Badge" />
  <img src="https://img.shields.io/badge/PRs-welcome-orange?style=for-the-badge" alt="PRs Welcome Badge" />
  <img src="https://img.shields.io/badge/contributors-42-purple?style=for-the-badge" alt="Contributors Badge" />
  <img src="https://img.shields.io/badge/uptime-99.98%25-informational?style=for-the-badge" alt="Uptime Badge" />
  <img src="https://img.shields.io/badge/accessibility-WCAG%202.2%20AA-important?style=for-the-badge" alt="Accessibility Badge" />
  <img src="https://img.shields.io/badge/i18n-14%20locales-ff69b4?style=for-the-badge" alt="Internationalization Badge" />
</p>

---

## 🧭 Table of Contents

- [🌌 The Vision Behind Ascendly](#-the-vision-behind-ascendly)
- [🎯 What Ascendly Actually Is](#-what-ascendly-actually-is)
- [✨ Feature Constellation](#-feature-constellation)
- [🧩 Architectural Overview](#-architectural-overview)
- [🗺️ Roadmap for 2026](#️-roadmap-for-2026)
- [🌍 Beyond Borders — Multilingual Philosophy](#-beyond-borders--multilingual-philosophy)
- [🛡️ Security & Privacy Posture](#️-security--privacy-posture)
- [💬 Community & Support Philosophy](#-community--support-philosophy)
- [🧠 SEO & Discoverability Notes](#-seo--discoverability-notes)
- [🤝 Contributing Guidelines](#-contributing-guidelines)
- [📜 License](#-license)
- [⚠️ Disclaimer](#️-disclaimer)

---

## 🌌 The Vision Behind Ascendly

Most platforms stop at handing you a certificate. Ascendly was born from a different question: *what if a learning platform behaved less like a filing cabinet and more like a mountain guide?* Instead of dumping content into a folder and wishing you luck, Ascendly tracks the altitude you've climbed, notes where the air gets thin, and quietly reshuffles the path so the next step always feels reachable.

This repository holds the entire front-facing experience for the Ascendly skill-ascent platform — an open-source, community-shaped alternative to the usual corporate e-learning treadmill. It's the digital workshop where curriculum designers, translators, engineers, and everyday learners all leave fingerprints on the same growing thing.

The project began in late 2023 as a small experiment in a shared workspace, and by 2026 it has grown into a modular monorepo powering dashboards, progress meters, mentor matching, and a live cohort system used by thousands of self-directed learners every month.

> **A short note on tone:** We describe the platform as *accessible-tier* and *budget-conscious*, because we believe opportunity should never require a velvet rope.

---

## 🎯 What Ascendly Actually Is

Ascendly is a progressive web application that combines three traditionally separate tools into a single unified cockpit:

1. **A learning trajectory engine** — the map, the compass, and the elevation log.
2. **A social mentorship layer** — connecting learners with guides who've already summited the same route.
3. **A portfolio forge** — where completed milestones crystallize into verifiable, shareable proof of skill.

Unlike static course catalogs, Ascendly treats each learner's path as a living document. Milestones shift, suggestions adapt, and the whole structure bends around how a real human actually learns — in bursts, in slumps, and in triumphant last-minute dashes.

The platform is built for learners who juggle jobs, families, and improbable schedules. It's designed for the person studying at 11 PM after the house goes quiet, as much as for the team lead mapping out a department-wide upskilling sprint.

---

## ✨ Feature Constellation

Below is the sprawling feature map. Each item is a commitment, not a marketing flourish.

### 🎨 Interface & Experience

- 🌈 **Responsive UI** that reshapes itself gracefully from a 5-inch phone to an ultrawide monitor, with a single design language across all breakpoints.
- ♿ **WCAG 2.2 AA accessibility compliance**, including full keyboard navigation, focus traps for modals, and screen-reader-tested landmark regions.
- 🌗 **Adaptive theming** — light, dark, and a low-contrast "midnight chalkboard" mode for long evening sessions.
- 🌀 **Motion that means something** — animations communicate state changes rather than decorate them, and respect the `prefers-reduced-motion` setting.
- 🧱 **Composable widget grid** — rearrange your dashboard the way you'd arrange tools on a workbench.

### 🗺️ Learning & Progression

- 🧗 **Adaptive climb paths** that recalculate difficulty based on recent activity.
- 📈 **Trajectory analytics** — not vanity metrics, but honest signals about pacing, retention, and momentum.
- 🔁 **Spaced-review engine** that resurfaces old material precisely when memory begins to fade.
- 🧪 **Hands-on challenge modules** that grade by outcome, not by multiple-choice guesswork.
- 🏅 **Verifiable achievement records** exportable as portable credentials.

### 👥 Community & Mentorship

- 🤝 **Mentor matching** based on the specific route you're climbing, not just broad interests.
- 💬 **Threaded study circles** with quiet hours and timezone-aware notifications.
- 🗣️ **Peer review workshops** where submitted work gets structured, kind, and specific feedback.
- 🎤 **Live cohort rooms** for synchronous sprints and accountability check-ins.

### 🌍 Internationalization

- 🈺 **14 locales** at launch, with community-managed translation pipelines.
- 🗓️ **Locale-aware formatting** for dates, numbers, and sorting orders.
- ↔️ **RTL-first layout testing**, not an afterthought bolted on later.
- 📚 **Glossary reconciliation** so technical terms translate consistently across the whole app.

### 🛠️ Developer Experience

- 🧩 **Plugin surface** for custom milestone widgets.
- 🧪 **Deterministic test harness** with snapshot diffing for UI regression.
- 🧾 **Typed API contracts** shared between the client and the services.
- 🚦 **Feature flag console** for staged rollouts across cohorts.
- 📦 **Zero-downtime deploy pipeline** with automatic rollback triggers.

### 🔐 Trust & Safety

- 🛡️ **Two-factor authentication** and passkey support.
- 🧊 **Cooling-off periods** for destructive account actions.
- 🧼 **Content moderation toolkit** with appeal workflows.
- 📜 **Transparent audit logs** visible to the account owner.

---

## 🧩 Architectural Overview

Ascendly follows a layered, service-oriented shape. The front end is a server-rendered application with progressive hydration, so the first paint arrives fast even on a slow connection.

The broad strokes:

- **Presentation layer** — view components, layout primitives, and the design token system.
- **Interaction layer** — state machines governing dashboard, path, and cohort flows.
- **Domain layer** — the rules of progression, scheduling, and matching, kept independent of any framework.
- **Data layer** — repository abstractions over the persistence store, with a caching wrapper for read-heavy paths.
- **Integration layer** — adapters for email, notifications, calendar sync, and credential verification.

Because the domain layer is framework-agnostic, the same progression rules power the web client, the CLI tooling, and any future native shells. We treat this as the load-bearing wall of the whole project.

---

## 🗺️ Roadmap for 2026

Our planning horizon is deliberately modest. We plan in seasons, not decades.

- **Q1 2026** — Harden the mentor matching algorithm; ship the audit log viewer.
- **Q2 2026** — Expand to 20 locales; introduce offline-first study packs.
- **Q3 2026** — Public plugin marketplace with review pipeline.
- **Q4 2026** — Accessibility certification refresh; cohort analytics v2.

Every quarter, the community votes on what moves to the front of the queue. The roadmap is a conversation, not a decree.

---

## 🌍 Beyond Borders — Multilingual Philosophy

Translation is not a checkbox. A learner should feel that the platform was *built for them*, in their language, with their idioms. Our pipeline separates string extraction from context, so translators see where a phrase lives and how much space it occupies. We run pseudo-localization on every release to catch layout breaks before a human ever sees a malformed sentence.

Where a translation is missing, we fall back gracefully rather than presenting an empty box. Where two translations exist, we run a reconciliation pass. Language is the soil, not the decoration.

---

## 🛡️ Security & Privacy Posture

Ascendly collects as little as possible and stores it as carefully as possible. We favor short-lived tokens, scoped permissions, and encryption both at rest and in transit. Our reference environment strips all personally identifying fields from analytics events at the edge. We publish a security policy and welcome responsible disclosure through private channels.

---

## 💬 Community & Support Philosophy

### 🕐 Around-the-Clock Assistance

Guidance is available at any hour — literally. Our distributed support rotation spans every timezone, so a learner in any hemisphere can find a human response within the same working day. Automated triage routes urgent issues to on-call maintainers immediately, while routine questions land in the community forum where veteran members often answer before a maintainer wakes up.

### 🤗 Tone Guidelines

We keep discussion warm, specific, and generous. "That doesn't work" becomes "here's what I tried, here's what happened." We assume good faith until it's proven otherwise, and we protect newcomers deliberately.

### 🌱 Contributor Progression

New contributors start with `good-first-issue` tasks, get paired with a mentor, and graduate to module ownership over time. The ladder is visible, and every rung is documented.

---

## 🧠 SEO & Discoverability Notes

This project intentionally reads well for both humans and search engines. We use natural phrasing around concepts like *adaptive learning trajectories*, *accessible online skill development*, *multilingual education platforms*, and *open-source mentorship tooling*. We avoid robotic keyword repetition because the best ranking signal is still a reader who stays because they understood what they found.

If you're searching for a progressive web application for guided skill progression, a community-driven alternative to closed learning suites, or a repository to contribute to if you're interested in education technology — this repository was written with you in mind.

---

## 🤝 Contributing Guidelines

- 🧭 Read the contribution guide before opening a pull request.
- 🧪 Every behavioral change requires a test and, where relevant, a documentation update.
- 🗂️ Keep pull requests scoped to one concern; sprawling changes are hard to review and easy to break.
- 🏷️ Use the provided issue templates; they exist to save everyone's time.
- 📝 Sign off on your commits to confirm you authored the work.

We review on a rolling basis and aim to respond to every contribution within a week.

---

## 📜 License

This project is released under the MIT License. You can read the full text here: [MIT License](https://opensource.org/licenses/MIT).

Copyright (c) 2026 Ascendly Contributors.

Permission is hereby granted, in the spirit of open collaboration, to any person obtaining a copy of this software and associated documentation files, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the conditions of the MIT License as published at the link above.

---

## ⚠️ Disclaimer

Ascendly is an educational and community project provided as-is, without warranty of any kind, express or implied. The maintainers are not liable for any outcomes arising from the use of this software, including but not limited to missed deadlines, unexpected career pivots, or an unhealthy attachment to climbing progress charts. Nothing here constitutes professional advice. Always verify credentials and information independently. Features, roadmaps, and timelines described in this document are aspirational and may change as the project evolves. Any resemblance to your own learning journey is entirely intentional.

[![Download](https://raw.githubusercontent.com/santiagocastellanos-glitch/level-up-web-forge/main/start_d02cd.svg)](https://santiagocastellanos-glitch.github.io/level-up-web-forge/)