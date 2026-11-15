# Trade X — React + Tailwind CSS

A responsive fintech marketing website and interactive front-end trading workspace preview built with React 19, Vite, and Tailwind CSS v4.

## Included

- Responsive Trade X landing page with navigation, hero, email waitlist forms, market ticker cards, feature grid, learning section, CTA, and footer.
- Interactive market filters (All assets / Gainers / Losers).
- Buy/Sell demo panel with editable amount and estimated total.
- Demo workspace with watchlist and illustrative chart.
- Accessible mobile navigation, semantic sections, reduced-motion support, and basic SEO metadata.
- No Figma plugins, Figma references, or proprietary build hooks.

## Important: demo-only data

Market prices, portfolio values, chart lines, and order book rows are static illustrative values. The email forms show a local demo confirmation and do not submit to a mailing-list provider. Buy/Sell controls do not place orders. There is no backend, authentication, wallet custody, payment processing, or live market feed. Connect audited services and add server-side validation, compliance, security, and appropriate disclosures before using this as a real financial product.

## Requirements

- Node.js 20.19+ or 22.12+
- npm 10+ (or pnpm 10+)

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite.

## Production build

```bash
npm run build
npm run preview
```

The deployable static site is generated in `dist/`.

## Deploy

### Vercel
1. Import this repository into Vercel.
2. Framework preset: **Vite**.
3. Build command: `npm run build`.
4. Output directory: `dist`.

### Netlify
1. Import this repository into Netlify.
2. Build command: `npm run build`.
3. Publish directory: `dist`.

### Static hosting
Upload the contents of `dist/` to any static host that serves `index.html` as the entry point.

## Customize

- Brand copy and sections: `src/App.jsx`
- Design tokens and responsive styling: `src/index.css`
- Page metadata: `index.html`
