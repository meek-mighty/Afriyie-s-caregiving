# Afriyie Care — Caregiving-Only Website

Plain HTML/CSS/JS. No build step, no framework — upload these files to
any static host (Netlify, GoDaddy, cPanel, GitHub Pages, etc.) and it
just works.

This is the caregiving-focused version of the site (no cleaning
services content).

## Files
- `index.html` — the page
- `css/styles.css` — all styling, colors, and animations
- `js/script.js` — nav, scroll reveal, marquee, magnetic buttons, contact form
- `images/` — only the caregiving photos, named by what they show (e.g.
  `hero-tablet.jpg`, `feeding.jpg`, `wheelchair-elbow.jpg`). Replace any
  file with your own image as long as you keep the same filename.

## Contact form
The form posts to Formspree (`https://formspree.io/f/myegpdpl`), which
emails submissions to afriyiecarellc@gmail.com. The first real submission
triggers a one-time confirmation email from Formspree — click the link
in it to activate delivery.

## Hosting
Upload the whole folder (keeping the `css/`, `js/`, and `images/`
subfolders intact) to your host, or drag-and-drop the folder into
Netlify Drop (netlify.com/drop) for instant hosting.
