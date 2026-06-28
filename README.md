# Liuli Natural Energy Healing Website

Professional static website for Liuli Natural Energy Healing LLC.

## Pages
- `index.html` — premium homepage
- `shop.html` — demo ecommerce/shop page
- `assets/styles.css` — full responsive design
- `assets/script.js` — mobile menu, reveal animation, demo cart button

## Local preview
Open `index.html` directly in your browser, or run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub upload method
1. Go to GitHub and create a new repository, for example `lneh-website`.
2. Extract this ZIP.
3. Open the extracted folder.
4. Select all files and folders inside it: `index.html`, `shop.html`, `assets`, `README.md`, and `vercel.json`.
5. Upload them to the new GitHub repository.
6. Commit the files.

## Vercel deployment method
1. Go to Vercel and sign in.
2. Click **Add New Project**.
3. Import the GitHub repository.
4. Framework preset: **Other** or **Static HTML**.
5. Build command: leave empty.
6. Output directory: leave empty or use `.`.
7. Click **Deploy**.

Every future GitHub update will automatically create a new Vercel deployment.

## Notes
This is a static demo website. The shop is visual only and does not process payments. To sell products, connect it later to Shopify, WooCommerce, Stripe, or a custom backend.

## Asset Images Included

This corrected version includes an `assets/images/` folder with SVG product and botanical visuals:

- `hero-botanical-skincare.svg`
- `clear-balance-gel.svg`
- `scar-comfort-oil.svg`
- `calm-clay-mask.svg`
- `chamomile-mist.svg`
- `calendula-cream.svg`
- `ritual-kit.svg`
- `ingredient-journal.svg`

These are lightweight vector images and work directly on GitHub Pages, Vercel, Netlify, or any static hosting.


## Folder Structure

```
lneh_professional_website/
├── index.html
├── shop.html
├── pages/
│   ├── about.html
│   ├── approach.html
│   ├── research.html
│   ├── ingredients.html
│   └── contact.html
├── assets/
│   ├── styles.css
│   ├── script.js
│   └── images/
└── vercel.json
```

The `pages` folder now contains real standalone pages.
