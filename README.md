# Growcite – Recruitment Website

Static site (HTML/CSS/JS). Hosted free on GitHub Pages at https://growcite.co.in

## Edit before going live
In `index.html`, search for the CONFIG block near the bottom `<script>`:
- `WHATSAPP` (country code + number, no +), `PHONE`, `EMAIL` – your real contact details.
- `JOBS` – add/remove jobs in this list.

## Deploy
1. Create a GitHub repo, upload these files (index.html, CNAME, .nojekyll, README.md).
2. Settings > Pages > Deploy from branch `main` / root.
3. At your domain registrar add DNS: four A records for `@` -> 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153 and a CNAME for `www` -> `<your-username>.github.io`.
4. In Pages settings enter `growcite.co.in` and tick Enforce HTTPS.
