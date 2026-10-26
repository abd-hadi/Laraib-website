# Starlight Cosmetics

A responsive, elegant static beauty storefront designed for phones, tablets, and laptops. Built with plain HTML, CSS, and JavaScript. No installation, dependencies, or build step required.

## Open locally
Double-click index.html, or serve the folder with any static web server. Google Fonts needs an internet connection; serif and sans-serif fallbacks work offline. All photographs are bundled in assets/.

## Deploy on Vercel
1. Extract the ZIP.
2. Upload the contents of the starlight-cosmetics folder to a GitHub repository, with index.html at the repository root.
3. Import that repository into Vercel as a new project.
4. Use the Other framework preset. Leave the build command empty and use the project root as the output directory (.).
5. Deploy.

Alternatively, from this folder use the official Vercel CLI and run `vercel` to follow its deployment prompts.

## Edit your website
- index.html: page copy, story, navigation, FAQs, and footer.
- styles.css: colours, fonts, layout, and mobile breakpoints.
- app.js: sample catalogue, prices, filters, bag controls, and preview form.
- assets/: bundled photography and favicon.

Prices are sample USD prices. Change the currency in the money formatter in app.js.

## What works
Collection category filters, responsive menu, shopping bag with quantity and remove controls, device-local bag persistence, informational dialogs, FAQ accordions, and email input validation.

## Before taking real orders
This is a frontend storefront preview, not a connected commerce backend. Products, names, prices, and imagery are illustrative. Photographs show third-party beauty products and should be replaced with your own product photography before selling. No payments, orders, email subscriptions, or customer information are transmitted. Connect your commerce provider and mailing list service, replace demo copy, and add real contact, shipping, returns, and privacy details before launch.

## Photography
Source: Unsplash. Bundled images were downloaded from:
- https://images.unsplash.com/photo-1611930022073-b7a4ba5fcccd (hero / Golden Hour)
- https://images.unsplash.com/photo-1608571423902-eed4a5ad8108 (Dew Drops)
- https://images.unsplash.com/photo-1608248543803-ba4f8c70ae0b (Cloud Cream / story)
- https://images.unsplash.com/photo-1596462502278-27bfdc403348 (colour edit)
- https://images.unsplash.com/photo-1556229010-6c3f2c9ca5f8 (ritual)

Fonts: Cormorant Garamond and Manrope via Google Fonts.
