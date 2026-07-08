# AIO.InfoTech website

A static site (plain HTML/CSS/JS, no build step) matching your Figma design:
- `index.html` — Home (hero, vision, values, contact form)
- `services.html` — Services
- `team.html` — Founding Team / About
- `projects.html` — Our Work
- `assets/style.css`, `assets/script.js` — shared styles & behavior

## Go live — pick one (all free, all take a few minutes)

### Option A: Netlify (drag & drop, easiest)
1. Go to https://app.netlify.com/drop
2. Drag the whole `aio-site` folder onto the page
3. You'll get a live URL immediately (e.g. `random-name.netlify.app`)
4. Optional: add your own domain in Site settings → Domain management

### Option B: Vercel
1. Go to https://vercel.com/new
2. Choose "Deploy without Git" / drag-and-drop the folder, or push this folder to a GitHub repo and import it
3. Deploy — you'll get a live URL (e.g. `your-project.vercel.app`)

### Option C: GitHub Pages (free, good if you already use GitHub)
1. Create a new GitHub repo and push this folder's contents to it
2. Repo → Settings → Pages → Source: `main` branch, `/ (root)`
3. Your site will be live at `https://<username>.github.io/<repo-name>/`

## Notes
- The contact form is front-end only right now — it shows a confirmation message but doesn't send anywhere. To actually receive submissions, either:
  - Use a form backend like Formspree (https://formspree.io) or Netlify Forms (just add `netlify` and `name="contact"` attributes to the `<form>` tag if hosting on Netlify), or
  - Wire it to your own backend/email service.
- Fonts (Space Grotesk, Outfit) load from Google Fonts via CDN — no local font files needed.
- Icons and decorative shapes were rebuilt as inline SVG so nothing depends on Figma's temporary asset links.
