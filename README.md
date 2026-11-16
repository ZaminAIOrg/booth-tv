# ZaminAI booth TV

Videos for the booth screen at events. Public on purpose: these are marketing videos.

- `videos/` holds the files.
- `playlist.json` says what plays. `tv` is the main screen (played in order, then repeated); `logo` is the logo-only screen.
- `zaminai.com/tv` and `zaminai.com/tv/logo` read this playlist, so changing a video here needs no website deploy.
  The same screens also run straight from GitHub Pages: `https://zaminaiorg.github.io/booth-tv/` and `.../booth-tv/logo/`.

To change a video: add the new file under a **new name** (for example `brand-loop-v3.mp4`, so no TV keeps an old cached copy), point `playlist.json` at it, and push. Refresh the TV, or wait for the current round to end; the screen re-reads the playlist each round.
