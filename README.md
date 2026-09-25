# Interactive Quiz Platform

A React single-page app for generating, creating and playing quizzes. Built as a team project for a web development course at Braude College of Engineering.

## Features

- Generate a quiz automatically from The Trivia API, filtered by category and length
- Build a custom quiz manually, question by question
- Play a quiz by entering its ID, with scoring and an end-of-quiz summary
- Light and dark theme

## Tech stack

React 18, React Router, Vite, Tailwind CSS, axios.

Questions are fetched from [The Trivia API](https://the-trivia-api.com). There is no backend: each quiz is saved to the browser's localStorage under a generated UUID, which doubles as the quiz ID.

## Running locally

```bash
cd HW3
npm install
npm run dev
```

## Limitations

Quizzes live in localStorage, so a quiz ID only opens in the browser that created it. Moving persistence to a small backend is the natural next step for this project.

## Credits

Coursework project by group 16. Imported from [OfirBraude/HW3_G16](https://github.com/OfirBraude/HW3_G16).
