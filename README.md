# Letyar Brand Assets

Official brand identity and visual asset library for **Letyar Labs**.

> **Every build carries a fingerprint.**

Letyar (လက်ရာ) represents craftsmanship, authorship, and the maker's fingerprint. This repository is the **source of truth for approved Letyar visual assets** used across Letyar Labs websites, products, applications, social profiles, documents, and partner materials.

## Brand

| Item | Official direction |
| --- | --- |
| Brand | **Letyar / Letyar Labs** |
| Positioning | **Web · Software · Product** |
| Primary domain | https://letyarlabs.com |
| Developer / open-source home | https://letyar.dev |
| Tagline | **Every build carries a fingerprint.** |
| Alternate line | **Built by hand, shipped on time.** |

## Repository structure

```text
letyar-brand-assets/
├── README.md
├── LICENSE
├── docs/
│   └── brand-guidelines.md
├── svg/
│   ├── mark-master-8k.svg
│   ├── mark-transparent.svg
│   ├── mark-light.svg
│   ├── mark-gold-accent.svg
│   ├── mark-on-ink.svg
│   ├── mark-on-gold.svg
│   ├── mark-on-cream.svg
│   ├── mark-on-lacquer.svg
│   ├── mark-monochrome-black.svg
│   ├── mark-monochrome-white.svg
│   └── icon-*.svg
└── raster/
    ├── mark-8k.png
    ├── mark-transparent-2048.png
    ├── mark-gold-accent-2048.png
    ├── mark-on-cream-2048.png
    ├── icon-*.png
    └── favicon.ico
```

## Logo system

The approved Letyar mark is based on the **three-groove geometry**.

### Master

- `svg/mark-master-8k.svg` — primary vector master.
- `raster/mark-8k.png` — high-resolution raster export.
- The SVG master is the source of truth.
- Do not redraw, trace, or alter the geometry.

### Approved variants

| Variant | Intended use |
| --- | --- |
| `mark-transparent.svg` | General placement on approved backgrounds |
| `mark-light.svg` | Light/negative treatment |
| `mark-on-ink.svg` | Standard dark brand surface |
| `mark-on-cream.svg` | Light editorial surface |
| `mark-on-lacquer.svg` | Accent surface |
| `mark-on-gold.svg` | Gold/premium surface |
| `mark-gold-accent.svg` | Premium/global accent treatment |
| `mark-monochrome-black.svg` | Single-colour print/embossing |
| `mark-monochrome-white.svg` | Single-colour dark-surface use |

## Colour tokens

| Token | Hex | Role |
| --- | --- | --- |
| Ink | `#000000` | Primary dark surface |
| Groove | `#1A1714` | Core groove stroke |
| Lacquer | `#E34B2E` | Standard accent |
| Thanaka Gold | `#D9A441` | Premium/global accent |
| Cream | `#F5F0E6` | Primary light surface |

Use only approved colour combinations. Do not introduce gradients, arbitrary colours, shadows, or effects to the mark.

## Digital implementation

Prefer SVG for websites, apps, documentation, and other digital interfaces.

```html
<link rel="icon" href="/brand/svg/icon-32.svg" type="image/svg+xml">
<link rel="apple-touch-icon" href="/brand/raster/icon-180.png">
<img src="/brand/svg/mark-transparent.svg" alt="Letyar">
```

For favicon fallbacks and platforms that do not accept SVG, use the supplied PNG/ICO exports.

## Clear-space and scaling

- Keep sufficient empty space around the mark so it remains visually distinct.
- Never stretch, compress, rotate, skew, or crop the mark.
- Do not place text, UI controls, or decorative elements inside the mark's clear space.
- Use the supplied icon assets at small sizes rather than shrinking the master mark excessively.

Detailed usage guidance is maintained in [docs/brand-guidelines.md](docs/brand-guidelines.md).

## Naming convention

Asset names describe their intended role and treatment:

- `mark-*` — primary Letyar mark
- `icon-*` — application/favicon icon exports
- `master` — source-of-truth artwork
- `transparent` — transparent background
- `on-ink`, `on-cream`, `on-gold`, `on-lacquer` — approved surface variants
- `gold-accent` — Thanaka Gold accent treatment
- `monochrome-*` — one-colour production variants

Do not rename source assets casually; stable names make product and website integrations predictable.

## Brand usage rules

### Do

- Use the supplied artwork without modifying its geometry.
- Prefer SVG where supported.
- Use the standard Lacquer accent for everyday brand communication.
- Reserve the Gold accent treatment for premium/global, awards, keynote, and special partnership contexts.
- Preserve the intended contrast between the mark and its background.

### Do not

- Stretch, rotate, mirror, or redraw the mark.
- Change groove proportions or spacing.
- Add gradients, bevels, shadows, glow, or decorative effects.
- Apply unapproved colours.
- Use the Gold accent as the default everyday treatment.
- Export a low-quality screenshot when an approved asset is available.

## Source of truth

This repository is the canonical Letyar visual asset source for production work.

When an asset is updated, update the repository first and then propagate the approved version to products, websites, social profiles, and documents.

## Ownership

Letyar and the associated visual identity are maintained by **Letyar Labs**.

Brand assets are not automatically open-source merely because this repository is public. See [LICENSE](LICENSE) for permitted use.

## Contact

- Website: https://letyarlabs.com
- Email: hello@letyarlabs.com
- GitHub: https://github.com/letyarworks

---

**Letyar Labs**  
*Every build carries a fingerprint.*
