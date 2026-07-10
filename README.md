# My Water People Website

## Design direction
Dark, immersive, cinematic single-page site for a local water-treatment company. Liquid is the theme: the hero keeps the morphing particle-sphere animation, and a site-wide splash engine erupts high-speed water splashes (crown bursts, stringy filaments, fine mist — modeled on real splash footage) as sections scroll into view, with extra spray kicked up by fast scrolling.

## Key features
- **Hero (unchanged)**: canvas particle sphere morphing blob → crown → blast → torus → helix → vortex over an ambient particle ocean.
- **Splash engine**: fixed full-page canvas behind content; section-entry bursts (IntersectionObserver, alternating left/right emitters) + scroll-velocity spray; respects `prefers-reduced-motion`; capped particle counts and DPR for performance.
- **Cinematic scroll**: word-by-word heading reveals, staggered card rises, pinned "How it works" scene with a scroll-scrubbed waterline and step activation.
- **Free water test inquiries**: form opens the visitor's email app addressed to `mywaterpeople@gmail.com` (mailto); all call CTAs are real `tel:+12108163027` links.
- **SEO**: title/meta description, canonical + Open Graph/Twitter tags, LocalBusiness and FAQPage JSON-LD, semantic single-h1 heading structure, on-page FAQ section, geo keywords (San Antonio / South Texas).
- Products organized into cards: kitchen systems, whole-house filtration, softeners, iron breakers, Water Cube, and maintenance.
- Mobile sticky CTA bar keeps Call and Schedule accessible.

## Before going live
- Update the canonical/OG URLs in `index.html` if the domain isn't `www.mywaterpeople.com`.
- Replace the testimonial video placeholder with real YouTube embeds.

## How to open
On macOS:

```bash
open /Users/donallie/mywaterpeople-mockup/index.html
```

Or open the file directly in a browser:

```text
file:///Users/donallie/mywaterpeople-mockup/index.html
```
