# Aayushi — Product Portfolio

A static product portfolio with four original/concept stories (Ray, Hormony, Myra and NexBridge) and five clearly credited open-source adaptations.

## Update the website
1. Open index.html in GitHub and choose Edit this file.
2. Update the introduction, project stories, demo links or contact information above the embedded-assets block.
3. Preview your changes and commit to main. Vercel automatically builds and publishes the update.

To add a project, duplicate a project card/story section, give its section a unique ID and update its links. Preserve a clear account of what works, what is simulated, the source licence and your specific contribution. Never present an upstream project as original work.

## Screenshots
The real prototype screenshots are packaged once as base64 data in the embedded-assets JSON block near the bottom of index.html, so the site does not depend on external image hosting. A small script assigns those assets to the page images and enlargement dialog. Project prose stays above this block. To change screenshots, replace the matching asset entry or use an ordinary hosted image URL in the corresponding image and enlargement button.

## Hosting
No build tools, API keys, database or paid services are required. vercel.json serves the repository root as static files. The source repository and the public website have separate visibility settings.

## Open-source credits
- Spend Lens: mrinamoto/expense-tracker-localstorage, MIT.
- Journey Lab: xyflow/vite-react-flow-template, MIT.
- Merchant Cashflow Desk: tuanpham-dev/react-invoice-generator, MIT.
- Payment Insights Lab: lana-k/sqliteviz, Apache-2.0.
- ShopSense: Rhymond/product-compare-react, MIT.

Each adaptation retains its original licence and documents additions in its own repository.
