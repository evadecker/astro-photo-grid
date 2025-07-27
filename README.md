![Astro Photo Grid Preview](./public/cover.png)

# Astro Photo Grid

A minimal, single-page photo gallery for [Astro](https://astro.build/). See the [demo](https://astro-photo-grid.netlify.app/)!

## Features

- **Responsive, justified grid using modern CSS.** All layout and reflow logic is handled with pure CSS—no JS required for positioning!
- **Automatic lightbox integration.** Images open in a full-screen preview using [Fancybox](https://fancyapps.com/fancybox/), which includes swipe, drag, pinch-to-zoom, and a customizable toolbar.
- **Optimized image loading and sizing.** Images on the grid are optimized using Astro's [`<Image />` component](https://docs.astro.build/en/guides/images/). Images on the grid beyond the first screen are lazily loaded.

## Getting Started

1. Click "Use this template" and create a new repository.
2. In `astro.config.mjs`, update `site` from `https://mysite.com` to your site URL.
3. In `src/layouts/BaseLayout.astro`, update `siteName` to your site name.
4. Replace the items in `src/images` with your own photos.
5. Good to go!

## Credits

- CSS-only justified gallery layout from [Helmut Wandl](https://medium.com/@ehtmlu/css-image-grid-gallery-4ec8824560a1) and [SmolCSS](https://smolcss.dev/#smol-aspect-ratio-gallery)
- [Fancybox](https://fancyapps.com/fancybox/) lightbox
- All demo images from [Unsplash](https://unsplash.com/)
