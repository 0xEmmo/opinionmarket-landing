# OpinionMarket frontend rebuild plan

## Product approach

Turn the current two-file concept into a single responsive prediction-market product shell. The interface will use an evergreen/near-black foundation, warm ivory content surfaces, bright Nigerian green, and amber market-signal accents. It will feel editorial and active without copying Polymarket or Kalshi branding.

## Interaction model

A shared `markets` data model powers the category rail, search and sort controls, featured moment, discovery cards, trending/ending-soon/movers context panels, and quick-stake suggestions. Category changes filter real visible content. Search narrows the same feed. The floating quick-stake control expands into a swirl-to-sheet panel; tapping it again reshuffles suggestions. Selecting a suggestion opens a clearly labeled demo ticket with outcome and amount choices. No network calls, payments, deposits, authentication, or real trading occur.

## Project structure

- `index.html`: complete self-contained frontend shell and interaction logic.
- `app-ui.html`: same coherent product experience for compatibility with the original repo links.
- `public/manus-routes.json`: declared page route set for the web preview contract.
- `README.md`: updated project notes and demo boundary.
- `TODO.md`: outcome-based acceptance record.

## Design system

- **Design movement:** Nigerian market-floor editorial, probability dashboard, restrained kinetic exchange.
- **Core principles:** recognizable event imagery; high signal-to-noise; tactile category navigation; credible data hierarchy.
- **Color philosophy:** near-black/evergreen creates depth, ivory surfaces make prices readable, green signals positive market movement, amber signals urgency and activity.
- **Layout paradigm:** asymmetric editorial lead with a wide featured moment, dense discovery feed, and right-side activity rail on desktop; a bottom-sheet rhythm on mobile.
- **Signature elements:** stitched green market ticker, image-led lead card with probability rail, swirl quick-stake button with radial pick chips.
- **Interaction philosophy:** every control changes visible information or opens a useful next action; motion is short, purposeful, and respects reduced-motion preferences.
- **Typography:** `DM Sans` for UI and `DM Serif Display` for editorial headlines.
- **Brand essence:** a Nigerian lens on the questions people are already debating. Personality: observant, energetic, grounded.
- **Brand voice:** direct and local without hype. Examples: “The room has a read.” and “Pick a side. Watch the signal.”
- **Wordmark:** a compact O/M monogram with a split-ring market signal, paired with a confident wordmark.
- **Signature brand color:** market green `#b7f36b`.

## Boundaries

All values, odds, volume, market names, imagery, and tickets are illustrative demo content for an interview frontend prototype. No unverified OpinionMarket claims are repeated. No emoji are used.
