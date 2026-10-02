# Hellaven game project context

The user wants a Turkish, playable top-down 2D perfume-making game branded Hellaven.
Preserve the working game rather than creating a landing page or changing it back to a form-only interface.

## Architecture

Single static index.html with inline CSS and JavaScript; HTML Canvas scene; perfume.png decorative asset.
No framework, build, backend, credentials, or dependencies. Serve with python3 -m http.server 8000.

## Preserve

Movement via WASD/arrows, touchscreen controls and click-to-walk; E for stations and Esc to close.
Three distinct ingredients, named perfume, four label colors, four bottle shapes (round/square/tall/oval).
Player-carried bottle and table preview must match the production-time shape.
Customer requests, balance, reputation, sales, production cost, upgrade and restart.
Guard actions during mixing and freeze produced bottle configuration until sold.
Device-session-only state; do not claim progress survives reload.
Optional feature-detected WebMCP tools use the same game state.

## Validation

Check JavaScript syntax, ingredient selection, production cost, customer match payouts,
all four shape previews and produced shape preservation, invalid shape and busy-state guards,
restart, movement and station interactions. Use browser QA when available at desktop and mobile sizes.
Do not assume a browser test passed just because a mock test passed.

## Delivery

This repository is a portable source export, not the Sites deployment checkout.
No Site identity, hosting credentials or repository tokens are included.
Confirm the intended hosting destination before publishing elsewhere.
