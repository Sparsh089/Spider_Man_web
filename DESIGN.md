---
name: Spider-Verse Editorial
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e7bdb8'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#ad8884'
  outline-variant: '#5d3f3c'
  surface-tint: '#ffb4ac'
  primary: '#ffb4ac'
  on-primary: '#690007'
  primary-container: '#e62429'
  on-primary-container: '#ffffff'
  inverse-primary: '#c00016'
  secondary: '#afc8f0'
  on-secondary: '#163152'
  secondary-container: '#2f486a'
  on-secondary-container: '#9eb7de'
  tertiary: '#00dddd'
  on-tertiary: '#003737'
  tertiary-container: '#008484'
  on-tertiary-container: '#ffffff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ac'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#93000e'
  secondary-fixed: '#d4e3ff'
  secondary-fixed-dim: '#afc8f0'
  on-secondary-fixed: '#001c3a'
  on-secondary-fixed-variant: '#2f486a'
  tertiary-fixed: '#00fbfb'
  tertiary-fixed-dim: '#00dddd'
  on-tertiary-fixed: '#002020'
  on-tertiary-fixed-variant: '#004f4f'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-hero:
    fontFamily: Anton
    fontSize: 120px
    fontWeight: '400'
    lineHeight: 110px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Anton
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 52px
  headline-md:
    fontFamily: Anton
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-tech:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.1em
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  panel-skew: -3deg
---

## Brand & Style
The design system captures the frenetic, multi-sensory energy of a high-end cinematic experience. It targets an audience that appreciates both pop-culture lore and sophisticated editorial design. The brand personality is aggressive, heroic, and technologically advanced, blending the raw "street" aesthetic of urban graffiti with the precision of a luxury tech interface.

The design style is a hybrid of **High-Contrast Bold** and **Modern Brutalism**. It utilizes the "Spider-Verse" visual language—specifically chromatic aberration, halftone screen textures, and skewed geometry—to create a sense of motion and depth. The UI should feel like a living comic book: tactile, rhythmic, and uncompromisingly vibrant.

## Colors
The palette is rooted in a "Carbon Black" darkness to allow the heroic tones to pop with maximum luminosity. 
- **Deep Spider-Red (#E62429):** Used for primary actions, critical branding, and "hero" moments.
- **Midnight Blue (#001F3F):** Used for deep backgrounds, secondary containers, and tonal depth.
- **Electric Cyan (#00FFFF):** Reserved for "Web-Tech" highlights, data visualizations, and interactive hover states.
- **Paper White (#F4F4F4):** Used sparingly for high-contrast typography and "ink splatter" accents.

Texture overlays (halftone dots) should use a multiplication blend mode over the Midnight Blue and Spider-Red surfaces to add grit and cinematic grain.

## Typography
Typography is the core of this design system's impact. **Anton** provides a powerful, condensed verticality reminiscent of vintage comic mastheads. It should always be used in uppercase with tight tracking. **Inter** provides the necessary legibility for long-form editorial content, acting as a clean anchor to the aggressive headers. **Space Grotesk** is introduced for labels and technical data, providing a futuristic, geometric "tech-suit" vibe.

For "hero" moments, apply a subtle CSS text-shadow in Cyan and Red (1px offset) to mimic the chromatic aberration effect seen in modern animation.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a heavy emphasis on "Comic-Panel" compositions.
- **Grid:** 12-column grid for desktop with wide 24px gutters.
- **Asymmetry:** Content should frequently break the grid. Use 3-degree skews on container edges to create a sense of kinetic energy.
- **Panel Logic:** Group related content in boxes with heavy 4px or 8px borders. These "panels" should overlap slightly to create depth.
- **Responsive:** On mobile, panels stack vertically, but maintain their skewed borders and high-contrast margins.

## Elevation & Depth
Depth is created through **Tonal Layering** and **Graphic Overlays** rather than soft shadows.
- **Layers:** Use "Carbon Black" as the base, "Midnight Blue" for mid-ground panels, and "Spider-Red" for foreground elements.
- **Halftone Blurs:** Instead of standard box-shadows, use halftone dot gradients to suggest shadow.
- **Z-Index:** Interactive elements (cards) should "pop" upward on hover, increasing their skew angle and revealing a Cyan "web-glow" underneath.
- **Glass:** Use background-blur (12px) on tech-related overlays, tinted with a faint Cyan hue to simulate high-tech lenses.

## Shapes
The shape language is **Sharp (0)**. Everything in this design system is built on hard angles, triangles, and parallelograms. Soft corners are non-existent, reflecting the sharp, jagged edges of "thwip" sound effects and glass shards. Use diagonal cuts on button corners and container edges to reinforce the aggressive, heroic aesthetic.

## Components
- **Sticky Web Buttons:** Rectangular buttons with a heavy 4px border. On hover, the button should "stretch" (scale slightly) and the background should swap from Red to Cyan. Use a "thwip" animation transition.
- **Comic Panels:** Cards used for news or character profiles. Features a heavy black border, a halftone-pattern background, and a skewed 3-degree angle. Titles should overlap the top border in a "sticker" style.
- **Tech Chips:** Small, Electric Cyan outlines with Space Grotesk text, used for metadata or suit specs.
- **Web-Pattern Inputs:** Form fields featuring a subtle, low-opacity web-tracery pattern in the background. Focused states use a vibrant Cyan glow.
- **Ink-Splatter Lists:** Standard lists where the bullet point is a randomized "ink blot" or "spider icon" in high-contrast Red.
- **Glitch Dividers:** Horizontal rules that feature a "glitch" effect (staggered segments) instead of a solid line.