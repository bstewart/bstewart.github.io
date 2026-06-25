# Site TODO

Audit date: 2026-06-22

This is a synthesis of three agent passes plus local checks over the Hugo source, generated HTML, publication metadata, and static assets.

## Done During This Audit

- Fixed imported spacing errors in the abstract for `computer-assisted-text-analysis-comparative-politics`.
- Removed the visible Dropbox-folder wording from the Text as Data teaching page.
- Fixed `occassionally` on the Soc 500 page.
- Standardized `Co-Editor-in-Chief` in the homepage intro.
- Removed the stale legacy-site root link from the Text as Data talk archive page.
- Fixed duplicate BibTeX keys in three publication pairs.
- Replaced HTML `&amp;` entities inside BibTeX journal names with BibTeX-safe `\&`.
- Standardized `month=Sept` to `month=sep` in BibTeX entries.
- Cleaned the Latent Factor Regressions and `lbfgs` imported citation strings.
- Removed stale FlexSearch/home JSON configuration now that search uses Pagefind.
- Pinned Pagefind to `1.5.0` in the local build script and GitHub Pages workflow.
- Defanged the orphaned Research Areas page links so they no longer point to an unsupported `area` publication filter.
- Updated `UPDATING.md` to reflect the current Bio, People, and build workflow.
- Added Fall 2026 to Applied Social Statistics and Spring 2027 to Machine Learning for Policy Analysis.
- Polished hyphenation and spacing on the recommendation-letter page.
- Removed the Research Areas page and the Talk archive.
- Deleted duplicate old teaching filenames, an unused duplicate headshot, and candidate unreferenced research PDFs.
- Removed the stale scraped teaching-material manifest and the unused template code that depended on it.
- Decided to keep `software` tags in publication metadata but suppress them in the publication UI, since Software has its own top-level page.
- Fixed the interior-page gutter regression by preserving container inline padding on `.page-shell`.
- Rebuilt the homepage Featured Publications area as publication cards with authors, venues, tags, abstracts, and action links.
- Filled the Bio right column with contact, education, editorial, and awards metadata.
- Expanded the footer to include Bio, Publications, Teaching, Software, People, CV, and email.
- Removed the duplicate landing homepage template and the stale home-page `type: landing` marker.
- Changed publication type filters from ARIA tab controls to pressed filter buttons, and added a search-modal focus trap.
- Added a restrained serif display-font trial for headings using local system font stacks.
- Added subtle hover micro-interactions for nav links, buttons, standalone cards, dense publication rows, and portraits.
- Pinned Featured Publications action buttons to the bottom of cards and clamped long author/abstract snippets.
- Tightened the Bio prose so factual items now owned by the sidebar are not repeated in the main narrative.

## P1 - Next Sustained Session

- Review the homepage Featured Publications selection.
  - The section now renders as cards from `data/featured_publications.yaml`.
  - Decide whether the current six featured publications are the right set; the 2026 *Nature* paper may belong here.

- Finish publication detail pages paper by paper.
  - Add or improve paper images.
  - Update publication metadata, links, abstracts, citations, and local PDFs.
  - Check that each "Paper", "Preprint", "Website", "Replication", and "Publisher's Version" button reflects the best current material.
  - Review whether each page should have body text beyond the abstract and links.

## P1 - Publication Metadata Gaps

- Add `featured.*` images for these publication bundles:
  - `state-media-control-influences-large-language-models`
  - `what-makes-foreign-policy-teams-tick-explaining-variation-group-performance`
  - `decade-long-growth-government-authored-news-media-china-under-xi-jinping`
  - `correcting-measurement-errors-ai-assisted-labeling-image-analysis-using-design-based`
  - `short-term-exposure-filter-bubble-recommendation-systems-has-limited-polarization`
  - `multilanguage-word-embeddings-social-scientists-estimation-inference-and-validation`
  - `fine-tuned-large-language-models-replicate-expert-coding-trained-coders`
  - `civic-mission-moocs-computational-measures-engagement-across-differences`
  - `how-algorithmic-confounding-recommendation-systems-increases-homogeneity-and`
  - `navigating-local-modes-big-data-case-topic-models`
  - `measuring-distances-high-dimensional-spaces-why-average-group-vector-comparisons`
  - `global-diffusion-law-transnational-crime-and-case-human-trafficking`
  - `using-large-language-model-annotations-social-sciences`
  - `combating-transnational-crime-role-learning-and-norm-diffusion-current-rule`
  - `using-imperfect-surrogates-downstream-inference-design-based-supervised-learning`

- Add abstracts for these entries:
  - `state-media-control-influences-large-language-models`
  - `state-of-thoughts-structured-action-templates-tree-of-thoughts`
  - `decade-long-growth-government-authored-news-media-china-under-xi-jinping`
  - `correcting-measurement-errors-ai-assisted-labeling-image-analysis-using-design-based`
  - `short-term-exposure-filter-bubble-recommendation-systems-has-limited-polarization`
  - `fine-tuned-large-language-models-replicate-expert-coding-trained-coders`
  - `navigating-local-modes-big-data-case-topic-models`
  - `measuring-distances-high-dimensional-spaces-why-average-group-vector-comparisons`
  - `using-large-language-model-annotations-social-sciences`
  - `combating-transnational-crime-role-learning-and-norm-diffusion-current-rule`
  - `machine-learning-social-science-agnostic-approach`

- Add or intentionally omit outbound links for:
  - `naive-regression-requires-weaker-assumptions-factor-models-adjust-multiple`
  - `using-large-language-model-annotations-social-sciences`

- Revisit "Other" classification.
  - Current `report` entries mix reports, software/vignettes, workshop papers, and working-paper-like material.
  - Review `plain-text`, `structural-topic-model-and-applied-social-science`, `latent-factor-regressions`, `lbfgs`, and the older media/source workshop items.

## P2 - Content And Page Polish

- Homepage / research entry points:
  - Consider a compact Research themes band using the current publication tag taxonomy, linking to pre-filtered publication lists.
  - Consider a short Recent section for awards, press, and newly published work.

- People page:
  - The current design is intentionally spare after removing descriptive subheaders.
  - Consider whether it needs a one-sentence scope note explaining current students, alumni, postdocs, and committee roles.

- Publication/software/data graph:
  - Add "Associated software" links on publication pages where relevant.
  - Add "Related papers" on software pages for packages introduced or used in publications.
  - Consider award or press ribbons on publication cards/pages where the CV records strong signals.

## P2 - Technical And Asset Cleanup

- Production build discipline:
  - Local `public/` can be stale if generated by `hugo server`.
  - Use `npm run build` from `hugo-site/` before deployment review.

- Static payload:
  - `hugo-site/static` is about 409 MB after deleting old duplicate filenames.
  - Most of the size is teaching PDFs, especially older Soc 500 slides/handouts.
  - Consider another compression pass for the largest PDFs if page load or repository size becomes a problem.

## Checks From This Audit

- Generated-site internal link check: no missing internal links found.
- Publication count: 58 entries.
- BibTeX: present for all 58 publication entries after this pass; duplicate keys fixed.
- Non-exception `et al.`: none found. The only publication-level `et al.` is the mass-collaboration paper.
- Search: Pagefind template is active; FlexSearch leftovers removed from config.
