# Lura Studio V5 — Mobile Cockpit

A responsive LED blush-hat concept simulator for desktop browsers and iPhone.

## New mobile layout

When the iPhone is held vertically, the camera is **always on the left** and the settings are **always on the right**. The entire app fits in the visible browser viewport without page scrolling. To keep the sliders large enough to use, choose one of four right-side settings tabs:

- **Color:** Six color presets, hue, saturation and LED intensity
- **Light:** Face coverage, feathering, light width, downward reach, and diffusion
- **Hat:** Virtual hat sizing and brim tilt
- **Motion:** Breathing/pulsing animation and speed

The left panel has the Face/Wearer views, Hide/Show hat, Single/Compare (before and after), camera enable and save image buttons. The small `% Units` switch at the top right toggles approximate real-world unit labels (RGB, lumens, centimeters and degrees).

The desktop layout is unchanged, with full-size sliders. iPhone portrait orientation is recommended for the no-scroll two-column layout.

## Run locally with VS Code

1. Open the folder in VS Code.
2. Right-click `index.html` and choose **Open with Live Server**.
3. Allow camera access in your browser. On iPhone use an HTTPS URL, such as a published GitHub Pages site.

Or run `python3 -m http.server 8000` and open `http://localhost:8000` on the same computer.

## Notes

The face tracker loads its AI model when the camera is enabled, so initial internet access is required. The preview is a conceptual lighting simulation, not calibrated photometric equipment. The lumens and centimeter readouts are **illustrative estimates**, not measured properties of an actual Lura hat.
