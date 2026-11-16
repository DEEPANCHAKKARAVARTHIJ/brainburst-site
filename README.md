# BrainBurst website

Production source for the responsive BrainBurst static brand website.

## Contents

- `index.html` — mobile-first brand website and interactive spot-the-difference number game
- `privacy.html` — website-specific privacy policy
- `favicon.svg` — vector brand icon
- `robots.txt` and `sitemap.xml` — search-engine discovery assets
- `.nojekyll` — publish files directly without Jekyll processing

## Hosting

1. In this repository select **Settings → Pages**.
2. Choose **Deploy from a branch**, **main**, **/(root)**, then **Save**.
3. In **Settings → Pages → Custom domain**, enter `brainburst.store` and save.
4. In Namecheap for `brainburst.store`, open **Manage → Advanced DNS** and set these records (only if using Namecheap BasicDNS and no incompatible pre-existing records):
   - A @ 185.199.108.153
   - A @ 185.199.109.153
   - A @ 185.199.110.153
   - A @ 185.199.111.153
   - CNAME www deepanchakkaravarthij.github.io
5. Once Pages reports the domain is configured and the certificate is available, enable **Enforce HTTPS**.
6. Confirm both `https://brainburst.store` and `https://www.brainburst.store` reach the website, and review the website privacy policy before adding analytics, ads, account logins or forms.

**Important:** The existing `DEEPANCHAKKARAVARTHIJ.github.io` repository serves the Arrow Way site and its Google Search Console verification file. Do not change that repository's Pages domain or remove the verification files.

The showcase cards are descriptions of game concepts; they do not currently link to external store listings. This static site does not include accounts or payments.
