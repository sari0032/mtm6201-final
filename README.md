# mtm6201-final — Active Life Centre

Bootstrap 5 rebuild of the Active Life Centre design (Home, Programs & Activities, Facilities).

## What's inside
- `index.html` — Home
- `programs.html` — Programs & Activities (search + category filter)
- `facilities.html` — Facilities (Bootstrap tabs: Aquatic Centre / Ice Rink / Fitness Gym / Wellness Area)
- `style.css` — custom theme layered on Bootstrap (CSS custom properties, component overrides, hover/focus states)

## Before you submit — swap the placeholder images
All photos currently load from `picsum.photos` (free placeholder service) so you can see the layout.
**Replace every `<img src="https://picsum.photos/...">` and matching `srcset` with your own photos** before
submitting, per the "all images must be your own" requirement. Keep two file sizes per image (e.g.
`photo-480.jpg` and `photo-960.jpg`) so the `srcset`/`sizes` attributes keep working.

## Publish it to GitHub Pages
1. Create a new GitHub repo named **mtm6201-final** (all lowercase, matches the naming rule).
2. Clone it locally, then copy `index.html`, `programs.html`, `facilities.html`, and `style.css` into the repo root.
3. Commit and push:
   ```
   git add .
   git commit -m "Final build: Bootstrap site for Active Life Centre"
   git push
   ```
4. On GitHub: **Settings → Pages → Source → Deploy from a branch → main / (root)** → Save.
5. Your live site will be at `https://<your-username>.github.io/mtm6201-final`.

## Submit to Brightspace
Paste both links:
```
https://github.com/<your-username>/mtm6201-final
https://<your-username>.github.io/mtm6201-final
```

## Rubric self-check (see full audit in chat)
- [x] 3 pages, 3+ content sections each, consistent footer
- [x] Bootstrap grid/components drive every layout (navbar, tabs, cards, buttons)
- [x] `:root` CSS variable overrides + component-level overrides (`.btn-primary`, `.nav-link`, etc.)
- [x] Skip link, semantic landmarks, ARIA on tabs, alt text on every image
- [x] `srcset`/`sizes` on every `<img>` (2 sizes minimum)
- [x] Hover + focus + transition states on all links/buttons
- [x] AOS (Animate On Scroll) integrated as the additional library
- [x] Passed offline HTML5 (vnu) validation and CSS parse check — recheck at validator.w3.org / jigsaw.w3.org once your own content/images are in
- [ ] Swap in your own images/content (see above) — do this before submitting
