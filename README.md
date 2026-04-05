# IconNova — Icon to Code Engine

From icons to code in seconds.

IconNova is a Figma plugin that transforms your icons into a clean, production-ready icon system.
Generate structured outputs ready for development — no manual work, no external tools.

## ✨ Features
- Scan icons from selection, frame, or entire page
- Convert icons into a structured `icons.json` file (with stable codepoints)
- Export per-icon SVG files
- Generate `icons.css` with `@font-face`
- Build TTF & WOFF fonts (when supported in your environment)
- Preview icons via a demo HTML file
- Import existing icon libraries using `icons.json`
- Smart grid for managing icons (search, edit metadata, manage codepoints)

## 🧩 Input Requirements
- Select vector layers or icon frames
- Non-vector layers are automatically ignored during processing

## 📦 Output
Export a ready-to-use ZIP package including:
- `icons.json` (structured icon manifest)
- SVG files (one per icon)
- `icons.css`
- Font files (`.ttf`, `.woff`) when supported
- `demo.html` preview file

## 🚀 How to Use
1. Select your icons (vector layers or frames)
2. Run IconNova from Figma plugins
3. Review and organize icons in the grid
4. Export your icon system as a ZIP file
5. Use the exported files directly in your project

## 🔒 Privacy
IconNova does not use any network access.  
All processing happens locally within Figma, and your data stays in your file and exported assets.

## ⚠️ Notes
- Font generation (TTF/WOFF) depends on environment support
- For best results, ensure icons are clean vector shapes

## 📄 License
MIT License (or specify your license)

## 🤝 Support
If you have feedback or issues, feel free to open an issue or reach out.

## 💡 About
IconNova is built to bridge the gap between design and development — helping teams create design system–ready icon workflows faster and more reliably.
