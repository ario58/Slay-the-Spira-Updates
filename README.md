# Slay the Spira (releases)

Downloads and automatic updates for Slay the Spira, a private, non-commercial fan project for friends. This repository holds no
source code and no Final Fantasy X data: only signed release manifests, update packages and the Windows download.

## Install (once)

1. Open [Releases](https://github.com/ario58/Slay-the-Spira-Updates/releases) and download `Slay-the-Spira-<version>-win64.zip` from
   the newest release (any release's ZIP works: it updates itself on its first start).
2. Unzip the whole `Slay the Spira` folder somewhere you can write (not Program Files), e.g. `D:\Games\Slay the Spira`.
3. Double-click `Slay the Spira.exe`. If Windows says "Windows protected your PC": More info > Run anyway (the program is not
   code-signed).

## Updates

Automatic: every start checks this repository, downloads only what changed, checks the developer's signature, and starts the new
version. Profiles, saves and settings (`%APPDATA%\Godot\app_userdata\Slay the Spira`) are never touched.

The other files in each release (`release-manifest.json`, `spira-*.zip`) are what the game downloads; you don't need them.
