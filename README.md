# Style Guide

Your guide to consistency and sustaining complexity.

This document defines the colors, fonts, and text styles used across the styling page project.
## Colors

| Name   | Hex       | Preview |
|--------|-----------|---------|
| Gray   | `#687E8C` | ![Gray](https://placehold.co/15x15/687E8C/687E8C.png) |
| Blue   | `#5B9CB0` | ![Blue](https://placehold.co/15x15/5B9CB0/5B9CB0.png) |
| Maroon | `#8A394C` | ![Maroon](https://placehold.co/15x15/8A394C/8A394C.png) |
| Purple | `#503949` | ![Purple](https://placehold.co/15x15/503949/503949.png) |

```css
:root {
  --color-gray:   #687E8C;
  --color-blue:   #5B9CB0;
  --color-maroon: #8A394C;
  --color-purple: #503949;
}
```

## Fonts

Three typefaces are used in this project:

- **Nanum Gothic Coding** - monospace, used for code or technical text.
- **Outfit** - used for main headings.
- **Poppins** - used for subheadings and body copy.

Each supports regular, bold, and italic styling.

## Text Styles

### H1: Main page heading
- Font-family: Outfit
- Font-weight: 700 (SemiBold)
- Font-size: 30px

### H2: Subheading
- Font-family: Poppins
- Font-weight: Medium (500)
- Font-size: 26px

### P: Paragraph text
- Font-family: Poppins
- Font-weight: Normal (400)
- Font-size: 21px

```css
h1 {
  font-family: "Outfit", sans-serif;
  font-weight: 700;
  font-size: 30px;
}

h2 {
  font-family: "Poppins", sans-serif;
  font-weight: 500;
  font-size: 26px;
}

p {
  font-family: "Poppins", sans-serif;
  font-weight: 400;
  font-size: 21px;
}
```

## Usage

Import the fonts (for example, from Google Fonts) and reference the CSS variables and text styles above to keep the design consistent across all pages and components.
