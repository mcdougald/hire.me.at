<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/hero-dark.png">
    <img src=".github/assets/hero.png" alt="hire.me.at landing page" width="880">
  </picture>
</p>

<h1 align="center">hire.me.at</h1>

<p align="center"><strong>Stay hireable. Era after era.</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/status-live-171717?style=flat-square" alt="Status: live">
  <img src="https://img.shields.io/badge/license-source--available-404040?style=flat-square" alt="License: source-available">
  <img src="https://img.shields.io/badge/self--host-supported-525252?style=flat-square" alt="Self-host: supported">
  <img src="https://img.shields.io/badge/part%20of-me.at-737373?style=flat-square" alt="Part of me.at">
</p>

<p align="center">
  <a href="https://hire.me.at">Website</a> ·
  <a href="#features">Features</a> ·
  <a href="#how-it-works">How it works</a> ·
  <a href="#screenshots">Screenshots</a> ·
  <a href="#built-with">Built with</a>
</p>

Most people rebuild their job search from nothing every few years. I built hire.me.at as career ops for one job seeker, and it keeps the search: the pipeline, the resume history, the answers, the stories, the contacts, and the evidence about what actually worked. It assists and never auto-applies, so a human presses every apply button. Everything in your workspace is private to your account, and the whole thing is self-hostable.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/overview-dark.svg">
    <img src=".github/assets/overview.svg" alt="hire.me.at at a glance: never auto-applies, your search kept, jobs found by API, yours end to end" width="880">
  </picture>
</p>

## Why hire.me.at

| The usual job search | hire.me.at |
| --- | --- |
| Rebuilt from nothing every few years | Pipeline, resumes, answers and stories carry over to the next search |
| Tools that apply on your behalf | It assists and drafts; you press every apply button |
| Listings scraped from job boards | API-only discovery with a review funnel and per-source health |
| Your history locked inside a tracker | One-file takeout any time, and self-hostable |

## Features

- **Application pipeline**: a kanban tracker with an activity timeline, interview scheduling and debriefs.
- **Resume studio**: sections, layouts and templates, with restorable version history and PDF, JSON and JSON Resume export.
- **Import your existing resume**: PDF and DOCX import with accept-or-skip cards for each parsed section.
- **API-only job discovery**: Greenhouse, Ashby, Lever and Adzuna read by API, with a review funnel, per-source health and saved searches on a schedule.
- **Bounded AI copilot**: fit score, review, tailoring, interview prep, and cover letter and outreach drafts, using your own AI key, encrypted at rest.
- **What you already worked out**: a contact book, a question bank and a STAR-R story bank that carry over to the next search.
- **One-file takeout**: export everything you own in one file, any time.
- **Self-hostable**: run the core on your own infrastructure with Docker Compose; a Pro license key unlocks the full surface.

## How it works

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/flow-dark.svg">
    <img src=".github/assets/flow.svg" alt="How hire.me.at works: import, discover, tailor, apply, keep" width="880">
  </picture>
</p>

You start by importing a PDF or DOCX resume, accepting or skipping each parsed section. Discovery reads job boards by API and sends new roles through a review funnel, and the copilot scores fit and drafts tailored material using your own AI key. You apply yourself, the pipeline tracks each application through interviews and debriefs, and your stories, answers and contacts stay in the workspace for the next search.

## Screenshots

<table>
  <tr>
    <td width="50%"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/hero-dark.png"><img src=".github/assets/hero.png" alt="Landing page"></picture><br><sub>The public home page, before you sign in to the console.</sub></td>
    <td width="50%"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/pricing-dark.png"><img src=".github/assets/pricing.png" alt="Pricing"></picture><br><sub>Pricing: a free self-hosted core and a key-based Pro tier.</sub></td>
  </tr>
</table>

## Built with

<p>
  <img src="https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js 16">
  <img src="https://img.shields.io/badge/React-19-171717?style=flat-square&logo=react&logoColor=white" alt="React 19">
  <img src="https://img.shields.io/badge/TypeScript-5-262626?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-4-404040?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS 4">
  <img src="https://img.shields.io/badge/Drizzle-Postgres-525252?style=flat-square&logo=drizzle&logoColor=white" alt="Drizzle ORM and Postgres">
  <img src="https://img.shields.io/badge/React%20PDF-export-737373?style=flat-square" alt="React PDF export">
  <img src="https://img.shields.io/badge/AI-bring%20your%20own%20key-737373?style=flat-square" alt="Bring-your-own-key AI">
</p>

- Next.js 16 (App Router), React 19, TypeScript
- Tailwind CSS 4
- oRPC for the typed API
- Drizzle ORM + Postgres
- Better Auth (the shared me.at account)
- React PDF, mammoth and unpdf for resume export and import
- Bring-your-own-key AI providers (OpenAI, Anthropic, Gemini, OpenRouter, Ollama)

## Part of the me.at family

hire.me.at is one of my [`*.me.at`](https://me.at) apps. They share one design system, account, and app shell. Development happens in a private monorepo; this repository is the project's public-facing home.

## License

Source-available. See [LICENSE](LICENSE).
