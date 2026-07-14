# Microsite Builder

A self-contained, single-file HTML tool for building Shopee-style campaign microsites and landing pages — no build step, no server, no dependencies to install. Open `index.html` in a browser to start building.

## Features

- **Drag-and-drop block editor** — text, tables, dividers/CTAs, cards grids, calendar highlights, image uploads, a header/hero block with an image background and headline overlay, and adjustable spacer ("component gap") blocks.
- **Rich text formatting** — bold/italic/underline, alignment, font family/size/leading, per-word or per-letter color, and Google Docs–style numbered/bulleted lists (with auto-detect, indent/outdent, and correct renumbering).
- **Tables** — row/column insert & delete (with direction), cell merge/unmerge, per-cell background/text color/formatting, vertical alignment, adjustable row height, and click-and-drag range selection.
- **Cards grid** — unified text formatting that follows whatever title or description you're editing (or just a highlighted selection), resizable number badges, and swappable icons/images.
- **Calendar widget** — 1 or 2 month spans, adjustable size, and an editable color-coded legend.
- **Undo/redo, keyboard shortcuts, zoom, and canvas panning** for a smooth editing experience.
- **Export** — download the finished microsite as a ZIP of per-block PNG/JPG slices, each exactly 1200px wide, ready to drop into an email or CMS.

## Usage

1. Open `index.html` in any modern browser (Chrome, Edge, Safari).
2. Drag blocks from the left palette onto the artboard, or click a palette item to append it.
3. Click any block to edit its content and options in the right-hand panel.
4. Use the Download button (top right) to export your microsite as PNG or JPG slices.

## Notes

- Everything runs client-side; no data leaves the browser except loading Google Fonts and a few CDN-hosted libraries (Sortable.js, html2canvas, JSZip).
- There's no save/load-to-file feature — work is kept in the browser via autosave (local storage) for the current session.
