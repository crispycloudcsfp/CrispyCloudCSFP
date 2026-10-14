# Crispy Cloud — GitHub Pages website

A responsive static website for Crispy Cloud with seven product cards, cart, checkout, delivery/pick-up/dine-in choices, Cash and GCash payment options, promotions, About Us, and Google Maps location.

## Deploy to a NEW GitHub repository
1. Create a repository named `crispycloud-new` (or any name you prefer) on GitHub.
2. Upload all files and the `assets` folder from this ZIP to the repository root. Keep `index.html`, `style.css`, and `script.js` at the root.
3. In the repository, open **Settings → Pages**. Choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
4. Wait for GitHub Pages to publish the website.

## Important configuration before publishing
- The checkout opens WhatsApp to **0917 682 3300** to send the order request. Verify that this is the correct business WhatsApp number before launch. Update `639176823300` in `script.js` if needed.
- GCash is selectable at checkout, but the site intentionally says payment details will be confirmed after the order is received. Add your verified GCash details only when ready.
- Delivery fee is set to **₱50** and all seven flavors are **₱89 each**. Update in `script.js` if your actual fee changes.
- Google Maps uses the provided location link: https://maps.app.goo.gl/MhaW26L341Fbx56y5
- Facebook link: https://www.facebook.com/crispycloud (verify the page URL if needed).
- Promotions are seasonal placeholders; confirm the current mechanics and inclusions before publishing any specific offer.

## Notes
This is a static front-end. Orders are sent to WhatsApp for manual confirmation; there is no automatic payment processing, database, stock management, or order dashboard.
