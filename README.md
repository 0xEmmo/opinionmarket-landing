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
