DRIVER DAILY LOG — MOBILE APP
World Bank Group · Suva, Fiji
================================

WHAT'S INCLUDED
  index.html   — The mobile app (all code inside)
  manifest.json — Makes the app installable
  sw.js         — Offline support
  icon-192.png  — App icon
  icon-512.png  — App icon (large)
  README.txt    — This file

HOW TO DEPLOY (required for installation on phones)
---------------------------------------------------
Option A — SharePoint (easiest for WBG staff):
  1. Go to a SharePoint site you manage
  2. Upload ALL files in this folder to a document library
  3. Click index.html → click the "..." menu → Share
  4. Copy the link and send to drivers

Option B — Free web hosting (GitHub Pages):
  1. Create a free GitHub account at github.com
  2. Create a new repository
  3. Upload all files
  4. Go to Settings → Pages → Deploy from main branch
  5. Your app URL will be: https://yourusername.github.io/repo-name/

HOW DRIVERS USE THE APP
------------------------
Android (Chrome):
  1. Open the URL in Chrome
  2. Chrome shows "Add to Home Screen" banner — tap it
  3. App installs like a native app, works offline

iPhone/iPad (Safari):
  1. Open the URL in Safari
  2. Tap the Share button (square with arrow)
  3. Scroll down → tap "Add to Home Screen"
  4. Tap Add

UPDATING DRIVER & VEHICLE NAMES
---------------------------------
The driver/vehicle dropdowns are set inside index.html.
To update them, open index.html in a text editor and search for
"DRIVERS" near the top of the <script> section. Edit the names there.

EXPORTING DATA TO EXCEL
-------------------------
1. Driver taps Export → Download CSV
2. Driver sends the CSV file to you (email or Teams)
3. You open "Drivers Log and Tracker.xlsx"
4. Go to the Daily Log sheet
5. Paste data starting at row 5 — columns match exactly

DATA STORAGE
-------------
All data is stored on each driver's device (browser storage).
Data is NOT shared between devices automatically.
Each driver exports their own CSV and sends it to you.

SUPPORT
--------
Contact your IT team or system administrator for hosting assistance.
