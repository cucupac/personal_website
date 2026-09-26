# Adam Cuculich

Personal website with a research index and a dedicated manuscript page. Plain HTML and CSS; no build dependencies or client-side JavaScript.

## Preview

From this repository, run `python3 -m http.server 8000 --directory docs`, then open http://localhost:8000.

## Hosting

Publish `main` → `/docs` with GitHub Pages. The configured custom domain is https://adamcuculich.com/.

## Research

The paper page contains the unchanged manuscript abstract, its DOI and ResearchGate link, license, and downloadable PDF. The PDF is copied from the `program-synthesis` repository; refresh it here when the manuscript changes.

Discovery metadata includes Google Scholar citation tags, ScholarlyArticle JSON-LD, unique titles and descriptions, canonical URLs, Open Graph tags, and a sitemap. The full abstract is plain HTML and the PDF has searchable text. Indexing is controlled by search engines and is not guaranteed.

## Custom domain

GitHub Pages is configured for `adamcuculich.com` through `docs/CNAME`. Citation, canonical, structured-data, and sitemap URLs use this domain.

GoDaddy DNS points to GitHub Pages, and Enforce HTTPS is enabled. The apex and `www.adamcuculich.com` certificate is active. Email remains `adam@cuculich.me`; preserve its MX, SPF, DKIM, and DMARC records.

GoDaddy permanent (301) forwarding is configured for `cuculich.me` and `www.cuculich.me` to `https://adamcuculich.com`. At migration time, forwarding activation and HTTPS provisioning were still pending. Verify that old manuscript and PDF URLs retain their paths once forwarding is active; path preservation has not yet been confirmed.

Domain ownership can also be verified in GitHub's account Pages settings using its generated TXT record. Submit `https://adamcuculich.com/sitemap.xml` in Google Search Console for regular Google Search; Scholar uses its own indexing process.

## Licensing

The website code is MIT licensed; see LICENSE. Original personal content retains its copyright unless otherwise stated. The paper is licensed under CC BY 4.0, as shown on its page. Third-party material retains its own license.
