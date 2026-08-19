# keep-asking-site

Public landing and companion site for **Keep Asking** — a Curtin University
learning & teaching research project testing whether a one-line conversational
nudge shifts how students engage with AI (toward follow-up, challenge, and
extension rather than one-shot delegation). HREC 83897; NBF L&T grant 2026.

Live at **<https://keep-asking.locolabo.org>** — part of the
[LocoLabo](https://locolabo.org) family.

This repo holds only the public website. The study itself (protocol, manuscript,
instruments, data) lives in a private research repository; the chat platform is
open source at [`keep-asking-app`](https://github.com/michael-borck/keep-asking-app).

## Stack

Astro, deployed to GitHub Pages by `.github/workflows/deploy-pages.yml` on push
to `main`. Custom domain via `public/CNAME`; DNS on Cloudflare.

```
npm install
npm run dev       # local preview
npm run build     # production build to dist/
```

## Editorial policy

Until the associated papers clear peer review, the site deliberately omits the
manuscript title, the OSF registration link, and any link to the live study
platform. Talk slides are added under `public/talks/` as they are cleared.
