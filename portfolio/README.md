# Luke Coffin — ePortfolio

Static site, no build step. Files:

- `index.html` — home / bio / index of artifacts
- `artifact-1.html` — infographics
- `artifact-2.html` — running & mental health essay
- `artifact-3.html` — race, education & economic status lit review
- `styles.css` — shared styles
- `assets/` — the coaches infographic (embedded via iframe) and the running infographic image

## Get a URL with GitHub Pages (free, ~2 minutes)

1. On github.com, click **New repository**. Name it whatever you want (e.g. `eportfolio`). Keep it **Public**. Don't add a README/gitignore — leave it empty.
2. On your computer, open a terminal in this folder and run:
   ```
   git init
   git add .
   git commit -m "ePortfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/eportfolio.git
   git push -u origin main
   ```
   (Replace `YOUR-USERNAME` and the repo name with your own.)
3. On GitHub, go to your repo → **Settings** → **Pages** (left sidebar).
4. Under "Build and deployment," set **Source** to **Deploy from a branch**, branch **main**, folder **/(root)**. Click **Save**.
5. Wait ~1 minute, then refresh that Pages settings page — it'll show your live URL, something like:
   `https://YOUR-USERNAME.github.io/eportfolio/`

That URL is what you paste into the assignment submission box.

**Before submitting:** open that URL in a private/incognito window (not signed into anything) and click through all three artifact pages, per the assignment instructions, to confirm everything loads.

## To personalize before submitting

- `artifact-3.html`: the contextual statement has a bracketed note asking you to fill in your specific course/term/role in the group project — replace that sentence with the real details.
- `index.html`: the bio assumes things like year/major aren't specified — feel free to tighten it up with your actual details.
- Swap "University of Maryland" mentions anywhere that need updating.
