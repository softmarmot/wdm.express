# WDM Express website

Static website for WDM EXPRESS LLC, served at https://wdm.express/ by GitHub Pages. Plain HTML, CSS and JavaScript, no build step.

- `index.html`, `style.css`, `app.js`: home page
- `privacy-policy.html` (`/privacy-policy`) and `ccpa.html` (`/ccpa`): legal pages
- `assets/`: images, video, favicon and self-hosted fonts

## Deploy

Every push to `main` publishes the repository as is through `.github/workflows/main.yml`.

## Forms

Both forms (shipping request and driver application) are delivered to dispatch@wdm.express by Web3Forms. The access key is `accessKey` at the top of `app.js`; it is public by design.

## Rollback

The previous Vue 3 + Vite site is tagged `v1-vue`.
