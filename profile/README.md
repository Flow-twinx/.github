<div align="center">

# Flow-twinx

**Why pay for Spotify when Flow can handle all the things for you?**

A terminal-and-web music player, plus the tools that extend it.

[![Flow](https://img.shields.io/badge/Flow-terminal%20music%20player-1e2327?style=for-the-badge)](https://github.com/Flow-twinx/Flow)
[![Python](https://img.shields.io/badge/Python-3-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/Flow-twinx/Flow)

</div>

---

## What we build

**[Flow](https://github.com/Flow-twinx/Flow)** is our flagship project — a dual-mode terminal (and web) music player that automatically switches between online streaming and offline library playback. It ships as a CLI, a full-screen Textual TUI (`flowt`), and a Flask-based web GUI.

-  **Online mode** — search and stream from YouTube via `yt-dlp` + `python-vlc`
-  **Offline mode** — local library playback with albums, search, and liked songs
-  **Download** — save streamed tracks to your local library
-  **Repeat, shuffle & radio** — flexible playback controls
-  **Playlists** — create, manage, and play custom playlists
-  **Colored TUI & web GUI** — cyan for online, magenta for offline, plus an audio-reactive visualizer and synced lyrics
-  **Background play** — run in the background and control it from your shell

```bash
pip install flow-twinx
flow
```

## Extending Flow

**[flow-plugins](https://github.com/Flow-twinx/flow-plugins)** is the community plugin repository for Flow. It hosts a catalog of installable plugins (e.g. `thumbnail-circle`, `nowplaying`) that hook into Flow via the bundled `flow_api` module.

```bash
flow install <plugin-name>
flow plugins list
flow run <plugin-name>
```

## Other repositories

| Repo | Description |
|---|---|
| [Flow](https://github.com/Flow-twinx/Flow) | The core terminal & web music player |
| [flow-plugins](https://github.com/Flow-twinx/flow-plugins) | Community plugin catalog for Flow |
| [Singularity-api-saavan](https://github.com/Flow-twinx/Singularity-api-saavan) | TypeScript API project |
| [Coins](https://github.com/Flow-twinx/Coins) | Python project |

---

<div align="center">

Questions, ideas, or plugin contributions welcome — open an issue or PR on the relevant repo.

</div>
