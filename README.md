# Clare Stokolosa — The Lives of Objects

Exhibition catalog and printable price list for New York City. Both views use the same 47 entries in artworks.json. Prices are original USD inventory amounts, without added fees.

## Edit artworks

Open artworks.json on GitHub, click the pencil, edit, and commit to main. GitHub Pages updates after its deployment finishes; a hard refresh may be needed to see the latest version. No ChatGPT subscription is needed.

Each artwork has a unique SKU, title, price_usd (a number without a currency symbol), medium, size_unframed, size_framed, image_url, product_url, and visible. Dimensions are in inches. Use visible: "no" to hide an entry. Upload artwork images into images/ and use a relative path such as ./images/CS061.jpg. Keep JSON punctuation intact. Do not add sold pieces or duplicate SKUs.

## Show settings

Edit show.json to change the exhibit title, subtitle, currency, price field, or QR filename. This show uses USD and price_usd. Search supports titles and SKUs; sorting defaults to numeric SKU order. The print button prints the full catalog regardless of search results.

## Printable list and QR

The printable catalog retains the previous exhibition's 12-point text and uniform rows, ascending SKU order, repeated headings, and page numbers. The current 47 artworks fit into three balanced A4 pages. Select A4 paper, 100% scale, and disable the browser's own headers and footers.

The QR at the top right is a clearly labeled, non-scannable placeholder. When the final URL is known, replace **qr-code.png** in the repository root with your new PNG QR image and commit. Keep the exact filename; no code or settings edits are needed. The print action requests a fresh QR image each time.

## GitHub Pages and moving to Clare's account

In Settings → Pages, select Deploy from a branch, main, and / (root), then Save. The expected project address is https://fliou0704.github.io/clare-objects/ after deployment succeeds.

Copy all project files into a repository on Clare's account and enable Pages there. Relative paths keep this catalog portable. Generate a new QR for her final address and replace qr-code.png. Updates to separate repository copies are independent.

## Images and review notes

The purple signature is clare-logo.png. Artwork images are display-size copies. Right-click, touch saving, and dragging are discouraged on artwork images, but screenshots and direct-file access remain possible.

CS148, CS346, CS379, and CS522 use inventory details because they were not returned by the current public shop feed. Confirm their availability before the show. Dimensions for CS358 and CS370 were absent from both sources and are left blank. Do not upload original inventory spreadsheets or private notes.
