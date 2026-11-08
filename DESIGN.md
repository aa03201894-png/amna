---
name: Artify Studio
colors:
  surface: '#fff8f6'
  surface-dim: '#e6d7d2'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1ec'
  surface-container: '#faebe6'
  surface-container-high: '#f4e5e0'
  surface-container-highest: '#eedfda'
  on-surface: '#211a17'
  on-surface-variant: '#55423e'
  inverse-surface: '#372f2b'
  inverse-on-surface: '#fdeee8'
  outline: '#88726d'
  outline-variant: '#dbc1ba'
  surface-tint: '#9a442d'
  primary: '#9a442d'
  on-primary: '#ffffff'
  primary-container: '#e07a5f'
  on-primary-container: '#5b1604'
  inverse-primary: '#ffb4a1'
  secondary: '#605c6a'
  on-secondary: '#ffffff'
  secondary-container: '#e6e0f0'
  on-secondary-container: '#666270'
  tertiary: '#6a5b54'
  on-tertiary: '#ffffff'
  tertiary-container: '#a4938b'
  on-tertiary-container: '#382c27'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd2'
  primary-fixed-dim: '#ffb4a1'
  on-primary-fixed: '#3c0800'
  on-primary-fixed-variant: '#7c2e19'
  secondary-fixed: '#e6e0f0'
  secondary-fixed-dim: '#c9c4d3'
  on-secondary-fixed: '#1c1a25'
  on-secondary-fixed-variant: '#484552'
  tertiary-fixed: '#f3ded5'
  tertiary-fixed-dim: '#d6c3ba'
  on-tertiary-fixed: '#241914'
  on-tertiary-fixed-variant: '#51443e'
  background: '#fff8f6'
  on-background: '#211a17'
  surface-variant: '#eedfda'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 28px
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2.5rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system embodies an atelier atmosphere for the modern digital artist. Designed for illustrators, calligraphers, hobbyists, and concept designers, the interface feels less like an intimidating mechanical software suite and more like a tactile, sunlight-filled physical art studio.

The visual direction merges **Tactile Organic Warmth** with refined **Editorial Minimalism**:
- **Tactile Paper Grain & Soft Surfaces:** Warm, fibrous paper-like backdrops replace cold stark whites, generating a soothing, reflective workspace.
- **Poetic Editorial Presence:** Literary serifs elevate UI headlines to feel like fine art publications and exhibition catalogs.
- **Frosted Pastel Atmosphere:** Delicately tinted translucent panels lend dimension without rigid division lines.
- **Quiet Clarity:** Restraint in decorative clutter ensures the creator's artwork remains the supreme focal point.

## Colors
The palette evokes natural pigment minerals, unbleached cotton paper, and tinted gouache washes.

### Palette Architecture
- **Primary (`#E07A5F` - Terracotta Coral):** Drives focused calls to action, primary tool selections, active brush states, and highlighted milestones.
- **Secondary (`#EBE5F5` - Glazed Lavender):** Provides atmospheric tinting for canvas palettes, layer panels, and secondary floating panels.
- **Tertiary (`#FDE8DF` - Warm Peach Wash):** Applied for subtle state selections, badge backdrops, and active brush preview containers.
- **Neutral (`#2D2522` - Deep Charcoal Umber):** Replaces pure digital black for all typographic hierarchies, iconography, and fine hairline borders, establishing high-legibility warmth.

### Functional Tinted Surfaces
- **Canvas Base:** `#FDFBF7` (Warm Cotton Cream)
- **Layer & Card Surface:** `#FFFFFF` with soft tinted borders, or `#FCE7E6` (Blush Pink) at 40%–60% opacity for floating tool shelves.
- **Muted Borders:** `rgba(45, 37, 34, 0.08)` for whisper-thin physical paper edges.

## Typography
Typographic rhythm sets the balance between artisanal craftsmanship and functional software tool ergonomics.

- **Headlines & Display:** Playfair Display introduces literary character, editorial weight, and fine serif curvature to showcase project galleries, title workspaces, and guide onboarding moments.
- **Body & Functional UI:** Plus Jakarta Sans ensures zero-fatigue legibility across brush adjustments, numeric dimensional pickers, layer metadata, and micro-labels.
- **Tracking & Proportion:** All upper-case sub-labels and micro-metrics use slight positive letter-spacing (`0.02em` to `0.04em`) to maintain clarity against pastel washes.

## Layout & Spacing
The layout adheres to a flexible, breathable structural grid that prioritizes the artist’s open drawing canvas.

