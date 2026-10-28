# The Tsunami History Period

A static, single-page global tsunami history atlas. The complete page styling and application logic are in `index.html`; no build step is required.

## Publish with GitHub Pages

1. Create a GitHub repository and upload the contents of this folder to its root.
2. In the repository, open **Settings → Pages**.
3. Choose **Deploy from a branch**, select the `main` branch and `/ (root)`, then save.

The page needs an internet connection. The basemap, historical event records, active U.S. alert feed, fonts, Leaflet library, and editorial images are loaded from their providers at runtime. See [ASSETS_AND_SOURCES.md](ASSETS_AND_SOURCES.md) for the service and attribution list.

## Local preview

Open `index.html` in a browser while online. Some browsers restrict network requests from local files; if that happens, serve this folder with any basic static file server.

