===============================================================
 THANT ZIN AUNG — ACCOUNT DIRECTOR PORTFOLIO WEBSITE
===============================================================

FILES IN THIS FOLDER
--------------------
index.html       → The full single-file website (HTML + CSS + JS)
images/
  profile.jpg    → Hero portrait  (REPLACE with real photo)
  clients.png    → Clients grid   (REPLACE with real graphic)
robots.txt       → Tells search engines to index the site
sitemap.xml      → Site map for Google Search Console
README.txt       → This file


QUICK START
-----------
1. Open index.html in any modern browser — the site works
   completely offline, no build step required.

2. REPLACE THE TWO PLACEHOLDER IMAGES with the real photos
   you uploaded:

     images/profile.jpg   ← use the black-and-white portrait
                            of Thant Zin Aung
                            (keep filename or update the src
                            in index.html)

     images/clients.png   ← use the "OUR ATL CLIENTS" graphic
                            (the red-black grid with all logos)

   Recommended dimensions:
     - profile.jpg  : 900 × 1200 (3:4 portrait), <250 KB
     - clients.png  : 1280 × 720 (16:9), <500 KB


DEPLOY TO A REAL DOMAIN
-----------------------
• Cheapest / fastest: upload all files to Netlify, Vercel,
  GitHub Pages or Cloudflare Pages — drag-and-drop works.

• Before going live:
    1. Buy a domain (e.g. thantzinaung.com).
    2. Replace "https://thantzinaung.com/" in:
         - index.html  (og:url, twitter:url, canonical, JSON-LD)
         - sitemap.xml
         - robots.txt
       with your real domain.
    3. Submit the sitemap in Google Search Console.


CONTACT FORM
------------
The contact form is pre-wired to open the visitor's email
client with a fully-formatted message addressed to
meebuu@gmail.com (Thant Zin Aung's email).

TO USE A REAL FORM BACKEND (recommended):
  • Sign up for Formspree (free) → https://formspree.io
  • Replace the <form id="contactForm"> handler in the JS
    with:  <form action="https://formspree.io/f/YOUR_ID"
                 method="POST">
  • Remove the JS event-listener submit block.

  Or use Netlify Forms (just add  netlify  to the <form> tag
  if you deploy on Netlify).


KEY FEATURES INCLUDED
---------------------
✓ Responsive (mobile, tablet, desktop)
✓ Smile loading animation (SVG, ~1.9s)
✓ Smooth scroll + reveal-on-scroll animations
✓ Number counters in hero
✓ Campaigns grid with industry filter
✓ Campaign detail modal with challenge / strategy / result
✓ Sticky glass-blur navigation
✓ Back-to-top button
✓ Full SEO metadata:
    – Title, description, keywords, author
    – Open Graph + Twitter Cards
    – Structured data (Person JSON-LD schema)
    – Canonical URL
    – robots.txt + sitemap.xml
✓ Accessibility:
    – Semantic HTML5
    – ARIA labels on interactive elements
    – Respects prefers-reduced-motion
✓ Contact form with validation + mailto fallback


CAMPAIGNS INCLUDED  (22 total)
------------------------------
Automotive:        MG Luxury EV Taxi, Honda NXC Myanmar
Healthcare:        Asia Royal Hospital, Kan Thar Yar Hospital,
                   Ensure, Pediasure, Similac Gain
FMCG / Beauty:     Acqua Sanitary Ware, Arty Cosmetics,
                   BSC Cosmetics, Now How Cosmetics
Retail / Fashion:  MK Myanmar Celebrity Campaign, MK Myanmar
                   Multi-celebrity program, Haier Myanmar,
                   New Motion Travels & Tours
Tech / Gaming:     Venus Lab "Pwal Kyam" MOBA, Mandalay Rum AR,
                   Gazar Streaming Platform, bebee TV
Social Impact:     #HerStories with Inspiring Women Myanmar
Events:            Digital Business in YGN 2018, DJ LED Festival


EDITING TIPS
------------
• To add a new campaign: find the CAMPAIGNS array near the
  bottom of index.html and add a new object using the same
  shape as the existing ones.

• To change the accent colour: edit `--accent` in the :root
  block at the top of the <style>.

• To change typography: the site uses Inter + Playfair Display
  from Google Fonts (already preconnected).


Questions? meebuu@gmail.com · +95 9 763 740 237
