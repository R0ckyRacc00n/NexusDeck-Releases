# Nexus Deck for Windows

A Game Master workspace for scenes, music, layered ambience, maps and a player TV screen.

## First-steps guide

[Read in English](docs/GETTING-STARTED.md) · [Read in Ukrainian](docs/GETTING-STARTED-UA.md)

[Download the offline bilingual HTML guide](https://github.com/R0ckyRacc00n/NexusDeck-Releases/releases/download/v0.2.0-preview.18/NexusDeck-0.2.0-preview.18-Guide.html). Open it locally, switch languages and print or save to PDF. The same guide is bundled with the app: **Technical settings > First steps**. It covers installation, background operation, music, scenes, atmosphere, TV, maps, tools and backups. This edition contains written steps and a lifecycle diagram; fresh interface screenshots are still pending.

## Download and install

**[Download NexusDeck-0.2.0-preview.18-Setup.exe](https://github.com/R0ckyRacc00n/NexusDeck-Releases/releases/download/v0.2.0-preview.18/NexusDeck-0.2.0-preview.18-Setup.exe)**

[All versions and portable ZIP downloads](https://github.com/R0ckyRacc00n/NexusDeck-Releases/releases)

1. Download Setup.exe and run the English or Ukrainian installation wizard. The language selector appears on every interactive launch, including manual updates.
2. The default location is `%LOCALAPPDATA%\Programs\NexusDeck`. Administrator privileges, Python and manual ZIP extraction are not required.
3. Open Nexus Deck from the Start menu or desktop shortcut.

Alternatively, download the Windows ZIP, extract the entire folder and run `NexusDeck.exe`. Keep its `_internal` folder alongside it. The installer and portable ZIP contain the same application and all 11 base ambience sounds.

The installer is not yet code-signed; Windows may show an unknown publisher notice.

## Updating

From preview.10 or later: open **Technical settings > Nexus Deck updates > Check for updates > Download update > Install and restart**. From preview.11, the deck also checks in the background at startup and announces newer versions. Downloads do not interrupt play; install between sessions.

You can also close the deck and run a newer Setup.exe. It updates program files in the existing installation folder. The installer asks you to close a running deck rather than forcibly ending your game.

## Your table data

Scenes, sounds, configuration and the prepared Chrome extension are kept separately. The default table is `%LOCALAPPDATA%\NexusDeck\Tables\default`. Keep any custom table folder. Back up your table as a ZIP from the app before moving it to another computer.

If your old portable installation used a `data` subfolder, or a custom shortcut supplied `--data`, first open the old deck and select that same folder through **Technical settings > Table data folder**. Close the old deck before opening the newly installed program. No table files need to be moved or deleted.

Uninstalling Nexus Deck through Windows Installed apps removes installed program files and shortcuts, while leaving table data in place.

## YouTube Music and TV

For YouTube Music, prepare the Chrome extension in Technical settings, then load that prepared folder through `chrome://extensions` > Developer mode > Load unpacked. Keep the prepared folder on disk. You do not need to reinstall the extension when updating Nexus Deck.

For a player screen, open TV view, move the browser to the HDMI-connected display and use fullscreen.

Nexus Deck runs in the background without terminal windows. Closing a browser tab does not quit the app; use its system tray icon or Technical settings to quit.

This repository contains binary releases and documentation only. Source code, personal scenes and configuration remain private. A GitHub account is not needed to download the application.


Music extension update: preview.18 fixes scene track lookup and uses extension **0.1.2**. Prepare the extension files in Technical settings, reload Nexus Deck at `chrome://extensions`, refresh YouTube Music and choose **Connect this tab**. Keep the existing extension folder and local key.
