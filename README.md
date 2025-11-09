# FlippyCards — Minimal Memory Game

Live Demo: https://flippycards.vercel.app

FlippyCards is a clean, modern memory matching game built with React and Tailwind.
It emphasizes elegant UI, component-driven architecture, and well-structured game logic.

## Features

- Minimal, soft UI design
- Difficulty modes (Easy / Medium / Hard)
- Real-time timer & move tracking
- Subtle card flip animation
- Game summary modal
- Responsive layout & mobile-friendly

## Tech Stack

- React (Hooks + Context API)
- Tailwind CSS
- Vercel Deployment

## Architecture Highlights

- Game state stored in Context for clean component communication
- Custom hook `useGameLogic` encapsulates match/timer core logic
- Card data normalized to avoid excessive re-renders

## Future Enhancements

- Global leaderboard using Supabase/Firebase
- User accounts + progress history
