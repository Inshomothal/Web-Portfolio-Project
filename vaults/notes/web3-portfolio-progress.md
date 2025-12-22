---
id: wlf6dlqnzb5bb4lequjr4ez
title: Web3 Portfolio Progress
desc: ''
updated: 1766398289611
created: 1766396922333
---

## Current Focus

- Stand up a polished Jekyll-based portfolio under `docs/` that can host Web2 + Web3 case studies and link to live demos.
- Keep deployment manual via GitHub Pages until the content stabilizes, then layer in GitHub Actions for CI/tests.
- Track learning outcomes while iterating so the site doubles as a living résumé.

## Progress Snapshot *(2025-12-22)*

| Area | Status | Notes |
| --- | --- | --- |
| Repo + tooling | ✅ | `docs/` scaffolded with Jekyll `minima`; local `bundle exec jekyll serve` works when run without `--detach` (Windows limitation). |
| Deployment | ⚠️ | GitHub Pages not yet picking up `/docs`; need to set Pages source and configure `url`/`baseurl`. |
| Content | 🚧 | Default “Welcome to Jekyll” post only; home page still empty. Need hero, about, and project tiles. |
| Documentation | 🚧 | `steps-to-deploy.md` exists but progress checklist still mostly unchecked; no README guidance for `docs/` workflow yet. |

## Portfolio Build To‑Do

### Foundation & Deployment

- [x] Update `docs/_config.yml` with `url: "https://inshomothal.github.io"` and `baseurl: "/Web-Portfolio-Project"` so links resolve under the project path.
- [x] Switch `docs/Gemfile` to `gem "github-pages", group: :jekyll_plugins` for parity with GitHub’s build environment; re-run `bundle install`.
- [x] In repo settings, set Pages source → `main` branch / `docs` folder; confirm successful build in Pages deployment logs.
- [x] Document the local workflow in `readme.md` (run commands from `docs/`, Windows caveats around `--detach`).
- [ ] Add optional GitHub Actions workflow after core content is stable (lint, tests, `jekyll build`, deploy artifact).

### Content & UX (Web2/Web3 Friendly)

- [ ] Craft a landing hero: name, concise mission statement, CTA buttons (Download CV, View Projects, Contact).
- [ ] Create an “About Me” section summarizing CS degree progress, teaching focus, and Web3/Web2 aspirations.
- [ ] Build a featured projects grid highlighting at least 3 efforts (e.g., NFT marketplace, full-stack CRUD app, AI-assisted tool) with tech stacks and links.
- [ ] Stand up a “Projects” collection (`_projects/`) with detailed case-study pages per project (problem, solution, role, stack, lessons).
- [ ] Add a blog/updates section fed by `_posts/` for learning logs, audits, or tutorials.
- [ ] Include testimonials or metrics (hackathon wins, course milestones) once available.

### Visual Design & Accessibility

- [ ] Customize `minima` via SCSS overrides to introduce a distinct color palette + typography pairing suitable for Web3/tech aesthetics.
- [ ] Ensure responsive layout: test hero, cards, and navigation on mobile, tablet, desktop.
- [ ] Provide light/dark mode toggle only if necessary; prioritize contrast and readability first.
- [ ] Optimize assets (SVG logos, compressed screenshots) and add descriptive alt text.

## Roadmap Toward Flagship Projects

- **2025 Q4:** Ship baseline portfolio + classic Web2 CRUD project write-up; start NFT marketplace case study.
- **2026 Q1–Q2:** Add decentralized identity/auth demo and document tooling; publish smart-contract testing notes.
- **2026 Q3:** Launch AI-augmented DeFi dashboard prototype; write accompanying blog post.
- **2027:** Layer in smart-contract security tool, cross-chain work, and GitHub Actions CI to showcase professional workflows.

## Checklist: Hallmarks of a Strong Web2/Web3 Portfolio

- [ ] Clear hero statement with mission + CTA.
- [ ] Concise bio explaining your stack (React/Next.js, Solidity, AI tooling) and what problems you solve.
- [ ] Highlighted metrics/outcomes (e.g., “Deployed NFT marketplace on Goerli; 100 test mints”).
- [ ] Featured projects with consistent cards: problem → solution → role → stack → links.
- [ ] Deep-dive case studies for flagship Web3 builds (architecture diagrams, contracts, audits, lessons learned).
- [ ] Classic Web2 project(s) proving CRUD/auth/data skills for traditional roles.
- [ ] Blog or lab notes sharing research (smart contract security, AI-assisted dev workflows).
- [ ] Contact and downloadables (email, LinkedIn, résumé PDF, Calendly link if mentoring/consulting).
- [ ] Social proof (GitHub stats, open-source contributions, testimonials, certifications once earned).
- [ ] Accessibility + performance considerations (lighthouse scores, alt text, keyboard navigation).

---

*Use this page as the running ledger: check tasks off as you complete them, log blockers (e.g., GitHub Pages config), and align upcoming work with the 2025–2028 project roadmap.*
