# Data Structures Using C — BCA Exam Prep

A small set of interactive HTML lessons + a master "Exam Blueprint", built to pass the BCA *Data Structures Using C* semester exam. Content is grounded in the official SLM textbook and the four recorded lecture transcripts.

**Live site (after you enable Pages):** `https://<your-username>.github.io/<repo-name>/`

## What's here

| Path | What it is |
|------|-----------|
| `index.html` | Home page — links to every lesson and the blueprint. |
| `reference/exam-blueprint.html` | Master reference: all exam-flagged topics, tiered by certainty, checked against the SLM. |
| `lessons/*.html` | Self-contained interactive lessons, each ending in a recall drill. |
| `MISSION.md` | Why this exists (the learning goal). |
| `RESOURCES.md`, `NOTES.md`, `learning-records/` | Teaching workspace (not part of the website). |
| `pdf_extracted.txt`, `lectures/` | Source material (not linked from the site). |

## Host it on GitHub Pages (first-time steps)

You've never done this — here's the whole thing. No command line needed beyond the push you're already doing.

1. **Push this repo to GitHub** (you're doing this part).
2. On GitHub, open the repo → **Settings** (top tab).
3. Left sidebar → **Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. **Branch:** pick `main` (or `master`), **folder:** `/ (root)`. Click **Save**.
6. Wait ~1 minute. Refresh the Pages settings page — it shows a green box with your live URL:
   `https://<your-username>.github.io/<repo-name>/`
7. Open that URL. `index.html` loads automatically as the home page.

That's it. Every time you push to the chosen branch, the site updates.

### Notes
- `.nojekyll` (empty file in the root) tells GitHub to serve the files as-is, skipping Jekyll processing. Leave it there.
- All internal links are **relative** and **case-sensitive** — they work as-is on Pages. Don't rename files without updating links.
- The site is 100% static HTML/CSS/JS — no build step, no dependencies.

## Local preview

Just double-click `index.html` — it opens in your browser and works fully offline.
