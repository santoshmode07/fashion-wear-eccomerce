# Fashion-Wear E-commerce Website

A static front-end e-commerce project built with HTML, CSS, JavaScript, and Bootstrap.

## Overview

This project includes a landing page and separate category pages for:
- Men's wear
- Women's wear
- Kid's wear

The landing page (`Ecommerce.html`) contains:
- A fixed top navigation bar
- Hero carousel and welcome section
- Category cards linking to each category page
- Featured product cards
- FAQ accordion
- Logout toast notification

Each category page renders product cards dynamically using JavaScript arrays in the page script.

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Bootstrap 5
- Font Awesome (icons on category pages)

## Project Structure

```text
Eccomerce/
├── Ecommerce.html
├── styles.css
├── script.js
├── mens/
│   ├── mens.html
│   └── products.json
├── womens/
│   ├── womens.html
│   └── products.json
└── kids/
    ├── kids.html
    └── products.json
```

## How to Run

1. Open `Ecommerce.html` in your browser.
2. Click a category card to navigate to product listing pages.

No build setup or package installation is required.

## Notes

- Product data is currently hardcoded inside each category HTML file.
- `products.json` files exist and can be used in future to move data outside HTML scripts.
