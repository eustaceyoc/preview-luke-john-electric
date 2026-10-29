# Luke & John Electric (sample site)

A sample website I designed for Luke & John Electric, a family electrical business in Atlanta, GA. I put together sites like this to show local businesses what a modern, mobile-friendly web presence could look like for them before they commit to anything.

**Live preview:** https://preview-luke-john-electric.vercel.app

## Design

A minimal, luxury-feeling layout with lots of whitespace, in ivory, navy and brass with Cormorant Garamond and Manrope. A fine-line pendant lamp draws itself in and has a light on/off switch, services are shown as tabs, the license number sits on a navy panel, neighbor quotes appear in a slow slider, and there is a validated consultation form. I kept the restrained concept from my first version and raised the finish. Phone number, hours and years in business are left off on purpose because the public listings differ. No photos.

## Stack

- Plain HTML and CSS in a single `index.html`, with no framework and no build step
- Vanilla JavaScript (no libraries) for the blurred sticky header, mobile menu, scroll reveals, a drawn-in SVG lamp with light switch and gentle parallax, keyboard-accessible service tabs, a quote slider, animated counters for numbers sourced from Nextdoor and Google, and client-side form validation. It respects `prefers-reduced-motion`
- Responsive layout, checked at 375, 768 and 1280 px
- Fonts and images: Cormorant Garamond and Manrope, and no photos
- Hosted on Vercel

## Running it locally

Open `index.html` in a browser, or serve the folder with something like `npx serve .`

## Notes

- This is a sample site, not the business's official website, and it isn't affiliated with or published by Luke & John Electric.
- The contact form is for demo purposes only and doesn't send anything.
- Search engines are blocked for now (`robots.txt` and a `noindex` header in `vercel.json`) until the business decides whether it wants the site live.

Built by Eustace Crentsil
