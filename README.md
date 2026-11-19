# Crumb & Co. — Customer Storefront

A frontend-only React + TypeScript + Vite bakery storefront. The existing homepage and shopping experience are retained, with two interactive product customisers added in the same illustrated, scrapbook-inspired visual style.

## Run locally

```powershell
npm install
npm run dev
```

Open the local URL printed by Vite (usually `http://localhost:5173`).

## Customer pages

- `/` — Homepage
- `/menu` — Product catalogue, search and filters
- `/product/:id` — Product detail page
- `/cake-builder` — Build Your Own Cake customiser
- `/bakery-box` — Bakery Box Builder
- `/cart` — Shopping cart
- `/checkout` — Demo checkout
- `/order-success` — Demo order confirmation

## New customisers

### Build Your Own Cake
- Choose vanilla, chocolate truffle, red velvet or strawberry.
- Choose 0.5 kg, 1 kg or 2 kg.
- Choose frosting and eggless option.
- Add a cake message and special notes.
- Price updates as options change.
- Add the custom cake to the existing cart or go directly to demo checkout.

### Bakery Box Builder
- Choose a 4, 6, 9 or 12-piece box.
- Filter the existing catalogue by category.
- Add and remove products until all slots are filled.
- See a live box fill indicator and itemised price summary.
- Add the completed box to the existing cart or go directly to demo checkout.

Custom cakes and bakery boxes are stored as custom cart lines, so they work with the existing cart, checkout and order confirmation pages. Cart and wishlist data continue to use browser localStorage.

## Notes

- This is a frontend portfolio demo. No real order is submitted and no payment is collected.
- Product catalogue, prices, reviews, delivery fee and customisation surcharges are sample data and should be reviewed before any real business use.
- Product photography is loaded from remote Unsplash image URLs, so images require an internet connection.
- No staff/admin dashboard or backend is included.


## Latest visual update
- Added a muted, autoplaying, looping bakery dough-preparation video behind the top
  navigation only. The clip is intentionally subdued with a cream wash so the logo,
  order button and cart remain readable. The bottom illustrated dock is unchanged.
- Tightened the homepage hero's top spacing and adjusted its composition to reduce
  unused vertical space while retaining the scrapbook photo frame.
- The navigation video is externally hosted and requires an internet connection.
  Reduced-motion preferences disable the moving video.
