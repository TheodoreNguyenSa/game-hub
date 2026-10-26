# Game Hub

Four classic games in one app, rebuilt for Android TV / Google TV.

Made by **Toan Nguyen In Oz** — free apps and content for the Vietnamese community in Australia.

![Game Hub](https://img.shields.io/badge/platform-Android%20TV%20%7C%20Google%20TV-green)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

## What is it?

One app, four games — pick a tile on the Hub and play. No account, no internet needed; the games run fully offline on the TV. Your best score for each game is saved on the TV.

## The four games

- **Minesweeper** — the classic Microsoft rules, exactly as in the standalone Minesweeper v1.0.0: 3 levels (Easy 9×9/10, Medium 16×16/40, Expert 30×16/99), first click is always safe, grey beveled grid, red LED mine counter, smiley face. Best time saved per level.
- **2048** — 4×4 board. Push a direction on the remote and the whole board slides; equal numbers merge. Reach the 2048 tile to win. A new tile appears after every slide; a full board with no merge ends the game.
- **Match-3** — 8×8 board of coloured gems. Pick a gem with OK, then push a direction to swap it with its neighbour. Line up 3 or more of the same colour to clear them; gems above fall down and new ones drop in. No time limit — a swap that makes no match swaps straight back.
- **Runner** — a stick figure runs on its own. Press OK to jump, hold OK to jump higher. Collect coins, dodge spikes and cacti; the run gets faster the further you go. One hit ends the run.

## Controls (remote only — DPAD + OK)

| Screen | Controls |
|---|---|
| Hub | DPAD chooses a game (UP from the top row reaches the Music / Buy me a coffee pills), OK plays, BACK exits the app |
| Minesweeper levels | ◀ ▶ choose level, OK starts, BACK returns to the Hub |
| Minesweeper game | DPAD moves, OK reveals, **hold OK 0.5s to place/remove a flag**, UP from the top row focuses the smiley (OK = new game), BACK returns to levels |
| 2048 | DPAD slides the board, BACK returns to the Hub |
| Match-3 | DPAD moves the cursor, OK picks a gem, DPAD swaps the picked gem, BACK returns to the Hub |
| Runner | OK jumps, hold OK jumps higher, BACK returns to the Hub |

Every screen also has **Music: On/Off** (or the MUTE key on the remote) and a **"Buy me a coffee"** button — it shows a QR code to scan with your phone; OK on the QR screen still opens the support page in the browser.

## Auto-update

The app checks GitHub once a day when you open it, and asks before downloading a new version — it never updates without asking. (The update check is against the `TheodoreNguyenSa/game-hub` repo; until that repo has a release, the check quietly does nothing.)

## Install on your TV

The app is a standard Android TV APK. Pick the easiest method:

### Option A — Downloader (AFTVnews)
1. Install **Downloader** from the Play Store (Android TV / Google TV) or Amazon Appstore (Fire TV).
2. Open Downloader and enter the APK link from the latest release below.
3. Tap **Go** to download, then **Install** (allow "Install unknown apps" for Downloader if asked).

### Option B — Send Files to TV
1. Install **Send Files to TV** on your TV and on your phone.
2. Send the APK file from your phone to the TV, then open it with a file manager and tap **Install**.

### Option C — USB
1. Copy the APK onto a USB drive (FAT32).
2. Plug it into the TV, open a file manager, tap the APK and install.

Requires Android 5.0+ (Android TV / Google TV). The app appears as **Game Hub** in your apps. It is a separate app — the standalone Minesweeper app is untouched and keeps working.

## Download

Get the APK from the latest release on the [Releases](../../releases) page.

## Support the project

Game Hub is free and always will be. If you enjoy it, you can support the developer here:

☕ [Buy me a coffee](https://buymeacoffee.com/toannguyeninoz)

Or send directly via PayPal: [paypal.me/ToanNguyen189](https://www.paypal.me/ToanNguyen189)

Your support keeps the apps free and funds new ones.

## Changelog

### v1.0.0 (26 Oct 2026)
- First public version: Hub with 4 games (Minesweeper, 2048, Match-3, Runner), best score per game saved on the TV, music + MUTE, Buy Me a Coffee QR overlay, auto-update check
