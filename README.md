# DG Detail — concept demo (unofficial)

Single-file static site (`index.html`): no build step, no dependencies.
Not affiliated with DG Detail. Keep the link private until the owner gives written permission.

## Deploy with GitHub Pages
1. Create a new repository on GitHub (e.g. `dg-detail-demo`).
2. Upload `index.html`, `robots.txt`, `.nojekyll` and `README.md` to the repository root.
3. Go to **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. After about a minute the site is live at `https://YOUR-USERNAME.github.io/dg-detail-demo/`.

## Updating
- Reviews: edit the `REVIEWS` block in `index.html` (only with owner-confirmed data).
- Photos: currently embedded as base64 inside `index.html`; replace the `data:image/...` strings or switch to files in an `/images` folder.
