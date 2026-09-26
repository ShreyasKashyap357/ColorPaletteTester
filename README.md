# Color Palette Tester

**Live demo:** [https://ShreyasKashyap357.github.io/ColorPaletteTester/](https://ShreyasKashyap357.github.io/ColorPaletteTester/)

A free, browser-based tool to design, import, tweak, and preview **light + dark color palettes** for apps and websites.  
Single HTML file • No build step • Works offline after first load

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/demo-live-brightgreen)](https://YOUR_USERNAME.github.io/ColorPaletteTester/)

---

## Features

- **Live color editor** for all common design tokens  
  Primary & Secondary accents, Success, Warning, Error, Background, Surface, Text Primary/Secondary, Borders
- **Flexible import** (order doesn’t matter):
  - Markdown tables
  - CSS custom properties (`--primary: #2563EB`)
  - JSON objects
  - Key–value pairs / CSV-style text
  - File upload (`.txt`, `.md`, `.css`, `.json`, `.csv`, `.tsv`)
- **Realistic preview** — hero, cards, badges, alerts, forms, and buttons
- **Light / Dark mode toggle** with Lucide sun & moon icons
- **Smart contrast** — button and icon text automatically switches between black/white based on the accent’s luminance so nothing becomes invisible
- Fully client-side — no backend, no accounts, no tracking

---

## How to Use

1. **Import (optional)**  
   Paste a markdown table, CSS variables, JSON, or any key–value text into the Import box → click **Parse & Apply**.  
   Or upload a file.

2. **Tweak**  
   Use the color pickers or type hex values for every Light and Dark token.

3. **Preview**  
   Click **View Preview**. Use the sun/moon icon in the top-right to switch themes.

4. **Iterate**  
   Click the back arrow to return to the editor and keep refining.

### Example import (markdown table)

```text
| Token              | Light Mode  | Dark Mode |
| Primary Accent     | #2563EB     | #60A5FA   |
| Secondary Accent   | #7C3AED     | #A78BFA   |
| Success            | #059669     | #34D399   |
| Warning            | #D97706     | #FBBF24   |
| Error              | #DC2626     | #F87171   |
| Background Base    | #EEF2FF     | #0B1120   |
| Surface / Cards    | #FFFFFF     | #1E293B   |
| Text Primary       | #0F172A     | #F8FAFC   |
| Text Secondary     | #475569     | #94A3B8   |
| Borders & Dividers | #C7D2FE     | #475569   |
```

Other formats that work:

```css
--primary: #2563EB;
--dark-primary: #60A5FA;
```

```json
{ "primary": "#2563EB", "dark-primary": "#60A5FA" }
```

```text
primary: #2563EB
dark primary #60A5FA
Background Base #E0E7FF #0B1120
```

---

## Supported Tokens

| Token              | Light default | Dark default |
|--------------------|---------------|--------------|
| Primary Accent     | `#2563EB`     | `#60A5FA`    |
| Secondary Accent   | `#7C3AED`     | `#A78BFA`    |
| Success            | `#059669`     | `#34D399`    |
| Warning            | `#D97706`     | `#FBBF24`    |
| Error              | `#DC2626`     | `#F87171`    |
| Background Base    | `#EEF2FF`     | `#0B1120`    |
| Surface / Cards    | `#FFFFFF`     | `#1E293B`    |
| Text Primary       | `#0F172A`     | `#F8FAFC`    |
| Text Secondary     | `#475569`     | `#94A3B8`    |
| Borders & Dividers | `#C7D2FE`     | `#475569`    |

---

## Tech Stack

- Single HTML file (vanilla JavaScript + CSS)
- [Lucide](https://lucide.dev) icons (CDN)
- No build tools, no npm, no frameworks

---

## Contributing

Issues and pull requests are welcome.  
Feel free to open an issue if you find a bug or have a suggestion for new tokens / import formats.

---

## License

This project is licensed under the [MIT License](LICENSE).  
You are free to use, modify, and distribute it.
