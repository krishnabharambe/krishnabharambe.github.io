# Krishna Bharambe — Portfolio

Personal portfolio and resume website, published with GitHub Pages.

## Project files

- `index.html` — page content and navigation
- `css/site.css` — responsive layout and visual styles
- `assets/Krishna_Bharambe.pdf` — downloadable resume
- `Thinking/` — index of long-form technical articles
- `Thinking/identities/` — guide to identity types in IAM
- `Thinking/AIAgentsecurity/` — defensive guide to securing AI agents

This is a static site; it does not require npm, a build step, or third-party JavaScript libraries. To preview it locally, run `python -m http.server` from the project directory, then open `http://localhost:8000/`.

## Updating the resume

Replace `assets/Krishna_Bharambe.pdf` with the current resume, keeping the same filename so the download link continues to work. Update the page content in `index.html` and styles in `css/site.css` as needed.

## Deployment

The GitHub Pages site is served from the repository root. Push changes to the configured publishing branch to update the live site.

## Search indexing

The site includes `robots.txt`, `sitemap.xml`, canonical URLs, social previews, and structured data for the portfolio owner and articles. After publishing:

1. Add `https://krishnabharambe.github.io/` as a property in [Google Search Console](https://search.google.com/search-console/) and complete its ownership verification.
2. Submit `https://krishnabharambe.github.io/sitemap.xml` in Search Console's **Sitemaps** section.
3. Optionally add the site to [Bing Webmaster Tools](https://www.bing.com/webmasters/) and submit the same sitemap.

Search engines decide whether and when to crawl, index, and show pages. These steps help discovery but cannot guarantee indexing or a particular ranking for a name or search query.
