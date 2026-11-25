THE LANTERN OF HOLLOWMERE - installable web app (PWA)

WHAT'S IN THIS FOLDER
  index.html              the game
  manifest.webmanifest    app name, icon and colours
  sw.js                   offline support
  icon-*.png, icon.svg,
  apple-touch-icon.png    app icons

Upload ALL of these files. They all sit side by side, with no folders,
so you can select them together on your phone.
The game will not install or work offline if you only open index.html
from your phone's files. It has to be served from a website.

PUT IT ONLINE WITH GITHUB PAGES (free; works from a phone browser)
  1. Sign in at github.com in your browser (not the GitHub app).
     If you can't find a menu below, switch the browser to "Desktop site".
  2. Tap "+" > New repository. Name it, e.g. "hollowmere".
     Choose Public, then Create repository.
  3. Tap "uploading an existing file" (or Add file > Upload files).
     Select all the files from this folder, upload them, then tap
     "Commit changes".
  4. Go to Settings > Pages. Under "Build and deployment", set Source
     to "Deploy from a branch", choose the "main" branch and "/ (root)",
     then Save.
  5. Wait a minute or two. Your game will be at:
       https://YOUR-USERNAME.github.io/hollowmere/

INSTALL IT ON YOUR PHONE
  Android (Chrome): open the link, then menu (three dots) > Install app
                    or Add to Home screen.
  iPhone (Safari):  open the link, tap Share > Add to Home Screen.
  Open it once while online; after that it also works offline.

EASIER ALTERNATIVE: NETLIFY DROP
  On a computer, go to app.netlify.com/drop and drag this whole folder
  onto the page. You get a link immediately.

UPDATING THE GAME LATER
  Replace index.html, and change VERSION at the top of sw.js
  (e.g. hollowmere-v2). Players get the update next time they open
  the game online.

Your progress is saved on your device. Uninstalling the app or clearing
site data erases it.
