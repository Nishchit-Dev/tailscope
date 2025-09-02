# TailwindX — Color Peek for Tailwind CSS

Peek Tailwind colors inline. TailwindX highlights `bg-*`, `text-*`, and `border-*` classes, shows a hover **color swatch + HEX**, updates the **status bar** with the active color, and adds a **Copy Color HEX** command. Works alongside the official Tailwind CSS IntelliSense.

<p align="center">
  <img src="images/demo.gif" alt="TailwindX demo" width="720"/>
</p>

## ✨ Features
- Inline highlight for Tailwind color utilities: `bg-*`, `text-*`, `border-*`
- Hover tooltip with a color **swatch** and **HEX** value
- Status bar shows the active class + HEX (tinted)
- Command: **Tailwind: Copy Color HEX**
- Theme-aware highlights (different tints for light/dark)
- Works in HTML, JSX/TSX, Vue, Svelte, and plaintext

> Uses Tailwind v3 default color palette (slate/gray/zinc/…/rose, shades 50–950).

## 🚀 Quick Start
1. Install **TailwindX** from the Marketplace (or “Install from VSIX…”).
2. Open an HTML/JSX/TSX/Vue/Svelte file and type:
   ```html
   class="bg-orange-400 text-blue-600 border-gray-200"
