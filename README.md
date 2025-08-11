# html-tailwind-launch

Static landing page built with Tailwind CSS (via CDN) and Font Awesome. It showcases a "Data Solutions" homepage with responsive navigation, a bold hero, a continuous brand ticker, engagement metrics, a masonry-style reviews grid, and a footer.

## Prerequisites
- Modern web browser. No local dependencies or build step: Tailwind and icons are loaded via CDN.

## Run locally
1. Clone or download this repository.
2. Open `index.html` directly in your browser (double click), or serve the folder with a static server (e.g., VS Code Live Server).

## Project structure
```
html-tailwind-launch/
├─ index.html
└─ README.md
```

## Key features
- Responsive navbar with mobile hamburger menu.
- Hero section with grid background and call-to-action buttons.
- Horizontal, continuous brand ticker using a duplicated slider for infinite loop.
- Engagement metrics in a responsive grid.
- Masonry-like reviews grid (CSS columns) with hover animation.
- Footer with documentation and community links.

## Quick customization
- Colors/theme: tweak Tailwind utility classes on elements (e.g., `bg-[#38bdf8]`, `text-gray-400`).
- Icons: swap Font Awesome classes (e.g., `fa-github`, `fa-slack`).
- Content: edit copy and labels in `index.html` (nav, hero, metrics, reviews, footer).
- Layout: adjust Tailwind grids, spacing, and breakpoints as needed.

## Deploy
- Because it is static, you can host it on GitHub Pages, Vercel, or any static hosting.
  - GitHub Pages: push to `main` and enable Pages in repository settings.
  - Vercel: import the repository and deploy as a static project.

## Technologies
- Tailwind CSS via CDN.
- Font Awesome via CDN.

## License
Define a license for your needs (for example, MIT). There is currently no specific license in this repository.
