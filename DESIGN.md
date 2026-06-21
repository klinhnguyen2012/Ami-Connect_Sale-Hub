---
name: AMI CONNECT SALES HUB
colors:
  surface: '#f6fafe'
  surface-dim: '#d6dade'
  surface-bright: '#f6fafe'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f4f8'
  surface-container: '#eaeef2'
  surface-container-high: '#e4e9ed'
  surface-container-highest: '#dfe3e7'
  on-surface: '#171c1f'
  on-surface-variant: '#434656'
  inverse-surface: '#2c3134'
  inverse-on-surface: '#edf1f5'
  outline: '#737688'
  outline-variant: '#c3c5d9'
  surface-tint: '#004ee8'
  primary: '#0046d4'
  on-primary: '#ffffff'
  primary-container: '#1f5eff'
  on-primary-container: '#f0f0ff'
  inverse-primary: '#b6c4ff'
  secondary: '#00629d'
  on-secondary: '#ffffff'
  secondary-container: '#69b6fd'
  on-secondary-container: '#004673'
  tertiary: '#545656'
  on-tertiary: '#ffffff'
  tertiary-container: '#6d6e6e'
  on-tertiary-container: '#f1f1f2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#001550'
  on-primary-fixed-variant: '#003ab2'
  secondary-fixed: '#cfe5ff'
  secondary-fixed-dim: '#99cbff'
  on-secondary-fixed: '#001d34'
  on-secondary-fixed-variant: '#004a78'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#f6fafe'
  on-background: '#171c1f'
  surface-variant: '#dfe3e7'
typography:
  display-xl:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-md:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Manrope
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is built to bridge the gap between high-tech SaaS efficiency and the nurturing, aspirational world of children's education. It targets internal staff and sales teams, empowering them with a professional environment that feels premium yet inherently friendly.

The aesthetic follows a **Modern Startup / Glassmorphic** direction. It draws heavily from the "Apple" school of thought: immense whitespace, soft depth through frosted glass textures, and a strict adherence to a harmonious blue-centric palette. The visual narrative centers on "The Sky," using subtle gradients and floating 3D elements to evoke feelings of potential, growth, and clarity. By utilizing translucent surfaces and deep shadows, the interface feels lightweight and intelligent, reflecting the AI-driven nature of the platform.

## Colors

The palette is anchored by **Deep Blue (#1F5EFF)**, representing authority, trust, and the "Core" of the training hub. This is contrasted by **Sky Blue (#6BB8FF)**, which is used for interactive states, progress tracking, and secondary highlights to keep the UI energetic and approachable.

White is used as the primary surface color to maintain a clean "Modern Startup" look. Backgrounds use a very light cool-gray (neutral) to allow white cards to "pop" via elevation. Glassmorphism effects should utilize high-transparency white fills with a heavy backdrop blur (20px-40px) to create the signature frosted appearance seen in the reference visuals.

## Typography

This design system uses **Hanken Grotesk** for headlines to provide a sharp, contemporary, and technical feel. It is paired with **Manrope** for body text and labels to maintain a sense of balance and warmth. 

Headlines should utilize slightly tight letter-spacing to mimic premium editorial layouts. Body text is prioritized for legibility with a generous line height. For labels and captions, uppercase treatment is encouraged to differentiate them from narrative content while maintaining a structured, professional hierarchy.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for core content sections, centered within a maximum width of 1280px. This ensures the dashboard content remains readable and scannable on large monitors without excessive horizontal eye movement.

A 12-column grid is used for desktop, shifting to a 4-column grid for mobile. Spacing follows an 8px rhythmic scale. To achieve the "floating" aesthetic, cards and panels should have generous internal padding (32px+) and be separated by significant vertical gaps (48px-64px), creating an airy, light-filled atmosphere.

## Elevation & Depth

Visual hierarchy is established through **Glassmorphism** and **Ambient Shadows**. Instead of traditional solid borders, surfaces use a combination of:
1.  **Backdrop Blur:** 20px to 40px blur on semi-transparent layers.
2.  **Inner Glow:** A 1px semi-transparent white border on the top and left edges to simulate light hitting a glass edge.
3.  **Soft Shadows:** Multi-layered shadows using the Primary Deep Blue tinted at very low opacity (3-5%) to give the impression that elements are floating in a three-dimensional space rather than sitting on a flat page.

Higher elevation tiers (e.g., modals, active training cards) should have increased shadow spread and higher backdrop blur intensity.

## Shapes

The shape language is defined by **large, friendly radiuses**. Standard UI components like input fields and small buttons use a 0.5rem (8px) radius. However, major containers, floating cards, and feature panels should lean into the `rounded-xl` (1.5rem / 24px) or even larger custom radiuses (up to 40px for hero containers) to echo the soft, approachable nature of a children's education brand.

Interactive elements should feel "tactile" but digital—avoiding harsh corners entirely to reinforce the "Connection -> Confidence" philosophy.

## Components

### Buttons
Primary buttons use a solid gradient from Deep Blue to Sky Blue with a subtle drop shadow. Secondary buttons should be "Ghost Glass" style: transparent background with a 1px frosted border and backdrop blur.

### Training Cards
Cards are the primary vehicle for content. They should feature a frosted glass header, white semi-transparent body, and a "floating" icon or 3D element that breaks the top boundary of the card to create depth.

### Input Fields
Inputs use a soft-gray fill that turns white with a Deep Blue glow on focus. The radius must match the "Soft" setting (8px) to feel modern and precise.

### Progress Chips
For tracking student growth, chips use pill-shapes (radius: 100px) with vibrant color fills and white text. They should have a subtle inner-shadow to appear slightly recessed into the glass panels.

### Navigation
The sidebar or top-nav should be a persistent glass panel. Active links are indicated by a soft Sky Blue glow behind the icon, rather than a heavy solid bar.