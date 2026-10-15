# Aether Studio

An experimental animated website exploring modern UI, motion, and creative
web interactions — built with Vite, React, Tailwind CSS, and GSAP /
ScrollTrigger, with Gemini and Claude Code used throughout the build.

**Live site:** [aether-studio-motion.netlify.app](https://aether-studio-motion.netlify.app/)

## Features

- Scroll-driven reveal animations powered by GSAP's ScrollTrigger
- Seamless looping video background in the hero section
- Responsive layout with a dedicated mobile navigation menu
- Single-page structure: hero, about, logo marquee, and a "why us" section

## Tech stack

- [Vite](https://vite.dev/) — build tooling & dev server
- [React](https://react.dev/) — UI
- [Tailwind CSS](https://tailwindcss.com/) — styling
- [GSAP](https://gsap.com/) + ScrollTrigger — animation

## Getting started

```bash
npm install
npm run dev      # start the dev server
npm run build    # production build to dist/
npm run preview  # preview the production build locally
```

## Project structure

```
src/
  components/   # page sections (Hero, About, Marquee, WhyUs, Navbar, Footer, ...)
  hooks/        # shared animation hooks (scroll reveal, etc.)
  lib/          # GSAP setup
public/         # static assets (video, images)
```

## Deployment

Hosted on [Netlify](https://www.netlify.com/), auto-deploying from the `main`
branch on every push.

## License

MIT — see [LICENSE](./LICENSE).
