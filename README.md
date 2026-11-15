# kpsafvan.github.io

Official personal landing page and product showcase for **K P Safvan** ([kpsafvan.in](https://kpsafvan.in)).

## 🚀 Features

- **Tile / Button Format**: Bento-inspired responsive grid of product cards with interactive buttons, hover lift effects, and status indicators.
- **Live Product Spotlight**: Dedicated featured styling and pulsing status dot for active hosted apps (e.g. **Kerala Transit Analytics**).
- **In Development Pipeline**: Cards for products currently in development with clear status tags.
- **Instant Search & Category Filters**: Real-time filtering by status (`Live`, `In Development`) or search keywords.
- **Zero Build Setup**: Pure HTML5, modern CSS3, and vanilla JavaScript. Deploys instantly via GitHub Pages.

## 🛠️ Adding or Editing Products

All products are configured in the `productsData` array in [`index.html`](./index.html):

```javascript
{
  id: "your-product-id",
  title: "Product Name",
  description: "Short description of what the product does.",
  status: "live", // "live" or "in-dev"
  statusLabel: "Live Product",
  featured: true, // true to give it emerald glow and highlighted border
  icon: `<svg ...></svg>`, // SVG icon markup
  tags: ["Vue 3", "TypeScript"],
  primaryUrl: "https://your-live-app.com",
  primaryLabel: "Launch App",
  githubUrl: "https://github.com/..."
}
```
