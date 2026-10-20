# D4 Builder

**English** · [한국어](README.ko.md)

Paste a Diablo IV build link and D4 Builder shows, right on top of the game window, which skill and which Paragon node to take next. It recognises what you have already allocated and moves to the next step on its own.

This repository hosts the **downloads and release notes** only. It contains no source code.

- Website: https://d4bd.trenddigestnews.com
- Top builds today: https://d4bd.trenddigestnews.com/builds/
- **Download:** [latest release](https://github.com/leeyc09/d4-builder/releases/latest)

## Features

- **Skill tree guide** — a yellow box marks the node for this step; nodes you have taken get a green check.
- **Paragon guide** — boards, rotation and the gate to attach to, node order, off-screen arrows, legendary nodes.
- **New board guide** — a card shows which board to attach and how to rotate it; in the in-game preview it tells you whether you picked the right board.
- **Auto-advance** — reads the game screen and moves to the next step when the current one is done.
- **Gear checklist** and a **status panel** (permissions, game window, recognition).
- **Build sources:** Maxroll · Mobalytics · D4Builds · InfinityBuilds · D2Core.
- Korean and English.

## Requirements

| | |
|---|---|
| OS | macOS 14 or later, Apple Silicon (Intel Macs untested) |
| Game | Diablo IV in **windowed** mode (e.g. through CrossOver) — macOS full-screen hides the overlay |
| Permission | Screen Recording (System Settings → Privacy & Security → Screen Recording) |

## Install

1. Download `D4-Builder-<version>-mac.dmg` from [Releases](https://github.com/leeyc09/d4-builder/releases/latest), open it and drag **D4 Builder** into **Applications**. Eject the dmg and launch the app from Applications (not from inside the dmg).
2. **First launch — macOS asks twice.** The app is self-signed (not notarized by Apple), so:
   1. Open **D4 Builder**. macOS says it can't verify the app — click **Done** (do not move it to the Trash).
   2. Go to **System Settings → Privacy & Security**, scroll down to the D4 Builder message and click **Open Anyway**, then enter your Mac password.
   3. Open **D4 Builder** again. A second dialog appears — click **Open Anyway** once more (and enter your password if asked).

   This is needed only once per downloaded version.
3. **Keychain prompt.** When the app starts it may ask: *"D4 Builder wants to use your confidential information stored in "D4 Builder" in your keychain."* This is the app reading its own saved connection key. Enter your Mac login password and click **Always Allow** so it doesn't ask again.
4. Allow **Screen Recording** when asked (System Settings → Privacy & Security → Screen & System Audio Recording → turn on D4 Builder), then quit and reopen the app.
5. D4 Builder lives in the menu bar (no Dock icon). Click its icon to open the window.
6. **Link the app:** sign up for free at https://d4bd.trenddigestnews.com/account/ (Google, email link or Battle.net), create an **app connection key**, and paste it into the app's **Settings → Account**. The overlay needs a linked key; importing builds and browsing steps work without one.

To verify a download: `shasum -a 256 D4-Builder-<version>-mac.dmg` and compare with the `.sha256` file attached to the release.

## Updates

The app checks for new versions once a day and shows a "new version" chip with release notes. Download the new dmg from Releases and replace the app; your settings and permissions carry over.

## Safety

D4 Builder is **read-only**:

- It only reads the game window with standard macOS screen capture and draws on a click-through window.
- It never sends mouse or keyboard input, never reads game memory, never injects code or hooks into the game.
- It does not hide or disguise itself; it runs as "D4 Builder".

No third-party tool is risk-free. Using one is your own responsibility under Blizzard's Terms of Use.

## Feedback

Bug reports, ideas and questions: from v0.9.1, use **Send feedback…** in the app's menu-bar menu or https://d4bd.trenddigestnews.com/account/#feedback (sign-in required). Until then, an import error in the app can be reported with **Report this error**.

Privacy policy: https://d4bd.trenddigestnews.com/privacy/

## Disclaimer

D4 Builder is an unofficial fan tool, not affiliated with or endorsed by Blizzard Entertainment. Diablo IV © Blizzard Entertainment, Inc. Build data belongs to each source site; the app always links to the original guide.
