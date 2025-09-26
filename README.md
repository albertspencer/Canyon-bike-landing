# Canyon-bike-landing


**Status:** Finished — ready to publish to GitHub Pages tonight.

## What this project is
A single-page, production-quality static landing page for a local bike shop (Canyon Bike Co). It includes:
- Responsive UX built with Bootstrap (no build step required).
- Accessible semantic HTML (labels, aria attributes, alt text).
- Basic SEO: meta description, keywords, and JSON-LD LocalBusiness schema.
- A simple booking form (mailto fallback) and clear calls-to-action.

This repo includes:
- `index.html` — the landing page (artifact).
- `styles.css` — small custom styling.
- `README.md` — this file describing business value and usage.
- `Reflection.md` — AI brainstorming transcript and lessons learned.

> **Assignment reference:** See the assignment doc used for this project.

---

## Why this delivers business value
- **Immediate presence:** Gives a small business a fast, low-cost, professional web presence.
- **Conversion-focused:** Hero CTA + booking form to capture leads.
- **Accessible & SEO-friendly:** Helps attract search traffic and improves usability.
- **Low-maintenance & deployable:** Works on GitHub Pages (no hosting cost).

---

## How to use / apply it
1. Replace placeholder phone and images in `index.html` with real content.
2. Option A — **Quick publish** (GitHub web UI): create repo, add files, and enable GitHub Pages (instructions below).
3. Option B — **Local git**: clone, add files, push to remote and enable Pages.
4. For production bookings: replace `mailto:` form with Netlify Forms or a small server endpoint.

---

## Where AI was used
AI was used to create first drafts of:
- Hero headline, subhead, CTA and benefit bullets.
- Meta description and JSON-LD.
- Alt text for images and accessible form labels.
- Initial drafts of README.md and Reflection.md which were then edited and validated.

**Prompts used** (examples you can re-run):
- "Write a 12-word hero headline and a 25-40 word subhead for a local bike shop in Canyon, TX..."
- "Write concise alt text (max 15 words) for a photo showing a mechanic working on a bicycle wheel..."
- "Provide a JSON-LD LocalBusiness schema for 'Canyon Bike Co'..."

---

## Quick local setup (terminal) — exact commands
```bash
mkdir canyon-bike-landing
cd canyon-bike-landing
# create the files (paste the provided contents into index.html, styles.css, README.md, Reflection.md)
git init
git add .
git commit -m "Initial: Canyon Bike landing page + README + Reflection"
git branch -M main
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/canyon-bike-landing.git
git push -u origin main
