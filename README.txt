NICO CARS AS – Netlify/GitHub package

Dette er en oppdatert versjon av nettsiden.

Beholdte funksjoner:
- Vipps-betaling via netlify/functions/vipps.js
- Netlify Forms
- Leveringskalkulator og «Bestill levering»
- Bilseksjon og eksisterende design

Oppdateringer:
- Telefon: +47 484 21 292
- Telefontid: 18:00–20:00
- Ny «Om oss»-seksjon
- SEO metadata og strukturert data
- robots.txt og sitemap.xml
- Open Graph/Twitter metadata
- favicon og delingsbilde
- 404-side
- Mobil- og ytelsesforbedringer uten å endre hoveddesignet

Deploy:
1. Last opp/push hele innholdet til GitHub-repositoriet.
2. Netlify må bygge fra repoets rot.
3. Build settings: Functions directory = netlify/functions.
4. Ikke slett environment variables for Vipps i Netlify.
5. Vipps krever fortsatt VIPPS_CLIENT_ID, VIPPS_CLIENT_SECRET,
   VIPPS_SUBSCRIPTION_KEY og VIPPS_MSN, samt eventuelt VIPPS_BASE_URL/FRONTEND_URL.
