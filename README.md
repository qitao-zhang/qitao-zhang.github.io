# Qitao Zhang — academic website

English academic website hosted at https://qitao-zhang.github.io, built with Jekyll and Academic Pages.

## Update content

- Home: `_pages/about.md`
- Research: `_pages/research.md`
- Publications: `_data/publications.yml` (articles ordered newest first; `selected: true` controls home-page highlights)
- CV: `_pages/cv.md` and `files/Qitao_Zhang_CV.pdf`
- Navigation and profile: `_data/navigation.yml` and `_config.yml`
- Visual refinements: `assets/css/academic.css`

Only add verified bibliographic metadata. Keep the CV page and downloadable PDF current together.

## Local preview

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Build validation: `bundle exec jekyll build --strict_front_matter`.
GitHub Pages builds and deploys the `master` branch automatically.

## Credits

Based on [Academic Pages](https://github.com/academicpages/academicpages.github.io), derived from Minimal Mistakes. See `LICENSE`.
