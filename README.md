# Alex — GitHub Portfolio

A beautiful, dark-themed portfolio page that **dynamically fetches all your GitHub repositories** using the GitHub API and displays them in a card grid.

## Features
- Live data from GitHub API (always up-to-date — no rebuild needed)
- Filter by: All / Mine (non-forks) / Forked / Language
- Sort by: Recently Updated / Most Stars / Name A-Z / Newest First
- Real-time search across name, description, topics, and language
- Stars, forks, language, topics, and relative "updated X ago" on each card
- Animated cards with hover effects
- 100% responsive

## Deploy to GitHub Pages

1. Create a repo named `0-Name-Alex.github.io` (served at `https://0-name-alex.github.io/`) or any name, e.g. `github-portfolio` (served at `https://0-name-alex.github.io/github-portfolio/`).
2. Push these files to the `main` branch (`index.html` must be at the repo root).
3. In the repo go to **Settings → Pages → Build and deployment → Source** and choose **GitHub Actions**.
4. The included workflow (`.github/workflows/pages.yml`) deploys on every push. Check the **Actions** tab for the live URL.

Prefer no Actions? Choose **Deploy from a branch → main / (root)** instead.

## Local Preview
Just open `index.html` in your browser — no build step needed.
