# Živina Kimchi Landing Pages

## Overview
Conversion-optimized landing pages for Živina kimchi products (https://www.zivina.cz).
Two variants for different campaign strategies.

## Pages
- **zivina-kimchi-landing.html** — Original v1 (archived, not actively used)
- **zivina-kimchi-landing-v2.html** — Product-first variant (deployed on Vercel as index.html)
  - Hero → Trust bar → "Proč kimchi?" → Products → Testimonials → Video → Bundles → FAQ → Story → CTA
- **zivina-kimchi-landing-v3.html** — Benefit/microbiome-first variant
  - Hero (health-led) → Trust bar → Benefits grid → Infographic → USP strip → Video → Products → Bundles → Testimonials → FAQ → Story → CTA

## GitHub & Deployment
- **Repo**: https://github.com/wofer357/zivina-kimchi-landing
- **Vercel URL**: https://wofer357-zivina-kimchi-landing.vercel.app
- V2 is deployed as `index.html`, V3 as `zivina-kimchi-landing-v3.html`
- Push to `main` triggers Vercel auto-deploy

## Brand
- **Fonts**: Albra Bold/Black (headings), Montserrat variable (body) — in `fonts/`
- **Colors**: pink `#d63370`, green `#008566`, gold `#f0b852`, red `#cd171a`, cream `#FBF6F0`
- **Logo**: `logo-zivina.svg` (black background, white text)

## Assets
- `images/carousel_*.webp` — Optimized product photos (800px, ~30KB each)
- `images/carousel_*.png` — Source photos (4500px, ~3MB each, not used by pages)
- `images/kimchi infografika.webp` — Brand infographic (used in V3 hero + standalone section)

## Product URLs (zivina.cz)
- Kimchi Nepálivé 300g → `/kimchi-nepalive-300-g-2/` (169,90 Kč)
- Kimchi Natur 300g → `/kimchi-natur-300-g-2/` (169,90 Kč)
- Kimchi Pálivé 300g → `/kimchi-palive-300-g-2/` (169,90 Kč)
- Kimchi Fenykl 300g → `/kimchi-fenykl-300-g-2/` (169,90 Kč)
- Kimchi Jidášovo ucho 400g → `/kimchi-jidasovo-ucho-400-g/` (249,90 Kč)
- Kimchi Shiitake 400g → `/kimchi-shiitake-400-g/` (249,90 Kč)

## Important notes
- **"přídatných" ne "přidaných"** — správný potravinářský termín
- **Žádná zdravotní tvrzení** — "Plné probiotik" apod. je regulatorně nebezpečné. Používat "živé kultury", "fermentovaný", "mléčně kvašený" místo zdravotních claimů.
- **Testimonials jsou placeholder** — Markéta K., Tomáš R., Jana S. jsou vymyšlené, nahradit reálnými recenzemi
- **Email form action="#"** — endpoint pro sběr emailů zatím není nastavený
- Blog články pro content: https://www.zivina.cz/blog/kimchi-co-to-je-a-proc-ho-jist/ a https://www.zivina.cz/blog/proc-zaradit-do-jidelnicku-fermentovane-potraviny-jako-napr--kimchi/

## Preview
```bash
python3 -m http.server 8080
```
