# Markitha
# PDF Reader with Highlights & Notes
https://nikithaprojects.github.io/Markitha/
A browser-based PDF reader that lets you highlight text and auto-save it as bullet-point notes — no backend or installation needed.

## How to Use

1. Open `index.html` in any modern browser (Chrome, Edge, Firefox, Safari).
2. Click **Open PDF** or drag & drop a PDF file onto the reader.
3. **Select any text** on the page — it gets highlighted and instantly added as a bullet point in the Notes panel.
4. Choose a **highlight color** (yellow, green, pink, blue) from the toolbar.
5. Use **Prev / Next** buttons to navigate between pages.
6. Click **Export notes as .txt** to download all your notes.

## Features

- Renders all pages of any PDF
- Text selection highlights the canvas in your chosen color
- Notes panel shows all highlights as bullet points with page numbers
- Remove individual notes with the ✕ button
- Export notes as a plain text file
- Works 100% offline (uses pdf.js from CDN — internet needed for first load)

## Requirements

- A modern web browser (Chrome 90+, Edge 90+, Firefox 88+, Safari 14+)
- Internet connection on first open (to load pdf.js from CDN)

## Dependencies

- [PDF.js 3.11.174](https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.min.js) — Mozilla's open-source PDF renderer
