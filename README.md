# CKRecorder

A WoW arena recorder and analyser: it records your arena games, reads the combat log on your own PC, and shows each match with a timeline,
death recaps, a post-game review and rotation analysis. Nothing is uploaded anywhere.

## Install

1. Download `CKRecorder-Setup-<version>.exe` from the newest release on the [Releases](../../releases) page.
2. Run it. Windows may say "Windows protected your PC": click **More info**, then **Run anyway** (the installer is not code-signed).
   It installs for your Windows user only. No admin rights are needed.
3. In CKRecorder open **Settings** and click **Install addon**. If WoW is not found, click **Choose…** next to the WoW folder first.
4. Play arena. Games and videos show up after each match.

## Updates

CKRecorder checks this page for a new version a minute after it starts and every few hours, but never during a match. A new version
downloads in the background and installs when you close CKRecorder, or straight away with **Settings > Updates > Restart and update**.

## Source

CKRecorder is a fork of ArenaCoach, under GPL-2.0-or-later. The full source code ships inside the app, in
`%LOCALAPPDATA%\Programs\CKRecorder\resources\app` (plain JavaScript).
