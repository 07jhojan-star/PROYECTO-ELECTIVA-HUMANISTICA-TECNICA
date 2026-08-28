---
name: Epicurean Flow
colors:
  surface: '#fef8f4'
  surface-dim: '#ded9d5'
  surface-bright: '#fef8f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f2ef'
  surface-container: '#f3ede9'
  surface-container-high: '#ede7e3'
  surface-container-highest: '#e7e1de'
  on-surface: '#1d1b19'
  on-surface-variant: '#5a4139'
  inverse-surface: '#32302e'
  inverse-on-surface: '#f5f0ec'
  outline: '#8e7067'
  outline-variant: '#e3bfb4'
  surface-tint: '#ad3300'
  primary: '#a93200'
  on-primary: '#ffffff'
  primary-container: '#d14307'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb59e'
  secondary: '#5b5f63'
  on-secondary: '#ffffff'
  secondary-container: '#dde0e5'
  on-secondary-container: '#5f6368'
  tertiary: '#653ad6'
  on-tertiary: '#ffffff'
  tertiary-container: '#7e57f0'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#ffb59e'
  on-primary-fixed: '#390b00'
  on-primary-fixed-variant: '#842500'
  secondary-fixed: '#e0e3e8'
  secondary-fixed-dim: '#c3c7cc'
  on-secondary-fixed: '#181c20'
  on-secondary-fixed-variant: '#43474c'
  tertiary-fixed: '#e8deff'
  tertiary-fixed-dim: '#cdbdff'
  on-tertiary-fixed: '#20005f'
  on-tertiary-fixed-variant: '#4f1bc0'
  background: '#fef8f4'
  on-background: '#1d1b19'
  surface-variant: '#e7e1de'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Newsreader
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Newsreader
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  price-tag:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: '1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  container-margin: 20px
  gutter: 16px
---

## Brand & Style

The design system is crafted for high-end digital gastronomy, blending the tactile warmth of a physical menu with the efficiency of modern self-service technology. It targets diners who value both culinary excellence and frictionless ordering. 

The aesthetic identity is **Sophisticated Organic**. It utilizes a "Neo-Bistro" approach: combining high-contrast editorial typography with soft, inviting surfaces. The emotional response is one of trust, appetite stimulation, and effortless navigation. We avoid the clinical look of standard SaaS by using warm neutrals and rich accent colors that mimic natural ingredients. 

The UI prioritizes high-quality food photography, using it as a structural element rather than just decoration. Layouts are spacious, evoking the feeling of a clean table setting.

## Colors

This design system utilizes a palette rooted in culinary psychology. 

- **Primary (Terracotta):** Used exclusively for primary actions, price tags, and brand moments. It is the "appetite trigger."
- **Secondary (Charcoal):** Provides the grounding force for the design system. Used for headers, icons, and primary navigation to ensure a premium, authoritative feel.
- **Background (Cream):** A soft, off-white base that reduces eye strain compared to pure white and makes food photography pop with a natural glow.
- **Tertiary (Lavender):** An optional accent used sparingly for secondary tags (e.g., "Chef's Special" or "New") to provide a cool contrast to the warm primary tones.

## Typography

The typography strategy employs a "High-Low" pairing. **Newsreader** (Serif) is used for dish names and section headers to evoke the heritage of printed menus and premium dining. **Plus Jakarta Sans** (Sans-serif) handles all functional data—descriptions, modifiers, and navigation—to ensure maximum legibility on mobile devices under varying restaurant lighting.

- **Headlines:** Use Medium or Semi-Bold weights. Tighten letter spacing slightly for a more "locked-in" editorial look.
- **Body:** Use a generous line height (1.6) to ensure descriptions of ingredients are easy to scan.
- **Prices:** Should always be rendered in the Sans-serif font at a bold weight to ensure clarity during the checkout process.

## Layout & Spacing

The layout follows a **Fluid-Responsive Model** with a strong emphasis on the vertical scroll "Feed" experience on mobile.

- **Mobile (Default):** A single-column layout with 20px side margins. Elements like product cards should span the full width of the container.
- **Desktop:** A 12-column grid. Menus should utilize a "Sticky Sidebar" for categories on the left, a central "Menu Feed," and a "Persistent Cart" on the right.
- **Rhythm:** Use the 4px baseline grid. Components should be separated by `lg` (24px) spacing to maintain a sense of luxury and avoid clutter.

## Elevation & Depth

To maintain the "Sophisticated Organic" feel, this design system avoids heavy shadows. Depth is created through **Tonal Elevation** and soft, ambient occlusion.

1.  **Level 0 (Base):** The Cream (#FFF9F5) background.
2.  **Level 1 (Cards):** Pure white (#FFFFFF) surfaces with a 1px stroke of #E9ECEF and a very soft, diffused shadow (0px 4px 20px rgba(33, 37, 41, 0.05)).
3.  **Level 2 (Active/Overlays):** Used for bottom sheets (modifiers) and modals. These use a more pronounced shadow (0px 10px 40px rgba(33, 37, 41, 0.12)) and a background blur on the content underneath to focus the user’s attention on the selection.

## Shapes

The shape language is friendly and modern. A default `rounded-md` (8px) is used for small interactive elements like checkboxes and steppers, while `rounded-lg` (16px) is the standard for product cards and primary buttons. Top-level containers like "Food Category" images should use `rounded-xl` (24px) or even fully rounded "pill" shapes for a soft, approachable feel.

## Components

### Buttons
- **Primary:** Terracotta (#D9480F) background, white text, 16px radius. On hover/active, darken the background by 10%.
- **Secondary:** Transparent background with a 2px Charcoal (#212529) border. For "Add to Cart" functions inside a list.
- **Floating Action Button (FAB):** A large "View Order" button should be pinned to the bottom-center on mobile, using the Primary color and high elevation.

### Product Cards
- Cards must feature a 1:1 or 4:3 aspect ratio image at the top.
- Typography within the card should place the Price at the top-right and the Dish Name at the bottom-left, overlapping the image or immediately below it in a white container.

### Input Fields & Steppers
- **Steppers (Quantity):** Use a horizontal pill shape with a Charcoal background and white "+" and "-" icons. This makes the most frequent interaction (adjusting quantity) feel tactile and distinct.
- **Search:** A full-width input with a Cream-darker (#F1F3F5) background and no border to blend seamlessly into the header.

### Chips & Tags
- Used for dietary restrictions (e.g., "Vegan," "Gluten-Free"). Use a small, bold Sans-serif font with a low-saturation background color (e.g., light green for vegan) to avoid competing with the Primary Terracotta.