# Md. Jahim Uddin Shorif — research profile

A Jekyll site using the [Hydejack](https://github.com/hydecorp/hydejack) theme (v9.2), deployed to GitHub Pages by `.github/workflows/pages.yml` on every push to `main`.

## Pages

- `index.md` — introduction, education, interests and featured work
- `projects.md` — research projects (shown as "Research" in the menu)
- `publications.md` — papers and manuscript status (articles live in `_data/publications.yml`)
- `contact.md` — email and academic profiles

Site settings and the sidebar menu are in `_config.yml`; the author card and social links are in `_data/authors.yml`. Custom CSS goes in `_sass/my-inline.scss` or `_sass/my-style.scss`.

The sidebar picture is `assets/profilepic.jpg` (a square image; replace the initials placeholder with your photo).
The downloadable CV is `assets/Md-Jahim-Uddin-Shorif-CV.pdf`. Update the PDF and page text together when the record changes.

## Local preview

```sh
bundle install
bundle exec jekyll serve --livereload
```
