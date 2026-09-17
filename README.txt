Chinmay Shende — portfolio site (static, no build step)

Upload to GitHub (in the browser)
1. github.com → New repository → name it chinmay-site → Public → Create.
2. On the empty repo page click "uploading an existing file".
3. Open this chinmay-site folder in Finder, select everything inside it
   (index.html, archive.html, film.html, avatars folder, tv.png, ...) and drag it
   onto the GitHub page. Wait for the progress bars, then click "Commit changes".
   (The avatars folder drags in as a folder — Chrome and Safari both allow this.)

Connect to Vercel
1. vercel.com → Add New → Project → Import chinmay-site.
2. Framework preset: Other. Build command: none. Output directory: blank. Deploy.
   Every later change pushed to GitHub redeploys automatically.

Pages (clean URLs are on via vercel.json)
/            home
/archive     all films
/film#slug   one film

Files
index.html, archive.html, film.html   the three pages
tv.png, tv-mask.png                    the television and its glass mask
showreel.mp4                           muted loop inside the TV (full screen plays from YouTube)
chinmay.jpg                            About photo
avatars/                               commenter photos for "All the love"
favicon.svg, vercel.json

Notes
- Fonts load from Google Fonts; film thumbnails load from YouTube.
- To change email/phone/links, search for "chinmay.s.work@gmail.com" in index.html.
