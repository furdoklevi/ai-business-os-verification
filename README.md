# ai-business-os-verification

A minimal Next.js project for verifying the AI Business OS deployment
pipeline: a merged pull request is built and published by Netlify, and the
AI Business OS records the deploy. It is a test repository, not a client
website, and it holds no secrets.

- Next.js 15 (App Router), React 19, TypeScript; no other dependencies.
- `npm run build` builds the site; `npm run dev` and `npm run start` serve it.
- `npm run lint` runs the TypeScript type check (`tsc --noEmit`): the project
  has no ESLint, so the check needs no extra dependency.
