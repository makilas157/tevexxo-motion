# Tevexxo animation and effects pass

## Scope
- Import the existing Tevexxo site from the provided repository, preserving every route, page, asset, section, copy block, and existing dark charcoal/amber/burnt-orange visual system.
- Add motion and interaction polish only; no redesign or content changes.

## Motion layer
- Refine the existing viewport reveal helper to fade upward and scale from 0.98, trigger once, and honor per-item stagger delays.
- Give the home introduction a deliberate 90ms load sequence and animate the fixed navigation down into place.
- Add a reusable count-up treatment for the home statistics, preserving prefixes/suffixes and stopping at the current values.

## Interaction polish
- Intensify the cursor-grid glow while catalog, depth, and social cards are hovered.
- Tune card lift, accent border, and glow transitions; add a primary-button shimmer and consistent arrow movement.
- Upgrade section-tag dots to a soft scale-and-opacity pulse.
- Animate active navigation underlines and make the mobile menu panel and links slide/fade in smoothly.

## Contact form
- Add smoothly animated accent focus rings.
- Add a short submit sequence with spinner, then checkmark and success state, while keeping the current non-persistent form behavior.

## Accessibility and verification
- Disable or simplify reveals, count-up, shimmer, cursor motion, and menu transitions under `prefers-reduced-motion`.
- Verify all routes compile and inspect desktop and mobile rendering, menu behavior, statistics, hover states, and form feedback.
