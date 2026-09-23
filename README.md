# Quiz Scoreboard

A scorekeeper for running quizzes on YouTube. It is a single `index.html` file with no build step.

**Live app:** https://jviegas6.github.io/quiz-scoreboard/

## Features

- Add up to 12 players. Rename a player by clicking their name.
- Choose the points per correct answer (1, 2, 3, 5 or 10), or enter any other amount, including negative ones.
- Question counter, undo, and a score history grouped by question.
- **Stream view** (`S`) shows a large scoreboard, sorted by rank, on a chroma-key green background. Capture the window in OBS and key out the green.
- Scores are saved in your browser, so a refresh keeps them.

## Keyboard shortcuts

| Key | Action |
|---|---|
| `1`–`9` | Give points to player 1–9 |
| `Shift` + `1`–`9` | Take points away from player 1–9 |
| `N` | Next question |
| `U` | Undo the last change |
| `S` | Turn stream view on or off |
| `Esc` | Leave stream view |

## Run locally

Open `index.html` in a browser.
