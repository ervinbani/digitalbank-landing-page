## Challenges you encountered during the project.

A key challenge was translating static JPG designs into a pixel-faithful, responsive layout while blending Bootstrap with custom design tokens (CSS variables, gradients, spacing). Getting the hero composition right—overlaying the mockup PNG on an SVG background without overflow or layout shifts—also required careful positioning and breakpoint tuning. Another hurdle was ensuring accessible navigation with the Bootstrap collapse plus smooth scrolling and consistent hover/focus states across components.

## Your approach to solving these challenges.

To solve these, I used a mobile-first approach: Bootstrap’s grid/utilities for structure, then layered bespoke CSS for the brand look (gradient CTA, icon sizing, card hover effects). I centralized colors and radii in :root, tested at common widths (375–1440), and verified contrast/keyboard behavior.

## Improvements you would make if given more time.

Modularize styles (SCSS +) and set up a tiny design system; add dark mode, reduced-motion variants.
