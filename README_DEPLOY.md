# ZOZOTRONICS Static HTML Website

This folder is ready for Cloudflare Pages static hosting.

## Files
- `index.html` — homepage
- `projects.html` — robotics kits/projects page
- `schools.html` — school STEM lab partnerships page
- `contact.html` — WhatsApp/contact inquiry page
- `styles.css` — complete responsive styling
- `script.js` — mobile menu, reveal animation, WhatsApp message builder
- `assets/logo.png` — Zozotronics logo from the uploaded design
- `_headers` — basic security headers for Cloudflare Pages

## Before publishing
Replace every placeholder:
- `91XXXXXXXXXX` with your WhatsApp number in international format, for example `919876543210`
- `+91 XXXXX XXXXX` with your display number
- `hello@zozotronics.com` with your real email

## Cloudflare Pages hosting
1. Open Cloudflare Dashboard.
2. Go to **Workers & Pages** → **Create** → **Pages**.
3. Choose **Upload assets**.
4. Upload the ZIP file or the full extracted folder.
5. No build command is needed.
6. Build output directory: leave blank or use `/`.
7. Deploy.

## Custom domain
After deploy, open your Pages project → **Custom domains** → add your domain/subdomain.
