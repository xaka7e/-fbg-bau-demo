# FBG Bau — Website Prototype v2

Interactive front-end prototype for FBG Bau GmbH.

## What is included
- Large FBG branding in the hero
- Hero slogan: **WIR BRINGEN BETON IN FORM.**
- Scroll-controlled crane / hook / formwork animation
- Worker seen from behind with **FBG BAU GMBH** on the back
- Company numbers (30+ years, 60+ employees, 550+ projects)
- Services / equipment
- Current construction projects
- Reference projects: Vulcano, Westlink, Nidfeld A1
- Company history
- Team / leadership
- Careers
- Contact and opening hours
- Responsive layout for mobile

## Open locally
Open `index.html` in a browser. If your browser restricts local assets, run a small local server from this folder, for example:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Important for the final site
The project photos are currently loaded from external architecture/project websites as prototype references. Before publishing the final company website, replace them with FBG-owned photos or images with confirmed publication rights.


## v2.1
- Worker reduced in size and FBG BAU GMBH branding moved to upper back/shoulder area.
- Hero copy now changes across all five scroll stages with a crossfade/slide transition.
- Each construction phase has its own headline, supporting copy and project fact.

## v2.2 changes
- Rebuilt the crane as a straight truss/mast and removed the blur-causing shadow filter from the crane.
- Rewrote the scroll animation so trolley, cable, hook, slings and panel use one synchronized rig.
- Added an FBG wordmark badge to the worker helmet and raised the jacket badge toward the shoulders.
- Added the same wordmark treatment to the crane sign.

Note: `assets/fbg-wordmark.svg` is a clean vector redraw based on the wordmark visible on the official FBG website. For a production launch, replace this single asset with the original logo file supplied by FBG (SVG/PNG) to guarantee exact brand artwork.


V2.3 updates:
- Added official FBG symbol (user-provided) to helmet and header.
- Added symbol to crane signage next to the wordmark.
- Adjusted load pick-up/start support so the panel rests on a transport support.
- Adjusted final placement so the panel lands on the slab instead of floating.


V2.4 hotfix:
- Fixed oversized official logo rendering in the hero/header.
- Official symbol remains in the header, on the helmet, and on crane branding.
- Removed the giant hero icon that was breaking the layout.


V2.5 detail polish:
- Lowered the crane FBG Bau GmbH branding plate so it clears the dark fixed header.
- Raised the helmet logo and reduced its size.
- Rounded the helmet badge with a circular clip and subtle tilt to sit more naturally on the helmet.
- Crane motion and scroll timing unchanged.


V2.6 updates:
- Added mobile/adaptive layout for iPhone and common phones (safe areas, tighter spacing, mobile menu, revised hero scaling).
- Moved the 'Scroll steuert die Baustelle' note away from the crane brand to avoid overlap.
- Improved tablet/mobile breakpoints for hero, worker, crane scene, grids, contact and footer.


V2.7 updates:
- Improved universal phone layout (not iPhone-only) for 360 / 375 / 390 / 412 / 430 px widths.
- Kept the tower crane visible in the mobile hero frame.
- Shifted the load path on phones so the panel stays farther right and does not run over the left-side text as much.


V2.8 stability pass:
- Preserves current scroll-animation progress when resizing the browser window across breakpoints.
- Stabilized interactive section height for desktop/tablet widths.
- Moved the scroll-control note next to the lower progress UI so it cannot overlap the crane sign.
- Tested specifically for reduced MacBook/browser-window widths.
