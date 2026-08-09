# CodeAlpha Image Gallery

A responsive image gallery built with HTML, CSS and vanilla JavaScript, styled as a photographer's contact sheet with a film-strip aesthetic.

**Domain:** Frontend Development Internship
**Organization:** CodeAlpha

## Features

- Lightbox view with next/previous navigation, keyboard support (← → to navigate, Esc to close)
- Category filters (Nature, Urban, Portrait, Abstract) that build themselves dynamically from the photo data
- Add photos — upload any image from your device directly into the gallery, no backend required
- Delete photos — remove any photo from the grid or from within the lightbox
- Hover effects and smooth transitions throughout
- Fully responsive layout, down to small mobile screens
- Lazy-loaded images for better performance on larger galleries

## How to run

Just open `index.html` in any browser — no build steps or dependencies.

## Tech stack

HTML5, CSS3 (Grid, custom properties, animations), vanilla JavaScript — no frameworks or libraries.

## Note

Uploaded and deleted photos only persist for the current browser session — refreshing the page resets the gallery back to the default set, since this is a static front-end-only project with no backend or database.
