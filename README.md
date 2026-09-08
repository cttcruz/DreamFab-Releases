# DreamFab Releases

Public downloads for **DreamFab** (Windows installer and OTA update packages).

- **Source code is not published here.** It lives in a private repository.
- Install from [Releases](https://github.com/cttcruz/DreamFab-Releases/releases) (`DreamFab-win-Setup.exe`).
- The app checks this repository’s Releases feed for updates (Velopack).

## v1.0.0 notes

- Self-contained Windows x64 build (no separate .NET install)
- Bundled ffmpeg
- WebView2 Evergreen is bootstrapped by Setup if missing
- **Unsigned:** SmartScreen may show “Unknown publisher” → More info → Run anyway

User data lives under `%LocalAppData%\DreamFab\` (`data`, `output`, `webview2`) and survives updates.
