# AIO.InfoTech website

A static site (plain HTML/CSS/JS, no build step) matching your Figma design:
- `index.html` — Home (hero, vision, values, contact form)
- `services.html` — Services
- `team.html` — Founding Team / About
- `projects.html` — Our Work
- `assets/style.css`, `assets/script.js` — shared styles & behavior


## Notes
- The contact form is front-end only right now — it shows a confirmation message but doesn't send anywhere. To actually receive submissions, either:
  - Use a form backend like Formspree (https://formspree.io) or Netlify Forms (just add `netlify` and `name="contact"` attributes to the `<form>` tag if hosting on Netlify), or
  - Wire it to your own backend/email service.
- Fonts (Space Grotesk, Outfit) load from Google Fonts via CDN — no local font files needed.
- Icons and decorative shapes were rebuilt as inline SVG so nothing depends on Figma's temporary asset links.
