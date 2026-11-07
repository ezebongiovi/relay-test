# Crew — public website

The public web page for Crew, built with [Next.js](https://nextjs.org) (App Router), TypeScript and Tailwind CSS.

## Requirements

- Node.js 22 (see `.nvmrc`; Next.js needs 20.9 or newer)
- npm

## Getting started

```bash
npm install
npm run dev
```

Then open http://localhost:3000.

## Scripts

| Script              | What it does                          |
| ------------------- | ------------------------------------- |
| `npm run dev`       | Start the dev server                  |
| `npm run build`     | Production build                      |
| `npm run start`     | Serve the production build            |
| `npm run lint`      | ESLint (Next.js core-web-vitals + TS) |
| `npm run typecheck` | Generate route types, then `tsc`      |

CI (`.github/workflows/ci.yml`) runs lint, typecheck and build on every pull request.

## Layout

```
src/app/        routes, layout and global styles
public/         static assets
```
