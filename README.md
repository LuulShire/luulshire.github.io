# Luul Shire — Portfolio Site (Pixel/Game Edition)

A 6-page retro game-menu style portfolio. No build tools, just static HTML/CSS/JS.

## Pages
- `index.html` — home / game menu screen
- `about.html` — About Me (bio + photography + drink photos + animated pet)
- `projects.html` — 4 projects with real charts
- `skills.html` — skills + certifications
- `education.html` — both degrees
- `contact.html` — email / LinkedIn / GitHub buttons

All pages share `style.css` and `script.js`.

## Latest update: About page revamp v2

- Two-column Photography/Drink Making layout confirmed working correctly
  (if it looked stacked before, that was a browser cache issue — hard
  refresh fixes it)
- Replaced the human sprite with a small animated pixel bear/blob pet
  (`blob_pet.svg`) sitting next to the bio. It waddles gently and has a
  pulsing heart beside it. Pure CSS animation, works as a plain `<img>` tag.
- `avatar_sprite.svg` (the old human sprite) is no longer used — safe to
  delete from your repo if it's still there from the last upload.

### Files to delete from your repo (no longer used)
- `avatar_sprite.svg` (replaced by `blob_pet.svg`)
- `about_roses.jpg`, `about_paris_street.jpg`, `about_drink_minicookies.jpg`,
  `about_drink_cocoa.jpg` (from earlier rounds, if not already removed)

### New/changed files to upload
- `about.html` (rewritten)
- `style.css` (updated)
- `blob_pet.svg` (new — the animated pet)

`script.js` and all other pages are unchanged from before.

## No new repo needed

You do not need to delete and recreate `LuulShire.github.io`. Just upload the
files in this folder into the same repo (same filenames overwrite
automatically), then delete the old files listed above. Give it a minute to
rebuild, then hard-refresh `https://luulshire.github.io/about.html`.

## Put it live on GitHub Pages (from scratch, if ever needed)

1. Create a repo named exactly `LuulShire.github.io`
2. Upload every file in this folder to the repo root, everything sits flat,
   no subfolders needed
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
