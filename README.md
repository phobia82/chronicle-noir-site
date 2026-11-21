# Chronicle Noir public site

Static homepage, privacy policy and terms for the Chronicle Noir OAuth consent screen.

Intended live URLs after GitHub Pages is enabled from `main`:

- https://phobia82.github.io/chronicle-noir-site/
- https://phobia82.github.io/chronicle-noir-site/privacy.html
- https://phobia82.github.io/chronicle-noir-site/terms.html

## Publish

1. Create a public repository named `chronicle-noir-site` under `phobia82` (empty is fine).
2. Push this directory to the `main` branch.
3. In the repo: Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)` → Save.
4. Wait until the three URLs above return HTTP 200.

## Google Cloud values

- Authorized domain: `phobia82.github.io`
- Application home page: `https://phobia82.github.io/chronicle-noir-site/`
- Privacy policy: `https://phobia82.github.io/chronicle-noir-site/privacy.html`
- Terms of service: `https://phobia82.github.io/chronicle-noir-site/terms.html`

Verify `https://phobia82.github.io/` as a URL-prefix property in Google Search Console before adding the authorized domain. If Google provides an HTML verification file, add it to this repo at the path Search Console specifies (often the user-site root; a project-site path works only for a prefix property of that path).
