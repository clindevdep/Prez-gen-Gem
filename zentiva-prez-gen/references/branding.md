# Zentiva Brand Guidelines for Presentations

This reference defines the visual standards for creating PowerPoint presentations branded for Zentiva.

## Color Palette

| Element | Hex Code | RGB | Usage |
| :--- | :--- | :--- | :--- |
| **Zentiva Dark Blue** | `#0C4160` | (12, 65, 96) | Primary headings, slide headers, dark backgrounds |
| **Zentiva Teal** | `#00A98F` | (0, 169, 143) | Accents, gradients, bullet points, secondary elements |
| **Zentiva Light Teal** | `#E8F5F2` | (232, 245, 242) | Table rows, subtle backgrounds |

## Template Layouts

The template `Brand_v001.pptx` contains 24 slide layouts. Key layouts used by the generator:

| Layout Name | Purpose | Placeholders |
| :--- | :--- | :--- |
| `1_Title Slide` | Full-image title or quote slide | CENTER_TITLE, PICTURE |
| `2_Title and Content` | Standard content with bullets | TITLE, BODY (idx 14) |
| `3_Title Slide` | Split layout with left gradient panel | CENTER_TITLE, SUBTITLE, PICTURE |
| `17_Title and Content` | Two-column content layout | TITLE, BODY (idx 14, 15) |

## Slide Types

### Title Slide (Template Slide 0)
- Full-width background image with blue gradient overlay
- White centered title text
- Optional subtitle
- Zentiva logo in footer

### Quote/Statement Slide (Template Slide 1)
- Full gradient background (dark blue to teal)
- White centered statement text
- Zentiva logo in footer
- Page number in teal (bottom-right)

### Split Layout (Template Slide 2)
- Left panel: gradient background with title/subtitle
- Right panel: full-height image
- White text on gradient panel

### Content Slide (Added via layout)
- White background
- Dark blue title at top
- Teal bullet points with hierarchical indentation
- Zentiva logo in footer

### Two-Column Layout (Added via layout)
- Circular gradient accent shape on right
- Left column: teal bullets on white
- Right column: white text inside gradient circle
- Teal gradient accent at bottom

## Placeholder Reference

| Type | Index | Description |
| :--- | :--- | :--- |
| CENTER_TITLE | 0 | Main title (type 3) |
| SUBTITLE | - | Secondary text (type 4) |
| BODY | 14 | Primary content area |
| BODY | 15 | Secondary content (two-column) |
| PICTURE | 13 | Image placeholder (type 18) |
| FOOTER | 11 | Footer text |
| SLIDE_NUMBER | 12 | Page number |

## Design Principles

- **Logo**: Always visible in bottom-left footer (inherited from master)
- **Page Numbers**: Teal color, bottom-right corner
- **Gradients**: Dark blue (#0C4160) to teal (#00A98F) diagonal
- **Text on Dark**: White (#FFFFFF)
- **Text on Light**: Dark blue titles, teal body text
- **Simplicity**: Clean, minimalist layouts with ample white space
