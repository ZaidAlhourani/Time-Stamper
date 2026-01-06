# Time-Stamper

Stamps a date and time onto your photos, like old digital cameras used to. Upload your photos, the app reads the capture date from EXIF data and draws it onto the image. Everything runs in the browser — nothing gets uploaded anywhere.

**[Try it here](https://zaidalhourani.github.io/Time-Stamper/)**

---

## What you can customise

**Timestamp**
- Source: EXIF date, file modified date, or current time
- Format: DD/MM/YY, MM/DD/YY, or ISO (YYYY-MM-DD)

**Look**
- Font: VT323, Share Tech Mono, Press Start 2P, Orbitron, or plain monospace
- Colour, size, opacity, and position (any corner)
- Optional outline, drop shadow, and background box

**Output**
- PNG or JPEG, or keep the same format as the original
- Download individually or grab everything as a ZIP

---

## How to use it

1. Open the [live demo](https://zaidalhourani.github.io/Time-Stamper/)
2. Drop in your photos
3. Adjust the settings
4. Hit **Process** and download

No install, no account, no uploads.

---

## Tech

- Vanilla JS + HTML Canvas
- [ExifReader](https://github.com/mattiasw/ExifReader) for reading photo metadata
- [JSZip](https://stuk.github.io/jszip/) for batch ZIP downloads
- Google Fonts for the retro typefaces
