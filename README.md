<p align="center">
  <img src="https://it-community.online/assets/logo.png" alt="IT-Community" width="96">
</p>

<h1 align="center">Juntas — IT-Community</h1>

<p align="center">The homeowners' meeting app of the IT-Community ecosystem.<br>Meeting calls, documentation and access to your community's portal — on Android, iOS, Windows and macOS.</p>

<p align="center">
  <a href="https://it-community.online"><img src="https://img.shields.io/badge/website-it--community.online-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/juntas-it-community-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/juntas-it-community-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-Android%20%C2%B7%20iOS%20%C2%B7%20Windows%20%C2%B7%20macOS-black" alt="platforms">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <strong>🇬🇧 English</strong> · <a href="README.de.md">🇩🇪 Deutsch</a> · <a href="README.fr.md">🇫🇷 Français</a> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **This repository publishes official binary releases only** — the source code is private. Signed downloads, checksums and auto-update feeds.

## Download

| | |
|---|---|
| 📥 **macOS** | [Juntas-<version>.dmg](https://github.com/mavksoft/juntas-it-community-releases/releases/latest) in every release |
| 📱 **Mobile** | Android & iOS — from the stores or via [it-community.online](https://it-community.online) |
| 🪟 **Windows** | Installer available in every release |
| 🌍 **Website** | [it-community.online](https://it-community.online) |

## What it is

Juntas is the assembly app of the IT-Community ecosystem: it connects to your homeowners' community portal to receive meeting calls, browse each assembly's documentation and follow your community's life from any device. This repository distributes the public binaries and auto-update feeds.

<p align="center"><img src="./screenshots/website.png" width="640" alt="screenshot"></p>

## Features

- **Portal connection** — the app links to your community's IT-Community portal via the `portals.json` directory.
- **Multi-platform** — builds for Android, iOS, Windows and macOS.
- **Auto-update** — `version.json` and `appcast.xml` feed the built-in updater.
- **Meeting documentation** — calls, minutes and attachments from the portal, on mobile and desktop.

## How to use it

1. Download the build for your platform from the latest release (or install the mobile app from your store).
2. Open the app and find your community in the portals directory.
3. Sign in with the credentials your property manager gave you.
4. Browse meeting calls, minutes and documentation for each assembly from the app.

## Requirements

Android, iOS, Windows 10+ or recent macOS · Requires an active IT-Community portal for your community (managed by your property manager).

## What's in this repository

- `Juntas-<version>.dmg` — signed macOS installer
- `Juntas-<version>.zip` — packaged build / auto-update archive
- `version.json` — version feed for the app updater
- `appcast.xml` — Sparkle feed for macOS
- `portals.json` — directory of IT-Community portals consumed by the app
- Source code lives in the private repo `mavksoft/juntas-it-community`.

[Latest release](https://github.com/mavksoft/juntas-it-community-releases/releases/latest)

## FAQ

**Can I use the app if my community has no portal?**  
The app requires an active IT-Community portal — set up by your community's property manager.

**Where is the source code?**  
It's private software: this repository only publishes binaries and update feeds.

## Support

- Website: [it-community.online](https://it-community.online)
- Email: [hola@it-community.online](mailto:hola@it-community.online)

---
<p align="center"><sub>Juntas — IT-Community · © MavkSoft / IT-Systems</sub></p>
