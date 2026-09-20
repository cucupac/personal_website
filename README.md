# Adam Cuculich

Personal website with a research index and a dedicated manuscript page. Plain HTML and CSS; no build dependencies or client-side JavaScript.

## Preview

From this repository, run `python3 -m http.server 8000 --directory docs`, then open http://localhost:8000.

## Hosting

Publish `main` → `/docs` with GitHub Pages. The initial URL is https://cucupac.github.io/personal_website/.

## Research

The paper page contains the unchanged manuscript abstract, its DOI and ResearchGate link, license, and downloadable PDF. The PDF is copied from the `program-synthesis` repository; refresh it here when the manuscript changes.

Discovery metadata includes Google Scholar citation tags, ScholarlyArticle JSON-LD, unique titles and descriptions, canonical URLs, Open Graph tags, and a sitemap. The full abstract is plain HTML and the PDF has searchable text. Indexing is controlled by search engines and is not guaranteed.

## Connect cuculich.me later

1. Verify the domain in GitHub's account Pages settings using its generated TXT record.
2. Set the repository's Pages custom domain to `cuculich.me`.
3. Configure the apex A records and the `www` CNAME using GitHub's current documentation. Preserve the existing email MX, SPF, DKIM, and DMARC records.
4. Replace `https://cucupac.github.io/personal_website` with `https://cuculich.me` throughout `docs` so citation, canonical, structured-data, and sitemap URLs match the live site. Relative navigation and asset links already work on either host.
5. Once DNS resolves, enable Enforce HTTPS and verify every page and the PDF. Submit the sitemap in Google Search Console for regular Google Search; Scholar uses its own indexing process.

The `robots.txt` file will apply to the site when served at the custom-domain root. It does not control crawling of the shared `github.io` origin while this is a project site.

## Licensing

The website code is MIT licensed; see LICENSE. Original personal content retains its copyright unless otherwise stated. The paper is licensed under CC BY 4.0, as shown on its page. Third-party material retains its own license.
