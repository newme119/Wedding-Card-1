# Luxury Wedding Invitation

A self-contained, responsive wedding invitation website. Open `index.html` in a browser to preview locally or upload all files to a GitHub repository and enable GitHub Pages.

## Quick edits
Open `index.html` and find `const WEDDING = { ... }` near the bottom. Change:
- `groom` and `bride`
- `year`
- `city`, `venue`, `mapQuery`
- `whatsapp` (include country code, digits only recommended)
- `events` array for dates, titles, descriptions and tentative status

Photo spaces are optional: visitors can toggle them off on the website. To add real photos, replace each `.photo-placeholder` block inside the couple section with an `<img src="your-photo.jpg" alt="...">` and upload the image file alongside `index.html`.

## Publish on GitHub Pages
1. Create/open a GitHub repository.
2. Upload `index.html` and `README.md` (plus any photos you add) to the repository root.
3. Open Settings → Pages.
4. Set Build and deployment source to Deploy from a branch, select `main` and `/(root)`, then Save.
5. Wait a few minutes and open the Pages URL shown there.

The RSVP buttons open WhatsApp with a prefilled message; they do not store responses in a database. The venue is a placeholder until you edit it. Dates currently use December 2026 as a sample year; change the year in the `WEDDING` object if needed.
