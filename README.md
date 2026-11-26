# Shayran · UI Preview

Public, synthetic-data preview of the three Shayran portals. The private application source is not hosted here. This preview does not authenticate real users, connect to a database, send SMS, or perform payments.

## Deployment

1. Enable Pages in Settings → Pages → Source → GitHub Actions.
2. Run **GitHub Pages demo export** in the private application repository.
3. Download its `shayran-github-pages` artifact and upload the ZIP, unextracted, to this repository's main branch as `shayran-github-pages.zip`.
4. The **Publish Shayran demo** workflow validates and publishes only the static site.

Expected site: https://cianium.github.io/shayran-demo/

Only reviewed generated public frontend assets with synthetic data belong in this repository. Never upload the source archive, credentials, customer data, or environment files.
