# Neon Snake

A polished, dependency-free Snake game built with a single HTML file. It uses a dark, responsive interface with a subtle grid, neon gameplay elements, score tracking, and an accelerating difficulty curve.

## Features

- Touch controls with swipe gestures or an on-screen directional pad
- Keyboard controls with arrow keys or `WASD`
- Neon-colored snake and food with high contrast
- Score and persistent best-score tracking using `localStorage`
- Speed increases every five apples
- Game-over overlay with a restart button
- Responsive layout for desktop and mobile screens
- Dark styling with `prefers-color-scheme` support
- No server, build step, or external dependencies

## Run locally

Open `index.html` directly in a modern web browser:

```text
index.html
```

The game starts automatically. On mobile, swipe across the board or use the directional pad below it. On desktop, use the arrow keys or `WASD`. Select **Play again** after a game over.

## Project structure

```text
.
├── index.html   # Game markup, styling, and JavaScript
└── README.md    # Project documentation
```

## Gameplay

Eat the pink food to grow the snake and increase your score. Avoid the board edges and the snake's own body. The game becomes faster as your score increases.
