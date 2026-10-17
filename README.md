# lg-intranet

Embeds for the Lynk Medical intranet (Google Sites). Staff-facing only. No patient information in this repo, ever.

Published with GitHub Pages at `https://lg-health.github.io/lg-intranet/`

| File | What it is | Google Sites embed height |
|---|---|---|
| `lg-home-hero.html` | Home page banner with the spinning logo | about 300 px |
| `lg-home-hub.html` | Tabbed resource hub (5 tabs) | about 550 px |
| `lg-home-tx-providers.html` | Texas provider list | about 600 px |
| `assets/spinning-logo.js` | 3D logo script used by the hero. Keep it in `assets/` | n/a |
| `index.html` / `preview.html` | All three together, for review | n/a |

## Editing

- Hub links: open `lg-home-hub.html`, find `EDIT HERE`, paste a link into a card's `url`. Empty `url` shows "Coming soon".
- Providers: open `lg-home-tx-providers.html`, find `EDIT HERE`, one line per provider. `status` is `active` or `pending`. Staff details only.
- `preview.html` and `index.html` are a snapshot; regenerate them (or ignore them) after editing the three embed files.

## Note

This repo is public (GitHub Pages). Before real provider names go into the provider list, decide whether that list should live here or as a table built directly in Google Sites.
