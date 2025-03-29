# Unicode Atlas

**Explore the characters that make the world readable.**

Unicode Atlas is a clean, modern, and powerful Unicode explorer. It lets you browse every official Unicode block and inspect individual characters with rich detail—including codepoints, categories, UTF encodings, and more.

## Features

- **Full Unicode Block Explorer**
  - Dynamically generated from `Blocks.txt`
  - Plane filtering (BMP, SMP, SIP, TIP)
- **Character Pages (`letter.html`)**
  - UTF-8 and UTF-16 encoding
  - HTML entity
  - Unicode name, category, plane, script, bidi class, mirrored flag, and combining class
  - External link to Codepoints.net
- **Favorites + Recently Viewed**
  - Stored locally using `localStorage`
  - Persistent across sessions
- **Dark Mode**
  - Toggle-able
  - Preference saved across pages

## Files

- `index.html` — The main Unicode block browser
- `letter.html` — Individual character detail view
- `UnicodeData.txt` — Official Unicode character metadata
- `Blocks.txt` — Unicode block definitions
- `Scripts.txt` — Unicode script ranges
- `unicode-blocks.js` — Parsed Unicode block data

## How to Use

1. Download or clone this repo
2. Open `index.html` in your browser (or host via GitHub Pages, or click the website down there)
3. Click on a block to see its characters
4. Click a character to view detailed info
5. Toggle dark mode and save favorites as you go!

## Credits

Built with love, logic, and a deep obsession with character encoding.

Data sources:
- [UnicodeData.txt](https://www.unicode.org/Public/UNIDATA/UnicodeData.txt)
- [Blocks.txt](https://www.unicode.org/Public/UNIDATA/Blocks.txt)
- [Scripts.txt](https://www.unicode.org/Public/UNIDATA/Scripts.txt)

## Website
[Unicode Atlas](https://sevennai7.github.io/Unicode-Atlas/index.html)

## License

MIT — Feel free to remix, share, and expand!
