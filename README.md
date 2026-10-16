# PDC ArchAI — Releases

Windows installers for **PDC ArchAI**: architectural drawings to material take-off, 3D renderings,
construction drawings and trade bid packages.

**Download:** see [Releases](https://github.com/patelhardik/PDCArchAI_Releases/releases/latest).

## Install

1. Download `PDC-ArchAI-Setup-<version>.exe` and run it (Windows 10 or 11, 64-bit).
2. Windows may show *"Windows protected your PC"* because the installer is not code-signed yet:
   click **More info → Run anyway**.
3. Keep the PC online during the install: the optional DWG support and photoreal renderer
   (Blender, ~400 MB) are downloaded while installing. No administrator rights are needed.
4. Start **PDC ArchAI** from the desktop or Start menu. It opens in your browser; keep its window
   open while you work. Demo projects are ready on the Projects page.

Silent install for IT: `PDC-ArchAI-Setup-<version>.exe /S` (add `/NODOWNLOADS` to skip Blender and DWG support).

Projects are stored in `%LOCALAPPDATA%\PDC ArchAI`; uninstall from Windows Settings → Apps.
