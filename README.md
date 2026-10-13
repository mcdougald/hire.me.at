<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/hero-dark.png">
    <img src=".github/assets/hero.png" alt="hire.me.at landing page" width="880">
  </picture>
</p>

# hire.me.at

Stay hireable. Era after era.

Hire is career ops for one job seeker. Most people rebuild their job search from nothing every few years; hire keeps it: the pipeline, the resume history, the answers, the stories, the contacts, and the evidence about what actually worked. It assists and never auto-applies: a human presses every apply button. Everything in your workspace is private to your account, and the whole thing is self-hostable.

## Features

- **Application pipeline**: a kanban tracker with an activity timeline, interview scheduling and debriefs.
- **Resume studio**: sections, layouts and templates, with restorable version history and PDF, JSON and JSON Resume export.
- **Import your existing resume**: PDF and DOCX import with accept-or-skip cards for each parsed section.
- **API-only job discovery**: Greenhouse, Ashby, Lever and Adzuna read by API, with a review funnel, per-source health and saved searches on a schedule.
- **Bounded AI copilot**: fit score, review, tailoring, interview prep, and cover letter and outreach drafts, using your own AI key, encrypted at rest.
- **What you already worked out**: a contact book, a question bank and a STAR-R story bank that carry over to the next search.
- **One-file takeout**: export everything you own in one file, any time.
- **Self-hostable**: run the core on your own infrastructure with Docker Compose; a Pro license key unlocks the full surface.

## Screenshots

<table>
  <tr>
    <td width="50%"><img src=".github/assets/pricing.png" alt="Pricing"><br><sub>Pricing: a free self-hosted core and a key-based Pro tier.</sub></td>
  </tr>
</table>

## Built with

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

See [LICENSE](LICENSE).
