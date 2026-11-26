# Redro Pricing

Smart Pricing & Profit Calculator by Redro.

A free, mobile-first, bilingual (Arabic / English) pricing calculator for products and services.

## Features

- Live selling-price calculation using target profit margin or fixed profit.
- Product, shipping, packaging and additional costs.
- Advertising, commission and tax percentages.
- USD, SYP and EUR display and conversion.
- Automatic exchange rates from open.er-api.com with manual editing and manual mode.
- Locally saved calculation history and exchange rates.
- Shareable calculation summaries.
- Installable PWA with an offline app shell.
- No account, backend or subscription.

## Deploy

Enable GitHub Pages from **Settings → Pages → Deploy from a branch → main → /(root)**.

## Exchange rates

Automatic rates are fetched from the open.er-api.com USD-base endpoint. SYP market rates may differ from the API reference rate. For business-critical pricing, verify the rate and use manual mode when needed. Manual mode prevents automatic refresh from overwriting the entered rates.

## Calculation

Margin mode: `Selling price = Fixed costs / (1 - advertising rate - commission rate - tax rate - target margin)`

Fixed-profit mode: `Selling price = (Fixed costs + target fixed profit) / (1 - advertising rate - commission rate - tax rate)`

All percentage deductions are modeled as a share of the final sale price.

## License

MIT
