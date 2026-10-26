# huayinb

Static English company website for huayinb. No dependencies or build step.

## Local preview

Run `python -m http.server 4173 --bind 127.0.0.1` from this directory, then open http://127.0.0.1:4173/.

Pages: `/`, `/privacy-policy/`, and `/terms-of-service/`.

## Publishing

- Repository: https://github.com/huayi678/huayinbWebsite
- GitHub Pages source: branch `main`, folder `/ (root)`.
- Primary URL: https://huayinb.me/
- Keep the root `CNAME` and `.nojekyll` files.

Set the apex (`@`) A records to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, and `185.199.111.153`. Point the `www` CNAME to `huayi678.github.io`. Preserve unrelated DNS records. Verify the domain and configure the Pages custom domain before switching website DNS. Enable HTTPS enforcement when the certificate is ready.

## Pending company details

Contact email: `akafi7977@gmail.com`. Keep the contact sections on all three pages and the related contact wording in the privacy policy in sync.

`app-ads.txt` is served from the site root, with `OWNERDOMAIN=huayinb.me`.
