# ACS Mechanical Inc. — Website

A modern, clean, fully responsive multi-page website for ACS Mechanical Inc. (Whitehorse, Yukon heating contractor).

## Pages
- `index.html` — Home (hero, services, biomass, heating comparison table, service area, reviews)
- `about.html` — About + team
- `services.html` — All services with anchored sections
- `gallery.html` — Project gallery
- `careers.html` — Careers / open roles
- `blog.html` — Blog listing
- `contact.html` — Contact form, info & map

Shared assets: `styles.css` (design system) and `main.js` (mobile nav, scroll reveal, form handling).

It's a plain static site — no build step. Open `index.html` in a browser to preview.

## Deploy to Vercel (1 command)
From this folder, with the Vercel CLI installed and logged in (`npm i -g vercel` then `vercel login`):

```bash
vercel deploy --prod
```

Accept the defaults (framework: **Other**, build command: none, output dir: `./`).

Alternatively, drag this folder onto https://vercel.com/new, or push it to a Git repo connected to Vercel.

## Notes
- The contact form is front-end only (shows a success message). To receive submissions, connect it to a form service (Formspree, Vercel Forms, etc.) or your email provider.
- Gallery and blog use placeholder visuals — swap in real project photos and published posts.
- Business details (phone, email, address, hours) are pulled from the current live site.
