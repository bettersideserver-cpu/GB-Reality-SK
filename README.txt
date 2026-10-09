GB REALTY — Airport Road (PR-7), Mohali
Salman Khan's first real estate project · Jacob & Co.'s second branded residence in India
Single-page pre-launch site
=====================================================================

HOW TO OPEN
-----------
Double-click index.html. It runs straight from the folder — no server, no
internet connection and no installation required. Everything the page needs
(the aerial, the logo, the fonts) is inside this folder.

To put it online, upload the whole folder to any web host and point the
domain at index.html. Nothing else needs configuring.

WHAT IS IN HERE
---------------
index.html          The page.
assets/app.js       The whole site (layout, styles, animation, form).
images/             The aerial of the site and the GB Realty monogram,
                    recoloured to the client's gold.
fonts/              Bodoni Moda and Jost, self-hosted so nothing loads
                    from an external service. Static instances, not the
                    Google variable build.
og-image.png        The image shown when the link is shared on
                    WhatsApp, LinkedIn, X or iMessage.
favicon.ico         Browser tab icon.

WHAT TO REPLACE BEFORE THIS GOES LIVE
-------------------------------------
1. The pre-booking dates. The 15-day window currently renews itself so it
   never expires. Real dates go in one place:
   src/web/lib/campaign.ts
2. The phone number and email address, in the same file.
3. The RERA registration number, once it is issued. There is deliberately
   none on the page today.

THE PAGE
--------
Three sections, in this order:

  1. The hero      — the two names, the address and the one line of price.
  2. The location  — the aerial map with the route to the airport.
  3. The collaboration — Salman Khan, Jacob & Co. and GB Realty, and the
                     project details.

NOTES
-----
- No stock imagery of a building that does not exist and no projected
  returns. Every figure on the page is one the developer stated.
- The rate shown is 14,500 per sq ft, exclusive of GST, stamp duty,
  registration and other statutory charges.
- Distances (Airport Chowk a few metres, Chandigarh International Airport
  2 km) are approximate and measured from the site.
- The aerial is a satellite view and is not to scale.
