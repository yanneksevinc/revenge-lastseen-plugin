# Revenge Last Seen Plugin

A Revenge plugin that tracks the last observed online/offline transition for Discord users and shows the cache in the plugin settings page.

Import base URL for Revenge:

https://raw.githubusercontent.com/yanneksevinc/revenge-lastseen-plugin/main/

Current Revenge/Bunny plugin structure used here:
- repo.json at the repository root
- builds/lastseen/manifest.json
- builds/lastseen/index.js

Notes:
- This only records users after the plugin is installed and while presence updates are received.
- "Last seen" is inferred from online -> offline transitions that the client observes locally.
