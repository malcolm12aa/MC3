# MC3 Training Games — Instructor Edition

A single-page website with twelve classroom games for teaching the MC3 consultative communication process: Build Rapport, Listen with Purpose, Engage, Explore, Enable, Gain Commitment, Respond to Objections, and Respond to Disinterest.

## Features

- **12 game cards** with full rules, examples, and what each game teaches
- **Skill filter** so you can pull up only the games for today's lesson
- **Drill card generator** — draw random objections, motivators, disinterest openers, and recruiter scenarios live in class (no printed cards needed)
- **Competition Day plan** — a recommended full-class sequence
- **Print-friendly** — use the browser's Print for handouts (game cards expand automatically)

No build step, no dependencies. Everything is in one `index.html` file.

## Run it locally

Just open `index.html` in any browser.

## Put it on GitHub Pages (free hosting)

1. Create a new repository on GitHub (e.g. `mc3-training-games`).
2. Upload `index.html` and this `README.md` to the repository (drag and drop works on github.com → "Add file" → "Upload files").
3. Go to the repository's **Settings → Pages**.
4. Under **Source**, choose **Deploy from a branch**, select the `main` branch and `/ (root)` folder, then **Save**.
5. After a minute or two, your site will be live at:
   `https://YOUR-USERNAME.github.io/mc3-training-games/`

Share that link with your class — it works on phones, tablets, and projectors.

## Editing content

All content lives directly in `index.html`:

- **Game cards** are in the `<section class="games">` block — each `<article class="card">` is one game.
- **Drill deck cards** (objections, motivators, disinterest lines, scenarios) are in the `decks` object near the bottom of the file, inside the `<script>` tag. Add or remove strings from the arrays to change what can be drawn.
- **Competition Day plan** is in the `<section class="compday">` block.
