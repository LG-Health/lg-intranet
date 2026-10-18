# lg-intranet

Embeds for the LYNK intranet (Google Sites). Staff-facing only. No patient information in this repo, ever.

Published with GitHub Pages at `https://lg-health.github.io/lg-intranet/`

**This repo is public.** Only the look of the intranet and links to public patient pages go here.
Links to provider documents, tools, spreadsheets and anything internal go on the Google Site itself
(buttons or link lists there), which only lynkgroup.com accounts can open.

| File | What it is | Google Sites embed height |
|---|---|---|
| `lg-home-hero.html` | Home page banner with the spinning logo | about 300 px |
| `lg-home-hub.html` | Tabbed resource hub with the Provider Library button; internal cards open the Library page | about 720 px |
| `lg-home-tx-providers.html` | Provider credentialing placeholder (no names) | about 220 px |
| `spinning-logo.js` | 3D logo script used by the hero. Keep it next to the hero file | n/a |
| `index.html` | The three embeds stacked, for review | n/a |

## Editing

- Hub cards: open `lg-home-hub.html`, find `EDIT HERE`. Empty `url` shows "Coming soon".
  `status:"internal"` opens the Provider Library page on the Google Site (only Lynk accounts can open it); the document links themselves stay off this public repo.
- Provider credentialing will be its own private tool; this page stays a placeholder until then.
