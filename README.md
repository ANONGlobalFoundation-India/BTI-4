# BTI 4 Final Batch Report — ANON Global Foundation

Static site: `index.html` (HTML, CSS, JS inline), `data.js` (all public content), `assets/anon-logo.gif`.

## Preview
Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

## Deploy
Upload the folder (index.html, data.js, assets/) to any static host (GitHub Pages, Netlify, Cloudflare Pages, S3). Do NOT upload DATA_AUDIT.md.

## Update content (edit `data.js` only)
- **Interns/grades**: each entry in `interns` has `name, team, institution, grade ("O"|"A"|"B"|null), total, categories, rationale`. Set `grade` for Srishti Saini (currently `null` = "Assessment pending") and the stats, chart and filters recalculate. Never add emails, phones or excluded names.
- **Presentations**: replace "To be added" in `presentations`.
- **Fit & Wealthy / Chronicles**: replace placeholders in `fitWealthy` and `chronicles` (add or remove chronicle objects freely).
- **EC / Wellness**: edit `ec` and `wellness`.
