# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

@AGENTS.md

## Project overview

Study Buddy Finder helps UCL students find someone to study with. See `SPEC.md` for the pages (Home, Browse buddies, My profile) and features (browse student cards, filter by course, edit my profile).

This is a fresh Next.js app created with `create-next-app` (default options): App Router, TypeScript, Tailwind CSS and ESLint. There is no backend, database or login yet.

## Commands

- `npm run dev`: start the dev server at http://localhost:3000
- `npm run build`: production build (also type-checks)
- `npm run start`: serve the production build
- `npm run lint`: run ESLint

## Folder structure

- `app/page.tsx`: the home page (`/`)
- `app/layout.tsx`: the root layout that wraps every page (fonts, `<html>` and `<body>`)
- `app/globals.css`: global styles and the Tailwind import
- `public/`: static files such as images and icons
- `SPEC.md`: what the app should do
- `AGENTS.md`: Next.js notes for coding agents (written by `next dev`)

A new page goes in its own folder with a `page.tsx`, for example `app/browse/page.tsx` becomes `/browse`.
