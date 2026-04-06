# Aesthetic Studio

Aesthetic Studio is a single-page palette and typography generator built as a static front-end project. It creates curated visual directions with live previews, share cards, history, and favorites.

## Features

- Generate new color palettes and font pairings
- Preview the aesthetic in a live mock layout
- Copy individual hex values from palette cards
- Copy the full palette as CSS custom properties
- Save favorites and revisit recent generations
- Download a share card image
- Toggle dark mode
- Lock palette, fonts, or mood before generating again
- Press `Space` to generate a new palette

## Files

- `index.html` - app markup and asset links
- `style.css` - all visual styling and responsive layout rules
- `script.js` - palette generation, keyboard shortcut, copy actions, and storage logic

## How to run

1. Open `index.html` in a browser.
2. Click **Generate New Aesthetic** to create a new direction.
3. Use the copy and save controls to keep the parts you like.

If you prefer, serve the folder with any static file server instead of opening the HTML file directly.

## Keyboard shortcut

- `Space` - generate a new palette

## Notes

- The project is self-contained and does not require a build step.
- It uses `localStorage` to persist history, favorites, and theme preference in the browser.
