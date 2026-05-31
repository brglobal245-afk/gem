---
name: AURÉA
colors:
  surface: '#fcf9f4'
  surface-dim: '#dcdad5'
  surface-bright: '#fcf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ee'
  surface-container: '#f0ede9'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e5e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#4d463a'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f3f0eb'
  outline: '#7f7668'
  outline-variant: '#d0c5b5'
  surface-tint: '#745a27'
  primary: '#745a27'
  on-primary: '#ffffff'
  primary-container: '#c9a96e'
  on-primary-container: '#543d0c'
  inverse-primary: '#e4c285'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#685d49'
  on-tertiary: '#ffffff'
  tertiary-container: '#b9ac94'
  on-tertiary-container: '#49402d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdea4'
  primary-fixed-dim: '#e4c285'
  on-primary-fixed: '#261900'
  on-primary-fixed-variant: '#5a4312'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#f0e1c6'
  tertiary-fixed-dim: '#d3c5ac'
  on-tertiary-fixed: '#221b0a'
  on-tertiary-fixed-variant: '#4f4632'
  background: '#fcf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e5e2dd'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 40px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.15em
  button:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-desktop: 80px
  margin-tablet: 40px
  margin-mobile: 20px
  section-padding: 120px
---

## Brand & Style

The design system is engineered to evoke an atmosphere of heritage, exclusivity, and quiet luxury. It targets a discerning audience that values craftsmanship over trends. The visual language is deeply rooted in **Minimalism** and **Editorial Design**, utilizing extreme whitespace to frame products as pieces of art. 

The aesthetic response should be one of "Timeless Sophistication." By balancing the warmth of ivory and champagne with the structural weight of onyx, the interface feels both historically grounded and modern. The style avoids trendy UI effects (like glassmorphism or neomorphism) in favor of high-contrast layouts, precise typography, and tactile gold accents that mimic the physical presence of fine jewelry.

## Colors

The palette is a sophisticated interplay of warmth and depth. **Warm Cream (#FAF7F2)** and **Ivory (#F5EFE4)** serve as the primary canvas, providing a softer, more premium feel than pure white. **Gold (#C9A96E)** is used strategically for interactive elements and brand markers, while its darker counterpart **(#A07840)** provides depth for gradients or hover states.

**Onyx (#1A1A1A)** is the anchor, used for high-contrast typography and "Noir" sections—specialized layouts where the background shifts to dark to highlight diamond brilliance or high-carat pieces. **Champagne (#E8D9BF)** acts as a subtle divider and UI surface color, ensuring a soft transition between the cream backgrounds and the stark onyx text.

## Typography

This design system uses a classic serif/sans-serif pairing to distinguish between narrative and utility. **EB Garamond** (as the closest high-luxury alternative to Cormorant) is used for all headlines and display text, emphasizing the brand's editorial roots. It should be typeset with tight tracking for large displays and slightly more air for sub-headlines.

**Hanken Grotesk** (serving as a refined alternative to Jost) handles all functional UI, body copy, and labels. It provides a clean, architectural contrast to the serif. For navigation and labels, use the `label-caps` style with generous letter spacing to maintain a high-fashion, "spaced-out" look that feels premium and deliberate.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model on desktop to maintain a controlled, gallery-like experience. Central content is housed within a 1440px container. On mobile, the system shifts to a fluid 4-column layout.

Whitespace is treated as a core design element, not just a separator. **Section padding** is intentionally high (120px+) to allow the eye to rest and focus on one item at a time. The spacing rhythm is based on an 8px scale, but for editorial layouts, odd-numbered "optical" spacing is permitted to create asymmetrical, dynamic compositions.

## Elevation & Depth

This design system avoids heavy shadows and skeuomorphism. Depth is achieved through **Tonal Layers** and **Low-Contrast Outlines**.

- **Surfaces:** Use Ivory (#F5EFE4) for the main page body and Warm Cream (#FAF7F2) for elevated components like cards or menus.
- **Borders:** Instead of shadows, use 0.5px or 1px borders in Gold (#C9A96E) or Champagne (#E8D9BF) to define edges.
- **Shadows:** Only used for top-level modals or dropdowns. If used, they must be "Ambient Shadows"—extremely soft (20-40px blur), low opacity (5-10%), and tinted with the Primary Gold color to feel like light reflecting off precious metal.

## Shapes

The design system utilizes a **Sharp (0)** roundedness level. Straight edges and 90-degree corners communicate precision, architectural strength, and the "cut" of a diamond. This geometric rigor provides a stark, clean backdrop that allows the organic, flowing shapes of the jewelry photography to stand out. Only circles (e.g., color swatches or image carousels indicators) are permitted as exceptions to the square-edge rule.

## Components

### Buttons
- **Primary:** Solid Onyx (#1A1A1A) with White or Gold text. No border. Sharp corners.
- **Secondary:** Transparent background with a 1px Gold (#C9A96E) border.
- **Text Link:** Label-caps style with a subtle Gold underline that expands on hover.

### Input Fields
- Underline-only style (minimalist). A 1px Onyx line that turns Gold on focus.
- Labels remain in `label-caps` above the field at all times.

### Cards
- Zero-border or 1px Champagne border. 
- Image-centric with `display-sm` typography for product names and `body-md` for pricing.
- Hover state: Subtle scale-up of the image (1.05x) with a Gold overlay or border fade-in.

### Iconography
- Use ultra-thin (1pt) stroke weights.
- Icons should always be rendered in Gold or Onyx. 
- Avoid filled icons; stick to "Linear" styles to maintain the delicate visual weight.

### Navigation
- A centered, "floating" header or a fixed top bar with a Gold bottom divider.
- Search and Cart icons should be minimal and accompanied by small, serif-font counters.