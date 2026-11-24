# bts-info

Public info pages for BTS, a private building-committee tool. Served by GitHub Pages at
**https://bts.gohler.co.il**.

- `index.html` – about, `privacy.html` – privacy policy, `terms.html` – terms and legal disclaimer
- `style.css` – shared styles, `CNAME` – custom domain (do not delete)
- Plain static files, no build step. Edit the HTML, commit, push; Pages publishes within about a minute.

## Domain and certificate
- DNS at the `gohler.co.il` registrar: `CNAME  bts  ->  niveusjack.github.io`
- HTTPS certificate (Let's Encrypt) is issued and renewed automatically by GitHub Pages; "Enforce HTTPS" is on.
- These URLs are registered in the Google Cloud OAuth branding of project `bts-gohler`
  (home page, privacy policy, terms). Keep them reachable.

## Keep in sync
- The "כניסה למערכת" button links to the app's `/exec` URL on all three pages.
- The legal text in `terms.html` is duplicated inside the app (`src/index.html` in the private `bts` repo).
  Change both together.

Full deployment notes: `DEPLOYMENT.md` in the private `niveusjack/bts` repository.
