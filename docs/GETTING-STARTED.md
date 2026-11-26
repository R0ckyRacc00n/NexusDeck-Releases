# Nexus Deck — first steps

A short Game Master guide: from installation to your first session.

For version 0.2.0-preview.18

Start Nexus Deck → Control it in your browser → Show TV view to players

## 1. Install and launch

1. Download Setup.exe from the releases page. Choose English or Ukrainian in the wizard and install the application. Python and manual archive extraction are not required.
2. Open Nexus Deck from the Start menu or desktop shortcut. Its browser interface opens automatically. If it does not, open http://127.0.0.1:9878/ (the default address).
3. In the first-run dialog, name your table. Leave Lighting disabled unless your own lamps are configured. Save the settings.
4. Lighting and Google Drive setup are optional. Neither is required for your first scene.

> The portable ZIP is an alternative: extract the entire archive, keep _internal beside NexusDeck.exe and launch the EXE. Do not run it directly from the ZIP.

## 2. The deck runs in the background

1. The running application serves music, ambience and the GM and TV pages. The browser is its control window.
2. Closing the tab or browser does not quit Nexus Deck. Opening the shortcut again returns to the existing application.
3. Look for the Nexus Deck icon in the Windows system tray near the clock; it may be under the hidden-icons arrow. Its menu opens the deck, opens logs or quits the app.
4. After the session, quit through the tray menu or Technical settings (the wrench) > Application > Quit Nexus Deck.

> For YouTube Music, keep Chrome and the connected music tab open. Closing that tab disconnects the music player.

## 3. Find your tools


- **Scenes** — Prepared locations and moods: images or video, music and optional lighting. Clicking a card starts its configured scene components.
- **Maps and Drawing** — Private map preview, drawing, ruler, tokens, fog of war and temporary pointers.
- **Game Manager** — Encounters and active combat targets, monster library, story encounters, items and loot.
- **Wrench in the header** — Technical settings: lighting, music extension preparation, table folder, updates, logs and quitting.
- **Gear in the header** — Appearance: Fear tracker, scene descriptions and actions, background colors and sound-panel pinning.
- **Book in the header** — Session snapshots, ZIP backups, restore and Google Drive backups.
- **Right panel** — Effects are one-shot sounds. Atmosphere provides separate looping sound layers.
- **Bottom player** — Current music, seeking, pause, volume and a button to pause all audio.

> The edit button beside Open TV edits scenes. It is separate from Technical settings in the header.

## 4. Connect YouTube Music once

1. In Chrome, open music.youtube.com, sign in if needed and start a track.
2. In Nexus Deck, open Technical settings > YouTube Music > Prepare extension > Open folder. This prepared folder is the one Chrome needs.
3. Open chrome://extensions in Chrome. Enable Developer mode, choose Load unpacked and select the prepared folder.
4. While on the YouTube Music tab, open the Nexus Deck extension from the Chrome extensions menu and choose Connect this tab.
5. After the initial setup, quit and restart Nexus Deck. Keep Chrome and the music tab open.
6. Check the bottom player: the track title should appear, and pause and volume controls should work.

> Do not delete or share the prepared extension folder: it contains a key for this GM. Each GM prepares their own. Most deck updates do not require reinstalling it. If a release requires an extension refresh (for example 0.1.2), prepare its files, reload the extension at chrome://extensions, refresh YouTube Music and reconnect the tab.

## 5. Your first scene and sound

1. Open Scenes and enable editing using the button beside Open TV. Add a scene or edit a starter scene.
2. Set a name and description. Add an image or a YouTube video for the player display. Local videos require a browser-supported file format.
3. Add a playlist and/or individual track URLs. Both sources can form a combined queue with repeat. Private playlists may require separate local authorization; use a public or unlisted playlist for the first test.
4. Save the scene, leave edit mode and click its card. Where music preparation is configured, its preparation button lets you prepare before switching scenes.
5. Open Atmosphere on the right, start a layer and adjust its volume. Mix rain, wind or fire over music; each layer has independent pause and volume controls.
6. Use Effects for one-shot sounds. The bottom bar has a pause-all-audio button when you need to stop music, atmosphere and effects quickly.

> Edit an atmosphere layer to select another sound or upload your own. Deleting a layer leaves its audio file available. New tables include 11 disabled base layers.

## 6. Player display: HDMI and TV view

