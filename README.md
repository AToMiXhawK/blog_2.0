# Blog 2.0

This repository contains a Jekyll blog built with the [Chirpy theme](https://github.com/cotes2020/jekyll-theme-chirpy). Posts reside in the `_posts/` directory and the generated site is output to `docs/` so it can be served with GitHub Pages.

## Writing a Post

Create a Markdown file in `_posts/` using the `YYYY-MM-DD-title.md` format. The CI/CD workflow will run Jekyll and place the resulting HTML in `docs/`.

## Local Preview

Install dependencies and run Jekyll:

```bash
bundle install
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`.
