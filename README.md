# Raspberry Pi Camera (Static Viewer)

A single-file static page for viewing an MJPG stream (e.g., mjpg-streamer).

## Usage
- Serve this with GitHub Pages.
- Provide your stream URL via:
  - Query string: `?url=https://<your-ngrok>.ngrok-free.app/?action=stream`
  - Or paste it in the “Set stream URL” field (saved in LocalStorage).

> Your stream **must be HTTPS** because GitHub Pages is HTTPS and browsers block mixed content.

## Features
- Mobile-friendly dark UI
- FPS estimate and resolution readout
- Fullscreen
- Snapshot (PNG)
- Auto-reload on error