1. Connect a TV or second monitor through HDMI and choose Extend displays in Windows.
2. Choose Open TV, move the TV window to the player display and use its fullscreen button, F or a double-click.
3. Keep the GM page on your own display and control scenes there. TV view does not expose the GM settings or private notes.
4. Choose a scene, or use Show on TV for a prepared map. Check the actual player display before the session.
5. For video, use Now on TV: play/pause, seeking, skip backward/forward 10 seconds, restart and volume. Select the receiver if several TV windows are open.
6. Blackout TV temporarily hides the picture; Restore picture shows it again.

> Blackout does not pause video or audio. Browser autoplay rules may require one click in TV view to start video. The deck controls its own TV view, not direct YouTube Cast. YouTube may display startup elements or advertisements; use local video for a fully clean background.

## 7. Maps and drawing tools

1. Use Upload image or select a map from the left gallery. Favorites keep frequent images handy; Current session holds this table’s images.
2. The map first opens in a private preview. TV does not switch until you choose Show on TV.
3. Select a tool from the vertical rail beside the map. Its properties appear above the canvas; hover over buttons for tooltips.
4. Use the separate Zoom slider or ± buttons below the canvas. The curved arrow resets zoom and position. Toggle the grid separately.
5. Choose a token on the right and place it on the map. Player tokens have green borders, enemies red and allies blue. Change the role in the icon editor; tokens occupy one grid cell.
6. Select Fog of war to reveal enable, paint, erase, brush-size and cover-entire-map controls. Check the result in TV view before presenting it.

- **Hand** — Move the map view.
- **Pen / eraser** — Draw and erase strokes. Color and width are in the tool properties.
- **Ruler** — Measure distance. The ruler is visible on TV when that same map is displayed.
- **Pointer** — A brief pulsing marker that disappears automatically. A private map stays private; the pointer reaches TV only when that same map is already displayed.
- **Undo / redo** — Step through drawing history. These controls are separate from removing all tokens.

> Clear drawings and Clear all icons on the map are different actions. Create a session snapshot before clearing large amounts of work or restoring an older state.

## 8. Game Manager

1. Prepare adversary templates in the monster library. Add a monster to the arena for the current encounter and adjust its HP in the active combat targets.
2. Use story encounters for non-combat events. Items and loot tables help select rewards; check each table’s conditions before giving out a result.
3. Create a snapshot when preparing an encounter so you have a return point. Save lasting changes using the relevant editor’s Save button.

> Scenes, music and TV are enough for a first game. You can learn Game Manager gradually.

## 9. Data, backups and updates

1. The default table folder is %LOCALAPPDATA%\NexusDeck\Tables\default. Program files are in %LOCALAPPDATA%\Programs\NexusDeck. These are separate folders.
2. To use a custom folder, open Technical settings > Table data folder > Choose table folder. It applies after restarting; selecting a folder does not move the campaign.
3. Use the book button to save a session snapshot: a quick return point within this table. A snapshot does not replace an independent file backup.
4. Choose Create ZIP backup for a portable campaign backup with media. Keep another copy on a separate disk or device. Use Restore from ZIP when transferring to another PC and verify the selected file.
5. The deck checks for newer versions at startup. Downloading does not interrupt play; use Install and restart between sessions. Running a newer Setup.exe is another way to update.
6. Updating or uninstalling the installed app does not remove its table folder. Music authorization and lamp keys belong to the current GM and are not transferred like ordinary campaign files.

> An application ZIP and a campaign backup ZIP are different files. Do not use Restore from ZIP for an application build. Google Drive provides optional on-demand backups, not automatic synchronization of every change.

## 10. Before a session and troubleshooting

1. Start the deck and check that the correct table opened.
2. Check the YouTube Music connection in Chrome, then test pause and volume. A disconnected music player does not mean the deck itself is offline.
3. Open TV, show a test scene and check fullscreen, picture and audio from the player side.
4. Create a snapshot and a ZIP backup. Do not install an update in the middle of play.
5. After the session, quit through the tray icon or Technical settings.

- **No browser window** — Open the shortcut again or visit the default address http://127.0.0.1:9878/.
- **Music disconnected** — Open the correct YouTube Music tab and choose Connect this tab in the extension. Check the account and track availability.
- **TV did not change** — Check that TV view is open and that you chose Show on TV, rather than only opening a private preview.
- **An empty table after installation** — Keep the old files. Check the data path in the old shortcut and choose that same folder in Technical settings.
- **Need diagnostics** — Technical settings > Open logs. Default location: %LOCALAPPDATA%\NexusDeck\Logs. Review logs before sharing: they may contain local paths.

