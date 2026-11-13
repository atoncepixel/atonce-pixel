# Atonce Pixel

A bilingual (English/Bengali), responsive browser-based photo and PDF utility prototype.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser, or serve the folder with a local static server.
3. Internet is required for the PDF libraries loaded from CDN.

## Included working tools
- Image resize, compress, format conversion, crop, rotate/flip, basic adjustments
- Passport-photo print sheet (simple grid layout)
- Multiple images to PDF
- PDF pages to PNG, merge, extract selected pages, rotate, re-save/optimize

## Important limitations
- PDF compression is best-effort; re-saving does not guarantee a smaller file.
- Passport photo tool currently makes a simple print sheet; it does not automatically remove backgrounds or guarantee official photo compliance.
- Crop uses numeric coordinates rather than a drag-to-select crop frame.
- This is a front-end prototype. Add testing, accessibility, error handling, privacy notice, file-size limits, and deployment configuration before public launch.
- Third-party PDF libraries are loaded from public CDNs; for production, pin and self-host dependencies and review their licenses.

## Free static hosting
Suitable starting options include GitHub Pages, Netlify, or Cloudflare Pages. Upload the extracted folder as a static site.
