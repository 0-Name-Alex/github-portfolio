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

## Deploy to Vercel

### Option A — Vercel CLI
```bash
npm i -g vercel
vercel
```

### Option B — Vercel Dashboard (drag & drop)
1. Go to https://vercel.com/new
2. Drag the `github-portfolio` folder onto the page
3. Click **Deploy** — done!

### Option C — Connect GitHub repo
1. Push this folder to a GitHub repo
2. Import the repo on https://vercel.com/new
3. Vercel auto-detects it as a Static site

## Local Preview
Just open `index.html` in your browser — no build step needed.
