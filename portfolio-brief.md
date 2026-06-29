# Senior Product Designer — Portfolio Project Brief

## Goal
Build a personal portfolio website deployable to Netlify, plus a PDF version for email attachments.

---

## What to build

### Website (primary deliverable)
- Static HTML + CSS + JS — no framework, no build step
- Deployed to Netlify (free tier, drag-and-drop or GitHub integration)
- Responsive (desktop + mobile)
- Print stylesheet (`@media print`) for PDF export from the browser

### PDF (secondary deliverable)
- 1-page CV/resume PDF — for cold outreach
- Multi-page case study PDF — optional, for companies that request it

---

## Site structure

| Page | Purpose |
|---|---|
| Home / Hero | Name, role title, 1–2 line value prop, links to Work and Contact |
| Work (index) | Grid of 3–5 case study cards with thumbnail, title, and 1-line impact metric |
| Case study (detail) | One page per project — see structure below |
| About | Short bio, design philosophy, experience summary, photo |
| Contact | Email, LinkedIn, optional CV download button |

---

## Case study page structure (per project)

1. **Result first** — open with the outcome and a key metric
2. **Problem & context** — business situation, constraints, who the users were
3. **My role** — specific ownership (research, sprints, stakeholders managed)
4. **Process** — research → insights → iterations, including wireframes and rejected directions
5. **Design decisions & rationale** — why specific choices were made, connected to user needs and business goals
6. **Outcome & impact** — metrics, qualitative feedback, lessons learned

---

## What makes it senior-level

- Lead with **business impact** (conversion rates, retention, NPS, revenue), not just visual polish
- Show **cross-functional leadership** — how you influenced PMs, engineers, executives
- Include **trade-offs and constraints** — demonstrate real-world decision-making
- Show **design system contributions** if relevant
- Document **research ownership** — interviews, synthesis, insight generation
- Show **iterations and pivots**, not just the final polished result

---

## Design direction

- Clean, minimal, typographic — let the work speak
- Single-column layout for case studies (easier to read and print)
- Consistent color tokens and typography across all case study pages
- No heavy animations — subtle transitions only
- Accessible (contrast, keyboard navigation)

---

## Tech stack

- **HTML + CSS + JS** (vanilla) — simplest, most portable
- **Netlify** — free hosting, custom domain support, HTTPS auto-configured
- **@media print** stylesheet — hides nav, removes animations, single column, exports cleanly as PDF via browser

---

## Inspiration / references

- bestfolios.com — benchmark for quality and structure
- designlab.com/blog — annotated portfolio breakdowns
- github.com/netlify-templates — one-click deploy starters
- sitebuilderreport.com/inspiration/ux-portfolios — real senior designer portfolio examples

---

## Files to produce

1. `index.html` — home page
2. `work.html` — case study index (or section on homepage)
3. `case-study.html` — template for a case study detail page
4. `about.html` — about page
5. `style.css` — shared styles + print stylesheet
6. `README.md` — deployment instructions for Netlify
