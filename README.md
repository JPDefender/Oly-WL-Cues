# WL Error Correction — Coach Reference

A mobile-friendly web app for Olympic weightlifting coaches to quickly diagnose technique errors and find the right coaching cues and corrective drills.

**Live site:** [https://jpdefender.github.io/Oly-WL-Cues/](https://jpdefender.github.io/Oly-WL-Cues/)

## What It Does

This is an interactive reference tool built around a USAW-framework approach to error correction for the **Snatch**, **Clean**, and **Jerk**. For each common technique fault, the app provides:

- **Root Cause** — why the error is happening
- **Downstream Effects** — what breaks if it's not corrected
- **Coaching Cues** — verbal cues ranked by effectiveness
- **Corrective Drills** — exercises in priority order
- **Bar Path Deviation** — where the fault shows up in the bar path (Snatch & Clean)

## Features

- **Search** across all errors, cues, drills, and root causes
- **Filter by lift** (Snatch / Clean / Jerk) and by **phase** (First Pull, Transition, Second Pull, Third Pull, Receiving, Dip, Drive, Split)
- **Bar Path Diagnostic** — select a bar path deviation to find all related errors
- **Quick Cue mode** — compact card view showing just the error and top cue for fast courtside reference
- **Frequency indicators** — errors tagged as Common, Moderate, or Less Common
- **Mobile-first** — designed for use on a phone at the platform, with sticky header and touch-friendly controls
- **Installable** — supports Add to Home Screen on iOS/Android for app-like access
- **Zero dependencies to install** — single HTML file, no build step, runs entirely in the browser

## Tech Stack

- React 18 (CDN)
- Babel standalone (in-browser JSX transpilation)
- Vanilla CSS-in-JS (inline styles)
- GitHub Pages for hosting

## Usage

Open `index.html` in any modern browser, or visit the live GitHub Pages site. No server or build process required.

## Author

**Jacob Phillips**

## License

All rights reserved.
