# friends-make-tools

Tools, plugins, and themes built by friends who like making things.

Most of our work targets [Hermes Agent](https://github.com/NousResearch/hermes-agent) — the open-source agent framework that runs in your terminal, your desktop, and your chats. We write plugins that extend it and skins that restyle it.

## Public repos

| Repo | What it is |
|---|---|
| **[hermes-plugins](https://github.com/friends-make-tools/hermes-plugins)** | Hermes Agent plugins, each shipped as one folder — Python backend, desktop UI, and the spec that shaped it |
| **[hermes-themes](https://github.com/friends-make-tools/hermes-themes)** | Hermes Agent skins — Monokai Pro, IBM Carbon, and friends |

## Using them

**Install a plugin** — copy the plugin folder into `$HERMES_HOME/plugins/` (Windows default: `%LOCALAPPDATA%\hermes\plugins\`), enable it, and restart the desktop app. Each repo README has the full steps.

**Install a theme** — copy a `.yaml` skin into your `skins/` folder, then run:

```bash
hermes config set display.skin <name>
```

Every surface repaints live in about a second. Revert with `display.skin default`.

---

*We think you're gonna like it here.*
