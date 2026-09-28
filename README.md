# Music Studio

One-page AI music generator built on the [Suno API](https://docs.sunoapi.org). Static HTML: no build step, no server.

## Features
- **Simple mode**: describe a song and the lyrics are written for you.
- **Custom mode**: title, style tags, your own lyrics (or ✨ AI-written), vocal gender, excluded styles, style weight, weirdness.
- Instrumental toggle and model picker (V6, V6 Wild, V6 Mini).
- Live status, in-page player, cover art, MP3 download, lyrics view.
- Track library and credit balance, saved in the browser.

## Use
Open the site, click **🔑 API key**, and paste your key from https://sunoapi.org/api-key. The key stays in that browser's localStorage and goes only to `api.sunoapi.org`.

## Deploy (Netlify)
Connect this repo in Netlify. There is no build command, and the publish directory is the repo root (already set in `netlify.toml`). You can also drag the folder onto app.netlify.com/drop.
