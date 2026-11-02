# randenab.se

Randen AB's website: one static page served by GitHub Pages.

- `index.html` is the whole site.
- `CNAME` points Pages at randenab.se.

DNS lives in Cloudflare. The apex needs A records to GitHub Pages
(185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153), DNS only (grey cloud),
and `www` a CNAME to `randenab.github.io`.
