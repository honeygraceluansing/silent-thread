---
name: Silent Narrative
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#434843'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#737872'
  outline-variant: '#c3c8c1'
  surface-tint: '#506354'
  primary: '#334537'
  on-primary: '#ffffff'
  primary-container: '#4a5d4e'
  on-primary-container: '#c0d5c2'
  inverse-primary: '#b7ccb9'
  secondary: '#845333'
  on-secondary: '#ffffff'
  secondary-container: '#fdbb94'
  on-secondary-container: '#78492a'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cca830'
  on-tertiary-container: '#4f3e00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d3e8d5'
  primary-fixed-dim: '#b7ccb9'
  on-primary-fixed: '#0e1f13'
  on-primary-fixed-variant: '#394b3d'
  secondary-fixed: '#ffdbc8'
  secondary-fixed-dim: '#fab891'
  on-secondary-fixed: '#321300'
  on-secondary-fixed-variant: '#683c1e'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.8'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1140px
  gutter: 24px
  margin-mobile: 20px
  section-gap-desktop: 160px
  section-gap-mobile: 80px
---

## Brand & Style

This design system centers on a "Modern Minimalist" aesthetic with a cinematic, editorial soul. It is designed for mystery-style storytelling where the interface acts as a quiet stage for the narrative to unfold. The brand personality is reflective, intellectual, and intentionally paced, avoiding the frantic energy of traditional marketing.

The UI evokes a sense of discovery through expansive whitespace, high-quality typography, and a deliberate lack of decorative clutter. It balances the warmth of human touch with the precision of modern digital design, aiming for an emotional response of calm curiosity and quiet sophistication.

## Colors

The palette is rooted in soft, organic neutrals that mimic high-quality paper and natural environments.

- **Primary (Deep Forest Green):** Used for grounding elements, primary actions, and moments of narrative depth.
- **Secondary (Muted Terracotta):** An accent for human warmth, highlighting interactive story elements or "clues."
- **Tertiary (Soft Gold):** Used sparingly for subtle highlights and premium flourishes.
- **Neutral (Cream & Warm Grey):** The foundation of the design system, used for backgrounds and containers to maintain a soft, non-clinical feel.

The color strategy relies on low-saturation transitions to maintain a mysterious, atmospheric mood.

## Typography

Typography is the primary vehicle for the narrative. 

- **Playfair Display** provides an authoritative, literary weight for headlines. It should be used with tight letter-spacing in large formats to create a "title sequence" feel.
- **Inter** handles the functional and long-form reading aspects. High line-height (1.8) for body text is mandatory to ensure a relaxed reading pace and to honor the minimalist aesthetic.
- **Label Caps** are used for metadata, categories, and small navigational cues, providing a structured, modern contrast to the flowing serif headlines.

## Layout & Spacing

The layout follows a **fixed grid** philosophy for desktop to maintain editorial control over line lengths, switching to a fluid model for mobile.

- **Whitespace as Content:** Spacing is aggressive. Sections are separated by large vertical gaps (160px) to allow the reader's eyes to rest between story beats.
- **The Golden Ratio:** Use 1:1.618 ratios for image-to-text blocks to create a naturally pleasing visual hierarchy.
- **Centering:** Use centered layouts for pivotal narrative moments to draw the user into the "heart" of the mystery.

## Elevation & Depth

This system rejects heavy shadows in favor of **Tonal Layers** and **Subtle Outlines**.

- **Surfaces:** Depth is created by placing white containers (`#FFFFFF`) against cream backgrounds (`#F9F7F2`).
- **Outlines:** Use ultra-thin (1px), low-contrast borders in a slightly darker warm grey to define cards and inputs.
- **Shadows:** Only use "Ambient Shadows"—extremely diffused, 10-15% opacity, with a slight warm tint to match the secondary color. They should appear more like a soft glow than a physical drop shadow.
- **Glassmorphism:** Reserved exclusively for navigation bars to allow the narrative content to "peek through" as the user scrolls.

## Shapes

The shape language is **Soft (0.25rem)**. 

While the brand is modern, sharp corners feel too aggressive for a hopeful narrative, and fully rounded "pill" shapes feel too playful/tech-centric. Small radii on buttons and cards provide a sophisticated, tailored feel that suggests a high-end physical book or a curated gallery.

## Components

- **Buttons:** Primary buttons use a solid Forest Green fill with white text. Secondary buttons use a ghost style with a 1px Forest Green border. All buttons use 0.25rem corners and a slight letter-spacing on the label.
- **Cards:** Cards should have no background fill (transparent) or a solid white fill with a thin warm-grey border. Use ample internal padding (32px-48px) to keep text away from the edges.
- **Input Fields:** Minimalist underlines or 1px borders. Focus states should transition the border color to Muted Terracotta.
- **Progress Indicators:** For storytelling, use thin, horizontal lines that slowly fill with the Forest Green color, avoiding circular "loading" spinners which break the immersion.
- **Narrative Dividers:** Instead of standard horizontal rules, use a small Soft Gold diamond or a short, centered 1px line to separate story segments.