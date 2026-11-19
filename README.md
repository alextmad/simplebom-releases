# SimpleBOM

SimpleBOM is a Windows desktop app for building and managing bills of materials efficiently. It works offline on your own computer.

This repository holds the downloads and these pages. The source code is private.

> **SimpleBOM is in early access.** Updates bring fixes often. When you save, a file made by an older version may be upgraded to the new format, and SimpleBOM keeps a recovery copy of unsaved work.

This page covers everything you need: install, your key, reporting a problem and updating.

## Install

1. Open the [latest release](https://github.com/alextmad/simplebom-releases/releases/latest).
2. Under **Assets**, download `SimpleBOM_..._x64-setup.exe`.
3. Run it. It installs for your Windows account only and does not ask for administrator rights.

### Windows may warn you

SimpleBOM isn't signed yet, so Windows may warn you, and may do so again after an update.

Your browser may warn that the file is not commonly downloaded. Choose to keep the file.

If you see **Windows protected your PC**, choose **More info**, then **Run anyway**.

If Windows blocks SimpleBOM and offers no **Run anyway**, Smart App Control is probably on (on a work PC, ask your IT team). It can't make an exception for one app, and the portable zip is treated the same. To use SimpleBOM, turn it off in **Windows Security > App & browser control > Smart App Control settings**. On an up-to-date Windows 11 you can turn it back on there later. If you are unsure, ask the person who invited you first.

Sometimes there is no warning at all. That is fine.

## The portable zip

If you would rather not install, download `SimpleBOM_..._x64_portable.zip` from the same release. It holds one file, `SimpleBOM.exe`. Unzip it anywhere and run it. Windows may show the same warnings as above. A portable copy does not open `.sbom` files when you double-click them. Start SimpleBOM first, then use **File > Open**.

A portable copy never updates itself. When a newer version is out, the top bar shows **Download {version}**. Pressing it opens the release page, where you download the new zip or the installer.

## Your key

SimpleBOM needs a personal key from the developer. The first time you start SimpleBOM it asks for it: paste it into **Paste your SimpleBOM key** and choose **Use this key**. You only do this once. The key is saved on your computer. It also goes with each problem report so the report can be checked. To swap it later, choose **Change key** in **Help > About**.

If you cannot find your key, ask the person who invited you.

The key is yours alone. If a key is passed around, the developer can switch it off. SimpleBOM then says **This key is no longer valid**, asks for a new one and lets you save the project you have open. A switched-off key reaches your copy when SimpleBOM hears of it through an update.

## Report a problem

Issues are switched off here. Report from inside SimpleBOM with **Help > Report a problem** or the bug icon in the top bar. The dialog shows what will be sent before you press **Send**, and [PRIVACY.md](PRIVACY.md) explains it in full.

If a report cannot be sent, SimpleBOM keeps it and tries again the next time it starts. If it is turned down, SimpleBOM tells you and keeps the saved copy.

Security problems go through the private route in [SECURITY.md](SECURITY.md), never through a public report.

## Update

SimpleBOM checks for updates only if you say **Yes** when it first asks; you can change that in **File > Settings**. **Help > Check for updates** checks at any time. When a newer version is out, a button in the top bar downloads and installs it, after asking you to save any unsaved work.

## More

- [PRIVACY.md](PRIVACY.md): what a report sends, where it goes, how long it is kept.
- [SECURITY.md](SECURITY.md): how to report a security problem.
