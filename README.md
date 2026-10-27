# Gama Journey

Static, responsive project-journal website. No dependencies, build tool, trackers or external assets.

## Preview
Open `index.html` in a browser, or use `python3 -m http.server 8000` from this directory and open `http://localhost:8000`.

## Publish via GitHub Pages
1. Create a new public repo, e.g. `gama-journey` (do not use the private engineering repository).
2. Upload `index.html` and optionally this `README.md` to its root.
3. In the repo's Settings → Pages, select **Deploy from a branch**, `main`, `/ (root)` and save.
4. Once the site works at the `github.io` URL, configure `gama.vijaythamban.com` in Pages and add the corresponding Cloudflare DNS record; follow GitHub's domain verification/HTTPS guidance.

**Privacy:** GitHub Pages is a public website. Do not publish internal logs, original Figma design files, private screenshots, sensitive repo URLs or credentials.

## Updating milestones
Near the bottom of `index.html`, edit only the `journey` JavaScript object: `lastReviewed`, `capabilities`, `milestones`, and `upcoming`. The page updates automatically on refresh after the change is committed. The page does not independently monitor GitHub or update itself.

## Visual assets
The desktop editor illustration is **conceptual**, not a screenshot of a real Gama build. Replace it with a sanitized genuine screenshot later if desired.