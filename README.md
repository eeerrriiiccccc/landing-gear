# Retractable Landing Gear: portfolio page

This is a static site with no build step: `index.html` plus `assets/` (the 3D model `landing_gear.glb` and the PNG views exported from SolidWorks).

## Publish on GitHub Pages (free, about 5 minutes)

1. Sign in at github.com and create a **new public repository**, for example `landing-gear`.
2. On the new repo's page, click **"uploading an existing file"**. Drag in `index.html`, `README.md`, and the whole `assets` folder, then click **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment*, set **Source: Deploy from a branch**, **Branch: `main`**, folder **`/ (root)`**, then click **Save**.
4. Wait about a minute and refresh. GitHub shows your live URL:
   `https://<your-username>.github.io/landing-gear/`
5. Open the link in a private/incognito window to confirm it works without signing in. Then put it on your resume, as a hyperlink on the project title.

## Update later

Edit or replace files in the repo on github.com and commit. The site redeploys automatically within a minute.

## Preview locally

```bash
python -m http.server 8000
```
Then open http://localhost:8000. The 3D viewer needs a web server; opening `index.html` by double-click won't load the model.
