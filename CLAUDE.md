# CLAUDE.md

Guidance for Claude Code (or any AI assistant) working in this repository.

## Project Overview

Environment and AI toolchain is a Next.js + Node.js web app. AI-assisted development is the core skill of this track, and it starts with a working toolchain.

## Tech Stack

- **Language:** TypeScript (preferred) / JavaScript
- **Frontend:** React 18+, Next.js (App Router)
- **Backend:** Node.js, Next.js API routes
- **Styling:** Tailwind CSS
- **Database:** [fill in once decided]
- **Package manager:** npm

## Commands

npm run dev       # start dev server
npm run build     # production build
npm run lint      # run linter

## Code Conventions

- Use functional React components with hooks; no class components.
- Prefer named exports over default exports, except for Next.js page/layout files.
- Keep components small and single-purpose.
- Use async/await over raw Promise chains.
- Environment variables go in `.env.local` (never committed).

## Git Conventions

- Commit messages follow Conventional Commits: `type(scope): short description`
- Types: feat, fix, docs, style, refactor, test, chore
- One logical change per commit.

## What Claude Should Do

- Follow the conventions above without being asked each time.
- When editing README or docs, keep tone concise.
- Ask before introducing a new dependency or major architectural change.

## What Claude Should Avoid

- Don't commit `.env` files or secrets.
- Don't reformat unrelated code in the same commit as a feature/fix.