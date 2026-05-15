---
name: Design System
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#544247'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#877177'
  outline-variant: '#dac0c6'
  surface-tint: '#a03964'
  primary: '#a03964'
  on-primary: '#ffffff'
  primary-container: '#ff85b2'
  on-primary-container: '#781945'
  inverse-primary: '#ffb0c9'
  secondary: '#006a65'
  on-secondary: '#ffffff'
  secondary-container: '#6bf5eb'
  on-secondary-container: '#006f69'
  tertiary: '#665f34'
  on-tertiary: '#ffffff'
  tertiary-container: '#b6ad7b'
  on-tertiary-container: '#474119'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e3'
  primary-fixed-dim: '#ffb0c9'
  on-primary-fixed: '#3e001f'
  on-primary-fixed-variant: '#81204c'
  secondary-fixed: '#6ef7ee'
  secondary-fixed-dim: '#4cdbd1'
  on-secondary-fixed: '#00201e'
  on-secondary-fixed-variant: '#00504c'
  tertiary-fixed: '#eee3ad'
  tertiary-fixed-dim: '#d1c794'
  on-tertiary-fixed: '#201c00'
  on-tertiary-fixed-variant: '#4e471f'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
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
  lg: 40px
  xl: 64px
  gutter: 20px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style
The design system is engineered to capture the infectious energy and polished aesthetic of idol culture and high-end mobile gacha interfaces. The brand personality is celebratory, vibrant, and fan-centric, aiming to evoke a sense of "oshigoto" (supporting one's favorite idol) through every interaction. 

The visual style is a fusion of **Tactile Modernism** and **High-Contrast Anime Aesthetics**. It utilizes a layered approach where information is presented in clean, modular cards that feel like collectible physical goods. The interface remains lightweight and accessible by balancing heavy saturation with generous white space and sharp, modern typography, ensuring that the merchandising—the "stars" of the show—remains the focal point.

## Colors
The palette is anchored by a high-energy "Idol Pink" and a refreshing "Performance Teal." These two primary colors provide a dynamic contrast that drives the user’s eye toward calls to action and active states. 

- **Pink (#FF85B2):** Used for primary actions, branding elements, and highlighting rarity.
- **Teal (#26C2B9):** Used for secondary features, success states, and navigational accents to balance the warmth of the pink.
- **Pastel Yellow (#FFF4BD):** Reserved for "Gacha" elements, limited edition badges, and special alerts, evoking a "gold rarity" feel.
- **Neutrals:** A pure white surface is used for primary cards, while a very soft pink tint is applied to the global background to maintain the energetic atmosphere without the harshness of pure grey.

## Typography
To ground the colorful and busy UI, this design system utilizes **Plus Jakarta Sans**. Its geometric yet friendly curves perfectly complement the anime aesthetic while providing the legibility required for an e-commerce platform.

Headlines are set with heavy weights (Bold to ExtraBold) to mimic the impactful "title cards" found in gacha games. Body text is kept clean with standard weights and generous line heights to ensure product descriptions remain readable. Labels and prices utilize an uppercase, slightly tracked-out style to create a distinct hierarchy between editorial content and functional metadata.

## Layout & Spacing
The design system employs a **12-column fluid grid** for desktop and a **4-column grid** for mobile devices. Layouts are card-centric, drawing inspiration from gacha character selection screens.

Spacing follows an 8px base unit. Small units (4px, 8px, 12px) are used within cards to keep content compact and "collectible," while larger units (24px, 40px) define the relationships between major sections. Margins are kept tight to maximize screen real estate for visual merchandise, while gutters of 20px ensure that even high-density grids remain organized and scannable.

## Elevation & Depth
Depth in this design system is created through a mix of **Tonal Layering** and **Tinted Ambient Shadows**. Surfaces do not use generic grey shadows; instead, shadows carry a very subtle pink or teal tint depending on the surface color.

- **Level 1 (Base):** White surfaces with a soft, 15% opacity shadow (Pink-tinted) to lift cards from the tinted background.
- **Level 2 (Interactive):** Hover states increase shadow spread and decrease blur, making the card feel like it is physically moving toward the user.
- **Overlays:** Modals and menus use a high-blur backdrop filter (glassmorphism) with a 20% white tint to maintain focus on the content while keeping the vibrant background colors visible.

## Shapes
The shape language is defined by a consistent **Rounded (0.5rem)** approach. This softening of the UI removes the corporate "sharpness" and replaces it with a friendly, inviting feel characteristic of entertainment interfaces.

- **Standard Elements:** 8px (0.5rem) corner radius for small buttons and input fields.
- **Container/Card Elements:** 16px (1rem) corner radius for product cards and main containers.
- **Pill Elements:** 32px or full-round radius for tags, chips, and "Buy Now" buttons to create high visual contrast against rectangular product imagery.

## Components

### Buttons & Inputs
Buttons feature high-contrast fills (Pink for Primary, Teal for Secondary) with bold, centered text. Primary buttons should have a slight 2px bottom border of a darker shade of pink to give them a "pressed" feel. Input fields use a soft 1px teal border that thickens and glows when focused.

### Cards
Product cards are the core component. They feature a full-bleed image at the top, a 16px padding area for the title and price, and a "Rarity Ribbon" or "Collection Tag" in the top-right corner. Cards should have a subtle white inner-stroke to make them pop against darker image assets.

### Chips & Badges
Chips are used for category filtering and item attributes. They are fully rounded (pill-shaped) and utilize a "soft-fill" (15% opacity of the brand colors) with high-contrast text to remain legible without being visually overwhelming.

### Gacha Elements
Incorporate a "Quick View" modal that mimics the "New Pull" screen of a game, featuring high-saturation backgrounds, star ratings for items, and a prominent, pulsating "Add to Cart" button.