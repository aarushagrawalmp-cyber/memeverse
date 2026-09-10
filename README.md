# MemeVerse

A first-year React single-page application for discovering, voting on, saving, uploading, and creating memes.

## Run locally

1. Open this folder in VS Code.
2. In its terminal, run `npm install` once.
3. Run `npm run dev`.
4. Open the local address Vite prints (usually `http://localhost:5173`).

## What this demonstrates

- **HTML:** semantic layout inside React JSX.
- **CSS:** responsive grid, mobile breakpoints, animations, cards, and modal styling.
- **JavaScript:** array filtering, sorting, file previews, clipboard sharing, canvas image export, and browser storage.
- **React components:** `App`, `MemeCard`, and `MemeCreator` each own a clear part of the interface.
- **React Hooks:** `useState` controls the feed, search, filters, votes, saved items, upload preview, and creator; `useMemo` derives the visible list; `useEffect` persists saved memes and registers the keyboard shortcut.
- **SPA behavior:** all interactions update without page reloads.

## Features for the demo

- Trending/latest feed, live search, category filters, sample data
- Upvoting and locally persistent saved memes
- Image upload that adds an image card to the live feed
- Caption copier for sharing
- Canvas-powered meme download with editable top/bottom text and colour selection
- Leaderboard and fully responsive UI

## Important limitation

This MVP intentionally has no login, server, or database because those are outside the first-year requirements. Uploaded images, votes, and saved memes are client-side only; saved memes persist in `localStorage`.

