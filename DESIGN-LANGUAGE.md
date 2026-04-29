# Design Language — Royal Gold & Maroon Indian Wedding Invitation

Extracted from Canva design `DAHGd5cA9T4`

---

## Color Palette

| Role | Hex | RGB | Usage |
|------|-----|-----|-------|
| Gold (primary bg) | `#C9A84E` | 201, 168, 78 | Main background, card fill |
| Maroon (accent) | `#6B1D2A` | 107, 29, 42 | Arch decoration, borders |
| Maroon Deep | `#4A1018` | 74, 16, 24 | Dark sections, headers |
| Dark Navy (text) | `#2C3347` | 44, 51, 71 | Body text on gold bg |
| Cream | `#F5ECD7` | 245, 236, 215 | Text on dark bg |
| Gold Light | `#D4BE6A` | 212, 190, 106 | Subtle accents |
| Gold Dark | `#A8893A` | 168, 137, 58 | Dividers, subtle text |

## Typography

### Hierarchy (from Canva design)

| Level | Content | Style | Size (approx) | Weight | Color |
|-------|---------|-------|---------------|--------|-------|
| H1 | Names ("Sandhya", "Prem Chand") | Serif, italic feel | ~34pt | Semibold | `#2C3347` dark navy |
| H2 | "Celebrating 25 Years of Love" | Serif, small caps feel | ~12pt | Regular | `#2C3347` |
| H3 | "Silver Jubilee Anniversary / Dinner Celebration" | Serif | ~11pt | Regular | `#2C3347` |
| Date block | "MAY" | Serif, uppercase | ~13pt | Bold | `#2C3347` |
| Date number | "08" | Serif display | ~23pt | Bold | `#2C3347` |
| Day/Time | "FRIDAY" / "AT 7PM" | Serif, uppercase | ~11pt | Regular | `#2C3347` |
| Year | "2026" | Serif | ~13pt | Semibold | `#6B1D2A` maroon |
| Venue | "Hotel Dayal International..." | Serif | ~11pt | Regular | `#2C3347` |
| Ampersand | "&" | Italic serif | ~34pt | Regular | `#C9A84E` gold |

### Recommended Google Fonts

- **Playfair Display** — for headings, names (closest to the Canva serif)
- **Cormorant Garamond** — for body text, details, subtitles
- **EB Garamond** — alternative body text

### Text Alignment
- All text: **center-aligned**
- Names stacked vertically with "&" between
- Date block uses horizontal layout: `FRIDAY | 08 | AT 7PM`

---

## Layout Structure (Page 2 — main invitation)

Canvas size: **397 x 559 pt** (portrait, roughly 7:10 ratio)

### Vertical Zones (top to bottom)

```
┌─────────────────────────────┐
│  MAROON FLORAL ARCH         │ ~0-40% — decorative header
│  + Ganesha icon at top      │
│  + Hanging flower garlands  │
├─────────────────────────────┤
│  GOLD ZONE — TEXT CONTENT   │ ~40-55% — all event text
│  Names, date, venue         │
│  Heart divider below venue  │
├─────────────────────────────┤
│  ILLUSTRATION ZONE          │ ~55-100% — visual elements
│  Couple center              │
│  Dancers with umbrellas L/R │
│  Peacocks L/R               │
│  Stone railing              │
│  Fountain, plants, flowers  │
│  Floral pots L/R            │
└─────────────────────────────┘
```

### Symmetry
- Design is **bilaterally symmetrical** (mirrored left/right)
- Dancers, peacocks, garlands, vines, floral pots — all placed as mirror pairs

---

## Assets Inventory

All assets saved in `assets/individual/`

### Decorative / Structural

| # | File | Description | Original Resolution | Canva ID |
|---|------|-------------|---------------------|----------|
| 01 | `01-floral-motif-pattern.png` | Gold floral motif (tiled bg texture) | 404x489 | MAGHPS8CQWo |
| 07 | `07-floral-arch-maroon.png` | Maroon floral arch header | 440x238 | MAGjyGuW-YI |
| 19 | `19-heart-divider.png` | Heart swirl text divider | 809x172 | MAFhtEeWFIE |

### Figures / Characters

