---
name: Reformed Baptist Christmas Design System
colors:
  surface: '#faf9f7'
  surface-dim: '#dadad8'
  surface-bright: '#faf9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeec'
  surface-container-high: '#e9e8e6'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1b'
  on-surface-variant: '#424843'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#727973'
  outline-variant: '#c1c8c2'
  surface-tint: '#456553'
  primary: '#032517'
  on-primary: '#ffffff'
  primary-container: '#1b3b2b'
  on-primary-container: '#83a590'
  inverse-primary: '#abcfb8'
  secondary: '#9a4152'
  on-secondary: '#ffffff'
  secondary-container: '#fd91a2'
  on-secondary-container: '#772738'
  tertiary: '#2a1e00'
  on-tertiary: '#ffffff'
  tertiary-container: '#443200'
  on-tertiary-container: '#c19823'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c7ebd4'
  primary-fixed-dim: '#abcfb8'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#2d4d3c'
  secondary-fixed: '#ffd9dd'
  secondary-fixed-dim: '#ffb2bc'
  on-secondary-fixed: '#400013'
  on-secondary-fixed-variant: '#7c2a3b'
  tertiary-fixed: '#ffdf98'
  tertiary-fixed-dim: '#eec14b'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#5a4300'
  background: '#faf9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e3e2e0'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 28px
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 3rem
---

## Brand & Style

This design system embodies an elegant, reverent, and festive tone tailored for a Reformed Baptist Church during the Christmas season. The brand personality is solemn yet deeply celebratory, striking a balance between historical theological richness and warm, welcoming community hospitality. 

The visual style leans toward a refined editorial minimalism combined with tactile warmth. It rejects commercial gaudiness in favor of dignified tradition, featuring ample whitespace, exquisite typography, and a rich, purposeful color palette that evokes Advent and Christmastide. The UI should evoke a sense of quiet awe, reverence for Scripture, and joyful anticipation of the Incarnation.

## Colors

The color palette anchors the digital experience in liturgical tradition. 
- **Primary (Deep Forest Green - `#1B3B2B`):** Represents eternal life, steadfastness, and creation. Used for primary structures, hero banners, and grounding elements.
- **Secondary (Rich Burgundy/Cranberry Red - `#6B1D2F`):** Symbolizes the royalty of Christ and His sacrificial blood. Used for calls to action, high-priority highlights, and seasonal accents.
- **Tertiary (Warm Gold - `#C59B27`):** Evocative of the gifts of the Magi and divine glory. Used sparingly for borders, active states, icons, and subtle ornamentation.
- **Neutral (Cream / Clean White - `#F9F8F6`):** Provides an expansive, peaceful canvas that enhances legibility and creates a calm, worshipful reading environment.

## Typography

Typography pairs traditional, authoritative serif headings with clean, highly readable modern sans-serif body text. 

- **Headlines (`Playfair Display`):** Deliver an editorial, literary, and timeless quality suitable for Scripture passages, service titles, and major liturgical headers. 
- **Body & Labels (`Inter`):** Ensure crystal-clear legibility across digital interfaces, whether users are reading long-form doctrinal summaries, event descriptions, or navigating service times on mobile devices.

For viewports below 768px, scale down `headline-xl` to 36px and `headline-lg` to 28px to maintain proportional balance and prevent awkward wrapping.

## Layout & Spacing

The layout philosophy relies on a **fluid grid** combined with generous whitespace, reflecting the solemnity and breathing room of a traditional sanctuary. 

- **Grid System:** Built on a 12-column fluid grid with 24px gutters and responsive outer margins (scaling from 16px on mobile to 48px on desktop).
- **Rhythm:** Spacing follows a comfortable, human-centric scale that avoids crowding. Generous vertical spacing (`space-xl`) between major sections establishes a contemplative hierarchy, allowing users to absorb liturgical readings and event details without cognitive fatigue.

## Elevation & Depth

Visual hierarchy relies on **subtle tonal layering** and **low-contrast outlines** rather than heavy, distracting drop shadows. 

- **Surfaces:** Depth is achieved by stepping between the cream background (`#F9F8F6`) and crisp white container cards, accented by exceptionally fine, warm gold or forest green borders (`1px solid rgba(27, 59, 43, 0.08)`).
- **Shadows:** When shadows are necessary for floating elements (such as sticky navigation or modal dialogs), they utilize diffused, low-opacity ambient glows tinted with deep forest green to maintain organic warmth rather than stark digital neutrality.

## Shapes

The shape language is understated and classic, categorized under **Soft** roundedness (`0.25rem` base, `0.5rem` for large containers). 

Completely sharp edges (`0px`) feel too austere, while heavily rounded or pill-shaped containers feel too casual for a traditional church context. Restrained, gentle curves on cards, input fields, and buttons communicate approachability and care while maintaining architectural dignity.

## Components

All components should integrate the color palette and typography to reflect warmth, reverence, and clarity.

- **Buttons:** Primary actions utilize Deep Forest Green or Rich Burgundy backgrounds with clean white or gold text, featuring subtle hover states that deepen the hue. Secondary buttons employ ghost outlines with forest green borders.
- **Chips & Badges:** Used for liturgical tags (e.g., "Advent IV", "Lord's Supper"). Styled with soft cream backgrounds, fine borders, and deep green or burgundy text.
- **Input Fields:** Clean white backgrounds enclosed in soft borders, utilizing `Inter` for clear user input, paired with warm gold focus rings.
- **Cards:** White surfaces resting on the cream canvas, bordered lightly, used to frame sermons, upcoming Carol services, and giving opportunities.
- **Liturgical Callout Boxes:** Distinctive containers featuring a thick 3px vertical accent border in Warm Gold, specifically designated for Scripture memory verses and pastoral reflections.