ORA STUDIOS — orastudios.co
All website files. Updated 10 September 2026.

UPLOAD TO GITHUB LIKE THIS

  Top level of the repo (same place index.html already is):
    index.html
    schedule.html
    buy.html
    account.html
    privacy.html
    terms.html
    accessibility.html
    favicon.ico
    apple-touch-icon.png

  Inside the "images" folder:
    reception.jpg
    heated-room.jpg
    reformer-room.jpg

  Do not rename index.html. Do not move the JPGs out of images/.

WHY THE FONTS LOOK WRONG WHEN YOU OPEN THESE FILES LOCALLY
  Adobe Fonts only serves fonts to the domains listed in the
  "ORA Studios" web project. A file opened from your computer has
  no domain, so Adobe refuses and the browser substitutes.
  The fonts are correct on orastudios.co.

PAGES
  index.html          homepage
  schedule.html       Mariana Tek schedule      (noindex, unlinked)
  buy.html            Mariana Tek memberships   (noindex, unlinked)
  account.html        Mariana Tek member login  (noindex, unlinked)
  privacy.html        privacy policy — DRAFT, pending attorney
  terms.html          terms & conditions — DRAFT, pending attorney
  accessibility.html  accessibility statement — public, indexed

SERVICES
  Hosting    Vercel, auto-deploys from GitHub repo "orastudios"
  Domain     GoDaddy — A record @ -> 216.198.79.1
             DO NOT change nameservers; Google Workspace email
             (info@orastudios.co) depends on the DNS records there
  Fonts      Adobe Fonts project "ORA Studios"
             https://use.typekit.net/vrh5ttl.css
             Eurostile Extended 400/900, Normalidad Text 400/700
  Forms      Kit — founding list form 9743286 / tag 21664538
                   teach form      9743295 / tag 21664537
  Booking    Mariana Tek, tenant "orastudios"

BRAND
  Burgundy      #8D1914
  Rootbeer      #260D08
  Wistful       #FBE2A9
  Copper        #E27D44
  Ballet White  #EFEAE1   (screen value; paint is Benjamin Moore OC-9)

WHEN YOU OPEN
  Remove the noindex meta tag from schedule/buy/account and add
  them to the nav in every page's header.
