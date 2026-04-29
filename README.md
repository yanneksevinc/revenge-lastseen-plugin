# Revenge Last Seen Plugin

A Revenge plugin that tracks the last observed online/offline transition for Discord users and shows the cache in the plugin settings page.

GitHub Pages repository import URL:

https://yanneksevinc.github.io/revenge-lastseen-plugin/

Direct repository-style import JSON:

https://yanneksevinc.github.io/revenge-lastseen-plugin/repo.json

Current repository structure:
- repo.json at the repository root
- builds/lastseen/manifest.json
- builds/lastseen/index.js
- docs/ mirror for GitHub Pages sources that publish from /docs

Notes:
- This only records users after the plugin is installed and while presence updates are received.
- "Last seen" is inferred from online -> offline transitions that the client observes locally.
