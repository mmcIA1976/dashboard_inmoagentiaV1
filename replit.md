# InmoAgentia Landing Page

## Overview
Premium landing page for InmoAgentia, a B2B SaaS company offering AI-powered lead automation for real estate agencies. The page is designed to convert visitors into demo requests and personalized proposals.

## Architecture
- **Single-file architecture**: Everything lives in `index.html` (HTML + CSS + JS)
- **No frameworks**: Pure vanilla HTML, CSS, and JavaScript
- **External dependencies**: Google Fonts (Inter + Playfair Display) and Font Awesome via CDN
- **Server**: Python 3 built-in HTTP server (`python3 -m http.server 5000`)

## Design System
- **Color palette**: Dark navy (#0D1B2A) with gold accent (#C9A84C)
- **Typography**: Playfair Display for headings, Inter for body
- **Style**: Premium, dark, B2B SaaS aesthetic
- **Mobile-first**: Fully responsive with breakpoints at 768px and 1024px

## Sections
1. Fixed navbar with scroll effects and mobile hamburger menu
2. Hero with stats, CTAs, and agent support block
3. "Cómo funciona" - 5-step process flow
4. "Funcionalidades" - 6 feature cards in 2-column grid
5. "Casos de uso" - 3 chat-style use case cards
6. "Contacto agente" - Human support section
7. "Precios" - 2 pricing cards (consultative, no fixed prices)
8. "Contacto" - Full contact form with validation
9. Footer

## JavaScript Features
- Navbar background change on scroll
- IntersectionObserver for active nav link highlighting
- Scroll reveal animations (respects prefers-reduced-motion)
- Mobile menu toggle
- Form validation with success message
- Smooth scroll for anchor links

## Language
All content is in Spanish (Spain). B2B professional tone.
