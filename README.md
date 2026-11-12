# Windows 98 for Beekeeper Studio

A theme that recreates the look of Windows 98: beveled buttons and fields, navy title bars, pixel fonts and pixel icons.

## Files

- `style.css` holds the theme. The app wraps it in `@scope`.
- `scrollbars.css` holds the scrollbar arrow buttons. Chromium does not match
  their state selectors inside `@scope`, and an imported stylesheet is left
  unscoped.
- `fonts/` holds the pixel fonts. Text is set at 11px throughout, the one size
  at which the bitmap font is sharp.

## Credits

- MS Sans Serif recreation by "lou" on FontStruct, CC BY-SA 3.0, converted to WOFF2 by [98.css](https://github.com/jdan/98.css).
- Icons from [Pixelarticons](https://github.com/halfmage/pixelarticons) (MIT), patched into [Material Icons](https://github.com/google/material-design-icons) (Apache 2.0).

See [`fonts/LICENSE.txt`](fonts/LICENSE.txt) for details.
