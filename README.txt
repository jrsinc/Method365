METHOD365 WEBSITE — HOSTING GUIDE (GitHub Pages)
================================================

Contents
  index.html                 The full website (single page)
  images/method365-logo.png  Logo
  images/world-coverage.svg  Coverage map

Publish on GitHub Pages
  1. Create a PUBLIC repository on github.com (e.g. method365-website).
  2. Upload index.html and the images folder (top level of the repo).
  3. Settings > Pages > Deploy from a branch > main / (root) > Save.
  4. Your site appears at https://YOUR-USERNAME.github.io/method365-website/

Contact form
  No setup needed. When a visitor clicks "Request a consultation", their
  email app opens with the enquiry pre-filled and addressed to
  info@method365.com; they press Send.
  To change the address, edit the line  var TO='info@method365.com';
  near the bottom of index.html (and the email shown on the page).

Before going live, replace these placeholders in index.html:
  [FOUNDER NAME]  - About section quote
  [PHONE NUMBER]  - Contact section
  [CITY]          - Contact section ("[CITY], New Jersey")
