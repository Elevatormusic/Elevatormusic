# SHAYA Brand Guidelines

Version 1.0 - Signal Color

## Core identity

**Brand name:** SHAYA

**Tagline:** Stay curious. Look closer.

**Brand idea:** Curiosity made visible.

Signal Color turns careful observation into a bright and direct visual
language. It uses strong geometry, controlled color, and small details that
reward a second look.

The system must feel:

- curious
- precise
- optimistic
- practical
- evidence-first

## Logo

The primary mark is the folded angular S.

Use the supplied SVG masters. Do not rebuild the mark.

The SVG files are the source of truth. They contain path outlines, not a
raster image or live font text. Use the PNG files only as fallbacks for a
system that cannot use SVG.

### Preferred versions

- Use the warm white mark on Cobalt or Ink.
- Use the Ink mark on Warm White.
- Keep the original proportions.
- Keep the fold and center gap visible.

### Clear space

Keep clear space equal to one quarter of the mark width on every side.

### Minimum size

- Digital mark: 32 px minimum.
- Profile avatar: 128 px minimum.
- Printed mark: 10 mm minimum.

### Do not

- stretch or compress the mark
- rotate the mark
- add an outline, shadow, glow, or gradient
- place the mark on a low-contrast image
- put other text inside the clear-space area
- enlarge the PNG fallback when an SVG master is available

### Vector and raster policy

Use SVG for the mark, wordmarks, avatar master, palette, clear-space
guide, type specimen, and repeat pattern. These files must stay sharp at
every size.

Keep the illustrated hero, detail crop, and animated GIF as raster art.
They contain print grain, painted texture, or animation frames. Keep them
at their supplied native size and do not enlarge them beyond that size.

## Tagline

Write the tagline as:

**Stay curious. Look closer.**

Use uppercase letters only when the tagline is part of a display composition.
Use sentence case in prose.

Do not use a retired tagline.

## Color

### Primary colors

| Name | Hex | Main use |
| --- | --- | --- |
| Cobalt | `#0231B1` | Main identity field and large architecture |
| Warm White | `#F6F3EC` | Text, paths, calm space, and light backgrounds |
| Ink | `#151514` | Body text and high-contrast details |

### Signal colors

| Name | Hex | Main use |
| --- | --- | --- |
| Turquoise | `#03AEA9` | Water, motion, and positive technical signals |
| Vermilion | `#FE4B05` | Doors, steps, focus points, and warnings |
| Marigold | `#FCAB05` | Light, discovery, and secondary focus |
| Indigo | `#3B1F73` | Plants, depth, and quiet contrast |

### Color balance

Use Cobalt or Warm White as the main field. Add one or two signal colors.
Use Ink for text and small high-contrast details.

Suggested balance:

- Cobalt: 45%
- Warm White: 25%
- Turquoise: 10%
- Vermilion: 8%
- Marigold: 6%
- Indigo: 4%
- Ink: 2%

Do not use every signal color at the same visual weight.

## Typography

### Display

Use **Impact** for SHAYA, major titles, and short display statements.

- Use uppercase letters.
- Use large sizes.
- Keep lines short.
- Do not use Impact for paragraphs.

### Tagline and labels

Use **Arial Narrow Bold** for the tagline, labels, and compact headings.

- Use moderate letter spacing.
- Keep the text readable at final size.
- Do not place the tagline over detailed art.

### Body text

Use **Arial** for explanations and documentation.

- Use short sentences.
- Keep one main idea in each paragraph.
- Use clear headings.

### Technical text

Use **Cascadia Mono** for code, paths, values, and technical labels.

## Illustration

Signal Color illustrations use:

- flat modernist geometry
- hard-edged light and shadow
- large color fields
- simple architectural perspective
- subtle screen-print or paper grain
- one small human, animal, or technical clue
- clear foreground and background separation

The image must stay readable at banner size.

Avoid:

- glossy 3D rendering
- photorealistic surfaces
- soft generic gradients
- neon effects
- busy interface overlays
- decorative objects without a clear purpose
- text placed over plants, architecture, or motion

## Composition

Use strong negative space.

For a GitHub banner:

- keep the identity rail on the left
- keep SHAYA and the tagline clear of the illustration
- use the right side for the main scene
- keep the original `1280 x 480` ratio
- check the result at the width used on GitHub

The identity rail can use up to one third of the banner width.

## Motion

Motion must support the phrase "Look closer."

Use this camera curve:

`cubic-bezier(0.65, 0, 0.35, 1)`

Recommended sequence:

1. Hold on the complete scene.
2. Ease into one physical detail.
3. Bring small subjects on screen one at a time.
4. Use small timing and position changes.
5. Move every subject off screen.
6. Hold on the empty detail.
7. Ease back to the complete scene.

Keep ants and other moving details on a real surface. They must not fly or
cross the water.

## GitHub profile

### Hero

Use `shaya-signal-color-hero-animated.gif` as the main profile hero.

Fallback:

Use `shaya-signal-color-hero-1280x480.png`.

### Avatar

Use `shaya-signal-color-avatar.svg` as the master. Use the 512 px PNG
fallback for services that do not accept SVG.

### Readability

- Keep SHAYA and the tagline in the left identity rail.
- Keep the tagline at a readable size.
- Do not place motion over the name or tagline.
- Test the animated and static versions.

## Writing voice

The voice is curious, direct, and careful.

Use:

- clear claims
- short explanations
- explicit limits
- evidence that supports the result
- practical next steps

Avoid:

- vague confidence
- buzzwords
- long slogans
- claims that the work did not verify

## Release checklist

Before release:

- confirm that the current tagline is present
- confirm that every asset uses the Signal Color system
- check the logo shape against the supplied mark
- check contrast at final size
- check every local link
- check the animation loop
- keep moving details on physical surfaces
- verify the public result after upload

## Package files

This package includes:

- an editable PowerPoint deck
- a PDF guide
- this Markdown guide
- design tokens
- outlined SVG logo masters with high-resolution PNG fallbacks
- outlined SVG wordmarks with high-resolution PNG fallbacks
- an SVG profile avatar master and a 512 px PNG fallback
- a static GitHub hero
- an animated GitHub hero
- a detail image
- SVG color, clear-space, type, and pattern system graphics
- high-resolution PNG fallbacks for the system graphics
