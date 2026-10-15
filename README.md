# MAISON VERVE — Editorial Magazine

A free-to-host, mobile-responsive magazine with issue archive, editorial sections, article pages and a browser-based issue composer.

## Preview locally

Run `python3 -m http.server 8000` in this folder and visit `http://localhost:8000`. Browsers may block loading `magazine.json` directly from a `file://` page; use a local server or GitHub Pages.

## Publish for free

1. Create a public GitHub repository, e.g. `maison-verve`.
2. Upload `index.html`, `style.css`, `site.js`, `magazine.json`, `editor.html`, `editor.js` and this README to the repository root.
3. Settings > Pages > Deploy from a branch > main > / (root) > Save.
4. Visit `https://YOUR-USERNAME.github.io/maison-verve/` after deployment.

## Publish a new issue (as often as you like)

1. Open `editor.html` on your hosted site or local preview.
2. Download the CURRENT `magazine.json` from your repository, and load it into the editor. **Always load the newest file** so you do not lose older issues.
3. Fill in the issue, add articles and click **Download updated magazine.json**.
4. In GitHub, open `magazine.json`, click **Edit (pencil)**, select all, paste the contents of the downloaded JSON file, then **Commit changes**. You can also upload/replace it using GitHub's interface.
5. After deployment the latest issue becomes the homepage feature and previous issues remain under Issues.

The editor does not store data remotely and does not publish automatically. Keep backups. The editor is publicly accessible if you host it; it does not grant write access to your GitHub repository, but don't put private drafts or passwords in it.

## Image rights

The starter edition uses Unsplash-hosted example photos, not the vintage Vogue and runway images supplied as references. Do not republish copyrighted magazine covers or runway photographs without permission or a suitable license. Replace starter articles and images with your own work or appropriately licensed materials. Remote images require an internet connection and may change or disappear.

## Costs

GitHub Pages hosts public static repositories for free under its current free-plan rules. The URL uses `github.io`; a custom domain is optional and normally costs money. GitHub Pages does not include a CMS, so publication requires updating one JSON file.
