# Mandi — Smart Kirana Inventory & B2B Ordering

**Mandi** is a mobile-first inventory management and B2B ordering prototype designed for small kirana shop owners in India. It aims to simplify stock monitoring, identify products that need replenishment, discover suppliers by city, and track orders through a simple, accessible interface.

Prototype: https://ayanvsingh.github.io/mandi-smart-inventory/

## Problem Statement

Small kirana stores often rely on manual stock checks and informal coordination with suppliers. This can make it difficult to identify low-stock products early, maintain an organized inventory, and replenish products on time.

Mandi explores how a simple digital solution can make inventory visibility and replenishment decisions easier for small retailers.

## Key Features

- **Inventory Dashboard:** View products, SKU quantities, stock percentages, and critical items.
- **Low-Stock Alerts:** Highlight products that reach or fall below the 30% reorder threshold.
- **Product Repository:** Browse and search products by name or category.
- **Reordering:** Select products and adjust quantities before initiating a demo order.
- **City-Wise Vendor Discovery:** Browse supplier listings for selected Indian cities.
- **Order Tracking:** View order status, placement dates, and illustrative delivery milestones.
- **Product Scanning:** Demonstrate a scan-to-add workflow.
- **Multilingual Options:** Language selection for English and major Indian languages.
- **Light & Dark Modes:** Switch between visual themes.
- **Mobile-First UI:** Designed around simple navigation and readable screens for mobile users.

## Technology

- HTML
- CSS
- JavaScript
- GitHub Pages for static website hosting

## How to Run Locally

1. Clone this repository:

   ```bash
   git clone https://github.com/avanysingh/mandi-smart-inventory.git
   ```

2. Open the project folder.
3. Open `index.html` in a web browser.

No build step is required for the standalone HTML prototype.

## Deployment

The prototype can be hosted using **GitHub Pages**:

1. Open the repository's **Settings**.
2. Navigate to **Pages**.
3. Select **Deploy from a branch**.
4. Choose the `main` branch and the `/ (root)` folder.
5. Save and open the published website URL shown by GitHub.

## Current Limitations

Mandi is currently a front-end prototype developed for educational and demonstration purposes.

- Inventory data is illustrative and is not connected to a live database.
- Barcode scanning is simulated.
- Order placement and tracking are demonstrations, not real transactions.
- Supplier listings use publicly available information where included; supplier availability, prices, contact details, and delivery commitments must be independently verified.
- Language selection is a prototype feature and does not necessarily translate every screen.
- No live authentication, payment system, or supplier integration is implemented.

## Future Enhancements

- Integrate a real inventory database and persistent stock updates.
- Implement camera-based barcode scanning.
- Connect suppliers to live product catalogs, pricing, and availability.
- Enable real order placement and delivery tracking.
- Add complete regional-language localization.
- Introduce demand forecasting and reorder recommendations.
- Add secure user accounts and store-level inventory management.

## Project Objective

The objective of Mandi is to explore how accessible technology can help small retailers improve inventory visibility, reduce stockout risk, and simplify replenishment decisions.

**Project type:** Academic / Product Prototype  
**Status:** Interactive front-end prototype

---

*Built as a class project exploring inventory management, B2B commerce, and user-centered product design.*
