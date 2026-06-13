---
name: Horizon Sovereignty
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#43474e'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#476083'
  primary: '#000613'
  on-primary: '#ffffff'
  primary-container: '#001f3f'
  on-primary-container: '#6f88ad'
  inverse-primary: '#afc8f0'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#050606'
  on-tertiary: '#ffffff'
  tertiary-container: '#1d1f1f'
  on-tertiary-container: '#858687'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#afc8f0'
  on-primary-fixed: '#001c3a'
  on-primary-fixed-variant: '#2f486a'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-sm:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
The design system is engineered to evoke a sense of exclusivity, heritage, and meticulous precision. Targeted at ultra-high-net-worth individuals, the brand personality is authoritative yet welcoming, mirroring the service of a private concierge. 

The aesthetic blends **Modern Corporate** structure with **Minimalist Luxury**. It prioritizes high-end editorial layouts, expansive whitespace, and a restrained use of gold to signify value without ostentation. Visual motifs should focus on the quiet majesty of mountain ranges, the mathematical beauty of Islamic geometric patterns, and the sleek engineering of private aviation and luxury seafaring. All imagery must adhere to cultural sensitivities, omitting nightlife, alcohol, and female subjects, focusing instead on architecture, landscapes, and the mechanics of premium travel.

## Colors
The palette is rooted in a triad of prestige. 
- **Deep Navy Blue (#001F3F)**: Serves as the primary anchor, used for headers, heavy-weight typography, and primary brand surfaces. It represents stability and depth.
- **Luxury Gold (#D4AF37)**: Used as a precise accent color for call-to-actions, trim details, and active states. It should be used sparingly to maintain its perceived value.
- **Clean White (#FFFFFF)**: The canvas for the experience, ensuring the UI feels airy and expansive.
- **Off-White (#F5F5F5)**: Used for subtle section nesting and background differentiation to prevent eye strain.

## Typography
The typography strategy relies on the contrast between the timeless, high-contrast strokes of **Playfair Display** and the geometric clarity of **Montserrat**. 

Headlines should utilize generous tracking for a more "breathable" feel. For all uppercase labels, a letter-spacing of 0.1em is mandatory to maintain a premium, editorial look. Body text is set with a slightly increased line height (1.6) to ensure effortless readability during long-form itinerary reviews.

## Layout & Spacing
This design system utilizes a **Fixed Grid** model for desktop to maintain a controlled, high-end editorial feel, transitioning to a fluid model for mobile devices.

- **Desktop**: 12-column grid with 24px gutters. Content is centered within a 1280px container.
- **Tablet**: 8-column grid with 20px gutters.
- **Mobile**: 4-column grid with 16px gutters and 20px side margins.

Vertical rhythm is strictly maintained in increments of 8px. Large sections should be separated by significant whitespace (80px to 120px) to signify a transition in narrative or service offering.

## Elevation & Depth
Depth is conveyed through **Low-Contrast Outlines** and **Tonal Layering** rather than aggressive shadows. 

- **Surface Tiers**: The base layer is White (#FFFFFF). Secondary interactive elements sit on an Off-White (#F5F5F5) surface with a 1px border of #E0E0E0.
- **Shadows**: When required for depth (such as floating navigation), use a single, highly diffused "Ambient" shadow: `0px 10px 40px rgba(0, 31, 63, 0.05)`.
- **Gold Trim**: Use a 2px Gold (#D4AF37) top-border on cards or a left-border on active list items to denote "Royal" status or selection.

## Shapes
To reinforce the "Corporate" and "Architectural" nature of the brand, this design system uses **Sharp (0px)** corners. This reflects the precision of modern architecture and the crisp edges of professional documentation. 

Circular elements are permitted only for specific functional icons or user avatars to provide a singular point of visual softness against the structural grid.

## Components

### Buttons
- **Primary**: Solid Deep Navy (#001F3F) background, White text, 0px radius. On hover, a 2px Gold bottom-border slides in.
- **Ghost**: Transparent background, 1px Gold border. Text in Deep Navy. Hover state fills the background with a very pale Gold tint (5% opacity).

### Cards
Cards feature a 1px #E0E0E0 border and 0px corners. On hover, the card should subtly lift (4px transition) and the border color shifts to Gold (#D4AF37). Imagery within cards should use a subtle dark-to-transparent gradient overlay to ensure white typography remains legible.

### Navigation
A sticky top-bar with a White background and a 1px Deep Navy bottom border. Navigation links use `label-md` typography. The active link is denoted by a Gold underline that spans the width of the word.

### Input Fields
Fields are represented by a single Deep Navy bottom-border (1px). When focused, the border thickens to 2px and turns Gold. Labels should float above the line in `label-md` style.

### Itinerary Chips
Small, Deep Navy outlined rectangles with `label-md` text. Used to denote travel duration, transport type (e.g., "Private Jet"), or architectural style (e.g., "Moorish").