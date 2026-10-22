# OpinionMarket Market Floor

A premium, front-end-only OpinionMarket product prototype for an interview submission. The rebuild uses OpinionMarket's black/cyan product language with a more structured prediction-market information hierarchy: dense event inventory, category filtering, image-led market cards, market pulse context, and a full market-detail order ticket.

## Included interactions

- The single category rail filters the shared 14-market illustrative dataset without duplicate navigation. The selected category state and result count update together.
- Search and sort controls update the visible market feed.
- Market cards and the featured market moment open a full-screen market detail view with one smooth, fluctuating month-based chart line per outcome with range controls and outcome labels, outcome chips, Buy/Sell tabs, amount input, quick amount buttons, share calculations, estimated spend, fee, and max-return summary.
- The supplied brand logo is used in the top navigation and quick-picks control; the control opens a yin-yang-style swirl sheet with three suggestions, tap-again reshuffling, and explicit Shuffle and Close controls.
- The order ticket is visually modeled on a prediction-market staking flow, but remains demo-only: it never processes money, orders, deposits, authentication, or real trading.
- Responsive desktop and mobile navigation, keyboard focus, reduced-motion support, a dismissible mobile How it works guide, draggable quick picks, a back-to-top control, universal Yes/No market actions, and explicit illustrative-data messaging are included.

## Run locally

Open `index.html` directly, or serve the folder with any static server. `app-ui.html` mirrors the same experience for compatibility with the original two-file prototype.

All market names, values, odds, activity, imagery, wallet balance, and ticket behavior are illustrative demo content.


## Reference interaction pass

The mobile helper follows a compact Polymarket-style bottom bar above navigation, and each outcome row exposes illustrative Yes/No actions that open the market detail view.


## Typography and onboarding

The interface uses Inter across navigation, cards, controls, charts, market detail, and responsive layouts. The How it works helper opens a three-step interactive walkthrough with progress, Next, Back, Start exploring, backdrop dismissal, and an X close action.

## Market floor expansion

The demo inventory now contains 28 Nigeria-focused illustrative markets across Trending, Sports, Politics, Entertainment, Economy and Finance, World Events, and Technology. Cards use responsive auto-fit sizing, local Nigeria-relevant imagery for major event groups, and green/red Yes/No signal language. The detail chart uses denser month-aligned historical points, separate fluctuating series, and endpoint labels for each outcome.

## Buy-position clarity

The market detail ticket now puts Yes and No price buttons directly beneath the Buy/Sell tabs. Both are always visible, show the current illustrative percentage, highlight the active position, and immediately update the selected outcome, share estimate, and demo return calculation.

## Event-to-image matching

Sports imagery is now assigned at the individual market level rather than by one broad sports fallback: Super Eagles qualifier, PSG vs Barcelona, Liverpool vs Villarreal, Anthony Joshua boxing, Lagos City / NPFL, and Super Falcons each use a dedicated matching image. Politics markets retain politics imagery, while entertainment, economy, technology, and world-event markets retain their own subject treatment.

## Featured event image correction

The main featured “Can the Super Eagles keep a clean sheet in their next qualifier?” card now uses the dedicated Super Eagles qualifier image instead of the generic crowd image. Other market-card imagery remains unchanged.

## Front-end sign-in

The guest account control now opens a dedicated OpinionMarket sign-in screen. Users can enter a display name and email, then return to the market floor with their initials, name, and email shown in the header. This is intentionally front-end-only: no backend account is created, no data is sent or stored, and a refresh returns to the guest state.

## Startup position

The homepage now disables browser scroll restoration and explicitly opens at the top on a direct site load or refresh. Intentional in-page hash navigation remains available after the page is open.
