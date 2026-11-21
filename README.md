# Pathya Foods frontend

A responsive, multi-page frontend concept for Pathya Foods, built with semantic HTML and CSS only. No JavaScript, framework, or backend is used.

## Pages

- `index.html` — animated three-slide hero, categories, bestsellers, brand story, testimonials, newsletter, and footer.
- `pages/shop.html` — filter sidebar and product catalogue.
- `pages/product-details.html` — product gallery, details, CSS-only tabs, benefits, and related products.
- `pages/our-story.html` — brand story and philosophy.
- `pages/login.html` and `pages/register.html` — static account form designs.
- `pages/cart.html` — sample cart and order summary.
- `pages/contact.html` — contact details, form, and FAQ.

## Stylesheets

Shared styles live in `css/style.css`; page-specific styles live in `shop.css`, `product.css`, `auth.css`, and `cart.css`. `responsive.css` holds tablet/mobile rules.

## Preview

Open `index.html` in a browser, or serve the folder with any static file server. For example, from this directory run `python -m http.server 4173` and visit `http://localhost:4173`.

The newsletter, account, contact, cart, and checkout controls are frontend mockups. They do not store data or process orders. Food photography is stored under `assets/images` and sourced from Unsplash. Web fonts load from Google Fonts when online.
