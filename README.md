# A2S2 – Food Date With Us POS

A lightweight, browser-based point-of-sale app for A2S2 Food Date With Us.

## Run locally

Open `index.html` in a modern browser. No build step or server is required for local use.

## Deploy with GitHub Pages

1. Create a GitHub repository.
2. Upload the contents of this ZIP so `index.html` is in the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site.

## Included features

- Updated A2S2 menu and prices, including Combo Offers
- Product categories and cart quantity controls
- Cash and UPI payment selection (UPI must be verified manually in the UPI app)
- Bill numbering and 58mm receipt printing
- Sales summary and CSV export

## Important data note

Sales are stored in the browser's local storage on the device/browser where bills are created. They are not automatically synchronized between devices. Export the CSV regularly and avoid clearing browser data without a backup.
