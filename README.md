# roundabloom-landing-page

The landing page at https://bloom.simoliy.com/ (the link in @roundabloom's Instagram bio).

- `public/` holds the site: `index.html` (with a short "Start where you are" quiz), the Disclosure, Privacy and Terms pages, and `logo.svg`.
- `wrangler.jsonc` tells Cloudflare to serve `public/` from the Worker **roundabloom-landing**.
- Cloudflare builds and deploys automatically on every push to `main` (Workers Builds).
- The buttons use ClickBank hoplinks tagged `traffic_source=instagram-roundabloom`.
