# Redro Pricing

**Smart Pricing & Profit Calculator**

A free, mobile-first, bilingual (Arabic / English) pricing calculator for products and services.

## Features

- Live selling-price calculation using target profit margin or fixed profit.
- Product, shipping, packaging and additional costs.
- Advertising, commission and tax percentages.
- USD, SYP and EUR calculation modes (each calculation uses one selected currency; no currency conversion or exchange-rate service).
- Locally saved calculation history.
- Shareable calculation summaries.
- Built-in usage guide and About screen with version and creator information.
- Installable PWA with an offline app shell.
- No account, backend or subscription.

## Deploy

Enable GitHub Pages from **Settings → Pages → Deploy from a branch → main → /(root)**.

## Calculation

Margin mode: `Selling price = Fixed costs / (1 - advertising rate - commission rate - tax rate - target margin)`

Fixed-profit mode: `Selling price = (Fixed costs + target fixed profit) / (1 - advertising rate - commission rate - tax rate)`

All percentage deductions are modeled as a share of the final sale price. Enter all costs in the selected pricing currency.

## License

MIT
