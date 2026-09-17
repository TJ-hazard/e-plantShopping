# Paradise Nursery Shopping

A React + Redux single-page shopping experience for browsing and purchasing indoor plants by category.

## Overview

Paradise Nursery Shopping is a frontend e-commerce demo where users can:
- Start from a landing page with a brief store introduction
- Browse plant collections grouped by category
- Add plants to a shopping cart
- Increase, decrease, and remove cart items
- View running cart totals

## Tech Stack

- React 18
- Redux Toolkit
- React Redux
- Vite 5
- ESLint

## Getting Started

### Prerequisites

- Node.js 18+
- npm 9+

### Installation

```bash
npm install
```

### Run in Development

```bash
npm run dev
```

The app will run on the local Vite development server (typically `http://localhost:5173`).

## Available Scripts

- `npm run dev` — Start the Vite development server
- `npm run build` — Build the production bundle
- `npm run preview` — Build and preview the production bundle
- `npm run lint` — Run ESLint on JS/JSX files

## Project Structure

```text
/home/runner/work/e-plantShopping/e-plantShopping
├── public/
├── src/
│   ├── App.jsx           # Landing page and top-level navigation flow
│   ├── ProductList.jsx   # Plant catalog and cart navigation
│   ├── CartItem.jsx      # Cart rendering and quantity controls
│   ├── CartSlice.jsx     # Redux cart state and reducers
│   ├── store.js          # Redux store configuration
│   └── main.jsx          # React entry point
├── package.json
└── vite.config.js
```

## Current Behavior Notes

- Cart state is managed globally with Redux.
- Product data is currently hardcoded in the frontend.
- “Checkout” and parts of navigation behavior are currently placeholder/demo behavior.

## License

This project is licensed under the terms of the [MIT License](./LICENSE).
