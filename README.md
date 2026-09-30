# LimitScope releases

Public updater/release asset companion for **LimitScope**, the Windows
quota-monitor desktop app.

This repository hosts **signed update artifacts only**, published by the
release workflow of the source repository:

- `LimitScope_<version>_x64-setup.exe` — the signed NSIS installer
- `LimitScope_<version>_x64-setup.exe.sig` — its minisign updater signature
- `latest.json` — the Tauri updater feed

The installed app fetches updates from
`https://github.com/datawarsaw/limitscope-releases/releases/latest/download/latest.json`
without any credentials.

**This is not the source repository.** Source code, issues, and development
live in the private repository [datawarsaw/rate-limits](https://github.com/datawarsaw/rate-limits).
Nothing else belongs here.
