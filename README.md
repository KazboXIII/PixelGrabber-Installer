# Pixel Grabber Installer

Windows installer downloads for **Pixel Grabber**, a screenshot, color and reference tool for graphic designers.

**[Download the latest installer](https://github.com/KazboXIII/PixelGrabber-Installer/releases/latest)**

1. Download `PixelGrabber-<version>-Setup-x64.exe` from the latest release.
2. Run it. Windows may warn that the installer is unsigned; choose **More info > Run anyway**.
3. Pixel Grabber starts in the system tray. Press Ctrl+Shift+2 to capture a region.

Requires Intel/AMD x64 Windows 10 1809 or newer / Windows 11 and .NET Framework 4.8.

Once installed, Pixel Grabber updates itself from [KazboXIII/PixelGrabber](https://github.com/KazboXIII/PixelGrabber/releases), which also has full release notes.

Each release includes `SHA256SUMS.txt` so you can check the download:

```powershell
Get-FileHash .\PixelGrabber-<version>-Setup-x64.exe -Algorithm SHA256
```
