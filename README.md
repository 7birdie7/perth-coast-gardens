# Perth Coastal Gardens

Static multi-page lead generation website for garden rejuvenation across Perth's northern coastal suburbs.

## Build

Run `npm run build`. Cloudflare Pages should use:

- Build command: `npm run build`
- Build output directory: `dist`
- Production branch: `main`

The canonical domain is `https://perthcoastgardens.com` and `www` should redirect to the non-www domain.

## Contact form

Forms submit to `info@perthcoastgardens.com` through FormSubmit. After the first production test, approve FormSubmit's activation email, then repeat the form test and confirm delivery through Cloudflare Email Routing.

Do not add contractor credentials, project counts, testimonials, warranties, fixed hours or response-time claims unless they have been verified with the eventual tenant.
