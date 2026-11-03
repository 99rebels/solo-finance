# Solo Finance website

The marketing site and privacy policy for Solo Finance, a Chrome extension that finds every business purchase in Gmail, matches it to a bank statement and builds the accountant's pack at tax time, for sole traders in Ireland and the UK. Everything runs in the user's browser.

"Solo Finance" is a working name and will change.

## Files

| File | What it is |
|---|---|
| `index.html` | Homepage: hero with a mock of the app, how it works, features, subscriptions, privacy, pricing, FAQ |
| `privacy.html` | Privacy policy, including the Google API Services User Data Policy "Limited Use" statement that Google's OAuth verification asks for |
| `styles.css` | All styles. Colours and components follow the extension's design canvas (dark first, one accent, amber as a tint, Inter with tabular figures) |
| `favicon.svg` | The mark |

Plain HTML and CSS, no build step, no JavaScript. Open `index.html` in a browser, or serve the folder (`python3 -m http.server`).

All names, amounts and dates in the mock screens are made up.

## Before going live

- **Name and domain.** Replace "Solo Finance" throughout once it's decided.
- **Contact address.** `hello@example.com` is a placeholder (footer and privacy policy).
- **Who we are.** The privacy policy says "made by 99rebels"; use the legal name and address of the business that will publish the extension.
- **Payment provider.** The policy says "our payment provider"; name it once chosen (Paddle or Lemon Squeezy act as seller of record and handle VAT).
- **Chrome Web Store link.** Buttons point to `chromewebstore.google.com/detail/poifdgfdbgmjpblgaogeidddepffcpjp`, the extension's fixed ID. It works once the listing is published.
- **Prices.** €39 / £35 a tax year and €59 / £52 for two years are a first draft.
- **Google verification.** The homepage and privacy policy must be on a domain you've verified in Google Search Console, and the OAuth consent screen must link to both.

## Hosting

Works as-is on GitHub Pages (Settings › Pages › deploy from `main`, root folder), Netlify or Cloudflare Pages.
