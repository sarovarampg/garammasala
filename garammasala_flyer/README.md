# Sarovaram Ladies PG — Bilingual Flyer (GitHub Pages)

This folder contains a mobile-friendly bilingual (English/Malayalam) flyer to announce a food-photo drive and link to your Google Form / WhatsApp.

## How to deploy on GitHub Pages

1. Create (or use) a public repo, e.g., `garammasala`.
2. Copy the **contents of this folder** to the repo root:
   - `index.html`
   - `assets/header.jpg`, `assets/footer.jpg`, `assets/theme.jpg`
3. Edit `index.html` and replace:
   - `formURL` with your Google Form link
   - `whatsappURL` with your WhatsApp link (`https://wa.me/<countrycode><number>`)
4. Commit and push to `main`.
5. Repo **Settings → Pages → Deploy from branch → main / (root)**.
6. Open your Pages URL, e.g., `https://<user>.github.io/garammasala/`.

## Notes
- No external fonts used; works fully offline.
- Malayalam block uses common system fonts; add webfonts if you prefer.
- Background uses your provided theme image.
- Header/footer images are your supplied assets.
