# Ishneet Sukhvinder Singh

🔗 Live site: [ishneet0710.github.io](https://ishneet0710.github.io)

Personal academic website built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template (a fork of [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes)), hosted on GitHub Pages.

## Local development

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open <http://localhost:4000>.

## Editing content

- **Profile / sidebar & socials:** `_config.yml` (the `author:` block)
- **Home page sections:** `_pages/about.md`
- **Publications:** `_data/publications/*.yml` and `_data/publication_order.yml`
- **Theme colors:** `_sass/theme/_default_light.scss` and `_sass/theme/_default_dark.scss`
