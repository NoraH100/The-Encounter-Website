# The Encounter Website

Live at **https://norah100.github.io/The-Encounter-Website/**

Website for The Encounter, the Grads & Young Professionals Convention of the Coptic Orthodox Diocese of the Southern United States.

## Quick edits

Open `index.html` and search for `SITE SETTINGS` near the bottom:

- `mode`: `"register"` while registration is open, `"waitlist"` once it closes. This switches the menu button, top bar and Register page.
- `registrationUrl` / `waitlistUrl`: paste the form links.
- `email`: contact address used on the Contact page and contact form.

Photos and the logo live in `images/`.

## Hosting

GitHub Pages: Settings > Pages > Deploy from branch `main`, folder `/ (root)`.

To switch to the custom domain `theencountergypsus.org` later: add a `CNAME` file containing the domain, and set DNS at Namecheap: 4 A records for `@` to 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153, and a CNAME for `www` to `norah100.github.io`.
