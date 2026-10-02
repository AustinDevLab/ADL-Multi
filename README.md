# ADL Multi

A single-file multi-stream viewer for Kick. Watch up to 9 streams at once, with optional chat, favorites, recents, drag-and-drop ordering, layout modes and a clean mode.

## Run it

Open `index.html` in a browser. No build step, server or install needed.

## Host it on GitHub Pages

1. Create a repository named `adl-multi` at https://github.com/austindevlab and upload `index.html` to its root.
2. Go to **Settings → Pages**, choose the `main` branch and the `/ (root)` folder, then save.
3. Your site will be live at https://austindevlab.github.io/adl-multi/

## Notes

- Streams and chat use the `player.kick.cx` and `chat.kick.cx` embeds.
- Your setup, favorites and recents are stored in your browser's localStorage. Nothing is sent to a server.
- The Browse Streamers list checks live status through Kick's unofficial channel endpoint, which may be blocked in some browsers.

Made by [austindevlab](https://github.com/austindevlab).
