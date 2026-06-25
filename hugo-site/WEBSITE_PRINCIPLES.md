# Website Principles

- The site uses Hugo with the Hugo Blox module declared in `go.mod` and `hugo.yaml`; project-specific behavior lives in local layouts and `assets/css/custom.css`.
- URLs are stable. Publication directory names are treated as permanent slugs, with aliases for migrated legacy paths where titles changed.
- The Publications page is a dense server-rendered list enhanced by vanilla JavaScript filters. Content remains visible if JavaScript fails.
- Research-area metadata lives in `data/research_areas.json`, not duplicated in templates.
- Search is Pagefind-based and loaded only when the search modal opens.
- The homepage uses a standard academic side-by-side layout: portrait left, identity and intro right on desktop.
- All owner-provided and migrated assets are local. Do not hotlink images or PDFs when a local copy is available.
- Keep prose understated and avoid repeating the same bio text on the homepage and Bio page.
