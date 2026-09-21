# Letyar Brand Assets

This package was built from the **approved three-groove Letyar logomark geometry**. The SVG master is the single source of truth; do not redraw or alter its paths.

## Main files

- `svg/mark-master-8k.svg` — official 8K master SVG, black background
- `raster/mark-8k.png` — official 8192 × 8192 PNG export
- `svg/mark-transparent.svg` — transparent version for placement on approved backgrounds
- `svg/mark-on-ink.svg` — standard Ink/black square asset
- `svg/mark-on-cream.svg` — Cream background asset
- `svg/mark-on-lacquer.svg` — Lacquer background asset
- `svg/mark-on-gold.svg` — Gold background asset
- `svg/mark-gold-accent.svg` — Ink background with Thanaka Gold dot
- `svg/mark-monochrome-black.svg` / `mark-monochrome-white.svg` — one-color print/embossing use

## Colours

| Token | Value | Use |
| --- | --- | --- |
| Ink | `#000000` | Standard dark background |
| Groove | `#1A1714` | Core groove stroke on Ink |
| Lacquer | `#E34B2E` | Standard accent dot |
| Thanaka Gold | `#D9A441` | Premium/global accent dot only |
| Cream | `#F5F0E6` | Light background |

## Web use

```html
<link rel="icon" href="/brand/svg/icon-32.svg" type="image/svg+xml">
<link rel="apple-touch-icon" href="/brand/raster/icon-180.png">
<img src="/brand/svg/mark-transparent.svg" alt="Letyar">
```

## Rules

- Use the normal Lacquer dot for everyday brand usage.
- Use the Gold accent version only for premium/global, awards, keynotes, and special partnership contexts.
- Never stretch, rotate, recolour outside this palette, add gradients/shadows, or redraw the mark.
- Use SVG for digital and print whenever possible. PNG is supplied for platforms that do not accept SVG.
- At tiny sizes, use `raster/favicon.ico` or `raster/icon-32.png`.