### Layout Model
- **Studio Layout:** Central unbounded canvas bounded by floating, docking pastel panels. Fixed 72px left-hand studio rail for master instruments, collapsible 280px right-hand inspector for layers, color wheels, and brush engines.
- **Gallery & Portfolio Grid:** 12-column responsive fluid grid with 24px gutters on desktop; shifts down to an 8-column layout on tablet devices and a 4-column layout on mobile viewports.
- **Rhythm & Whitespace:** Margins scale from 40px (`margin`) on desktop down to 20px (`margin-mobile`) on smaller touch screens, allowing panels to hug display perimeters while giving the canvas uninterrupted focus.

## Elevation & Depth
Depth mimics paper strata, frosted drafting vellum, and ambient atelier sunlight rather than direct simulated cast lamps.

- **Layer 0 (Base Canvas):** Solid warm cream `#FDFBF7`.
- **Layer 1 (Cards & Static Trays):** Pure white `#FFFFFF` or pale blush tint `#FCE7E6` (30% opacity) with a whisper-light ambient glow: `0 4px 20px -2px rgba(45, 37, 34, 0.04)`.
- **Layer 2 (Floating Palettes & Tool Docks):** Frosted glassmorphism built with `backdrop-filter: blur(16px)`, translucent background `rgba(253, 251, 247, 0.78)`, bounded by a 1px border of `rgba(45, 37, 34, 0.06)`, and an ambient paper drop shadow: `0 12px 32px -4px rgba(45, 37, 34, 0.07)`.
- **Layer 3 (Modal Sheets & Color Pickers):** Higher elevation tinted with soft umber dispersion: `0 20px 48px -6px rgba(45, 37, 34, 0.12)`.

## Shapes
Forms celebrate curved organic contour lines found in freehand sketches:
- **Default Elements:** 8px (`0.5rem`) for compact fields, input swatches, and layer rows.
- **Panels & Dialog Cards:** 16px (`1rem`) to 24px (`1.5rem`) for main canvas overlays, preset cards, and floating tool docks.
- **Interactive Badges & Tool Pills:** Pill-shaped (`9999px`) rounded ends are used specifically for tool selector buttons, status indicators, and color swatch capsules to contrast structured layout boxes.

## Components

### Buttons
- **Primary:** Filled Terracotta Coral (`#E07A5F`) with stark cream text (`#FDFBF7`), subtle drop shadow (`0 4px 14px rgba(224, 122, 95, 0.25)`). Hover softly lightens the coral tone with a 1px upward translateY lift.
- **Secondary / Soft:** Frosted Lavender (`#EBE5F5`) or Peach (`#FDE8DF`) filled buttons with Deep Umber text (`#2D2522`).
- **Tertiary / Studio Tool:** Translucent icon buttons with no background until hovered, where a soft cotton wash (`rgba(45, 37, 34, 0.04)`) blooms behind the icon.

### Cards & Canvas Containers
- Built using white or soft blush grounds with 1px delicate borders `rgba(45, 37, 34, 0.07)`.
- Generous padding (`space-lg`) gives art previews room to breathe without borders encroaching on artwork margins.

### Input Fields & Tool Sliders
- **Inputs:** Soft `#FFFFFF` ground with recessed border in `rgba(45, 37, 34, 0.1)`. Focus state brings a warm terracotta ring (`0 0 0 2px rgba(224, 122, 95, 0.2)`).
- **Sliders (Opacity, Brush Size):** Slim 4px rail in pale lavender (`#EBE5F5`), filled with terracotta `#E07A5F`. Draggable thumb is a crisp 18px circle with a subtle paper drop shadow.

### Chips & Swatches
- **Tool / Brush Chips:** 32px height, pill-shaped, carrying an understated label in `Plus Jakarta Sans`. Active chips receive a soft peach background (`#FDE8DF`) with a delicate terracotta accent border.
- **Color Swatches:** Circular disks with an inset white border and subtle ambient shadow, arranged in rhythmic flex rows.

### Checkboxes & Toggle Switches
- Checkboxes feature rounded corners (`6px`) with a soft peach unselected frame; upon selection, they animate to terracotta with an umber or white check mark.
- Toggles utilize an organic pill track in frosted lavender with a white circular thumb.

### Studio-Specific Components
- **Floating Brush Bar:** Vertical pill dock featuring blurred frosted backing (`backdrop-filter: blur(18px)`), containing tactile vector icon triggers with smooth tooltip popouts.
- **Layer Panel Items:** Draggable horizontal strips featuring miniature artwork thumbnails, eye-toggle visibility icons, and subtle opacity percentages with drag-handle reordering cues.