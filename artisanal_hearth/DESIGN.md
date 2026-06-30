---
name: Artisanal Hearth
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
  on-surface-variant: '#54433e'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#86736d'
  outline-variant: '#d9c2ba'
  surface-tint: '#904b33'
  primary: '#88452d'
  on-primary: '#ffffff'
  primary-container: '#a65d43'
  on-primary-container: '#fff4f0'
  inverse-primary: '#ffb59c'
  secondary: '#805600'
  on-secondary: '#ffffff'
  secondary-container: '#ffc56c'
  on-secondary-container: '#785000'
  tertiary: '#6d5245'
  on-tertiary: '#ffffff'
  tertiary-container: '#886a5c'
  on-tertiary-container: '#fff3ef'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcf'
  primary-fixed-dim: '#ffb59c'
  on-primary-fixed: '#390c00'
  on-primary-fixed-variant: '#73351e'
  secondary-fixed: '#ffddb0'
  secondary-fixed-dim: '#f6bc64'
  on-secondary-fixed: '#291800'
  on-secondary-fixed-variant: '#614000'
  tertiary-fixed: '#ffdbcb'
  tertiary-fixed-dim: '#e3bfae'
  on-tertiary-fixed: '#2a170c'
  on-tertiary-fixed-variant: '#5a4135'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  headline-xl:
    fontFamily: Literata
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Literata
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Literata
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Literata
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  caption:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style
The design system is built on an **Artisanal & Organic** aesthetic, specifically tailored for a premium sourdough subscription service. The brand personality is grounded, warm, and deeply connected to the tactile process of baking. It targets quality-conscious consumers who value slow-living and heritage craftsmanship.

The visual style utilizes a **Tactile / Minimalist** hybrid approach. It avoids clinical precision in favor of "human" touches: subtle grain textures reminiscent of flour or handmade paper, soft organic shapes that mimic rising dough, and a warm, low-contrast atmosphere. The emotional goal is to evoke the scent of a kitchen at dawn—comforting, reliable, and authentic.

## Colors
The palette is derived from the natural lifecycle of a loaf. 
- **Primary (Terracotta):** Used for primary actions and key brand moments, representing the heat of the oven.
- **Secondary (Wheat Gold):** Used for highlights, rewards, and "freshness" indicators.
- **Tertiary (Crust Brown):** Used for high-contrast text and deep structural elements.
- **Neutral (Flour White):** The primary background color, providing a soft, non-reflective surface that feels like parchment.
- **Accent (Sage Green):** To be used sparingly for "Organic" or "Active Starter" status indicators.

## Typography
The typography strategy creates a dialogue between tradition and utility. 
- **Headlines:** Literata provides a "bookish" and scholarly warmth, suggesting the deep history of sourdough fermentation. Use it for all storytelling and page titles.
- **Body & UI:** Work Sans offers a grounded, neutral counter-balance. Its high legibility ensures that subscription data, delivery dates, and ingredient lists remain clear and professional.
- **Weight Usage:** Bold weights should be reserved for headlines. UI labels use Medium weight with slight tracking for a "stamped" appearance.

## Layout & Spacing
The design system employs a **Fluid Grid** with generous white space to prevent the UI from feeling cluttered or "industrial." 
- **Grid:** A 12-column layout for desktop, transitioning to 4 columns for mobile.
- **Rhythm:** An 8px base unit drives all padding and margins. 
- **Negative Space:** Elements should be given room to "breathe," mirroring the airy crumb of a well-proofed loaf. Vertical spacing between sections should be aggressive (80px+) to maintain an editorial, premium feel.

## Elevation & Depth
Depth is achieved through **Tonal Layers** and subtle textures rather than heavy shadows.
- **Surfaces:** Use slightly different shades of Neutral (Flour White) and light Wheat tints to separate content blocks. 
- **Texture:** A global, low-opacity "noise" or "paper grain" overlay should be applied to the background to break the digital perfection of the screen.
- **Shadows:** When necessary, use very soft, long, umber-tinted shadows (e.g., `rgba(78, 54, 42, 0.05)`) to simulate the gentle lift of an object resting on a tablecloth. Avoid harsh black shadows.
- **Borders:** Use thin, 1px borders in a muted Wheat shade to define inputs and cards without creating visual "noise."

## Shapes
The shape language is **Soft and Organic**. 
- **Corners:** Avoid sharp 90-degree angles. Use 8px (`rounded`) as the standard, but feel free to use irregular "blob" shapes for background decorations or image masks to represent the hand-shaped nature of artisanal bread.
- **Images:** Photography should always feature soft-focus backgrounds and natural lighting.

## Components
- **Buttons:** Primary buttons use the Terracotta background with Flour White text. Use a slightly higher corner radius (12px) than standard containers to make them feel "plump" and touchable.
- **Cards:** Cards should have a subtle 1px border in a "Crust" tint and no heavy shadow. On hover, they can lift slightly with a soft umber shadow.
- **Inputs:** Text fields should use a soft Wheat-tinted background rather than pure white, making the forms feel more integrated into the "paper" aesthetic.
- **Chips/Badges:** Use "Secondary" (Wheat Gold) with a low opacity for status tags like "Fermenting" or "Out for Delivery."
- **Progress Indicators:** Use a custom "Sourdough Starter" animation—a rising bubble effect—instead of a standard circular spinner to reinforce the brand narrative.
- **Lists:** Use custom icons for list bullets, such as a small wheat stalk or a simple hand-drawn dot.