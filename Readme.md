# E-Commerce Admin — Demo UI

Lightweight demo admin dashboard built as a single static HTML file.

## Preview

Open [index.html](index.html) in your browser (or use VS Code Live Server) to view the UI and interact with demo features.

## Features

- Responsive sidebar navigation and multiple demo pages (Dashboard, Products, Orders, Customers, Analytics, Settings).
- Demo data rendering for orders, customers and products.
- Charts powered by Chart.js (loaded via CDN).
- Local demo settings persistence (base API URL saved to localStorage).

## Files

- [index.html](index.html) — main single-file demo app.

## Important functions (in index.html)

- [`renderRecentOrders`](index.html) — injects rows into the Recent Orders table.
- [`renderCustomers`](index.html) — injects rows into the Customers tables.
- [`renderProductsTable`](index.html) — populates Products and Orders list tables.
- [`generateDemo`](index.html) — demo action triggered by the "Run Demo" button.

## How to run

1. Open [index.html](index.html) in a browser.
2. Or in VS Code install the "Live Server" extension and click "Go Live".

## Customize demo data

Edit the arrays defined near the top of [index.html](index.html):

- `demoOrders`
- `demoCustomers`
- the `prod` array inside `renderProductsTable()`

## Notes

- This is a static demo UI — replace demo data and alerts with real API calls when integrating with a backend.
- Charts require internet access to load Chart.js from the CDN.

## License

Use freely for demos and prototypes.
