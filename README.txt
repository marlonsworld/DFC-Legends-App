DFC Legends — Book Zero  (work-in-progress demo build)

HOW TO PUT IT ONLINE
1. Keep this folder intact — index.html loads everything else by relative path.
2. Drag the whole folder onto a static host:
     app.netlify.com/drop   (fastest, no account needed to start)
     or GitHub Pages / Vercel / Cloudflare Pages
3. You get a URL. Open it on a phone for the real feel;
   "Add to Home Screen" makes it behave like an installed app.

EMBEDDING IN WIX
   Add an Embed > "Embed a site" element, paste the URL,
   and size the box about 420 x 900 so the phone frame fits.
   Do not paste the HTML itself into Wix — it is far past the snippet limit.

WHAT'S IN HERE
   index.html          the app
   audio/              cover theme, chapter loop, 7 jukebox tracks, 4 panel VOs
   cover_00.gif        animated cover
   issue_hero.gif      Issue Zero card animation
   splash_3a.gif       full-page splash between pages 3 and 4
   slots.json          the panel artwork
   support.js, image-slot.js, ios-frame.jsx, _ds/   runtime + design system

NOTES
   Needs an internet connection for fonts and icons.
   Audio starts on the first tap - browsers block sound before that.
   Visitors can't change the art or audio; it's read-only for them.
