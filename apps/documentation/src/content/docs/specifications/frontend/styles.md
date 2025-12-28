---
title: Styles
---

We created a custom corporate theme to ensure all frontends have consistent, modern UI functionality. The theme features a formal color palette inspired by professional corporate designs, with clean typography and accessible color contrasts.

## Color Palette

The Conduit Corporate Theme uses the following color palette:

| Color | Hex | Usage |
|-------|-----|-------|
| Primary Blue | `#0056B3` | Primary buttons, links, brand elements |
| Primary Dark | `#003d80` | Hover states, active elements |
| Accent Red | `#C41E3A` | Danger buttons, error states |
| Dark Gray | `#212529` | Primary text, headings |
| Secondary Gray | `#495057` | Secondary text |
| Muted Gray | `#6c757d` | Placeholder text, metadata |
| Light Gray | `#f8f9fa` | Backgrounds, cards |
| Border Gray | `#dee2e6` | Borders, dividers |

## Typography

The theme uses a modern font stack:

- **Sans-serif**: Inter, Source Sans Pro (UI elements, body text)
- **Serif**: Source Serif Pro (article content)
- **Logo**: Titillium Web (brand elements)

## Loading the Theme

Include the corporate theme in your HTML head (our [header template](/specifications/frontend/templates#header) does this by default):

```html
<link rel="stylesheet" href="/conduit-corporate-theme.css" />
```

## CSS Variables

The theme uses CSS custom properties for easy customization:

```css
:root {
  --color-primary: #0056B3;
  --color-primary-dark: #003d80;
  --color-accent: #C41E3A;
  --color-dark: #212529;
  --color-secondary: #495057;
  --color-muted: #6c757d;
  --color-light: #f8f9fa;
  --color-border: #dee2e6;
}
```

## Component Classes

The theme provides styling for all standard Conduit components:

- **Buttons**: `.btn-primary`, `.btn-outline-primary`, `.btn-outline-secondary`, `.btn-outline-danger`
- **Tags**: `.tag-default`, `.tag-pill`, `.tag-outline`
- **Cards**: `.card`, `.card-block`, `.card-footer`
- **Forms**: `.form-control`, `.form-control-lg`
- **Navigation**: `.navbar`, `.nav-link`, `.nav-pills`

For the complete list of templates and HTML structure, see the [Templates](/specifications/frontend/templates) documentation.
