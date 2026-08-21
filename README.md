# Snacky Haus – Website

A one-page site with the logo, address, and a button that opens the menu
(PDF on tablet/laptop, JPEG on phones). Language toggle DE/EN, defaults to German.

## Files
- `index.html` – the site
- `logo.png` – logo (cropped from the phone menu)
- `speisekarte-laptop.pdf` – menu shown on tablets & laptops
- `speisekarte-phone.jpg` – menu shown on phones

Keep all four files in the same folder — the page links to the menu files
by their plain filename, so if you rename them, update the two filenames
inside `index.html`'s `<script>` at the bottom (`speisekarte-phone.jpg` /
`speisekarte-laptop.pdf`).

## Publish with GitHub Pages (free hosting)

1. Create a new GitHub repository (e.g. `snacky-haus`), public.
2. Upload these four files to the repo root (GitHub web UI: **Add file → Upload files**, drag them in, commit).
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Branch: `main`, folder: `/ (root)` → **Save**.
6. Wait ~1 minute, then your site is live at:
   `https://<your-username>.github.io/<repo-name>/`

That URL is what you share as "the website."

## Before you publish

Open `index.html` and replace the placeholder address with your real one —
search for `Musterstraße 1, 12345 Musterstadt` (and the placeholder phone
number `+49 00 000 000 00`) and swap in your details.
