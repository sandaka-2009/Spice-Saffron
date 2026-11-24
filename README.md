# Spice-Saffron
# Spice & Saffron — Contemporary Indian Dining Website

A responsive, single-page restaurant website built for a college web development project using HTML5, CSS3, and Vanilla JavaScript. It features an interactive food menu, live order cart with GST calculation, promo code functionality, table reservation modal, and dynamic customer reviews.

---

## Features

* **Hero & Navigation:** Sticky header with smooth-scroll navigation, mobile menu drawer, and a **Book a Table** reservation modal with instant confirmation.
* **Interactive Food Menu:**
  * Filter dishes by category (*All, Starters, Main Course, Desserts, Beverages*).
  * Real-time search bar to find dishes by name or ingredient.
  * **Pure Veg Only** toggle switch with standard Indian FSSAI-style Veg/Non-Veg indicators.
  * Indian Rupee (`₹`) pricing.
* **Live Order Tray (Cart):**
  * Slide-over cart drawer with item quantity controls (`+` / `-`) and item removal.
  * Automatic subtotal, promo discount, 5% GST, and grand total calculation.
* **Special Offers & Promo Codes:** One-click copyable coupon codes (`ROYAL20`, `CAMPUS150`, `SIP1PLUS1`) that can be applied directly inside the order tray.
* **Dynamic Customer Reviews:** Visitors can submit a star rating and review, which immediately renders on the page.
* **Contact & Location:** Includes restaurant address, opening hours, phone/email details, a styled location map card, and a working inquiry form.

---

## Tech Stack

* **HTML5:** Semantic structure and accessible form elements.
* **CSS3:** Custom CSS variables, Flexbox, CSS Grid, responsive media queries, and smooth transitions.
* **JavaScript (ES6+):** DOM manipulation, dynamic filtering, cart state management, and modal handling (zero external frameworks required).
* **Google Fonts:** *Playfair Display* (headings) and *Inter* (body text).

---

## Project Structure

```text
spice-and-saffron/
├── index.html      # Complete markup, styling, and interactive scripts
└── README.md       # Project documentation
