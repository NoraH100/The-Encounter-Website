# The Encounter Website

Live at **https://theencountergypsus.org**

Website for The Encounter, the Grads & Young Professionals Convention of the Coptic Orthodox Diocese of the Southern United States.

## Quick edits

Open `index.html` and search for `SITE SETTINGS` near the bottom:

- `mode`: `"register"` while registration is open, `"waitlist"` once it closes. This switches the menu button, top bar and Register page.
- `registrationUrl` / `waitlistUrl`: paste the form links.
- `email`: contact address used on the Contact page and contact form.

Photos and the logo live in `images/`.

## Hosting

GitHub Pages: Settings > Pages > Deploy from branch `main`, folder `/ (root)`.

The custom domain `theencountergypsus.org` is set in the `CNAME` file. Don't delete it, or the site will fall back to the github.io address.
