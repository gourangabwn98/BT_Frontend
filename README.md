# Bengal Tech Solution — Website

A single-file animated landing page for Bengal Tech Solution (IT Services & Consulting).

## What's inside
- `index.html` — the complete website (HTML + CSS + JS in one file)

## How to use it

### Option 1: Just open it
Double-click `index.html` to preview it in your browser. Note: the rotating 3D globe/prism and scroll animations need an internet connection (they load GSAP and Three.js from a CDN).

### Option 2: Deploy to Vercel (recommended)
1. Go to https://vercel.com and sign up / log in
2. Click "Add New Project" → "Deploy without Git" (or drag-and-drop)
3. Drag this whole folder in, or just `index.html`
4. Vercel will give you a live URL in ~30 seconds

### Option 3: Deploy via GitHub + Vercel
1. Create a new GitHub repo and upload `index.html` (rename to `index.html`, keep at root)
2. On vercel.com, click "Add New Project" → Import your GitHub repo
3. Framework preset: "Other" (it's a static HTML file) — no build command needed
4. Deploy

### Option 4: Any static host
This is a plain static HTML file — it also works on Netlify, GitHub Pages, Cloudflare Pages, or any basic web host. Just upload `index.html`.

## Editing content
Everything is in `index.html`:
- Text content is in the HTML body — search for section text (e.g. "IT Consulting & Strategy") to edit copy directly.
- Colors/theme are CSS variables at the top of the `<style>` block (the `:root { ... }` section) — change `--brass`, `--grad`, `--bg`, `--ink` etc. to retheme the whole site at once.
- Contact email/address/social links are in the `<footer>` section near the bottom.
- Pricing numbers are in the `#pricing` section.

## Libraries used (loaded via CDN, no install needed)
- Google Fonts: Fraunces, Inter, JetBrains Mono
- GSAP + ScrollTrigger (scroll animations, counters, magnetic buttons)
- Three.js r128 (rotating globe + prism in hero and contact section)

## Notes
- Fully responsive (mobile, tablet, desktop)
- Respects `prefers-reduced-motion` for accessibility
- No backend/server required — it's 100% static
