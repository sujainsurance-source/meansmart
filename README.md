# SAFEER STUDIO — React + TypeScript Storefront

Responsive fashion storefront demo built with React, TypeScript, Vite and Lucide icons.

## Local development
1. Install Node.js 20 or newer.
2. Run `npm install`.
3. Run `npm run dev` and open the local URL.

## Production build
`npm run build` creates the deployable `dist/` folder.

## Docker
`docker build -t safeer-studio .`
`docker run --rm -p 8080:80 safeer-studio`
Open http://localhost:8080.

## Render
Create a **Docker** web service from this repository. Set the branch to `main`. Render will build the root `Dockerfile`; no separate build or publish directory is needed.

## Included demo features
- Responsive React/TypeScript storefront and mobile navigation
- Product catalogue, category filters, search, sorting and price filter
- Product quick view and size selection
- Wishlist and cart drawer with quantity controls and subtotal
- Editorial sections and newsletter UI

## Demo limitations
This is a frontend demonstration. Authentication, database, real inventory, order management, email delivery, payment gateway, shipping integrations and persistent cart storage are not connected. Product images load from Unsplash and therefore require internet access.
