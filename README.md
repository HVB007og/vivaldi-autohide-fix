# Vivaldi Autohide Address Bar Fix

A CSS mod for Vivaldi that provides a smooth, auto-hiding address bar without "dead zones" in hover detection.

## Features
- **Smooth Animation:** Address bar slides down when hovering over the tab bar or the bar itself.
- **No Dead Zones:** Fixed issues where "drag regions" in the hidden address bar would block hover detection on the tab bar.
- **Layer Management:** Ensures tabs remain accessible and the address bar appears correctly over the web content.

## Installation
1. Open Vivaldi and go to `vivaldi://experiments`.
2. Enable "Allow for CSS modifications".
3. Open Vivaldi Settings -> Appearance.
4. Under "Custom UI Modifications", select the folder containing `fix-autohide.css`.
5. Restart Vivaldi.

## Configuration
The default tab height is set to `31px`. If you use a different tab height or UI scale, you may need to adjust the `top` and `translateY` values in the CSS file.
