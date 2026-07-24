# guoxiangng.github.io

Personal portfolio for Ng Guo Xiang — a plain static site (no build step), served by GitHub Pages.

## Design

Calm editorial theme with quiet motifs: a soft cloud backdrop (a nod to
`guoxlostinthecloud`) and a delicate lotus line-mark, kept low-opacity and
understated. Serif display type (Fraunces / Newsreader), warm rice-paper palette,
celadon accent. Light and dark are both handled via `prefers-color-scheme`.

## Structure

- `index.html` — all content (hero, about, writing, projects, contact)
- `styles.css` — the single stylesheet
- `.nojekyll` — tells GitHub Pages to serve files as-is (skip Jekyll)

## Local preview

Open `index.html` in a browser, or serve the folder:

```sh
python -m http.server 8000
# then visit http://localhost:8000
```

## Hosting

Deployed via GitHub Pages from this repo's default branch. Because it is pure
static files, it is fully portable — the same folder can later be dropped onto
AWS S3 + CloudFront unchanged (a planned infra-as-code exercise).

## To do

- Migrate detailed project write-ups from the old Wix portfolio.
- Optionally pull recent Medium posts into the Writing section.
