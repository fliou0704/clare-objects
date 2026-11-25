# Clare Stokolosa — Objects

Empty starter for a new exhibition catalog. No artworks from the Italy catalog are included.

## Show settings

Edit `show.json` on GitHub to set the title, subtitle, currency, matching price field, and optional QR image filename. EUR is a temporary default until the show details are supplied. Supported currency/field pairs are EUR/price_eur, USD/price_usd, and GBP/price_gbp.

## Artworks

Edit `artworks.json` on GitHub and commit to main. The website and printable list share this file; no ChatGPT subscription is required to edit it. It currently contains an empty list. Each artwork needs a unique SKU. Set visible to "yes" to display it or "no" to hide it.

Example structure (do not publish this placeholder as a real artwork):

```json
{
  "sku": "CS000",
  "title": "Artwork title",
  "price_usd": null,
  "price_eur": null,
  "price_gbp": null,
  "medium": "Watercolor",
  "size_unframed": "5 x 7",
  "size_framed": "7 x 9",
  "image_url": "./images/CS000.jpg",
  "product_url": "https://clarestokolosa.com/",
  "visible": "yes"
}
```

Dimensions are in inches. Prices are numbers, without currency symbols. Verify prices and availability against Clare's website before publishing. Do not add sold pieces or duplicate SKUs.

## GitHub Pages

In Settings → Pages, choose Deploy from a branch, main, and / (root), then Save. The expected project address is https://fliou0704.github.io/clare-objects/ once Pages is enabled and deployment succeeds. Search supports titles and SKUs; sorting defaults to numeric SKU order.

The print button stays disabled while there are no artworks. The printable catalog uses 12-point text, uniform rows, numeric SKU order, and repeated headings. Check print preview after adding artworks, especially long titles. Search never removes entries from the full printed list.

## QR and moving to Clare's account

Leave qr_image empty until the final hosting URL is known. Upload a PNG QR image to this repository, then set qr_image in show.json to its relative filename. The print list can work without a QR and requests a fresh image each time once one is configured.

Copy the whole project into a repository on Clare's account, enable Pages there, and generate a QR for that final URL. Relative file paths keep the catalog portable. Updates to separate copies are independent.

## Images

Upload display images to images/. Right-click and dragging are discouraged on artwork images, but public images cannot be made download-proof. Screenshots and direct-file access remain possible. Do not upload original inventory spreadsheets or private notes.
