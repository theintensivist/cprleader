ACLS Code Leader — installable web app (PWA)
============================================

This folder is the complete app. It must be served over HTTPS (any static host works).
Once someone opens it, the app caches itself and keeps working with no internet.

Ways to put it online (pick one)
--------------------------------
1. Netlify Drop (no account set-up needed, 1 minute)
   Go to app.netlify.com/drop and drag this whole folder onto the page.
   You get an https address; you can rename it in Site settings.

2. GitHub Pages
   Create a repository, upload the contents of this folder, then
   Settings → Pages → Deploy from branch → main / root.

3. Your own website
   Copy this folder into the site's public/static folder, e.g. public/code-leader/,
   and it is served at https://your-site/code-leader/

Install on a phone
------------------
Android (Chrome): open the address → tap "Install" on the start screen (or menu → Install app).
iPhone/iPad (Safari): open the address → Share → Add to Home Screen.

Updating
--------
Replace the files with a newer build. Installed copies download the update in the
background and show "An update is ready · Reload" on the start screen. They never
reload by themselves during a code.

Voice commands
--------------
Work in Chrome, Edge and Safari. Served over HTTPS, the microphone permission is
remembered. Chrome and Edge send audio to an online speech service, so voice commands
need internet; everything else works offline. Do not say patient identifiers aloud.

myICUnotes.com by Dr Abhijeet Anand · myicunotes.substack.com
