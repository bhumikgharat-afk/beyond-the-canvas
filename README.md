# Beyond the Canvas — Bhumik Gharat

A complete static artist portfolio site built from the two supplied PDFs.

## Publish free with GitHub Pages
1. Create a public repository on github.com (for example `beyond-the-canvas`).
2. Upload **index.html**, **artworks.json**, and the complete **assets/** folder to the repository root. Do not upload the ZIP itself as the website.
3. Open repository **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose **main** and **/(root)**, and save.
4. Your site will appear at `https://YOUR-USERNAME.github.io/beyond-the-canvas/` after deployment.

## Edit
- `index.html` contains layout, styling, site copy, and the embedded artwork catalogue.
- `artworks.json` is a human-readable reference copy of the catalogue. The site uses the embedded catalogue in `index.html` so it also works when previewed directly as a file. To edit displayed artwork titles/details, edit the `const artworks = ...` array in index.html. Editing artworks.json alone does not update the website.
- Replace images in `assets/` while keeping filenames unchanged, or update their paths in index.html.
- Contact form opens a prefilled email using the visitor's mail app; it is not a server-side form.
- Works without a confirmed official title have descriptive catalogue labels; confirm before publishing.

## Source notes
- All 31 artwork images extracted from `Bhumik gharat artworks (2).pdf` (one per page).
- Artist bio, education, exhibitions, awards, contact, and named work metadata derived from `Artist Bhumik Gharat Portfolio (2).pdf`.
- Artwork photos were resized/compressed for web delivery.
- Some medium labels for otherwise unidentified images are visual descriptions and should be reviewed.
- The uploaded portfolio lists the address as 26B, while another previous address has been 29B. To avoid publishing an unverified street address, the site lists Vasai, Maharashtra only.
