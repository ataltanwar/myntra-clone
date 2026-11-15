# Myntra Clone

A static front-end clone of the [Myntra](https://www.myntra.com/) e-commerce website, built with plain HTML and CSS. It recreates the look and feel of the Myntra shopping experience across three pages: the home page, a product listing page, and a product detail page.

## Pages

| Page | File | Description |
| --- | --- | --- |
| Home | `index.html` | Landing page with banner images, promotional deals, category grid, and a shared header/footer. |
| Product List | `productlist.html` | "Men T-shirts" listing with filters (bundles, country of origin, size), a sort dropdown, and a grid of product cards. |
| Product Detail | `productdetail.html` | Single product view with image gallery, price and discount, color options, size selection, "Add to Bag"/"Wishlist" buttons, delivery check, and best offers. |

## Tech Stack

- **HTML5** – page structure and content
- **CSS3** – styling, layout (Flexbox), hover effects, and sticky header
- **Google Fonts** – [Figtree](https://fonts.google.com/specimen/Figtree)
- **Font Awesome 7** – icons (bag, heart, truck, tag, star, etc.)

No JavaScript or build tools are used; every page is static.

## Project Structure

```
Week 3 Project/
├── index.html
├── productlist.html
├── productdetail.html
├── README.md
├── CSS/
│   └── style.css
└── Images/
    ├── Images/                 # Logos, banners, icons, category images
    ├── Slider-img/             # Home page slider images
    ├── Omg deals/              # Promotional deal images
    ├── Product Images/         # Listing page product photos
    └── Product Detail Images/  # Product gallery and color options
```

## Getting Started

Clone the repository and open `index.html` in any modern browser:

```bash
git clone https://github.com/ataltanwar/myntra-clone.git
cd myntra-clone
```

Then double-click `index.html`, or serve the folder locally:

```bash
# Python 3
python -m http.server 8000
```

and visit `http://localhost:8000`.

## Features

- Shared header with logo, category navigation, search bar, and profile/wishlist/bag links
- Sticky navigation bar with shadow
- Home page promotional banners and a category image grid
- Product listing with expandable filter dropdowns and sort options
- Product cards with images, brand names, prices, and ratings
- Product detail page with:
  - Multi-image gallery
  - Color swatches
  - Size selector with measurement tooltips
  - Price, MRP, and discount display
  - Pincode delivery check field
  - Best offers and return/originality information
- Reusable footer with shopping links, policies, app download, and social icons

## Notes

- This is a **static UI clone** for learning purposes. Links, search, filters, sorting, and buttons are not wired to any backend or JavaScript logic.
- The layout is designed for desktop screens; no media queries are included, so it is not yet responsive on mobile devices.
- All brand names, images, and trademarks belong to their respective owners.
