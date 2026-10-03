---
name: Titanium Precision
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#3f4850'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#707881'
  outline-variant: '#bfc7d2'
  surface-tint: '#006398'
  primary: '#006194'
  on-primary: '#ffffff'
  primary-container: '#007bb9'
  on-primary-container: '#fdfcff'
  inverse-primary: '#93ccff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#00628d'
  on-tertiary: '#ffffff'
  tertiary-container: '#007cb1'
  on-tertiary-container: '#fcfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cce5ff'
  primary-fixed-dim: '#93ccff'
  on-primary-fixed: '#001d31'
  on-primary-fixed-variant: '#004b73'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#c9e6ff'
  tertiary-fixed-dim: '#89ceff'
  on-tertiary-fixed: '#001e2f'
  on-tertiary-fixed-variant: '#004c6e'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-hero:
    fontFamily: Sora
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Sora
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 44px
    fontWeight: '600'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Sora
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Sora
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
  data-metric:
    fontFamily: Sora
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
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
  margin: 3rem
  margin-sm: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system embodies surgical precision, aerospace-grade engineering, and high-performance wearable technology. It evokes a tactile sense of brushed titanium, crystalline sapphire glass, and calibrated instrumentation. Designed for performance athletes, tech purists, and modern professionals, the emotional response should be uncompromising confidence, clarity, and industrial refinement.

The aesthetic fuses **Minimalism** with **Modern High-Tech Tactile Precision**:
- Razor-sharp structural discipline balanced with subtle micro-textures and precise containment.
- Pristine, architectural light surfaces accented by controlled, luminous electric blue energy states.
- Clean planar geometry that mimics machined metal bezels, fine bevels, and calibrated dials.

## Colors
The palette leverages clinical contrast and machined metal tonality:

- **Primary (`#0284c7`) & Tertiary (`#0ea5e9`)**: Electric cyan-blue hues reserved for primary actions, active telemetry data, power indicators, and high-priority states. A deep variant (`#0077cc`) serves as the hover/active state for primary interactive elements.
- **Secondary (`#0f172a`)**: Deep slate/onyx, providing near-black contrast for headlines, structural accents, and ultra-crisp technical indicators.
- **Neutrals & Surfaces**:
  - Global Canvas / Background: `#f8fafc` (Slate 50) for a pristine, technological environment.
  - Pure Surface Containers: `#ffffff` (machined face) layered over canvas.
  - Subdued Containers: `#f1f5f9` (Slate 100) for structural grouping and technical data wells.
  - Structural Borders: `#e2e8f0` (Slate 200) for micro-dividers and calibrated grids.
- **Text Tiers**:
  - Prominent/Headings: `#0f172a` (Slate 900)
  - Body/Primary Reading: `#1e293b` (Slate 800)
  - Secondary/Telemetry: `#334155` (Slate 700)
  - Captions/Muted Metadata: `#64748b` (Slate 500)

## Typography
Typography is strictly dual-engine: **Sora** anchors all numerical readouts, hardware specs, and structural headers with its geometric, engineered cadence, while **Inter** delivers high-density optical legibility for feature descriptions, telemetry micro-copy, and technical tables.

- **Numerics & Metrics**: All numerical specifications, watch face dimensions, battery statistics, and sensors render in `Sora` with tabular figures (`font-variant-numeric: tabular-nums`) enabled.
- **Labels & Micro-headers**: Utilize `label-sm` set in uppercase with deliberate tracking (`0.06em`) to emulate laser-etched hardware engravings.
- **Paragraphs**: Keep line height generous (`1.5` to `1.6`) to maintain effortless scanning across dense technical specs.

## Layout & Spacing
The layout relies on a 12-column responsive fluid grid with an absolute ceiling of `1280px` for structured marketing sections and telemetry layouts.

- **Breakpoints**:
  - `Desktop` (≥ 1024px): 12-column grid, `margin: 3rem`, `gutter: 1.5rem`.
  - `Tablet` (768px – 1023px): 8-column grid, `margin: 2rem`, `gutter: 1.25rem`.
  - `Mobile` (< 768px): 4-column grid, `margin: 1.25rem`, `gutter: 1rem`.
- **Rhythm & Grid Discipline**: Components, modular metric tiles, and hardware callouts align strictly to a 4px baseline sub-grid. Section stacking ranges between `space-xl` (mobile) and double `space-xl` (desktop) to give high-definition 3D watch renders generous negative space.

