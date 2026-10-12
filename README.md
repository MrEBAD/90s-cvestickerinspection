# SAHP Vehicle Inspection Sticker Generator

Static, GitHub Pages-ready website. The expiration month, day, and year (default 1995) can be changed; the preview cycles through gold, blue, green, and red every four months. The original user-provided PDF design is used as the image template. Download outputs a 1200 × 900 PNG.

## Deploy to GitHub Pages
1. Upload **both** `index.html` and `sticker-template.png` to the root of a GitHub repository.
2. Open repository **Settings → Pages**.
3. Select **Deploy from a branch**, `main`, `/ (root)`, and save.
4. Visit the Pages URL after deployment. If you see a 404, check that the file is named exactly `index.html` and Pages is enabled. If the sticker image is missing, verify the PNG is in the same directory.

No build system, npm, or external dependencies are required.

Updated: 12 distinct monthly colors (January–December).
