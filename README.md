# Classroom Noise Meter

A privacy-friendly classroom sound visualizer and quiet-room challenge built with the Web Audio API.

## Features
- Live microphone sound visualization
- Relative sound level from 0–100
- Quiet / Good / Noisy / Very Noisy room states
- Live waveform
- Session average and peak levels
- Quiet-time percentage
- Recent sound timeline
- Configurable Quiet Classroom Challenge
- Responsive mobile interface
- Audio is processed locally in the browser and is not uploaded or recorded

> The displayed value is a relative microphone level. It is **not** a calibrated physical decibel (dB) measurement; microphone hardware and browser processing vary between devices.

## Browser permission
The app requires microphone permission. Use HTTPS (the deployed site does) and tap **Allow** when your browser requests microphone access.

## Live Demo
🌐 https://classroom-noise-meter-ashoka.onrender.com


## Version history
- V1 — Core: live relative sound meter, waveform, statistics and quiet challenge.
- V2 — Reporting: downloadable session/settings snapshot.
- V3 — Recovery: versioned JSON backup/restore for persisted local settings plus session report metadata.

**Current version: V3**

V3 adds in-app **Backup** and **Restore** controls using portable JSON snapshots of this app's local browser state.
