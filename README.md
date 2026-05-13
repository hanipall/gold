# Rástlo to rýchlejšie ako zlato?

Static one-page HTML site prepared for GitHub Pages.

## Files

- `index.html` — the full webpage, with all CSS inside the file.
- `.nojekyll` — tells GitHub Pages not to process the site with Jekyll.
- `README.md` — this guide.

## How to publish on GitHub Pages

1. Create a new GitHub repository, or open an existing one.
2. Upload the contents of this folder to the repository root.
3. Commit the files.
4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/root`.
7. Save.

After GitHub finishes publishing, the page will open at a URL similar to:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

## Notes

This is a pure static site. It does not need Node, npm, build tools, Cloudflare, or a backend.
