# Luul Shire — Portfolio Site (Pixel/Game Edition)

A 6-page retro game-menu style portfolio. No build tools, just static HTML/CSS/JS.

## Pages
- `index.html` — home / game menu screen
- `about.html` — About Me (bio + photography + drink photos)
- `projects.html` — 4 projects with real charts
- `skills.html` — skills + certifications
- `education.html` — both degrees
- `contact.html` — email / LinkedIn / GitHub buttons

All pages share `style.css` and `script.js`.

## Put it live on GitHub Pages

1. Create a repo named exactly `LuulShire.github.io`
2. Upload every file in this folder (all the `.html`, `.css`, `.js`, and
   `.jpg` files) to the repo root — no subfolders needed, everything sits flat
3. Settings → Pages → Deploy from branch → `main` → `/ (root)` → Save
4. Live at `https://luulshire.github.io` in a minute or two

## Adding a new project later

Open `projects.html`, copy one whole `<article class="project">...</article>`
block, paste it in, and edit the text/images/links. Keep it inside the
`.project-list` div. Add any new photos as `.jpg` files in the same folder
as everything else (no subfolder) and reference them by filename only,
e.g. `src="my_new_chart.jpg"`.

## Notes
- Fonts (Press Start 2P, VT323, Plus Jakarta Sans) load from Google Fonts —
  render correctly once hosted online.
- No phone number anywhere on the site.
- The NDA-covered capstone project is not included anywhere.
- No GitHub/notebook links on the project cards right now, since those repos
  either don't exist or weren't saved. If you dig up or rebuild any of that
  code later, search `project-head` in `projects.html` for where to add a
  link back in per project.
