# My Brain

A simple to-do list PWA with descriptions and a calendar. Tasks are stored in the browser (localStorage). No build step.

## Deploy with GitHub Pages
1. Create a repo in your organization and upload all files at the root.
2. Settings > Pages > Source: Deploy from a branch > `main` / `(root)` > Save.
3. Open `https://<org>.github.io/<repo>/` and choose Add to Home Screen / Install.

When you change any file, bump `CACHE` in `sw.js` (e.g. `my-brain-v2`) so installed copies update.
