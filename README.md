# 163industries.com

Website for **163industries.com**, part of 163 Global.

- **Hosting:** GitHub Pages, served from the `main` branch root.
- **Custom domain:** set by the `CNAME` file. Don't delete it, or the custom domain is dropped.
- **DNS:** managed in Cloudflare. The apex has GitHub Pages `A`/`AAAA` records and `www` is a CNAME to `163global.github.io`, all DNS-only (grey cloud).

`index.html` is a placeholder. Replace it with the real site. A static site generator works too, if it builds via GitHub Actions.
