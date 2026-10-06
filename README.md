# PAIR ORBIT MAKER v16.5.20

PNG export stabilization:
- Full-body images no longer recalculate their X/height/transform in the export document.
  Their exact editor pixel rectangles are copied into the export clone.
- Rich-text prose no longer relies on html2canvas line wrapping.
  Existing `freezeRichTextForExport()` is now actually invoked before capture,
  preserving the editor's exact glyph positions and highlight geometry.
- v16.5.19 CSS-variable parity and edge isolation remain intact.
