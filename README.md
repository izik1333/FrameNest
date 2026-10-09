# FrameNest

A video player for local folders, Dropbox and MEGA, with hover previews, favorites, subtitles and fullscreen folder browsing. Previously called ReelFolder.

## Download the app

**[Download FrameNest for Windows or Mac](https://github.com/izik1333/FrameNest/releases/latest)**

The app downloads are in **Releases**.

- **Windows 10/11, 64-bit:** choose `FrameNest-Windows-Setup.zip`, extract everything, and run `Install-FrameNest.cmd`.
- **Mac, macOS 13 Ventura or later:** choose `FrameNest-Mac-Setup.zip`, extract it, and open `Install-FrameNest.command`. The installer selects Apple silicon or Intel automatically.

Both setup ZIPs are under 1 MB. First setup downloads the video engine: about 158 MB on Windows or 130–135 MB on Mac. Local videos work offline afterward.

Windows installation and playback were tested. The Mac installer and updater still need testing on a Mac, and this personal build is not Apple-notarized.

## Controls

- Single-click a library thumbnail to open a video.
- Double-click the playing video to play/pause; a single player click does nothing.
- Click the mouse wheel or press Enter to toggle fullscreen.
- Space also plays/pauses; scrolling over the video changes volume.
- Use **CC** to select embedded subtitle tracks, load SRT/VTT files, and turn subtitles on or off.
- Hover thumbnails to preview; hold and drag to scrub without opening them.
- In fullscreen, hover the right edge for folders, the bottom for playback controls, and the top for Library/Folder buttons.

## Embedded subtitles — new in 1.3.1

MKV text tracks appear in the CC menu with their names and languages. Embedded SRT, ASS/SSA and WebVTT are supported, including on-demand cloud reads. ASS/SSA captions display as plain text. PGS/VobSub image subtitles are listed as unsupported.

Opening a folder does not scan subtitle contents or download the videos. After you open a video, subtitle reads use a bounded memory cache and do not save a second video file. Cloud links need byte-range support. Unusual, damaged or unindexed files may hit the read limit; you can still load an external SRT/VTT file. Automatic transcription is not included.

## Updates

Use **Settings → Updates → Check for updates**, then **Install update & restart**. Your library and settings are preserved. New updates appear after we publish a release. Older ReelFolder versions need the new setup once to get this feature. The `.asar` and `reelfolder-update.json` release assets are used by the updater. For normal installation, choose the ZIP for your operating system.

## Formats

MP4 (H.264/AAC) and WebM are recommended; other extensions depend on their codecs. Cloud playback and previews require internet.
