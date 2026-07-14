# Microsite Builder

A self-contained, single-file HTML tool for building Shopee-style campaign microsites and landing pages — no build step, no server, no dependencies to install. Open `index.html` in a browser to start building.

## Features

- **Drag-and-drop block editor** — headings/paragraphs, tables, dividers (ribbon, sub-ribbon, CTA, footer, line), a cards grid, a calendar widget, image uploads, a placeholder box, a note/container callout, a spacer ("Component Gap"), and a Header block (full-bleed image background with a headline overlay and an optional logo).
- **Header block** — edge-to-edge background image, editable headline (font, size, color, alignment, leading, vertical position), and a dedicated logo area that sits centered above the headline; upload, resize, or remove the logo independently of the headline.
- **Rich text formatting** — bold/italic/underline, alignment, font family/size/leading, per-word or per-letter color, and Google Docs–style numbered/bulleted lists (auto-detect, indent/outdent, correct renumbering).
- **Tables** — row/column insert & delete (with direction), cell merge/unmerge, per-cell background/text color/formatting, vertical alignment, adjustable row height, and click-and-drag range selection.
- **Cards grid** — horizontal grid or vertical/list layout, unified text formatting that follows whatever title/description (or highlighted selection) you're editing, resizable number badges (46px default), and swappable icons/images.
- **Calendar widget** — 1 or 2 month spans (2 months by default), adjustable size (155% by default), and an editable color-coded legend with its own font size control.
- **Per-component download** — every block has its own "Download this component" button in the properties panel, exporting just that piece as a PNG.
- **Whole-page export** — download the finished microsite as either a single full-page PNG, or a ZIP of per-block PNG slices (each exactly 1200px wide) — PNG only, for lossless quality.
- **Undo/redo, keyboard shortcuts, zoom, and click-and-drag canvas panning** for a smooth editing experience.

## Usage

1. Open `index.html` in any modern browser (Chrome, Edge, Safari).
2. Drag blocks from the left palette onto the artboard, or click a palette item to append it.
3. Click any block to edit its content and options in the right-hand panel.
4. Use the Download button (top right) for a full-page or all-sections export, or use the "Download this component" button inside a block's properties panel to export just that one piece.

## Notes

- Everything runs client-side; no data leaves the browser except loading Google Fonts and a few CDN-hosted libraries (Sortable.js, html2canvas, JSZip).
- There's no save/load-to-file feature — work is kept in the browser via autosave (local storage) for the current session.
