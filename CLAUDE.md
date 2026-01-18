# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A modern, interactive portfolio website built as a 30-day learning journey. Currently in early development (Day 1 complete - project structure only).

## Tech Stack

- HTML5, CSS3, JavaScript (ES6+)
- Three.js for 3D graphics
- GSAP for animations
- Vite for build tooling

## Development Commands

Once dependencies are installed:

```bash
npm install          # Install dependencies
npm run dev          # Start Vite dev server
npm run build        # Build for production
npm run preview      # Preview production build
```

**Note:** `package.json` and Vite configuration need to be created as part of project setup.

## Project Structure

```
src/
├── index.html       # Main HTML entry point
├── scripts/
│   └── main.js      # JavaScript entry point
├── styles/
│   └── main.css     # Global styles
└── assets/          # Images, videos, and other media
```

## Architecture Notes

- Vanilla frontend project (no backend framework)
- Source files are in `src/` directory
- Build output will go to `dist/` (gitignored)
- Dependencies managed via npm with `node_modules/` gitignored
