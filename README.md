# ToolNest — Digital Products Storefront Demo

ToolNest is a responsive storefront-style frontend for browsing a catalogue of digital products and adding selected items to a shopping cart. It demonstrates product cards, pricing sections, cart interactions, and user feedback without connecting to a real payment processor.

## Features

- Product catalogue loaded from `public/products.json`.
- Product cards with descriptions, pricing periods, feature lists, and category badges.
- Add-to-cart and remove-from-cart interactions.
- Duplicate-item prevention and clear cart feedback.
- Cart count and checkout demonstration flow.
- Pricing, hero, statistics, and getting-started sections.
- Responsive layout and toast notifications.

## Tech stack

- React and Vite
- Tailwind CSS and DaisyUI
- Lucide React icons
- React Toastify

## Run locally

**Requirements:** Node.js and npm.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually `http://localhost:5173`).

## Useful scripts

```bash
npm run dev      # development server
npm run build    # production build
npm run preview  # preview the production build
npm run lint     # ESLint
```

## Important scope note

This repository is a frontend demonstration. Cart state is held in React memory and is not persisted to a server or database. The checkout action is a demo interaction; it does not charge a card, create a real order, or connect to a payment gateway. Product names and prices are sample catalogue data.

## Source attribution note

The supplied source archive's earlier README named **Md Al Amin Miah** as author and linked to `github.com/mdalaminmiah/B13-A6-DigiTools-Platform-App`. Confirm your right to publish this code and preserve any required attribution before making this repository public. No `LICENSE` file was included in the supplied archive.
