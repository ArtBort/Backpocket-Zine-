# Backpocket zine site

Static website (plain HTML) with a small admin page for editing text and uploading photos.

## Files
- `index.html` – the public site
- `content.json` – all editable text + photo list (written by the admin page)
- `images/` – uploaded photos
- `admin/index.html` – the admin page (`yoursite/admin/`)

## Publish for free with GitHub Pages
1. Push this folder to a new GitHub repository.
2. Repo → Settings → Pages → Deploy from a branch → `main` / root.
3. Your site appears at `https://<username>.github.io/<repo>/`.

## Use the admin page
1. GitHub → Settings → Developer settings → Fine-grained tokens → Generate new token.
   Repository access: only this repo. Permissions: Contents → Read and write.
2. Open `https://<username>.github.io/<repo>/admin/`, paste the token, press Connect.
3. Edit text, add photos, press Publish. The site updates in about a minute.

The token is stored only in your browser. Anyone can open /admin/, but nobody can save without the token.
