# Survivor.io Mount Calculator

A lightweight, browser-based board layout calculator for Survivor.io-style component placement.

## Live Demo (GitHub Pages)

Test the project here:  
[https://twalt89.github.io/Surviv-io-Mount-Calculator-Public/](https://twalt89.github.io/Surviv-io-Mount-Calculator-Public/)

## Features

- Interactive component board with multiple board widths (`7`, `9`, and `12`)
- Adjustable component inventory counts
- Automatic and manual solve modes
- "Another Layout" option for alternative valid placements
- Solver stats panel (lines completed, filled cells, solve time, searched states)
- Runs entirely in the browser (single `index.html` file)

## Run Locally

1. Clone this repository.
2. Open `index.html` in your browser.

Or serve it with a simple local server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Board Width URL Parameter

You can set board width via query param:

- `?w=7`
- `?w=9`
- `?w=12`

Example:

`http://localhost:8000/?w=12`

## Tech

- HTML
- CSS
- Vanilla JavaScript
