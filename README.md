# Client Portfolio — Next.js Starter

A TypeScript starter for a client portfolio using Next.js App Router, React, and Tailwind CSS. The current home page remains the generated Next.js starter screen, providing a foundation for future portfolio content.

**Stack:** Next.js 15 · React 19 · TypeScript · Tailwind CSS 4

## Highlights

- Next.js 15.5 App Router project structure.
- React 19.1 and TypeScript.
- Tailwind CSS 4 integration through PostCSS.
- Root layout with Geist and Geist Mono fonts.
- Development and production build scripts using Turbopack.

## Run locally

Install Node.js and npm, then:

```sh
git clone https://github.com/itzhoman/Client-portfolio.git
cd Client-portfolio
npm ci
npm run dev
```

Open http://localhost:3000. Font setup uses `next/font/google`; initial font fetching may require internet access.

## Development commands

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the development server |
| `npm run build` | Build the production app |
| `npm run start` | Serve the production Next.js build |
| `npm run lint` | Run the configured lint command |

Run `npm run build` before `npm run start`.

No automated test script is currently defined in `package.json`.

## Project structure

| Path | Responsibility |
| --- | --- |
| `app/page.tsx` | Current generated home page; starting point for portfolio sections |
| `app/layout.tsx` | Root document, metadata, and font configuration |
| `app/globals.css` | Global styles and Tailwind setup |
| `public/` | Starter images and icons |
| `next.config.ts` | Next.js configuration |
| `eslint.config.mjs` | ESLint configuration |

## Customize

- Replace `app/page.tsx` with your introduction, selected projects, and contact section.
- Update the title and description in `app/layout.tsx`.
- Replace starter assets in `public/` and add routes under `app/` as needed.

## Current scope

This repository is a starter rather than a completed client portfolio. Contact submission, project data, and additional portfolio routes are not implemented. The layout uses `next/font/google`, so font fetching may need network access during development/build.

## Repository

[Source on GitHub](https://github.com/itzhoman/Client-portfolio) · [Hooman Hajimohamadi](https://github.com/itzhoman)

Documentation reviewed against source commit [`e905554`](https://github.com/itzhoman/Client-portfolio/commit/e9055542b01c2a5770e0a7e280acc380367fdf73).
