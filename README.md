# Luul Shire — Portfolio Site (Pixel/Game Edition)

A 6-page retro game-menu style portfolio. No build tools, just static HTML/CSS/JS.

## Pages
- `index.html` — home / game menu screen
- `about.html` — About Me (bio + photography + drink photos + animated sprite)
- `projects.html` — 4 projects with real charts
- `skills.html` — skills + certifications
- `education.html` — both degrees
- `contact.html` — email / LinkedIn / GitHub buttons

All pages share `style.css` and `script.js`.

## Latest update: About page revamp

- Bio shortened to 3 tight paragraphs, no alcohol references, added the barista hobby
- Photo layout changed: Photography and Drink Making now each have their own
  column with a blurb up top and 2 photos underneath (was a 6-photo grid before)
- Added an animated pixel-art avatar sprite (`avatar_sprite.svg`) next to the
  bio — idles with a gentle bob, alternates holding a tiny camera and a mason
  jar every 3 seconds. Pure CSS animation inside the SVG, no JS needed, works
  as a plain `<img>` tag.
- Swapped the 🍹 emoji for 🍵 in the Drink Making header

## No new repo needed

You do not need to delete and recreate `LuulShire.github.io`. Just upload the
files in this folder into the same repo (same filenames overwrite
automatically), then delete these 4 old files that are no longer used:
- `about_roses.jpg`
- `about_paris_street.jpg`
- `about_drink_minicookies.jpg`
- `about_drink_cocoa.jpg`

Give it a minute to rebuild, then hard-refresh `https://luulshire.github.io/about.html`.

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
