[README.md](https://github.com/user-attachments/files/31551580/README.md)
# Quest Viewer

**Live VR streaming from Meta Quest to your Windows PC.** Under 100 ms on your own Wi-Fi,
peer-to-peer, no capture card and no cloud service. Watch one headset or a whole room of them
side by side.

### ➜ [Get Quest Viewer free on the Microsoft Store](https://apps.microsoft.com/detail/9NKR9T8MK6R8)

Website: **https://gowthamvrxr.github.io/Questviewer/**

---

## What this is

Quest Viewer is two halves:

| | What it does | Where to get it |
|---|---|---|
| **Quest Streaming SDK** | Unity package that makes your VR app streamable | Unity Asset Store — free, full C# source |
| **Quest Viewer** | Windows app that receives and displays the streams | [Microsoft Store](https://apps.microsoft.com/detail/9NKR9T8MK6R8) — free tier, no account |

Drop the SDK into your Unity project and every headset running your app shows up on the PC
automatically — no IP addresses, no pairing codes, no router changes.

## Download

### [Get Quest Viewer free on the Microsoft Store](https://apps.microsoft.com/detail/9NKR9T8MK6R8)

Signed and distributed by Microsoft, so there are no security warnings, and it keeps itself
up to date.

### [Download the portable build](https://github.com/GowthamVRXR/Questviewer/releases/download/v2.0.4/QuestViewer-v2.0.4-win-x64.zip)

For managed machines where the Store is blocked or unavailable — arcades, training floors,
locked-down classrooms. Unzip anywhere and run `QuestViewer.exe`, keeping the folder contents
together. Windows will warn that it is unsigned; choose **More info → Run anyway**. A SHA-256
checksum is published with each [release](https://github.com/GowthamVRXR/Questviewer/releases).

## Requirements

- Windows 10 version 1809 or newer, 64-bit
- A Meta Quest 2, Quest 3 / 3S or Quest Pro running an app built with the Quest Streaming SDK
- Both devices on the same Wi-Fi network
- Microsoft Edge WebView2 Runtime — already present on Windows 11 and most Windows 10 machines

Quest Viewer *receives* streams. It does not mirror arbitrary Quest games — the headset must be
running software built with the SDK.

## Free, trial and Pro

| | Free | Pro trial | Pro |
|---|---|---|---|
| Headsets at once | 1 | unlimited | unlimited |
| Resolution | up to 720p | full | full |
| Session recording | — | yes | yes |
| Machines | — | this PC | 3 |
| Cost | free forever | 15 days | from $150 |

The free tier needs no account and never expires. The 15-day Pro trial starts only when you
ask for it in the app — it does not begin on install. A lapsed licence never disables the
version you already have.

Full pricing: https://gowthamvrxr.github.io/Questviewer/#pricing

## Privacy

Video travels directly from the headset to your PC. It never passes through our servers,
because we do not run any. No analytics, no tracking, no telemetry.
[Full policy](https://gowthamvrxr.github.io/Questviewer/privacy.html).

## Terms

[Terms of Service](https://gowthamvrxr.github.io/Questviewer/terms.html) ·
[Refund policy](https://gowthamvrxr.github.io/Questviewer/#refunds)

## Support

**[Read the user manual](https://gowthamvrxr.github.io/Questviewer/manual.html)** — installation,
streaming and stream quality, recording, licence activation, moving a licence between computers,
and troubleshooting.

Email **gowthambaskaran.xr@gmail.com** — replies within two business days.

Common issues:

- **No headset appears** — same Wi-Fi? Guest networks and router "client isolation" block
  discovery. Firewall allowed on Private networks?
- **Tile appears but video is black** — install the
  [WebView2 Runtime](https://developer.microsoft.com/microsoft-edge/webview2/) and restart.
- **Everything capped at 720p** — that is the free tier. Start the trial or activate a licence.

---

This repository hosts the Quest Viewer website. Quest Viewer is built and
sold by Gowtham Baskaran, Salem, Tamil Nadu, India.

Meta, Meta Quest and Oculus are trademarks of Meta Platforms, Inc. Unity is a trademark of
Unity Technologies. This product is not affiliated with, endorsed by, or sponsored by either
company.
