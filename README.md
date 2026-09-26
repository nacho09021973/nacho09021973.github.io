# nacho09021973.github.io

Root GitHub Pages site for `nacho09021973.github.io`: the author page of
José Ignacio Martín Gandul (ORCID
[0009-0004-8129-1379](https://orcid.org/0009-0004-8129-1379)).

It lists the research outputs, each with its DOI, and links to the project
sites. It used to be a `meta refresh` redirector to `/bombelli/` whose
`canonical` also pointed there, which stopped the domain root from ranking on
its own; that redirect was removed on 2026-09-26.

- `index.html` — author page, with `ProfilePage`/`Person` and `ItemList`
  Schema.org blocks. The `Person` carries the ORCID as `identifier` and
  `sameAs`, so the pages resolve to one identity.
- `robots.txt` — full crawl, and declares both sitemaps.
- `sitemap.xml` — the root URL. The project site keeps its own sitemap at
  `/bombelli/sitemap.xml`, declared separately in `robots.txt`.

The biography section of `index.html` is deliberately left empty for the
author to write.
