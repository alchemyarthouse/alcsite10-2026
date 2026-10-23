Alchemy ArtHouse site. Static, no build step.

Deploy: drag this folder into vercel.com/new, or push to GitHub and import the repo.
Framework preset: Other. Build command: none. Output directory: leave blank.

Structure
index.html      the whole site (fonts, images and styles are embedded)
hero/           hero video (mp4, webm, mobile mp4) and poster
vercel.json     caching and headers

Keep hero/ next to index.html or the hero falls back to the poster image.
