# chamba.com

Static site for Chamba Development, LLC, hosted on GitHub Pages. Plain HTML + CSS, no build step.

- `index.html` - home page (company, BinCard, LandScope, contact)
- `privacy.html` - Privacy Policy
- `sms-terms.html` - SMS Terms and Conditions (Chamba Messaging)
- `style.css` - shared styles
- `CNAME` - custom domain for GitHub Pages (chamba.com)

Before publishing, replace every `support@chamba.com` with the real support address.

## Publishing
1. Push to a GitHub repo, then Settings > Pages > Deploy from branch `main`, folder `/ (root)`.
2. At the DNS host for chamba.com: A records for `@` to 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153, and a CNAME for `www` to `<user>.github.io`.
3. Once the certificate is issued, enable "Enforce HTTPS".
