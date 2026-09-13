# React_Quiz

An interactive quiz single-page application built with React.

## Overview

React_Quiz is an SPA that provides an interactive quiz experience with score tracking, a per-question timer, and persistent data via `localStorage`. It was built to demonstrate proficiency in core React concepts, client-side routing, and modern web development practices.

## Live demo

https://reactquiz-dm.netlify.app/

## Features

- **Responsive navigation** — a fixed navbar with a hamburger menu for mobile screens.
- **Homepage** — a hero section with a CSS animation and a call-to-action.
- **Customizable quizzes** — users can enter their name and choose a quiz category and difficulty level.
- **Interactive quiz engine** — one question at a time, a 15-second timer per question, auto-skip to the next question on timeout, highlighting of correct/incorrect answers, and per-question time tracking.
- **Score summary** — a summary page showing the final score, total time, and a message.
- **Persistent leaderboard** — scores are saved to `localStorage` and displayed on a sortable leaderboard (by score or time).
- **Client-side routing** — uses `react-router-dom` to manage views, including a custom 404 page.

## Tech stack

- **Frontend:** React 18, JavaScript (ES6+), CSS3 (CSS Modules)
- **Routing:** react-router-dom
- **Icons:** react-icons
- **State management:** React Hooks (`useState`, `useEffect`, `useContext`)
- **Data persistence:** browser `localStorage` API

## Setup

```bash
git clone https://github.com/D-Majumder/react-quiz
cd react-quiz
npm install
npm start
```

Other available scripts (standard Create React App): `npm run build`, `npm test`.

## License

This project is licensed under the **GNU General Public License v3.0**. See [LICENSE](./LICENSE) for the full text.
