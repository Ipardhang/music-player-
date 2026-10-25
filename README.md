# Music Player

A responsive browser-based music player built with HTML, CSS, and JavaScript, with support for local audio, persistent browser storage, search previews, playlists, and optional Spotify playback.

## Features

- Local audio file playback
- IndexedDB persistence for uploaded tracks
- Play, pause, seek, volume, repeat, and autoplay controls
- Playlist management
- iTunes Search API preview search
- Responsive glass-style UI
- Optional Spotify PKCE login and Web Playback integration

## Run locally

Because browser storage and API integrations work more reliably over HTTP than `file://`, serve the project from a local web server.

For example:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Project notes

The core player works with local audio files. Online search and Spotify functionality depend on their respective browser/API configuration and should be treated as optional integrations.

## Tech

HTML · CSS · JavaScript · IndexedDB · Web APIs
