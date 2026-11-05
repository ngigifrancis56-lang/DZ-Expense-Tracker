CAR PROFIT TRACKER — iPHONE INSTALLATION

This is a personal, offline-capable web app (PWA). It tracks multiple vehicles,
trip income, trip date, cargo/material carried per trip, quantity and unit,
customer name, delivery site, multiline trip notes, trip fuel/other costs, general vehicle expenses, weekly driver payments, profit,
CSV exports (including trip notes) and JSON backups. Currency is KES.

IMPORTANT: iPhone Home Screen installation requires the app to be served from
an HTTPS website. Opening index.html directly from Files will let you preview
it, but will not install the offline PWA correctly.

FREE INSTALL ROUTE USING GITHUB PAGES
1. On a computer, sign in or create a free account at https://github.com
2. Create a new public repository named car-profit-tracker.
3. Upload ALL files from this folder (index.html, manifest.webmanifest,
   sw.js, icon-192.png, icon-512.png).
4. In the repository, open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch, select main and
   /(root), then Save.
6. Wait for GitHub Pages to publish. Your address will look like:
   https://YOUR-USERNAME.github.io/car-profit-tracker/
7. On your iPhone, open that HTTPS address in Safari.
8. Tap Share (square with arrow) > Add to Home Screen > Add.
9. Launch Car Profit from the new Home Screen icon.

DATA & BACKUPS
- Data is stored locally in the browser on that iPhone. It is not automatically
  synced to other devices.
- Use Records > Download backup regularly and keep the JSON file somewhere safe.
- Export CSV to open your records in Excel or Numbers.
- Clearing Safari website data may erase locally stored records.

PROFIT METHOD
Net profit = trip income - trip fuel/other trip costs - general expenses -
weekly driver payments recorded in the selected reporting period.
Weekly driver payments are counted on the date you record/pay them. The week
start/end fields are descriptive coverage dates; they do not reallocate the
payment to earlier dates. Avoid entering the same fuel twice (both on a trip
and again as a general expense).
