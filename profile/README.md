<div align="center">

# PredictFlow

**Demand forecasting, inventory intelligence, and pricing optimization for e-commerce.**

[Website](https://predictflow.co) · [npm](https://www.npmjs.com/package/@predictflow/sdk) · [PyPI](https://pypi.org/project/predictflow/) · [Packagist](https://packagist.org/packages/predictflow/sdk)

</div>

---

PredictFlow connects to your Shopify or WooCommerce store and turns your order history into concrete, day-to-day answers: what to reorder and how much, what's about to become dead stock, what your prices should actually be, and how your revenue is trending. This organization hosts the official, open-source SDKs for building on top of the PredictFlow API.

## What you can do with the API

- **Demand forecasting** — per-product and per-store forecasts, with confidence intervals and Monte Carlo stockout simulation.
- **Inventory intelligence** — reorder point and quantity recommendations, safety stock policy optimization, dead stock and ABC revenue analysis.
- **Pricing** — price elasticity estimation, optimization suggestions, competitor price tracking, and what-if simulations.
- **Analytics** — revenue trends, day-of-week seasonality, KPI dashboards, customer analysis.
- **Scenario planning** — side-by-side what-if comparisons before you commit to a decision.
- **Alerts** — a daily action feed and configurable rules for restock, reprice, and liquidation signals.

## SDKs

| SDK | Status | Install |
|---|---|---|
| [javascript-sdk](https://github.com/PredictFlow/javascript-sdk) | ✅ Available | `npm install @predictflow/sdk` |
| [python-sdk](https://github.com/PredictFlow/python-sdk) | ✅ Available | `pip install predictflow` |
| [php-sdk](https://github.com/PredictFlow/php-sdk) | 🔧 Built, not yet published | not yet published |

Each SDK is a thin, typed client over the same REST API — pick the one for your stack. Every method in every SDK is verified against the live API before shipping, not just against a schema.

## Getting an API key

1. [Sign up](https://predictflow.co) and connect a Shopify or WooCommerce store.
2. From Account settings, create a personal access token (`pk_live_...`).
3. Use it as a bearer token with any SDK, or directly against the REST API.

## Contributing

Each SDK repo has its own `CONTRIBUTING.md` and `SECURITY.md`, all following the same rule: verify every API call against the real backend before opening a PR, not just against a schema - that's the one rule that matters most here. ([javascript-sdk](https://github.com/PredictFlow/javascript-sdk/blob/main/CONTRIBUTING.md) · [python-sdk](https://github.com/PredictFlow/python-sdk/blob/main/CONTRIBUTING.md) · [php-sdk](https://github.com/PredictFlow/php-sdk/blob/main/CONTRIBUTING.md))

## License

MIT. See each repository for its license file.
