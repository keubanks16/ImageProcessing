# GS Photo Lab

GS Baseball's browser-based photo enhancer. Drop in photos one at a time, a whole folder, or a ZIP, and every image is automatically corrected. Fine-tune anything, then save single photos or download everything as a ZIP.

Everything runs on your device (canvas + a Web Worker). No photos are uploaded anywhere.

## Features

- **Input:** individual photos, multiple selection, folders, ZIP files (nested folders inside the ZIP are fine), drag-and-drop, or paste.
- **Auto-enhance (per photo):** auto levels, gray-world white balance, exposure/gamma to a target brightness, plus suggested shadow lift, highlight recovery, contrast, vibrance, clarity and sharpening based on each photo's histogram and sharpness.
- **Manual controls:** auto strength, exposure, brightness, contrast, highlights, shadows, saturation, vibrance, warmth, tint, clarity, sharpen, noise reduction (edge-aware), and blur.
- **Before/after:** drag across the photo to compare.
- **Use on all photos:** copy one photo's settings to the rest (auto levels still adapt to each photo).
- **Export:** full resolution (up to 8192 px), as the original format, JPEG, PNG or WebP with adjustable quality. Download one, all as ZIP, or Share / Save to Photos on phones.

## Hosting

It's a single static `index.html`. Turn on GitHub Pages: **Settings → Pages → Source: Deploy from a branch → `main` / root**. The site will be at `https://keubanks16.github.io/ImageProcessing/`.

HEIC photos open in Safari; other browsers may not decode HEIC (convert first, or use Safari).
