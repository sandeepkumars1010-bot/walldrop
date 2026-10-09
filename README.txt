WALLDROP — OnePlus 15 wallpaper website

FILES
- index.html: responsive wallpaper website
- manifest.webmanifest: installable web app metadata
- sw.js: lightweight app-shell service worker

WHAT IT DOES
- Picks a random image from a curated set each time the site opens.
- Lets you request another image.
- Offers a download button.
- Uses portrait crops from Unsplash image URLs.

IMPORTANT
This is a starter version with a curated list of image IDs, not an unlimited image generator.
The images are loaded from Unsplash over the internet. A small subset of the image URLs may occasionally change or become unavailable; the site includes a retry behavior.
For an installable home-screen shortcut, upload these files to an HTTPS static host (for example GitHub Pages or Netlify), then open the hosted URL in Chrome on your OnePlus and choose:
Chrome menu (⋮) > Add to Home screen / Install app.

Image use and API notes:
- This version uses direct Unsplash image URLs for a simple prototype.
- If publishing for wider use, review Unsplash's current license and API guidelines; an official API integration may be preferable.
- Direct download can depend on browser/CORS behavior; if the button opens the image instead, long-press it and save/download.
