# Wedding Ledger — support site

Support, privacy policy and terms of use for **Wedding Ledger**, a wedding budget
and vendor tracker for iOS.

Published with GitHub Pages from `main` at the repository root:

| Page | URL | Used as |
|---|---|---|
| `index.html` | https://williamscott701.github.io/weddingledger-support/ | App Store *Support URL* and *Marketing URL* |
| `privacy.html` | https://williamscott701.github.io/weddingledger-support/privacy.html | App Store *Privacy Policy URL* (required) |
| `terms.html` | https://williamscott701.github.io/weddingledger-support/terms.html | EULA / *Licence Agreement* link, required for auto-renewing subscriptions |

All three are linked from inside the app (`LegalLinks` in
`Features/Paywall/Entitlements.swift`) and must stay reachable — App Review
checks them, and a dead privacy URL is a rejection.

Static HTML and one stylesheet. No build step, no JavaScript, no trackers.

## Editing

Change the HTML, commit, push. GitHub Pages redeploys in about a minute.
Update the "Last updated" date at the top of a page whenever its substance
changes, and keep the price table in `terms.html` in step with
`Products.storekit` and the App Store Connect products.
