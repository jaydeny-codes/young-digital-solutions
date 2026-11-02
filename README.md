# Young Digital Solutions website

One-page site for Young Digital Solutions (Jayden Young). Plain HTML and CSS with a little JavaScript for the image zoom. No build step.

- `index.html`: the page
- `assets/`: before/after demo images (fictional demo data)
- `.nojekyll`: tells GitHub Pages to serve the files as-is

## Publish on GitHub Pages (free)

1. On GitHub, create a new **public** repository named `young-digital-solutions`. Don't add a README, license, or .gitignore (this folder already has a commit).
2. From this folder, connect and push:
   ```
   git remote add origin https://github.com/<your-username>/young-digital-solutions.git
   git branch -M main
   git push -u origin main
   ```
3. In the repo, go to **Settings > Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/young-digital-solutions/`.
5. Open it on a phone and a computer, and tap the email button to confirm it opens a message to jayden.youngweb@gmail.com.

## Updating

Edit `index.html`, commit, and push to `main`. Pages redeploys automatically.
