# kadeya-maintenance-pub

**Public** repository for **kadeya-maintenance** distribution (Windows binaries and HTML documentation).

Source code and development live in the private `kadeya-maintenance` repository within the organization; this repo does not contain Go application sources, only what end users and machines need.

## Releases

Executables and archives for automated updates are published here:

**[Releases — kadeyaorg/kadeya-maintenance-pub](https://github.com/kadeyaorg/kadeya-maintenance-pub/releases)**

## Documentation (GitHub Pages)

Interface documentation (HTML) is in the [`docs/`](./docs/) folder. Table of contents: [`docs/index.html`](./docs/index.html).

To publish the site:

1. **Settings → Pages**
2. **Build and deployment**: *Deploy from a branch*
3. Branch `main`, folder **`/docs`**
4. Site URL: `https://kadeyaorg.github.io/kadeya-maintenance-pub/`

Docs are updated automatically when a release is published from the private source repo (GitHub Actions workflow).
