# Instrument Serif Custom

**Version 1.0.0**

A custom cut of [Instrument Serif](https://github.com/Instrument/instrument-serif) by Rodrigo Fuenzalida, made for [albcantero.com](https://albcantero.com).

## What changed

- **Lighter.** Every outline is inset by 6.6 units (of 1000), so stems and hairlines are thinner while each glyph keeps its original width and kerning.
- **Square dots.** The dots of `. : ; … ! ? ¡ ¿ i j` and the diaeresis are squares instead of circles.
- **Straight marks.** The comma, the acute and grave accents and the quotes (`' " ‘ ’ “ ” ‚ „`) are redrawn as straight, sharp shapes that match the square dots.
- **Tracking built in.** The -0.021em tracking it was designed with is baked into the advance widths, so it needs no `letter-spacing`.

## Two families

| Family | Files | Notes |
| --- | --- | --- |
| **Instrument Serif Custom** | Regular, Italic | Hinted. For text and display. |
| **Instrument Serif Custom Exposure** | Regular, Italic | The same, with the curves softened like an overexposed phototype print: rounded corners and ink pooling in the joints, without adding weight. Unhinted; meant for display sizes. The ogonek and the cedilla (`ą ę ş`) break slightly. |

Each comes as TTF (`fonts/ttf`) for desktop apps and WOFF2 (`fonts/webfonts`) for the web.

## Use on the web

```css
@font-face {
  font-family: 'Instrument Serif Custom';
  src: url('InstrumentSerifCustom-Regular.woff2') format('woff2');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: 'Instrument Serif Custom';
  src: url('InstrumentSerifCustom-Italic.woff2') format('woff2');
  font-weight: 400;
  font-style: italic;
  font-display: swap;
}
```

Use the Exposure files the same way under the family name `Instrument Serif Custom Exposure`.

## License

[SIL Open Font License 1.1](OFL.txt), like the original. Instrument Serif is copyright 2022 The Instrument Serif Project Authors; the modifications are copyright 2026 Alberto Cantero Soriano.
