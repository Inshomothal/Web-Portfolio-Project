---
id: pgurz4vqquvwfn1sjomfmf5
title: Steps to Deploy
desc: ''
updated: 1766396848184
created: 1766392486359
---

# GitHub Pages + Jekyll Portfolio Quickstart

## Repo prep
- Have a GitHub remote set up; choose Pages source (simplest: branch `main`, root folder).

## Scaffold Jekyll locally
- Install Ruby, Bundler, Jekyll.
- In repo root: `jekyll new . --skip-bundle`.
- Set `_config.yml` (title, url, theme such as `minima` for Pages compatibility).

## Stay within GitHub Pages limits
- Use only Pages-allowed plugins/themes. If you need others, you must build with Actions and deploy `_site`.

## Add your content
- Layouts: `_layouts/default.html`; includes in `_includes/`.
- Pages: `index.md`/`index.html` for landing; add posts/collections for projects.
- Assets: `assets/css`, `assets/js`, `assets/img`.
- Client-side dynamic bits: JS in `assets/js` calling external APIs/serverless endpoints.

## Test locally
```sh
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```

## Progress
- [x] Remote set up with Pages
- [x] Installed Ruby
- [x] Bundler
- [x] Jekyll
- [x] In repo root: `jekyll new . --skip-bundle`
- [x] Set `_config.yml`
- [x] Skeleton page