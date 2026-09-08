# de-notes

Source for **[Data Engineering Notes](https://hoile9119.github.io/de-notes/)** —
a Jekyll site published with GitHub Pages.

Content lives in the section folders (`streaming/`, `spark/`, `lakehouse/`, …).
Start at [`index.md`](index.md); each section has its own `index.md` acting as
that section's map.

## Running locally

Prerequisites: [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
and [Bundler](https://bundler.io/).

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000/de-notes/>.

`baseurl` is set in [`_config.yml`](_config.yml), so no `--baseurl` flag is
needed — local and production URLs match.

## Notes on the build

- Theme is [dinky](https://github.com/pages-themes/dinky), which renders page
  content and nothing else — no sidebar, no generated nav. Navigation is
  therefore hand-written: each section's `index.md` links to its own pages, and
  every page carries a back-link to its section. **A new page is unreachable
  until it is linked from its section index.**
- The `github-pages` gem bundles `jekyll-optional-front-matter`, which means
  **any `.md` file committed here becomes a public page** unless it is listed
  under `exclude:` in [`_config.yml`](_config.yml). `CLAUDE.md` and this README
  are excluded.
