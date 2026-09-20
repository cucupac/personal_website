# Adam Cuculich

Personal website with a research index and a dedicated manuscript page. Plain HTML and CSS; no build dependencies or client-side JavaScript.

## Preview

From this repository, run `python3 -m http.server 8000 --directory docs`, then open http://localhost:8000.

## Hosting

Publish `main` → `/docs` with GitHub Pages. The configured custom domain is https://cuculich.me/.

## Research

The paper page contains the unchanged manuscript abstract, its DOI and ResearchGate link, license, and downloadable PDF. The PDF is copied from the `program-synthesis` repository; refresh it here when the manuscript changes.

Discovery metadata includes Google Scholar citation tags, ScholarlyArticle JSON-LD, unique titles and descriptions, canonical URLs, Open Graph tags, and a sitemap. The full abstract is plain HTML and the PDF has searchable text. Indexing is controlled by search engines and is not guaranteed.

## Custom domain

GitHub Pages is configured for `cuculich.me` through `docs/CNAME`. Citation, canonical, structured-data, and sitemap URLs use this domain.

DNS setup in GoDaddy and HTTPS activation are pending. Point the apex A records to GitHub Pages and `www` to `cucupac.github.io`. Preserve existing email MX, SPF, DKIM, and DMARC records. Once DNS resolves, enable Enforce HTTPS and verify every page and the PDF.

Domain ownership can also be verified in GitHub's account Pages settings using its generated TXT record. Submit `https://cuculich.me/sitemap.xml` in Google Search Console for regular Google Search; Scholar uses its own indexing process.

## Licensing

The website code is MIT licensed; see LICENSE. Original personal content retains its copyright unless otherwise stated. The paper is licensed under CC BY 4.0, as shown on its page. Third-party material retains its own license.
