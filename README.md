<div align="center">

<img src="./assets/readme/logo.png" alt="Pixel Grabber logo" width="96" height="96">

# Pixel Grabber Installer

**Windows installer downloads for Pixel Grabber, a screenshot, color and reference tool for graphic designers.**

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/KazboXIII/PixelGrabber#design-desk"><img src="./assets/readme/covers/desk.webp" alt="Design desk" width="100%"></a>
<br/><a href="https://github.com/KazboXIII/PixelGrabber#design-desk"><strong>Design desk</strong></a>
<br/><sub>Annotate and keep every capture</sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/KazboXIII/PixelGrabber#capture"><img src="./assets/readme/covers/capture.webp" alt="Capture" width="100%"></a>
<br/><a href="https://github.com/KazboXIII/PixelGrabber#capture"><strong>Capture</strong></a>
<br/><sub>Select and annotate on screen</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/KazboXIII/PixelGrabber#screen-recording"><img src="./assets/readme/covers/record.webp" alt="Screen recording" width="100%"></a>
<br/><a href="https://github.com/KazboXIII/PixelGrabber#screen-recording"><strong>Screen recording</strong></a>
<br/><sub>GIF or H.264 MP4</sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/KazboXIII/PixelGrabber#boards-and-pins"><img src="./assets/readme/covers/boards.webp" alt="Boards and pins" width="100%"></a>
<br/><a href="https://github.com/KazboXIII/PixelGrabber#boards-and-pins"><strong>Boards and pins</strong></a>
<br/><sub>Floating references</sub>
</td>
</tr>
</table>

[![Latest installer](https://img.shields.io/github/v/release/KazboXIII/PixelGrabber-Installer?include_prereleases&style=flat-square&color=8B5CF6&label=installer)](https://github.com/KazboXIII/PixelGrabber-Installer/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/KazboXIII/PixelGrabber-Installer/total?style=flat-square&color=8B5CF6)](https://github.com/KazboXIII/PixelGrabber-Installer/releases)
[![platform](https://img.shields.io/badge/platform-Windows%2010%201809+%20x64-black?style=flat-square)](#requirements)

**[Download the latest installer](https://github.com/KazboXIII/PixelGrabber-Installer/releases/latest)** · [See every menu and feature](https://github.com/KazboXIII/PixelGrabber) · [Full release notes](https://github.com/KazboXIII/PixelGrabber/releases)

</div>

---

## Install

| Step | What to do |
|---|---|
| 1 | Download `PixelGrabber-<version>-Setup-x64.exe` from the [latest release](https://github.com/KazboXIII/PixelGrabber-Installer/releases/latest). |
| 2 | Run it. Windows may warn that the installer is unsigned; choose **More info > Run anyway**. |
| 3 | Pixel Grabber starts in the system tray. Press Ctrl+Shift+2 to capture a region. |

Once installed, Pixel Grabber updates itself from [KazboXIII/PixelGrabber](https://github.com/KazboXIII/PixelGrabber/releases), which also has full release notes.

Each release includes `SHA256SUMS.txt` so you can check the download:

```powershell
Get-FileHash .\PixelGrabber-<version>-Setup-x64.exe -Algorithm SHA256
```

## Requirements

| Needs | Details |
|---|---|
| Windows | Windows 10 1809 or newer, or Windows 11 |
| Processor | Intel or AMD x64 |
| Runtime | .NET Framework 4.8 |
