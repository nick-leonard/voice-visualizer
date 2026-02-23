# Wave Designer — Voice Visualizer Studio

A browser-based audio waveform visualizer built as a single HTML file. No dependencies, no build step, no server required. Drop it anywhere and it runs.

---

## What this is

An interactive tool for designing how a user's voice looks as a waveform. Supports:

- **Live audio file playback** (MP3, WAV, OGG, M4A, FLAC) with real-time frequency analysis via Web Audio API
- **Live microphone input** — visualizes your voice in real time
- **Demo mode** — animated sine wave when no audio source is active
- **4 wave modes** — Bars, Wave, Mirror, Radial
- **Full visual controls** — color, glow, fill, smoothness, amplitude, bar count, rounding, speed
- **7 color presets** including Love is Blind brand palette
- **Mobile phone mockup preview** — see exactly how it looks on a vertical screen
- **Clip recording** — capture a `.webm` video of the visualizer directly in the browser

---

## File structure

```
/
├── index.html       # The entire app (rename equalizer-mockup.html → index.html)
└── CLAUDE.md        # This file
```

Everything lives in one file. No npm, no webpack, no framework.


