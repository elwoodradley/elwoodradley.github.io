STONE TOAD — hand-built site
============================

Plain HTML + one CSS file. No build step, no framework, no dependencies.
Edit any .html file in a text editor and reupload. That's the whole workflow.

FILES
  index.html              home / hub
  about.html              about + links hub
  style.css               all styling (edit colors at the top under :root)
  games/index.html        game showcase
  games/garbage-route.html  game detail page (copy this as a template for others)
  devlog/index.html       devlog list
  writing/index.html      novels + poetry

ADD A DEVLOG POST
  Open devlog/index.html, copy one <a class="row"> block, change the
  title/date/blurb. For a full post, make devlog/my-post.html (copy any page
  as a starting point, fix the ../ paths) and point the row's href at it.

THINGS TO FILL IN (search the files for these)
  - "https://store.steampowered.com/"  -> real Garbage Route wishlist URL
  - patreon / tiktok "#" links in every footer + about.html
  - writing/index.html  -> real poem + novel info
  - the [ bracketed ] placeholders in writing/index.html

HOST IT (free options)
  - GitHub Pages: push this folder to a repo, enable Pages on the branch.
  - Neocities / Nekoweb: drag-drop these files. Very small-web.
  - Any static host or your own box: it's just files.

The font (Share Tech Mono) loads from Google Fonts. If you'd rather not call
out to Google, download the .woff2, drop it in, and swap the <link> for an
@font-face in style.css. Everything else is fully self-contained.
