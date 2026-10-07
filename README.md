# Piazza Clone

An early-stage clone of the Piazza Q&A forum, built with Next.js and TypeScript.

> **Status:** scaffold only. The root route redirects to a `/QandA` page, which has a placeholder navigation component. More of the forum UI is still to be built.

## Tech stack

- Next.js 15 (App Router, Turbopack)
- React 19 + TypeScript
- Tailwind CSS 4 (PostCSS setup)
- ESLint

## Getting started

```bash
npm install
npm run dev      # http://localhost:3000 (redirects to /QandA)
npm run build
npm start
npm run lint
```

## Project structure

```
app/
  layout.tsx
  (piazza)/
    page.tsx              # Redirects to /QandA
    QandA/
      page.tsx            # Q&A page
      navigation.tsx      # Navigation component (placeholder)
```
