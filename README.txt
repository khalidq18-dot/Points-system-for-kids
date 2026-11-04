DAILY POINTS BOARD - standalone app
====================================

What is in this folder
  index.html               the app
  manifest.webmanifest     tells the phone it can be installed
  sw.js                    lets it open without internet after the first visit
  icon-192.png, icon-512.png, icon-maskable-512.png   app icons

Records are saved only on the phone where you use the app. There is no
syncing between phones. Use Scoring > Download backup now and then.

STEP 1. Put the folder on a web address (needs https)
  Option A, GitHub Pages (free)
    1. Create a repository on github.com and upload all the files here to it.
    2. Open the repository Settings > Pages, choose the main branch and the
       root folder, then save.
    3. After a minute the app is at https://YOUR-NAME.github.io/REPOSITORY/
  Option B, Netlify Drop (free)
    1. Go to app.netlify.com/drop and drag this whole folder onto the page.
    2. Netlify gives you a web address for the app.

STEP 2. Install on the phone
  Open the web address in Chrome on the Android phone. Open the Chrome menu
  and choose Install app (or Add to Home screen). The Points Board icon
  appears with your other apps. It also shows an Install button on the
  Scoring tab when Chrome allows it.

OPTIONAL. Make a real Android package (APK)
  Go to pwabuilder.com, enter the web address from Step 1 and choose the
  Android package. It gives you an app file you can install or publish.

IMPORTANT
  Records belong to the web address. If you later move the app to a different
  address, download a backup first and restore it there.
  Opening index.html straight from the phone files also works, but it cannot
  be installed and its records are separate from the hosted copy.

TO CHANGE POINTS: open the Scoring tab and edit the numbers.
