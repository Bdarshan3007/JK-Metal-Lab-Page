---
name: Industrial Precision
colors:
  surface: '#f8f9ff'
  surface-dim: '#d0dbed'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dee9fc'
  surface-container-highest: '#d9e3f6'
  on-surface: '#121c2a'
  on-surface-variant: '#444653'
  inverse-surface: '#27313f'
  inverse-on-surface: '#eaf1ff'
  outline: '#757684'
  outline-variant: '#c4c5d5'
  surface-tint: '#3755c3'
  primary: '#00288e'
  on-primary: '#ffffff'
  primary-container: '#1e40af'
  on-primary-container: '#a8b8ff'
  inverse-primary: '#b8c4ff'
  secondary: '#bb0112'
  on-secondary: '#ffffff'
  secondary-container: '#e02928'
  on-secondary-container: '#fffbff'
  tertiary: '#003e18'
  on-tertiary: '#ffffff'
  tertiary-container: '#005825'
  on-tertiary-container: '#2cd769'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#173bab'
  secondary-fixed: '#ffdad6'
  secondary-fixed-dim: '#ffb4ab'
  on-secondary-fixed: '#410002'
  on-secondary-fixed-variant: '#93000b'
  tertiary-fixed: '#66ff8e'
  tertiary-fixed-dim: '#3de273'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005322'
  background: '#f8f9ff'
  on-background: '#121c2a'
  surface-variant: '#d9e3f6'
  surface-alt: '#F8FAFC'
  whatsapp-green: '#25D366'
  border-subtle: '#E2E8F0'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-sm:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  header-height: 70px
  container-max-width: 1280px
  gutter: 24px
  margin-mobile: 16px
  section-padding: 80px
---

## Brand & Style

The design system is engineered for a high-stakes industrial testing environment where precision, reliability, and technical expertise are paramount. The brand personality is clinical yet approachable, balancing the cold rigidity of metallurgy with the warm assurance of expert consultancy.

The visual style follows a **Corporate Modern** aesthetic. It prioritizes clarity through generous whitespace and a structured grid, reflecting the organized nature of laboratory workflows. High-contrast elements ensure that critical data and calls to action are immediately identifiable, while subtle interactive feedback provides a premium, responsive feel suitable for a modern B2B service provider.

## Colors

The palette is anchored by **Trust Blue**, utilized for headers and structural elements to establish professional authority. **Action Red** is reserved strictly for high-priority interactions, technical alerts, and primary conversion points, ensuring they pierce through the neutral layout. 

The background strategy employs a "pure white" primary canvas to maintain a sterile, lab-like environment, using **Light Gray** for secondary sections and card surfaces to create subtle visual grouping without introducing clutter. **WhatsApp Green** is a functional utility color, isolated specifically for instant communication channels.

## Typography

This design system utilizes **Inter** exclusively to ensure a systematic, utilitarian appearance that performs exceptionally well across various resolutions. 

Headings are set with tight letter spacing and heavy weights to convey strength and stability. The body text scale is intentionally generous (16px–18px) to maximize legibility for technical reports and service descriptions. Mobile typography automatically scales down for large display headings to maintain readability without excessive horizontal scrolling or awkward line breaks.

## Layout & Spacing

The design system employs a **Fixed Grid** model for desktop, centered within a 1280px container to ensure content density remains professional and readable. 

- **Desktop:** 12-column grid with 24px gutters.
- **Tablet:** 8-column grid with 20px gutters.
- **Mobile:** 4-column grid with 16px margins.

Vertical rhythm is driven by an 8px base unit. Section spacing is aggressive (80px+) to give technical content "room to breathe," preventing the information-dense laboratory data from feeling overwhelming. Components like cards and input groups should use consistent internal padding (usually 24px or 32px) to maintain a cohesive internal structure.

## Elevation & Depth

To maintain a clean industrial look, this design system avoids heavy gradients or complex textures. Depth is communicated through:

1.  **Low-Contrast Outlines:** Primary containers use a 1px solid border in `#E2E8F0` to define boundaries clearly against the white background.
2.  **Ambient Shadows:** Feature cards and testimonials utilize a "Soft Lift" shadow—a high-blur (24px), low-opacity (4%) black shadow with a subtle vertical offset.
3.  **Interactive Elevation:** Upon hover, elevated elements should transition to a slightly deeper shadow and a 1.02x scale transformation to provide immediate tactile confirmation of interactivity.

## Shapes

The shape language strikes a balance between technical precision and modern approachability. While buttons and smaller UI controls use standard rounding, **major containers and cards use a 16px (1rem) corner radius.** This softening of the "industrial" aesthetic makes the laboratory environment feel more modern and service-oriented. 

Smaller elements like chips or badges should utilize a full pill shape to contrast against the more structured rectangular cards.

## Components

### Buttons
- **Primary CTA:** Solid Red background, white text. Scale 102% on hover with a 300ms transition.
- **Secondary:** Outline Blue with 2px borders. 
- **WhatsApp:** Solid Green with a leading brand icon.

### Sticky Header
Fixed at 70px height. Uses a semi-transparent white background (90% opacity) with a `backdrop-filter: blur(10px)` and a subtle bottom border.

### Cards (Feature/Testimonial)
Background: `#FFFFFF` or `#F8FAFC`. 16px border-radius. 1px stroke. Subtle ambient shadow. Internal padding: 32px.

### Input Fields
Strict rectangular forms with 8px rounding. Focus states should use a 2px Blue ring. Labels must be `label-bold` for high visibility.

### Floating Contact Bar (Mobile Only)
A persistent footer bar anchored to the bottom of the viewport on mobile devices. It features two primary actions: "Call Now" (Blue) and "WhatsApp" (Green), ensuring immediate accessibility for clients.

### Icons
Use stroke-based icons with a 2px weight to match the clean lines of the Inter typeface.