# CRAAIIGBORED

Web Audio API guitar pedalboard with overdrive, delay, looper, cabinet sim, MIDI learn, presets, output recording, and PWA install support.

Live app: [https://craaiigbored.vercel.app](https://craaiigbored.vercel.app)

## Features

- Live input via `getUserMedia` and the Web Audio API
- Overdrive, delay, looper, and synthetic cabinet simulation
- Oscilloscope, low-latency mode, and output recording
- MIDI learn mappings and browser `localStorage` presets
- Installable PWA for desktop and mobile

## Local Development

Serve the folder on `localhost` so microphone permissions and PWA features work correctly.

```bash
python3 -m http.server 8123
```

Then open [http://127.0.0.1:8123](http://127.0.0.1:8123).
