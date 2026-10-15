---
name: Lumina Precision
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#006591'
  on-secondary: '#ffffff'
  secondary-container: '#39b8fd'
  on-secondary-container: '#004666'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#2a1700'
  on-tertiary-container: '#b87500'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#c9e6ff'
  secondary-fixed-dim: '#89ceff'
  on-secondary-fixed: '#001e2f'
  on-secondary-fixed-variant: '#004c6e'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-tablet: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies high-precision industrial craft and calm, architectural luxury. Drawing direct inspiration from minimalist hardware engineering and premium studio tools, the aesthetic merges the tactile authority of anodized metals with optical clarity and digital fluid responsiveness.

The interface serves discerning professionals, architects, and studio creatives who view their physical workspace as an extension of their craft. Visual density is kept low and deliberate; every element projects stillness, precision, and purpose. The design philosophy embraces Modern Industrial Minimalism with subtle translucent glass layers, fine hairline framing, and calibrated luminous accents that mimic the dynamic color temperatures of natural daylight.

## Colors

The palette balances cool, deep structural slate with luminous atmospheric accents:

- **Primary (`#0F172A`)**: Deep Matte Slate. Dictates dominant interface architecture, typography, high-priority actions, and structured elements. Communicates machined industrial density.
- **Secondary (`#0EA5E9`)**: Electric Cyan. Represents active smart connectivity, calibrated daylight color spectrums (6500K focus mode), and digital system states.
- **Tertiary (`#F59E0B`)**: Ambient Warmth. Signifies evening circadian shifts, relaxation modes (2700K warm glow), and ambient light intensity readouts.
- **Neutral (`#F8FAFC`)**: Clean Off-White canvas. Provides an airy, glare-free optical backdrop reminiscent of pristine white oak and bead-blasted aluminum studio desks. Pure white (`#FFFFFF`) is reserved strictly for elevated structural cards.

Subtle hairline dividers utilize `#E2E8F0` on light surfaces and `#334155` within dark control clusters.

## Typography

The type scale relies entirely on Plus Jakarta Sans to deliver crisp geometric curves balanced by tight modern terminals. 

- Large display headlines use tight negative letter-spacing (`-0.02em` to `-0.03em`) to mimic machined product titling.
- Small indicators, telemetry data, and mode indicators leverage uppercase styling with expanded letter-spacing (`0.02em` to `0.04em`) to project instrumentation clarity.
- Body text retains open apertures and generous line heights to preserve visual calm in dense technical readouts.

## Layout & Spacing

The interface employs a responsive 12-column fluid grid system pinned to a maximum container width of 1440px on desktop screens, shifting to an 8-column layout on tablet devices, and a 4-column layout on mobile viewports.

- **Desktop (>= 1024px)**: Generous 3rem outer margins allow cards and telemetry clusters to float unconstrained.
- **Tablet (768px - 1023px)**: 2rem outer margins and 1.25rem gutters keep multi-axis sliders and card layouts unified.
- **Mobile (< 768px)**: 1.25rem outer margins maximize canvas utility while safe areas protect fixed ergonomic control docks.

The vertical rhythm adheres strictly to an 8px baseline grid (with a 4px sub-grid for icons and telemetry tags). Spacing between decoupled surface modules remains expansive to evoke room ambiance and decluttered physical desk setups.

## Elevation & Depth

Visual depth is achieved through ambient, diffuse light cones and crisp, micro-fine boundaries rather than harsh, heavy drop shadows:

- **Flat / Canvas Level**: Base `#F8FAFC` background. Completely matte, grounding the interface.
- **Level 1 (Cards & Modules)**: Pure white `#FFFFFF` surfaces paired with a micro border (`1px solid #E2E8F0`) and an ambient, ultra-diffuse shadow: `0px 4px 20px -2px rgba(15, 23, 42, 0.04), 0px 1px 3px 0px rgba(15, 23, 42, 0.02)`.
- **Level 2 (Floating Controls & Hover States)**: `0px 12px 32px -4px rgba(15, 23, 42, 0.08), 0px 2px 6px 0px rgba(15, 23, 42, 0.03)`.
- **Translucent Overlays (Control Docks & Modals)**: Frosted glass constructed with `background: rgba(255, 255, 255, 0.8)`, `backdrop-filter: blur(16px)`, and an inner specular border `1px solid rgba(255, 255, 255, 0.6)`.
- **Active Light Glows**: Cyan and amber interactive components emit soft optical halos (`0px 0px 24px -4px rgba(14, 165, 233, 0.35)` and `0px 0px 24px -4px rgba(245, 158, 11, 0.35)`) signifying physical emission from the lamp diodes.

## Shapes

The design system uses a deliberate hierarchy of corner curvature to reflect high-end industrial product manufacturing:

- **Surface Modules & Cards**: Standardized to `1rem` (16px) or `1.5rem` (24px) corner radii (`rounded-2xl`), evoking the smooth edge-radii of CNC-machined metal enclosures.
- **Interactive Inputs & Nested Controls**: Styled at `0.5rem` (8px) for precise, tactile control definitions.
- **Status Tags, Dial Toggles, & Action Pills**: Full pill geometry (`rounded-full` / `9999px`) to distinguish actionable hardware triggers and mode switchers from structural content containers.

## Components

### Buttons
- **Primary**: Solid Matte Dark Slate (`#0F172A`) with crisp pure white text, full pill curvature (`rounded-full`), `space-md` horizontal padding, and subtle micro-scale down on active click (`scale(0.98)`).
- **Secondary**: Frosted white background, subtle hairline border (`#E2E8F0`), `#0F172A` text, shifting to a soft slate tint (`#F1F5F9`) on hover.
- **Accent Interactive**: Electric Cyan (`#0EA5E9`) or Warm Amber (`#F59E0B`) fill reserved for active lighting triggers, circadian synchronization, and hardware connection commands.

### Chips & Pill Tags
- Compact height (28px - 32px), pill-shaped (`rounded-full`), set with uppercase `label-sm` or `label-md` typography.
- Inactive state: `#F1F5F9` background with `#475569` text.
- Active state: Tinted cyan (`rgba(14, 165, 233, 0.12)`) with `#0284C7` text and an integrated 6px circular glowing LED indicator.

### Sliders (Circadian & Lux Calibration)
- Ergonomically thick (36px track height) with a continuous pill container.
- Background uses subtle continuous chromatic gradient tracks (e.g., cool daylight cyan `#38BDF8` transitioning to amber tungsten `#F59E0B`).
- Thumb is a crisp floating white disc with dual-ring elevation and physical drag feedback.

### Cards & Control Modules
- Rendered in pure `#FFFFFF` over `#F8FAFC`, contoured with `rounded-2xl` corners and hairline slate framing (`#E2E8F0`).
- Header areas feature integrated hardware telemetry icons, current lux/kelvin readouts, and quick-toggle affordances.

### Form Inputs & Text Fields
- Clean `#FFFFFF` fill with `1px solid #CBD5E1` boundary, transitioning to a focused state reinforced by a `2px` Electric Cyan outer ring (`#0EA5E9`) and zero offset.
- Floating minimalist micro-labels placed above or integrated directly into top borders.

### Checkboxes & Segmented Controls
- Segmented pill switches sit inside a recessed matte slate or light slate trough (`#E2E8F0`) with a spring-animated pure white pill slider indicating the current ergonomic preset.