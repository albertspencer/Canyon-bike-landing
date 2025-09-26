# Reflection — Canyon Bike Co Landing Page

**Author:** Albert Spencer  
**Date:** (9/24/25)

---

## 1) AI brainstorming transcript / summary

**Prompt used (I am a CIS capstone student who needs a project I can finish in one week and publish to GitHub tonight. Requirements:

Delivers business value to a small business / nonprofit / department.

Looks professional to a professor (clear, tightly scoped).

Uses AI during development.

Is doable in one week (ideally a single evening or overnight to finish).


Short name (1 line).

What it is (1–2 sentences).

Business value (1 sentence).

Exactly how AI will be used (bullet points).

Minimal tech stack (1 line).

A 3-step plan to finish tonight (concise).
At the end, recommend the single easiest plan to finish tonight and explain why (1 sentence).
Also output a 1-paragraph ready-to-paste summary that I can use in Reflection.md that says: "I brainstormed with AI and selected [chosen idea]. AI generated drafts and I did the implementation, totalling approximately 50% AI / 50% human work."):**



> "Static Local Business Landing Page — 1-page responsive site for a local business with AI-generated copy, JSON-LD, alt text, and an accessibility checklist."

I ran the prompt above, reviewed the ideas, and selected the **Static Local Business Landing Page** because it was fast to implement and delivers clear business value.

---

## 2) What I implemented (step-by-step)

1. **Scaffold & deploy**
   - Created `index.html` and `style.css`.
   - Published the repo `Canyon-bike-landing` and enabled GitHub Pages.

2. **Content & SEO**
   - Integrated AI-drafted hero headline, subhead, meta description, and a JSON-LD LocalBusiness schema (edited for accuracy).
   - Added accessible labels and descriptive alt text (AI drafted, I edited and validated).

3. **Images & branding**
   - Replaced placeholders with a bike hero image and uploaded a local `logo.jpg`.
   - Fixed hotlinking/name issues so images and CSS load reliably.

4. **UX polish**
   - Implemented an animated booking success toast (HTML + JS + CSS).
   - Disabled automatic mail client opening during demo (`AUTO_OPEN_MAILTO = false`) so the toast is visible.

5. **Docs**
   - Wrote a concise `README.md` in my voice and expanded this `Reflection.md`.

---

## 3) What worked

- AI produced usable first drafts for copy, JSON-LD, and alt text that saved time.
- Static site + GitHub Pages allowed instant deployment and simple iteration.
- The animated toast gives a polished demo experience and improves perceived reliability.

---

## 4) What didn’t work / limitations

- `mailto:` alone is unreliable for production form submissions. I disabled auto-mailto for demos; next step is FormSubmit or a serverless endpoint.
- Some external image hotlinks can be blocked; uploading key images to the repo solved that.
- A full WCAG audit (contrast, focus order) remains — beyond the one-evening scope.

---

## 5) Lessons about using AI

- Use AI for drafts and structure, then verify and edit. AI speeds drafting but must be reviewed.
- More precise prompts (word counts, tone) produce better initial outputs.
- Keep a short audit trail (save the prompt and sample outputs) so you can explain AI’s role.

---

## 6) Who did what (approximate)

- **Me (Albert):** ~50% — artifact selection, layout, accessibility fixes, image handling, JS toast implementation, testing, and publishing.  
- **AI (assistant):** ~50% — initial idea generation, headline/copy drafts, JSON-LD, alt text, and README/Reflection drafts that I adapted.

---

## 7) Next steps (recommended)

- Integrate **FormSubmit** (or a tiny serverless function) so booking requests are reliably delivered and logged.  
- Run Lighthouse/pa11y and add the report to the repo.  
- Add a demo screenshot or short GIF to `README.md`.  
- Address WCAG issues flagged by Lighthouse (contrast, focus states).

---

## 8) Evidence & commits

Key commits: initial site files, fix for stylesheet filename, image replacements, and adding the booking toast. See the repository commit history for timestamps and exact messages.

---

