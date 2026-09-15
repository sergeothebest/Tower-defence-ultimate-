# Ultra Tower Defense audio assets

The game looks for these optional files in this folder:

- `button.wav`
- `tower-attack.wav`
- `explosion.wav`
- `enemy-death.wav`
- `wave-start.wav`
- `boss-warning.wav`
- `victory.wav`
- `defeat.wav`
- `battle-music.mp3` (looping)

All files are optional. If an asset is unavailable or cannot be decoded, the game silently uses its lightweight Web Audio fallback and keeps gameplay running. Keep effects short and normalized; the music file should be a loop.
