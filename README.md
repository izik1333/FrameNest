# FrameNest

A video player for local folders, Dropbox and MEGA, with hover previews, favorites, subtitles and fullscreen folder browsing. Previously called ReelFolder.

## Download the app

**[Download FrameNest for Windows or Mac](https://github.com/izik1333/FrameNest/releases/latest)**

The app downloads are in **Releases**, not in the green Code download.

- **Windows 10/11, 64-bit:** choose `FrameNest-Windows-Setup.zip`, extract everything, and run `Install-FrameNest.cmd`.
- **Mac, macOS 13 Ventura or later:** choose `FrameNest-Mac-Setup.zip`, extract it, and open `Install-FrameNest.command`. Apple silicon and Intel Macs are supported by the installer.

Both setup ZIPs are under 1 MB. First setup downloads the video engine: about 158 MB on Windows or 130–135 MB on Mac. Local videos work offline afterward.

Windows installation and playback were tested. The Mac installer and updater still need testing on a Mac, and this personal build is not Apple-notarized.

## Controls

- Single-click a library thumbnail to open a video.
- Double-click the playing video to play/pause; a single player click does nothing.
- Click the mouse wheel or press Enter to toggle fullscreen.
- Space also plays/pauses; scrolling over the video changes volume.
- Use CC to load SRT/VTT subtitles and turn them on or off.
- Hover thumbnails to preview; hold and drag to scrub without opening them.
- In fullscreen, hover the right edge for folders, the bottom for playback controls, and the top for Library/Folder buttons.

## Updates

Use **Settings → Updates → Check for updates**, then **Install update & restart**. Your library and settings are preserved. New updates appear after we publish a release. Older ReelFolder versions need the new setup once to get this feature.

The `.asar` and `reelfolder-update.json` release assets are used by the updater. For normal installation, choose the ZIP for your operating system.

## Notes

Subtitles use SRT/VTT files; automatic transcription and embedded MKV subtitle extraction are not included. MP4 (H.264/AAC) and WebM are recommended; other extensions depend on their codecs. Cloud playback and previews require internet.