## Elevation & Depth
Depth is engineered through **Tonal Stacking**, crisp **Low-Contrast Structural Outlines**, and **Crystalline Diffused Shadows** that evoke optical sapphire glass.

- **Surface Levels**:
  - Level 0 (Base Canvas): `#f8fafc`
  - Level 1 (Card/Container): `#ffffff` backed by a 1px border of `#e2e8f0`.
  - Level 2 (Floating Instrument/Modal): `#ffffff` with a double-ring boundary (1px inner `#f1f5f9`, 1px outer `#e2e8f0`) plus a cold ambient shadow: `0 12px 32px -8px rgba(15, 23, 42, 0.06), 0 4px 12px -2px rgba(15, 23, 42, 0.03)`.
  - Level 3 (Active HUD / Overlay): Semi-opaque frosted glass backdrop (`rgba(255, 255, 255, 0.85)` with `backdrop-filter: blur(12px)`) framed by a subtle cyan-tinted highlight `rgba(2, 132, 199, 0.15)`.
- **Glow & Active States**: Interactive elements and active biometric states emit a micro-bleed cyan drop shadow: `0 0 16px rgba(14, 165, 233, 0.25)`.

## Shapes
Geometry is disciplined, precise, and balanced (Roundedness Level 2):
- Standard interactive elements, inputs, and modular metric tiles employ `0.5rem` (8px) corners, echoing the soft radiused bevels of machined titanium lugs and pushers.
- Feature containers and sensory radar displays utilize `rounded-lg` (1rem / 16px).
- Status pills, physical sensor representations, and battery level badges utilize full circular or pill radii (`9999px`).
- Sharp, 90-degree internal cuts are avoided to ensure the interface reflects industrial ergonomics and watchmaking precision.

## Components

### Buttons
- **Primary Action (CTA)**: High-luminance electric blue fill (`#0284c7`), solid white text (`#ffffff`), `font-weight: 600`. Hover shifts smoothly to `#0077cc` with a focused kinetic elevation (`translateY(-1px)` and a subtle `0 4px 14px rgba(2, 132, 199, 0.35)` glow).
- **Secondary (Titanium Slate)**: Deep slate container (`#0f172a`), white text, designed for secondary hardware actions or technical spec triggers.
- **Tertiary (Ghost / Outline)**: Crisp 1px border in `#e2e8f0`, transparent fill, `#0f172a` text. Hover fills with `#f1f5f9` and brightens the border to `#0284c7`.

### Interactive Telemetry Chips & Spec Tags
- Monospaced metric pills with a height of 28px.
- Background: `#f1f5f9`; border: 1px solid `#e2e8f0`; text: `#334155`.
- Selected/Active state: Background `#ffffff`, border 1.5px solid `#0284c7`, text `#0284c7`, accompanied by a pulsing 6px cyan status dot.

### Sensor & Metric Cards
- Layered `#ffffff` surfaces with a 1px border in `#e2e8f0`.
- Padding: `1.5rem` internal clearance.
- Header incorporates an etched sub-label in `label-sm` (`#64748b`), a large numeric telemetry display in `data-metric` (`#0f172a`), followed by micro-line charts or precision glyphs rendered in `#0ea5e9`.

### Technical Spec Lists
- Linear rows partitioned by hairline borders (`1px solid #f1f5f9`).
- Left column: Label in `#64748b`, `Inter` 14px regular.
- Right column: Precision value in `#0f172a`, `Sora` 14px semi-bold, aligned flush-right.

### Form Inputs & Pre-order Selectors
- Background `#ffffff`, height 44px, border 1px solid `#cbd5e1`.
- Focus state: Border transitions to `#0284c7` with an optical ring: `box-shadow: 0 0 0 3px rgba(2, 132, 199, 0.15)`.
- Input placeholder in `#94a3b8`; input value in `#0f172a`.

### Checkboxes & Radios
- Size: 18x18px.
- Unchecked: `#ffffff` with 1.5px border `#cbd5e1`.
- Checked: `#0284c7` fill with crisp white vector checkmark/dot, surrounded by a 1px halo in `#0ea5e9`.

### Specialized Hardware Components
- **Case Size Switcher (42mm / 46mm)**: Segmented control in `#f1f5f9` casing with a sliding white pill indicator (`box-shadow: 0 2px 6px rgba(15, 23, 42, 0.08)`).
- **Exploded View Hotspots**: Circular pulse beacons with an inner `#0ea5e9` core and an expanding ripple animation in `rgba(14, 165, 233, 0.2)` connecting to floating micro-spec cards.