# Placement Prep Tracker

A single-page, no-backend checklist for tracking placement preparation day by day — Full Stack Dev roadmap, DSA patterns, Aptitude, and Placement process, each as its own section.

**Live site:** https://Gnaneshwar2105.github.io/placement-prepare-tracker/

## What's inside

- **Full Stack Dev** — a 16-week Java + React + Spring Boot roadmap, broken into daily concepts
- **DSA Patterns** — 13 LeetCode-style phases (Two Pointers, Sliding Window, Graphs, DP, etc.) with concepts + problem lists and goals per phase
- **Aptitude** *(separate section)* — quant, logical reasoning, verbal ability
- **Placement** *(separate section)* — core CS interview fundamentals, resume building, mock interviews, company-specific prep

Full Stack Dev and DSA roll up into one combined progress percentage. Aptitude and Placement each track their own percentage, kept separate from the dev score on purpose.

## How it works

- Pure HTML/CSS/JS — no build step, no dependencies, no server
- Progress is saved with the browser's `localStorage`, so it persists automatically between visits **in the same browser**
- Checking a box updates that section's progress bar and the running counts in real time

## Usage

Just open `index.html` — either locally or via the live GitHub Pages link above. No installation needed.

## Updating content

The full roadmap data lives in a few JS arrays near the top of the `<script>` block in `index.html` (`FULLSTACK`, `DSA`, `APTITUDE`, `PLACEMENT`). Edit those to add, remove, or re-word any phase, week, or topic — the UI renders directly from that data.

## Deployment

This repo is deployed with **GitHub Pages** from the `main` branch, root folder. Any commit to `main` redeploys the site
