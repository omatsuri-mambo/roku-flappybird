# Flappy Roku

A tiny Flappy Bird-style Roku SceneGraph channel.

## Play

- Press `OK` or `Up` to flap.
- Fly through the pipe gaps to score.
- Press `OK` after a crash to restart.
- Press `Back` to leave the channel.

## Sideload

1. Zip the contents of this `roku-flappy` folder, not the folder itself.
2. Open your Roku device's developer installer in a browser.
3. Upload the zip and install it.

On PowerShell, from this folder:

```powershell
Compress-Archive -Path manifest,source,components -DestinationPath flappy-roku.zip -Force
```
