# Stumble Labs Cover Creator

This package contains the cover-editor frontend extracted from the source archive you provided, with Stumble Labs branding and graceful placeholders for missing background images.

## Preview locally
Open `cover-creator.html` in a browser. For best results, run a local static server from this folder (for example, `python -m http.server 8000`) and open `http://localhost:8000/cover-creator.html`.

## Important source limitation
The supplied archive did not include `public/backgrounds/bg_01.jpg` through the other map background files referenced by `main.js`. The editor therefore shows placeholders for those backgrounds until those images are added. Some emote assets are also absent from the archive. This is the standalone editor bundle, not yet merged into the live Stumble Labs `index.html`, and it does not yet save cover settings to Supabase or connect to tournament creation.

## Integration paths
- `cover-creator.html`: editor UI
- `main.js`: canvas preview and export logic
- `style.css`: editor styles
- `public/`: available image/font assets from the archive
