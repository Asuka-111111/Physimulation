---
name: Executive Intelligence Interface
colors:
  surface: '#fbf8ff'
  surface-dim: '#dad9e4'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f2fe'
  surface-container: '#eeedf8'
  surface-container-high: '#e8e7f2'
  surface-container-highest: '#e3e1ed'
  on-surface: '#1a1b23'
  on-surface-variant: '#434655'
  inverse-surface: '#2f3038'
  inverse-on-surface: '#f1effb'
  outline: '#747686'
  outline-variant: '#c4c5d7'
  surface-tint: '#2051da'
  primary: '#0040c7'
  on-primary: '#ffffff'
  primary-container: '#2d5be3'
  on-primary-container: '#e2e5ff'
  inverse-primary: '#b7c4ff'
  secondary: '#4d5b94'
  on-secondary: '#ffffff'
  secondary-container: '#b0befd'
  on-secondary-container: '#3d4c83'
  tertiary: '#8c3200'
  on-tertiary: '#ffffff'
  tertiary-container: '#b44200'
  on-tertiary-container: '#ffe0d5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#001551'
  on-primary-fixed-variant: '#0039b4'
  secondary-fixed: '#dce1ff'
  secondary-fixed-dim: '#b7c4ff'
  on-secondary-fixed: '#04164d'
  on-secondary-fixed-variant: '#35437a'
  tertiary-fixed: '#ffdbce'
  tertiary-fixed-dim: '#ffb598'
  on-tertiary-fixed: '#370f00'
  on-tertiary-fixed-variant: '#7e2c00'
  background: '#fbf8ff'
  on-background: '#1a1b23'
  surface-variant: '#e3e1ed'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
spacing:
  unit: 4px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 80px
---

## Brand & Style
The design system is engineered for a premium enterprise environment, prioritizing authority, clarity, and intellectual rigor. The aesthetic draws from high-end consultancy editorial styles, utilizing a **High-Contrast Minimalist** approach. 

The visual language is defined by sharp geometry, extreme precision, and an absence of decorative "softness." It avoids all rounded corners and shadows, relying instead on rigid grid structures, intentional whitespace, and a striking primary blue to denote action and importance. The emotional response is one of serious, data-driven confidence and professional excellence.

## Colors
The palette is rooted in a professional triad of Electric Blue, Slate Indigo, and Burnt Orange.

- **Primary Blue (#426CF4):** Used exclusively for primary calls to action, active states, and critical highlights.
- **Slate Indigo (#6674AE):** Acts as the secondary color for high-impact sections, headers, or footers.
- **Burnt Orange (#B34200):** A high-contrast tertiary color used for emphasis, status, or specific data alerts.
- **Functional Grays:** The neutral tone (#767680) ensures sophisticated legibility and professional anchoring for borders and metadata.
- **System States:** Error states use a standard error red, while the system leans heavily on the primary blue and burnt orange to communicate importance and focus.

## Typography
The typography system creates a hierarchy of "Editorial Authority." 

**Montserrat** is used for all headlines to provide a geometric, modern, and architectural feel. Large display titles should use the ExtraBold (800) weight with tight letter spacing.

**Inter** handles all long-form reading and UI labels. It is chosen for its neutral, highly legible characteristics. Body text should maintain a generous line height (1.6) to facilitate deep focus during long-form article consumption. All labels and overlines must be set in uppercase with slight tracking to reinforce the professional tone.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy on desktop and a fluid system on mobile. 

- **Grid:** A strict 12-column grid is used for all pages.
- **Alignment:** Strictly left-aligned. Avoid centered content, even for hero sections, to maintain the "asymmetric balance" typical of high-end editorial design.
- **Rhythm:** Spacing is based on a 4px baseline, but large sections should be separated by significant whitespace (64px to 120px) to give content "room to breathe."
- **Decoration:** Use `+` grid markers at the intersection of major border lines. Subtle 45-degree diagonal lines may be used as background watermarks in large empty containers.

## Elevation & Depth
This design system is **strictly flat**. 

- **No Shadows:** Depth is never communicated through drop shadows or glows.
- **Tonal Layering:** Hierarchy is achieved through background color shifts (e.g., a Slate Indigo header atop a White body).
- **Borders:** Use 1px solid borders for all containment. Light mode uses `#767680` for subtle separation and `#426CF4` for high-contrast emphasis on active elements.
- **Intersections:** Where horizontal and vertical borders meet, use a small `+` symbol (12px) to emphasize the grid-based construction of the UI.

## Shapes
The shape language is defined by **Absolute Rectilinearity**. 

Every element—including buttons, input fields, cards, and tags—must have a 0px border radius. This sharp geometry conveys a sense of precision and technical sophistication. No exceptions are permitted for "softening" the UI.

## Components

### Buttons
- **Primary:** Background `#426CF4`, Text `#FFFFFF`, 0px radius. Hover state: Slate Indigo (#6674AE).
- **Secondary:** Transparent background, 1px solid `#426CF4` border, Text `#426CF4`.
- **Tertiary/Ghost:** Text only with a 1px underline that disappears on hover.

### Cards & Containers
- Cards are defined by a 1px solid border (`#767680`).
- No shadows. 
- Padding should be generous (minimum 32px) to maintain the premium feel.
- Header cards may use the Slate Indigo background with White text.

### Input Fields
- 1px solid border.
- Label sits strictly above the field in uppercase Inter 14px (Label-MD).
- Focused state: Border becomes Primary Blue (#426CF4).

### Lists & Forums
- Use horizontal dividers (1px solid) between forum posts.
- Metadata (Author, Date, Category) should be separated by a vertical pipe `|`.
- Article thumbnails should be sharp-edged with no styling overlays.

### Decorative Elements
- **The "Grid Plus":** Place a small `+` icon at the corners of major section containers to simulate a drafting or architectural blueprint.
- **Diagonal Accents:** Use thin 1px diagonal lines (45-degree angle) in the background of page headers to fill "dead" whitespace.