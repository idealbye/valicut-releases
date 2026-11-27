# ValiCut

**ValiCut** turns short dramas into ready-to-post vertical clips: AI picks the best moments, adds subtitles in 20+ languages, and renders everything on your Windows PC. Videos are never uploaded — only dialogue text is processed in the cloud.

This repository hosts the official Windows installers and auto-update files for ValiCut. It does not contain source code.

## Download

- **Recommended:** [valicut.com/download](https://valicut.com/download) — always the latest official build, with release notes.
- Or get the installer directly from [Releases](https://github.com/idealbye/valicut-releases/releases/latest).

Requires 64-bit Windows 10 or 11. New accounts get free credits; pricing is at [valicut.com/pricing](https://valicut.com/pricing).

## Files in a release

| File | What it is |
|---|---|
| `ValiCut-Setup-<version>.exe` | Installer for a specific version |
| `ValiCut-Setup.exe` | Copy of the latest stable installer (fixed name, used by the website's fallback link) |
| `ValiCut-Setup-<version>.exe.sha256` | SHA-256 checksum of the installer |
| `latest.yml`, `*.blockmap` | Auto-update metadata used by the app |

## Verify your download

Compare the SHA-256 of the file you downloaded with the value in the matching `.sha256` file or on the download page:

```powershell
Get-FileHash .\ValiCut-Setup-1.0.0.exe -Algorithm SHA256
```

Only installers attached to Releases in this repository are official. If you got ValiCut from anywhere else, check the checksum first.

## Support

Questions, bugs and refunds: **support@valicut.com**. Issues are not monitored here.

ValiCut is proprietary software. Use of the app is governed by our [Terms of Service](https://valicut.com/terms) and [Privacy Policy](https://valicut.com/privacy).

---

中文：ValiCut 是短剧 AI 高光切片工具，官方下载见 [valicut.com/zh/download](https://valicut.com/zh/download)。本仓库只存放官方安装包和自动更新文件，不含源代码。
