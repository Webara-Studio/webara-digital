# Webara Digital — Ghana Web Design

Ghana's leading web designer. We build websites, web apps, and full online presence to win customers worldwide.

Live site: https://webara-studio.github.io/webara-digital/

## What's in this repo
- `index.html` — the whole site (single page: hero, services, global reach, pricing, process, contact)
- `styles.css` — all styling, using the Webara Studio brand (dark `#131C20`, gold `#E0B152`, cream `#E4DDCD`, card `#223239`) and the Webara fonts (Cinzel / Montserrat / Lato)

## Features
- **Responsive** — collapses to a single column on phones, with a slide-down menu (hamburger, top-right).
- **Dark / light mode** — toggle in the footer; choice is saved in `localStorage` and respects the visitor's system preference on first visit. Theme variables live in the `[data-theme="light"]` block in `styles.css`.

## How to edit
Everything is plain HTML + CSS — no build step. Open `index.html` in any editor:
- **Colours / fonts:** change the values in the `:root` block at the top of `styles.css`.
- **Words:** edit the text directly in `index.html`.
- **Pricing:** the "From GHS 5,000" figure and add-on list are in the `#pricing` section.

## Before you go live — fill these in
Search `UPDATE` in `index.html` for the spots to replace:
1. Contact email (`hello@webaradigital.com`) — used by the form and the contact card.
2. WhatsApp number (`wa.me/233000000000`).
3. Page `<title>` and meta description.
4. To make the form send without opening the visitor's email app, swap the `mailto:` handler for Formspree or Netlify Forms.

## Deploy
GitHub Pages is enabled on the `main` branch, so changes pushed here appear at the URL above automatically.


## 📈 Marketing & Promotion Plans

### Ghana Market Launch
We've created comprehensive promotion plans for the Ghana market:

- **[Lean Mode Plan](promotion-plan-lean.md)** - GHS 25,000/month (~$2,500 USD)
  - Organic growth focused
  - No paid ads initially
  - Break-even by month 2

- **[Full Plan](promotion-plan.md)** - GHS 120,000/month (~$12,000 USD)
  - Paid ads included
  - Full-scale launch

- **[Quick Summary](promotion-plan-summary.md)** - Executive overview

### Key Strategy
1. **Google First** - Local SEO + Business Profile
2. **Instagram Second** - Visual portfolio + Reels
3. **Facebook Third** - Community + groups

### Target Budget
**Lean: GHS 25,000/month** - Perfect for startup phase
**Scaling: GHS 60,000/month** - Add paid ads when ready

---
