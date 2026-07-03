# ALIEN STRIKERS (ASTRO EDITION)

This is the completely re-engineered version of the site using **Astro**, a modern static site generator.

By using Astro, you get the best of both worlds:
- **Partials/Components:** You can cleanly organize your code (e.g. `src/components/PlayerCard.astro`, `src/layouts/Layout.astro`).
- **Blazing Fast Performance:** When built, Astro strips out all JavaScript by default and ships pure, static HTML/CSS, making it extremely fast.

## How to Run This

Since this uses a static framework, you have two modes:

### 1. Developer Mode (To edit partials)
If you want to edit the alien components and see changes instantly:
1. Open your terminal in this folder (`cricket-team-site`)
2. Run: `npm run dev`
3. Open `http://localhost:4321` in your browser.

### 2. Production Static Mode (Fully Static)
If you just want the final, blazing fast static files:
1. Run: `npm run build`
2. Astro will generate completely static files in the `/dist` folder.
3. You can take the contents of that `/dist` folder and host them anywhere (GitHub Pages, Netlify, Vercel) for free. You can view the static output by running `npx serve dist`.
