# Time-Stamper

Stamps a date and time onto your photos, like old digital cameras used to do in the corner of every picture.

---

You know how photos from the early 2000s had that orange timestamp burned into the bottom-right corner? This recreates that. Upload your photos, and the app reads the original capture date from the EXIF data and draws it onto the image. Everything runs in the browser — nothing gets uploaded anywhere.

**[Try it here](https://zaidalhourani.github.io/Time-Stamper/)**

---

## What you can customise

**Timestamp**
- Source: EXIF date (when the photo was actually taken), file modified date, or current time
- Format: DD/MM/YY, MM/DD/YY, or ISO (YYYY-MM-DD)

**Look**
- Font: VT323, Share Tech Mono, Press Start 2P, Orbitron, or plain monospace
- Colour, size, opacity, and position (any corner)
- Optional outline, drop shadow, and background box for readability

**Output**
- PNG or JPEG, or keep the same format as the original
- Download individually or grab everything as a ZIP

---

## How to use it

1. Open the [live demo](https://zaidalhourani.github.io/Time-Stamper/)
2. Drop in your photos
3. Adjust the settings if you want
4. Hit **Process** and download

No install, no account, no uploads.

---

## Tech

- Vanilla JS + HTML Canvas for image processing
- [ExifReader](https://github.com/mattiasw/ExifReader) to pull capture dates from photo metadata
- [JSZip](https://stuk.github.io/jszip/) for batch ZIP downloads
- Google Fonts for the retro typefaces

---

## Why I built it

I wanted to add timestamps to a batch of old scanned photos but every tool I found either watermarked the output, required an account, or was some sketchy desktop app. So I built a simple browser tool that does exactly one thing without any friction.
