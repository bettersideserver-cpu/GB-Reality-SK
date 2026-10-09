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
images/             The aerial of the site, the GB Realty monogram.
fonts/              Bodoni Moda and Jost, self-hosted so nothing loads
                    from an external service.
og-image.png        The image shown when the link is shared on
                    WhatsApp, LinkedIn, X or iMessage.
favicon.ico         Browser tab icon.

THE FORM
--------
The pre-booking form in this standalone copy is presentational — opening the
file directly means it has no server to write to, so a submission shows a
confirmation but is not recorded anywhere. On the hosted version of the site
the same form writes every registration to a database, and the page reads the
live registration count back from it.

WHAT TO REPLACE BEFORE THIS GOES LIVE
-------------------------------------
1. The pre-booking dates. The 14-day window currently renews itself so it
   never expires. Real dates go in one place:
   src/web/lib/campaign.ts
2. The phone number and email address, in the same file.
3. The RERA registration number, once it is issued. There is deliberately
   none on the page today.

NOTES
-----
- No gold, no stock imagery of a building that does not exist, no projected
  returns. Every figure on the page is one the developer stated.
- The rate shown is 14,500 per sq ft, exclusive of GST, stamp duty,
  registration and other statutory charges.
- Distances (Airport Chowk a few metres, Chandigarh International Airport
  2 km) are approximate and measured from the site.
- The aerial is a satellite view and is not to scale.
