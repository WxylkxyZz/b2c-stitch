# Tabajoy static prototype for Vercel

This directory contains a browse-only static prototype assembled from the 26 current Stitch screens. The original export remains unchanged.

## Deploy

1. Import the Git repository containing this project into Vercel.
2. Set **Root Directory** to `stitch_japanese_squishy_dtc_storefront/vercel-prototype` (or `vercel-prototype` if this directory itself is the repository root).
3. Select **Other** as the framework preset.
4. Leave **Build Command** and **Output Directory** empty; this is a static HTML site.
5. Deploy and open the root URL. `index.html` is the page directory.

If deploying from the command line with Vercel CLI, run it from this directory and use Vercel's static deployment flow.

## Limitations

- This is a design prototype, not a production storefront.
- Cross-screen browsing is available from the index page; the original screens' internal controls are not comprehensively wired.
- No live cart, order submission, Medusa backend, or Stripe payment processing is included. Checkout remains non-functional and purchase controls stay disabled.
- Contact is not created.
- Tailwind, fonts/icons, and product images are fetched from third-party URLs; rendering may be incomplete if network access or those URLs fail.
- Prices, materials, shipping, and legal/operational details remain unconfirmed. Do not use this deployment to accept sales.
