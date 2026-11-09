# PDF Inspector Gadget

A minimalist, modern dark PDF reader for mobile and desktop. Open local PDF files directly in your browser—no account, editing tools, or document uploads.

## Features
- Open a local PDF
- Scroll through pages continuously
- Fit-width and zoom controls
- Find text and jump to the matching page
- Responsive dark interface
- Installable web app manifest

## Technology
Vanilla HTML, CSS and JavaScript, using Mozilla PDF.js loaded from cdnjs. PDF files are processed locally in the browser. An internet connection is currently required to load PDF.js; full offline support is a future enhancement.

## Cloudflare Pages deployment
Connect this GitHub repository to Cloudflare Pages, choose no framework, leave the build command blank and deploy the repository root.

## Local development
Run `python -m http.server 8000`, then visit `http://localhost:8000`.

## Limitations
Large PDFs may consume significant memory. Text search locates pages but does not highlight individual words. Password-protected PDFs are not yet supported. This is a reader, not an editor or file manager.

## Version history
- **1.0.0** — Initial dark mobile-first PDF viewer.
