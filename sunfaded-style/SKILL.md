---
name: sunfaded-style
description: "Create UI and graphic design layouts in the sunfaded style: oversized condensed typography, bilingual JP/EN type, high-contrast overlays on photo or illustration, halftone wave bands, and analog grain. Use when a user asks for sunfaded-like aesthetics, bold typographic posters, editorial layouts, or UI screens with this specific visual system."
---

# Sunfaded Style

## Overview

Create UI and graphic layouts with oversized condensed typography, bilingual JP/EN mixing, analog grain, and high-contrast overlays. Favor stark hierarchy and cropped type over delicate ornament.

## Workflow

1. Collect hero text, supporting text, language mix (JP/EN), target format, and asset availability.
2. Establish hierarchy: one dominant word or phrase, two to four secondary labels, and micro credits.
3. Build a strict grid, align edges, and allow type to crop at canvas boundaries.
4. Layer type over image or flat field; add a halftone band or strip for rhythm.
5. Apply texture (film grain, dust, mild blur) while keeping contrast high and the reading path clear.

## Style Pillars

- Typography: Use DIN (condensed/Engschrift if available) uppercase for hero text, pair with bold JP sans. Use micro uppercase for metadata and loosen tracking at small sizes.
- Layout: Scale headlines to edge-crop, repeat words or labels, and mix horizontal and vertical text blocks.
- Texture: Add halftone waves, moire, or noise; keep textures subtle but visible at 100%.
- Color: Prefer monochrome or cool desaturated tones; allow a single vivid accent color.

## Typography System

- Hero: DIN Condensed/DIN Engschrift, uppercase, 6x to 12x base size, tracking -0.02em to -0.04em.
- Secondary: DIN Condensed or standard DIN, 1.8x to 3x base, tracking -0.01em.
- Micro: DIN Regular uppercase, 0.6x base, tracking +0.08em to +0.12em.
- JP: Bold kaku gothic; use for main JP labels, keep tracking neutral.
- Fallbacks: If DIN is unavailable, use another condensed grotesk and note the substitution.

## Grid and Ratios

- Use a 12-column grid with generous gutters.
- Hero text width: 70 to 90 percent of canvas.
- Crop rule: allow at least one edge crop for the hero word.
- Margins: 5 to 8 percent outer margin; keep micro text aligned to grid.
- Vertical labels: set in a narrow 1-column strip or as a side rail.

## Layout Patterns

- Pattern A: Full-bleed image + oversized hero word + micro credits block + halftone band.
- Pattern B: Repeated hero word rows with alternating scale, plus vertical JP tag.
- Pattern C: Left-aligned JP block + right-aligned EN headline, both edge-cropped.

## Texture Recipes

- Grain: 2 to 6 percent opacity, fine noise, uniform across layers.
- Halftone band: diagonal lines warped by a sine curve, placed in lower third or side rail.
- Bloom: slight highlight bloom on bright areas, keep readable text crisp.

## UI Adaptation

- Hero: Oversized headline plus a small metadata strip; optional vertical side label.
- Navigation: Tight uppercase labels, separators or rules, and minimal iconography.
- Sections: Image-backed panels with overprint type; use halftone bands as dividers.

## Constraints

- Do not copy or embed copyrighted imagery; use user-provided assets or placeholders.
- Preserve readability; avoid more than two heavy type layers in the same area.

## References

Read `references/sunfaded-style.md` when you need layout recipes, scale ratios, or CSS token guidance.