| # | File | Description | Original Resolution | Canva ID |
|---|------|-------------|---------------------|----------|
| 06 | `06-dancer-with-umbrella.png` | Rajasthani dolly/dancer with umbrella | 6424x15009 | MAFxVE5odx4 |
| 18 | `18-lord-ganesha.png` | Lord Ganesha illustration | 3018x3533 | MAGBdp6cJK0 |
| 20 | `20-couple-illustration.png` | Custom couple portrait (uploaded) | 2641x4733 | MAHGesPTljI |

### Nature / Animals

| # | File | Description | Original Resolution | Canva ID |
|---|------|-------------|---------------------|----------|
| 09 | `09-peacock-spread.png` | Peacock with tail spread (side) | 4169x4468 | MAFoHXqLRsY |
| 11 | `11-peacock-standing.png` | Peacock standing (full body) | 4424x4494 | MAFoHYZD2_Y |
| 10 | `10-hanging-vine-plant.png` | Hanging vine/succulent | 1882x3525 | MAFu2wSjkgU |
| 14 | `14-banana-leaf.png` | Tropical banana leaf cluster | 2062x2893 | MAFhc0y0lCI |
| 15 | `15-gold-leaf-bouquet.png` | Green + gold leaf watercolor | 3874x5000 | MAFgc0_n7QU |
| 16 | `16-pink-flowers.png` | Pink roses watercolor bouquet | 2640x3791 | MAE8SDau_u0 |
| 17 | `17-green-leaves.png` | Green leaf branch | 1718x1926 | MAFmSCn7GjQ |

### Architecture / Props

| # | File | Description | Original Resolution | Canva ID |
|---|------|-------------|---------------------|----------|
| 02 | `02-gazebo-watercolor.png` | White gazebo/dome watercolor | 1646x2619 | MAFbw3aB9_Q |
| 04 | `04-perspective-grid-floor.png` | Marble perspective floor grid | 3195x1590 | MAFx7ZjanGQ |
| 05 | `05-stone-railing.png` | Stone balustrade/railing with vases | 2797x655 | MAE25TfsnRw |
| 12 | `12-fountain-watercolor.png` | Victorian fountain watercolor | 2548x1913 | MAFbw3uylu0 |

### Wedding Decoration

| # | File | Description | Original Resolution | Canva ID |
|---|------|-------------|---------------------|----------|
| 08 | `08-hanging-flower-garland.png` | Marigold hanging garland string | 792x4725 | MAGdTjAW-GM |
| 13 | `13-floral-pot-haldi.png` | Haldi ceremony floral pot backdrop | 3256x5870 | MAGVz6jgEaE |

### Background / Texture

| # | File | Description | Original Resolution | Canva ID |
|---|------|-------------|---------------------|----------|
| 03 | `03-green-watercolor-bg.png` | Soft green watercolor texture | 2500x2500 | MAFCoKXkUlc |

---

## Spacing & Composition Rules

- **Padding**: ~15-20pt from card edges to content
- **Text block spacing**: ~8-12pt between text lines
- **Date block**: uses decorative dotted lines as horizontal dividers
- **Symmetry axis**: vertical center of canvas
- **Layer order** (back to front):
  1. Gold floral motif pattern (tiled, full bleed)
  2. Maroon floral arch (top)
  3. Ganesha icon (top center, above arch)
  4. Hanging flower garlands (from arch corners)
  5. Text content (centered)
  6. Heart divider (below venue text)
  7. Perspective floor grid (bottom half)
  8. Stone railing (mid-bottom)
  9. Dancers with umbrellas (left + right, mirrored)
  10. Couple illustration (center)
  11. Peacocks (left + right)
  12. Gazebo domes (behind peacocks)
  13. Floral pots (left + right)
  14. Fountain (center bottom)
  15. Plants, flowers, leaves (foreground edges)

---

## Design Mood

- **Traditional Indian royal** aesthetic
- **Gold + Maroon** = regal, auspicious
- **Illustrated characters** (Rajasthani miniature art style)
- **Watercolor elements** for organic warmth (flowers, plants, fountain)
- **Symmetrical composition** creates formality and balance
- **Serif typography** reinforces classical elegance
