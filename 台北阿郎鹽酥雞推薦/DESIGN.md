---
name: Night Market Premium
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
  on-surface-variant: '#e4bebc'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#ab8987'
  outline-variant: '#5b403f'
  surface-tint: '#ffb3b1'
  primary: '#ffb3b1'
  on-primary: '#680011'
  primary-container: '#ff535b'
  on-primary-container: '#5b000e'
  inverse-primary: '#bb152c'
  secondary: '#ffd795'
  on-secondary: '#422c00'
  secondary-container: '#fbb400'
  on-secondary-container: '#694900'
  tertiary: '#ffb781'
  on-tertiary: '#4e2500'
  tertiary-container: '#de7500'
  on-tertiary-container: '#452000'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3b1'
  on-primary-fixed: '#410007'
  on-primary-fixed-variant: '#92001c'
  secondary-fixed: '#ffdea9'
  secondary-fixed-dim: '#ffba27'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5e4100'
  tertiary-fixed: '#ffdcc4'
  tertiary-fixed-dim: '#ffb781'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#703800'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-xl:
    fontFamily: Epilogue
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Epilogue
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Epilogue
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-bold:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.0'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 16px
  margin-mobile: 20px
---

## Brand & Style
The brand personality bridges the gap between raw, energetic night market culture and modern culinary professionalism. This design system focuses on a **Modern-Tactile** style, utilizing high-contrast imagery against clean, structured layouts to elevate street food to a premium experience. 

The target audience consists of local food enthusiasts and urban commuters who value authenticity but expect a high level of hygiene and digital convenience. The emotional response should be one of immediate craving (appetite appeal) and reliability. The aesthetic uses "bold-local" elements—such as thick borders and vibrant accents—reinterpreted through a minimalist lens to ensure the interface remains uncluttered and functional on mobile devices.

## Colors
This design system utilizes a dark-mode default to emulate the atmosphere of a night market under neon and warm stall lights. 

- **Primary (Cinnabar Red):** Used for critical actions, branding, and highlighting "hot" or "signature" items. It evokes the traditional red lanterns and signage of Taipei.
- **Secondary (Golden Sizzle):** A warm yellow used for ratings, pricing, and accents. It represents the golden-brown crispiness of the chicken.
- **Tertiary (Amber Glow):** Used for hover states and secondary highlights to add depth to the warm palette.
- **Neutral (Charcoal & Smoke):** The background is a deep charcoal (#121212), providing a high-contrast canvas that makes food photography "pop." Surface levels use slightly lighter grays to create hierarchy.

## Typography
The typography is designed to be loud yet legible. **Epilogue** provides a heavy, geometric presence for headlines that mimics bold storefront signage. For Chinese characters, use a heavy Weight Sans-Serif (like Noto Sans TC Bold) to maintain the "street" impact.

**Be Vietnam Pro** is used for body text to maintain a friendly, approachable feel that ensures readability during long-form menu descriptions. **Space Grotesk** is reserved for technical labels, pricing, and nutritional info to provide a subtle "modern-industrial" edge. Use tight line-heights for headlines to create a compact, energetic feel.

## Layout & Spacing
The design system employs a **Fluid Grid** model optimized for mobile-first consumption. 
- Mobile: 4-column grid with 20px side margins.
- Desktop: 12-column grid with a max-width of 1280px.

A strict 8px spacing scale (Base 8) ensures a rhythmic vertical flow. Use generous padding (`lg` or `xl`) between major sections to provide "visual breathing room" against the dark background, while keeping internal component padding (`sm` or `md`) tighter to maintain a high-energy, "packed" market feel.

## Elevation & Depth
Depth is conveyed through **Tonal Layering** rather than heavy shadows. In this design system, higher elevation is represented by lighter charcoal surfaces.

- **Level 0 (Base):** #121212 (The street)
- **Level 1 (Cards/Sections):** #1E1E1E (The stall counter)
- **Level 2 (Popovers/Modals):** #2C2C2C (Floating elements)

To mimic the glow of street lamps, use **Ambient Shadows** with a Primary Red or Secondary Gold tint (low opacity, 10-15%) for active items or featured product cards. This creates a "neon-underglow" effect that guides the user's eye to high-value interactions.

## Shapes
The shape language is **Rounded (0.5rem base)**. This softens the aggressive high-contrast color palette, making the brand feel more inviting and "appetizing." 

Food cards and main containers should use `rounded-lg` (1rem) to create a friendly, modern container for imagery. Buttons and interactive chips use the same base roundedness to ensure a tactile, "clickable" appearance. Avoid sharp corners to distance the brand from a cold, corporate aesthetic.

## Components
- **Buttons:** Primary buttons are Solid Cinnabar Red with White bold text. Secondary buttons use a thick Charcoal stroke with Golden Yellow text. Use a "squishy" active state (slight scale down) to enhance the tactile feel.
- **Cards:** Food item cards feature full-bleed imagery at the top with a subtle gradient overlay at the bottom to ensure the Golden Yellow price labels are legible.
- **Chips/Categories:** Use outlined pills for food categories (e.g., "Chicken," "Vegetables," "Sides"). When selected, they fill with the Secondary Golden color and shift text to Black.
- **Inputs:** Search bars and form fields use Level 1 surfaces (#1E1E1E) with a subtle 1px border that glows Red when focused.
- **Lists:** Menu lists should feature a thumbnail on the left and a "Quick Add" (+) button on the right.
- **Floating Action Button (FAB):** A fixed "Cart" or "Order Now" button should be present on mobile, styled in high-contrast Golden Yellow with a deep shadow to distinguish it from the content.
- **Status Badges:** Use "Freshly Fried" or "Spicy" badges with small, expressive icons and Bold Label typography.