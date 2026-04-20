# Danilo Freire - Personal Website

Source for [danilofreire.github.io](https://danilofreire.github.io), my academic homepage at Emory University. Built with [Quarto](https://quarto.org) and deployed from `docs/` on the `main` branch via GitHub Pages.

## Pages

- [About](https://danilofreire.github.io/) - short bio, affiliations, contact
- [Research](https://danilofreire.github.io/research.html) - peer-reviewed articles, working papers, book chapters, awards, and service
- [Teaching](https://danilofreire.github.io/teaching.html) - Emory courses, workshops, and previous teaching
- [Software](https://danilofreire.github.io/software.html) - R packages on CRAN and GitHub
- [CV](https://danilofreire.github.io/cv.html) - full academic record, plus a downloadable PDF

## Structure

- `*.qmd` - page source files
- `custom.scss` / `custom-dark.scss` - light and dark theme styles
- `_quarto.yml` - site configuration, navigation, fonts, head includes
- `docs/` - rendered output, served by GitHub Pages
- `assets/`, `syllabi/`, `texts/`, `evaluations/` - static resources

## Local development

```bash
quarto preview    # live preview at http://localhost:4848
quarto render     # rebuild docs/ for deployment
```

After editing, commit and push to `main`. GitHub Pages picks up changes within a minute.

## Licence

[MIT](LICENSE)
