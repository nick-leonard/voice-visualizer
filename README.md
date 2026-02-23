# Voice Visualizer Studio

A browser-based audio waveform visualizer built as a single HTML file. No dependencies, no build step, no server required. Drop it anywhere and it runs.

**[VIEW HERE](https://nick-leonard.github.io/voice-visualizer/)**

---

## What is this?

An interactive tool for designing how a user's voice looks as a waveform. Supports:

- **Live audio file playback** (MP3, WAV, OGG, M4A, FLAC) with real-time frequency analysis via Web Audio API
- **Live microphone input** — visualizes your voice in real time
- **Demo mode** — animated sine wave when no audio source is active
- **4 wave modes** — Bars, Wave, Mirror, Radial
- **Full visual controls** — color, glow, fill, smoothness, amplitude, bar count, rounding, speed
- **7 color presets** including Love is Blind brand palette
- **Mobile phone mockup preview** — see exactly how it looks on a vertical screen
- **Clip recording** — capture a `.webm` video of the visualizer directly in the browser

*Everything lives in one file. No npm, no webpack, no framework.*

---

## Converting .webm → MP4

Because this is a one file app w/ no backend, it can only record video in ```.webm``` format. To convert this to a more common, widely-supported format (like ```.mp4```), use onoe of the options below

### Option 1 — FFmpeg (free, command line, best quality)

```bash
ffmpeg -i wave-clip.webm -c:v libx264 -c:a aac output.mp4
```
Install via ffmpeg.org or ```brew install ffmpeg``` on Mac.


### Option 2 — Online converters (no install)

- [cloudconvert.com](https://cloudconvert.com) — reliable, handles large files
- [ezgif.com/video-to-mp4](https://ezgif.com/video-to-mp4) — simple, free
- [freeconvert.com](https://freeconvert.com)

### Option 3 — VLC (free desktop app)

1. Open VLC → Media → Convert/Save
2. Add your .webm file
3. Choose MP4/H.264 as output format
4. Click Start

### Option 4 — HandBrake (free, GUI)

Drag the .webm in, select MP4 preset, encode. Great if you want quality control.
