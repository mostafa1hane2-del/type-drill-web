![preview](https://raw.githubusercontent.com/mostafa1hane2-del/type-drill-web/main/promo_3e66ef.svg)
[![Download](https://raw.githubusercontent.com/mostafa1hane2-del/type-drill-web/main/fetch_4cb33a5.svg)](https://mostafa1hane2-del.github.io/type-drill-web/)

# 🧠 NeuroKeys — Adaptive Keyboard Mastery Environment

![Status: Active Development](https://img.shields.io/badge/status-active_development-brightgreen?style=flat-square)
![Platform: Web](https://img.shields.io/badge/platform-web-blue?style=flat-square)
![Language: TypeScript](https://img.shields.io/badge/language-TypeScript-3178C6?style=flat-square)
![License: MIT](https://img.shields.io/badge/license-MIT-yellow?style=flat-square)
![Build: Passing](https://img.shields.io/badge/build-passing-success?style=flat-square)
![Accessibility: WCAG 2.2 AA](https://img.shields.io/badge/accessibility-WCAG_2.2_AA-9cf?style=flat-square)
![Year: 2026](https://img.shields.io/badge/roadmap-2026-orange?style=flat-square)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-ff69b4?style=flat-square)

---

## 🚀 Overview

**NeuroKeys** is a keyboard mastery environment built for people who want their fingers to move faster than their thoughts — and then catch up. Where classic typing tools treat the keyboard like a treadmill, NeuroKeys treats it like a jazz instrument: it listens to how you play, where you hesitate, which keys betray you under pressure, and then it composes practice sessions around your personal rhythm.

This project started as an evolution of an earlier keyboard trainer concept and grew into something more ambitious: a multilingual, adaptive, browser-native typing gym that runs anywhere a modern web browser can breathe. No plugins. No obscure runtimes. Just a tab, a keyboard, and a steadily rising words-per-minute curve.

NeuroKeys was designed for the year 2026 and beyond — an era where remote work, live captioning, pair programming, and real-time collaboration reward anyone who can type with intention. Whether you are a developer hammering out function signatures, a student racing against a lecture transcript, or a hobbyist who wants to stop looking at their hands, the environment adapts to you.

---

## 🎯 Why This Exists

Most typing tools measure one number: speed. NeuroKeys measures the texture of your typing — burst velocity, recovery time after mistakes, finger travel economy, and consistency across language switches. Instead of dumping generic word lists on you, it builds a personal curriculum that evolves every single session.

Think of it as a coach who never grows bored of watching you type.

---

## ✨ Feature Highlights

- **Adaptive Drill Engine** — sessions reshape themselves based on your last performance, targeting the exact digraphs and n-grams where your fingers stumble.
- **Responsive Interface** — layout snaps gracefully from ultrawide monitors to tablet screens and compact mobile keyboards, preserving readability without cramping the canvas.
- **Multilingual Support** — practice sets available across a growing library of locales, with per-language layouts (QWERTY, AZERTY, QWERTZ, Dvorak, Colemak, and regional variants).
- **Live Metrics Overlay** — words per minute, accuracy heat, consistency index, and error clustering displayed in real time without distracting from the text stream.
- **Session Replay Timeline** — scrub backward through any completed practice run and watch where your cadence broke.
- **Focus Mode** — a distraction-shy canvas that dims everything except the next keystroke target.
- **Custom Text Sandbox** — paste your own prose, code snippets, or documentation drafts and train on material you actually care about.
- **Progress Vault** — local-first history storage keeps your streaks, personal records, and daily rhythm charts under your control.
- **Themed Environments** — light, dim, high-contrast, and a colorblind-safe palette tuned for extended sessions.
- **Keyboard Layout Sandbox** — prototype experimental layouts and compare performance against your current daily driver.
- **24/7 Customer Support Channel** — an always-open conduit for bug reports, feature ideas, and accessibility feedback, with documented response expectations.
- **Export & Share** — generate a snapshot of your progress to share with study groups or mentors.
- **Offline-Friendly Core** — the essential trainer keeps humming even when connectivity drops.

---

## 🧩 SEO-Friendly Integration Notes

NeuroKeys is engineered to be discoverable and useful for anyone searching for an **online keyboard trainer**, an **adaptive typing practice web app**, a **WPM improvement tool**, a **multilingual typing tutor**, or a **browser-based typing speed test**. The content, metadata, and route structure are built around natural language that real learners use when they describe their goals — improving accuracy, building muscle memory, learning alternate layouts, or training for professional transcription work. Rather than stuffing keywords into corners, we weave them into the actual user experience: headings, help text, and onboarding flows all speak the same vocabulary that new visitors search with.

---

## 🛠️ Tech Stack (At a Glance)

| Layer | Choice | Rationale |
|-------|--------|-----------|
| UI Framework | Component-driven TypeScript stack | Type safety across a fast-moving codebase |
| State | Lightweight reactive store | Predictable data flow for real-time metrics |
| Styling | Utility-first CSS with design tokens | Consistent theming and rapid iteration |
| Build | Modern bundler with route-level splitting | Fast cold start times |
| Storage | IndexedDB + local fallback | Privacy-first persistence |
| Testing | Unit, integration, and end-to-end suites | Confidence before every merge |
| Accessibility | WCAG 2.2 AA target | Typing practice should be open to everyone |

---

## 📦 Getting the Project Running Locally

NeuroKeys is intentionally approachable for contributors. The repository ships with a documented bootstrap path that avoids exotic tooling.

1. Ensure a current long-term-support runtime for the JavaScript ecosystem is available on your machine.
2. Bring the dependency graph into place using the package manager declared in the repository manifest.
3. Launch the development server target documented in the scripts section of the manifest.
4. Open the printed local address in your browser of choice — the app should greet you with the onboarding canvas.
5. Run the test suites before opening a pull request; the CI pipeline mirrors those exact commands.

For container enthusiasts, a declarative environment descriptor is included so the app can be brought up in an isolated sandbox without touching your host system.

---

## 🧪 Testing Philosophy

Every feature lands with coverage. The suite is organized into three rings:

- **Inner ring — unit tests:** pure functions, metric calculators, language tables, layout transforms.
- **Middle ring — integration tests:** session lifecycles, persistence round-trips, theme switching.
- **Outer ring — end-to-end tests:** realistic scenarios that simulate a learner completing a full drill.

Flaky tests are treated as bugs, not annoyances. If a test wavers, it gets fixed at the source.

---

## 🌍 Multilingual & Layout Coverage

NeuroKeys separates the *language* of the practice text from the *physical arrangement* of keys. That separation lets you train in, say, Spanish prose while sitting at a QWERTZ board — a combination that trips up many generic trainers.

Current coverage includes Romance, Germanic, Slavic, and Nordic language families, with community contributions steadily expanding the map. Layout support spans the classic ANSI/ISO families plus ergonomic alternates. Adding a new language or layout is a self-contained task documented in the contributor guide.

---

## ♿ Accessibility Commitments

- Full keyboard navigation for every control.
- Screen-reader-announced session events and metric updates.
- Color palettes verified against contrast guidelines.
- Reduced-motion mode that respects operating system preferences.
- Adjustable font scaling without layout breakage.

Accessibility issues are treated with the same urgency as crash reports.

---

## 🗺️ Roadmap Through 2026

The roadmap is public and updated as milestones close. Highlights on the horizon:

- **Q1 2026** — Expanded language packs and a formal plugin surface for custom drill generators.
- **Q2 2026** — Multiplayer practice rooms for study groups and classrooms.
- **Q3 2026** — Advanced analytics dashboard with longitudinal trend analysis.
- **Q4 2026** — Desktop companion sync for cross-device progress continuity.

Community votes shape priority order; the issue tracker is the primary steering wheel.

---

## 🤝 Contributing

Contributions are warmly welcomed — from one-line documentation fixes to whole new language packs. The repository maintains:

- A clear code of conduct.
- Issue templates for bug reports and feature requests.
- A pull request checklist that mirrors the CI pipeline.
- A contributor guide covering architecture, conventions, and review expectations.

If you are unsure where to start, look for issues tagged as good entry points. Small, well-scoped contributions land faster and help maintainers keep momentum.

---

## 💬 Community & Support Around the Clock

Questions, ideas, and gentle bug reports flow through the repository's discussion channels. Support is structured to be reachable at any hour — documentation is thorough, the FAQ section covers common setup snags, and maintainers triage incoming reports continuously so nothing rots in a forgotten corner.

---

## 🔐 Privacy Posture

NeuroKeys keeps your practice data local by default. There is no shadow telemetry selling your typing rhythm to anyone. When optional cloud sync arrives on the roadmap, it will be explicit, reversible, and documented in plain language.

---

## ⚠️ Disclaimer

NeuroKeys is provided as an educational and self-improvement tool. Results vary based on individual practice habits, hardware, and consistency. The project is not affiliated with any keyboard manufacturer, operating system vendor, or educational institution. Metrics shown in the application are estimates derived from client-side measurement and may differ slightly from other typing benchmarks. By using this software you acknowledge that you do so at your own discretion, and that the maintainers are not liable for any indirect outcomes of its use. Always take breaks, stretch your wrists, and listen to your body during extended practice sessions.

---

## 📄 License

This project is distributed under the **MIT License**. A working copy of the terms is available here:

[LICENSE](https://opensource.org/license/mit)

You are welcome to read, modify, and redistribute the project in accordance with those terms.

---

## 🧭 Final Note

NeuroKeys is more than a stopwatch for your fingers. It is a small instrument for building fluency, confidence, and calm at the keyboard. Whether you are chasing a personal record in 2026 or simply want to stop hunting for the semicolon, this environment was built with you in mind. Pull up a chair, warm up your hands, and let the drills do the rest.

[![Download](https://raw.githubusercontent.com/mostafa1hane2-del/type-drill-web/main/fetch_4cb33a5.svg)](https://mostafa1hane2-del.github.io/type-drill-web/)