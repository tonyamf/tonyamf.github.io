# tonyamf.github.io

My GitHub Pages site: a single page (`index.md`) rendered with the `jekyll-theme-cayman` theme (set in `_config.yml`).

## How to run

GitHub Pages builds it on every push. To build it locally (Ruby and Bundler needed):

```
# Gemfile
source "https://rubygems.org"
gem "github-pages", group: :jekyll_plugins
gem "webrick"
```

```
bundle install
PAGES_REPO_NWO=tonyamf/tonyamf.github.io LANG=C.UTF-8 bundle exec jekyll serve
```

Then open http://127.0.0.1:4000/.

## Other files

- `antonio_github_config.yml`: an unused al-folio style configuration (Pages only reads `_config.yml`).
- `index.txt`, `indexmd.txt`, `style.css`: earlier drafts, not published as pages.
