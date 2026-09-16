# expensemanager-site

The website for **Personal-Finances**, a personal ledger for expenses, trips and income.
Three static pages, no build step, no dependencies:

| | |
|---|---|
| `index.html` | the page, with a screenshot tour that advances itself and can be tapped |
| `privacy.html` | the privacy policy — **required by App Store Connect** |
| `support.html` | the support page — **required by App Store Connect** |

Served by GitHub Pages from `main`, at the root. Editing a file and pushing publishes it.

The screenshots in `img/` are of a **synthetic ledger**, never of real data — they are produced by
`ExpenseManager/Tools/DemoLedger` in the app repo. The colours are the app's own: the charcoal is
its icon background, the accents are the category colours out of the ledger.
