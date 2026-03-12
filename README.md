# Finbred-Site

Static landing page for **[Finbred](https://github.com/jacobbates/finbred)** -- a browser-based roguelite deck-builder set in a fish tank.

Live at **[finbred.io](https://finbred.io)**

Play at **[finbred.fish](https://finbred.fish)**

## Stack

| Layer   | Tech                                                                                         |
| ------- | -------------------------------------------------------------------------------------------- |
| Markup  | Vanilla HTML5                                                                                |
| Styling | Vanilla CSS + [Bootstrap 5.3.2](https://getbootstrap.com/)                                   |
| Icons   | [Iconify](https://iconify.design/) (CDN, icon sets: Font Awesome 6, Streamline, Tabler)      |
| Fonts   | [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) (headings via Google Fonts) |
| Hosting | GitHub Pages                                                                                 |

## Structure

```
finbred-site/
  index.html        # Single page
  terminal.md       # Patch notes (fetched at runtime)
  css/
    site.css         # All custom styles
  icons/
    favicon-*.png    # Browser tab icons
    apple-touch-icon.png
    og-image.png     # Social sharing card
  sprites/
    f_*.svg          # Fish sprites (used in hero + roster)
```

## Local Development

```bash
npx serve . -l 3001
```

## Attributions

- **Bootstrap** -- MIT License, (c) Twitter, Inc.
- **Iconify** -- MIT License, (c) Iconify OUE
- **Space Grotesk** -- SIL Open Font License 1.1, designed by Florian Karsten
- **Font Awesome 6 icons** (via Iconify) -- CC BY 4.0 (icons), SIL OFL 1.1 (font), MIT (code)
- **Streamline icons** (via Iconify) -- see [Streamline license](https://www.streamlinehq.com/license)
- **Tabler icons** (via Iconify) -- MIT License

All fish sprites and game content are original work (c) 2026 Jacob Bates.

## License

Site content and design (c) 2026 Jacob Bates. All rights reserved.
