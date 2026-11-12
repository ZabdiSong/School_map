# Campus Atlas — GitHub Pages website

A complete static website for exploring the 20 schools in your college list.

## Publish it on GitHub Pages

1. Unzip `campus-atlas-github-pages.zip` on your computer.
2. Create a **public** GitHub repository named `campus-atlas` (or use another name).
3. In that repository, choose **Add file → Upload files**. Drag in the extracted **contents**: `index.html`, `app.js`, `style.css`, `schools.json`, the entire `assets` folder, and the remaining files. Do not upload the ZIP itself. `index.html` must appear directly on the repository's main page, not inside another folder. Preserve the `assets` folder and its contents. The optional `.nojekyll` file may be hidden in Finder; the site also works without it.
4. Commit the upload to the `main` branch.
5. Open **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose **main** and **/(root)**, and click **Save**.
6. Wait for the Pages deployment to complete. Refresh **Settings → Pages** and click **Visit site**. Your address will normally be `https://YOUR-USERNAME.github.io/campus-atlas/` (replace the username and repository name with yours).

If your default branch has another name, select that branch instead of `main`.

## Included

- All 20 schools and their main-campus map locations
- Zoomable map, nearby-school clusters, search, and region filters
- Expandable school guides, culture, seasonal climate, and local activity ideas
- Downloaded photos with source links
- Current modeled weather from Open-Meteo, with Celsius/Fahrenheit toggle
- Responsive styles for phones and desktops

No build step, package installation, API key, or ChatGPT sign-in is required. The paths are relative, so this works under a GitHub repository URL.

An internet connection is needed for map tiles, live weather, and optional Google Fonts. School data, photos, map libraries, and the main styles are included in the ZIP. Weather and map failures have fallback messages.

## If the page does not load

- Upload the extracted files, not just the ZIP.
- Ensure `index.html` is in the repository root and Pages uses that same branch and `/(root)`.
- Check the repository's **Actions** tab for deployment status.
- Open the **Visit site** address from Pages settings, not the GitHub code page.
- If photos or the map library are missing, verify that the whole `assets` folder was uploaded with its original filenames.
- Opening `index.html` directly from your computer may block the school-data request. Use GitHub Pages or a local web server.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Photo sources

The school guides link to image sources for credits and usage information. A Chapel Hill campus photograph is also used for the Chapel Hill campus-setting card. Regional emoji are illustrative motifs, not official seals. Activities are exploration ideas rather than scheduled events.
