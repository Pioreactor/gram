# Grand River Products

A static page for https://grandrivermfg.ca, operated by Pioreactor, Inc. Plain HTML and CSS; no build or JavaScript required. Contact: info@grandrivermfg.ca.

## Preview

Run `make serve` and open http://127.0.0.1:8000.

## GitHub Pages

Push these files to the GitHub repository. In Settings → Pages, select **Deploy from a branch**, choose the published branch and **/ (root)**. Set the custom domain to `grandrivermfg.ca` and enable HTTPS once the domain is configured.

Configure the apex domain's DNS using GitHub's [custom domain instructions](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain). The checked-in `CNAME` file preserves the custom domain. `.nojekyll` lets GitHub serve the files directly.

## Sources

- Brand purples: `#5331ca` and `#2c1871`, from the Pioreactor storefront stylesheet.
- [Pioreactor 40 mL photo](https://pioreactor.com/en-ca/products/pioreactor-40ml), saved as `assets/pioreactor-40ml.jpg`.
- [OLED display photo](https://pioreactor.com/en-ca/collections/accessories-and-parts/products/pioreactor-oled-display), saved as `assets/oled-display.jpg`.
- [HQ address](https://pioreactor.com/en-ca/pages/about-us): 45 Princess St. E., Waterloo, Ontario, Canada, N2J 2H6.

Photos are stored locally so the page does not depend on Shopify image URLs at runtime.
