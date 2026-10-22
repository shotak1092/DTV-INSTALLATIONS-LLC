DTV INSTALLATIONS — SITE PHOTO PACKAGE (for the web team)

Open index.html first. It's a visual map of every photo, which page it goes on and its alt text.

FOLDERS
  <page>/            Publish-ready. Use on that service page.
  <page>/process/    Publish-ready process/behind-the-scenes shots. Use in a "How we build it" strip under the gallery.
  _hold-needs-fix/   DO NOT PUBLISH yet. The notes column in photo-manifest.csv says what to fix (usually on-screen movie/TV content, clutter, or the old 888 number).
  _preview/          Small thumbnails for index.html only. Don't upload these.

FILES
  .webp = upload this to the site. .jpg = fallback/social.
  All 2048px max on the long edge. EXIF/GPS removed, so no client addresses leak.
  Filenames are already SEO slugs. Keep them as is.

ALT TEXT
  photo-manifest.csv, column alt_text. Paste verbatim.

DO NOT
  - Rename files to IMG_xxxx or stock names
  - Use any image marked "Do not use" in the manifest (stock, manufacturer, AI renders, client names on screen)
  - Upscale or add filters
  - Lazy-load the hero image on each page (load it eagerly; lazy-load the rest)

BEFORE/AFTER PAIRS (build these as sliders)
  Boardroom:            commercial-av/...boardroom-before...  → ...boardroom-after...
  Marantz living room:  whole-home-audio/...in-wall-lcr-cutouts-before → ...marantz-room-in-wall-lcr-finished
  Stone fireplace:      tv-installation/...stone-fireplace-articulating-mount-before → (hold) ...stone-fireplace-tv-finished
  Waterfront bedroom:   motorized-shades/...waterfront-bedroom-before-shades → ...waterfront-bedroom-shades-mid
