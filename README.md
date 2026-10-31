# Starmaze Studios Support

Help for **Crystal & Frosted Glass for Apple Music** on Stream Deck.

Most problems are solved in a minute with the fixes below. If yours isn't, we're happy to help.

## Requirements

- Apple Music app
- Windows 10 or 11, or a Mac with Apple Silicon (M1 or newer) on macOS 13 or newer
- Intel Macs are not supported. To check your Mac, open the Apple menu and choose About This Mac.

## Common fixes

**The keys show a plain gradient instead of my album art**
Start a song in Apple Music. The plugin shows a soft gradient while there's no cover.

**Windows: the keys control YouTube instead of Apple Music**
The keys follow what's playing. Press Play in Apple Music, or click into Apple Music while nothing is playing, and they switch back.

**Mac: the keys don't react**
Open System Settings → Privacy & Security → Automation and allow Stream Deck to control Music.

**The Now Playing key shows "Open"**
Apple Music is closed and nothing is playing. Press the key to open Apple Music.

**A playlist key shows a yellow warning triangle**
The key has no playlist name yet. Select the key in the Stream Deck app and type the name exactly as it appears in Apple Music.

**A playlist key doesn't start the playlist**
Check the spelling of the name. Keep Apple Music open and not minimised, then try again.

**Windows: the volume keys don't move Apple Music's slider**
That's expected. They change Apple Music's level in the Windows Volume Mixer, and the sound changes. Apple Music's own slider can't be reached from outside the app.

**Windows: Favourite or Repeat doesn't show the right state**
These need Apple Music set to English.

**Windows: Favourite doesn't show songs I favourited earlier**
Apple Music for Windows doesn't report favourites, so the key only remembers presses for the current song.

**Windows: Add to Playlist says "Mac only"**
Apple Music for Windows offers no way to do this from outside the app.

**Mac: Add to Playlist doesn't add a song**
Add the song to your library in Music first, then press the key again. Music may refuse streaming songs that aren't in your library yet.

**Anything else**
Quit the Stream Deck app fully and open it again. Closing the window isn't enough: quit it from the tray icon on Windows or the menu bar icon on Mac.

## Still stuck?

Send us an Email: starmazestudios@gmail.com

Please include your system, your Stream Deck model, what you pressed and what happened. The plugin's log file helps too. It holds error messages and may include playlist names:

- Windows: `%APPDATA%\Elgato\StreamDeck\Plugins\com.frostdeck.music.sdPlugin\logs`
- Mac: `~/Library/Application Support/com.elgato.StreamDeck/Plugins/com.frostdeck.music.sdPlugin/logs`

## Privacy

The plugin runs on your computer, needs no account, and collects and sends no data.
