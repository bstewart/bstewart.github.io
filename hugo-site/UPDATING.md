# Updating the Site

This site is a Hugo project in `hugo-site/`. Most routine edits happen in Markdown files under `content/`.

## Add a Publication

1. Create a folder under `content/publication/` using a stable lowercase slug.
2. Add `index.md` with title, date, authors, publication venue, abstract, links, and tags.
3. Put any local PDF in `static/files/` and link to it as `files/name.pdf`.
4. Optional: put `featured.jpg` next to the publication `index.md`.

## Update the Bio Page

Edit `content/bio/_index.md`. Contact links are kept on the Bio page and in `hugo.yaml`.

## Add Software

Create `content/software/project-slug/index.md` and include a project link in front matter.

## Add a Person

Edit `data/research_group.yaml`. The People page is generated from that data file.

## Change Publication Tags

Edit the `tags` list in each publication's front matter.

## Build for Deploy

From `hugo-site/`, run `npm run build`. This runs Hugo and then builds the Pagefind search index.

## Preview Locally

From `hugo-site/`, run `hugo server --disableFastRender`, then open the localhost URL it prints.
