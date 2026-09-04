# Personal website — Quang-Huy DO

Jekyll site (based on the Minimal Mistakes / academicpages template), deployed on
GitHub Pages at https://huydo2105.github.io.

## Local Preview

```bash
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

## How Content is Structured

- **Publications** are driven by `_data/papers.json` and rendered on `_pages/publications.md`. Entries can include `title`, `authors`, `venue`, `date`, `link`, and optional `code` / `filename`.
- **Navigation** is configured in `_data/navigation.yml`.
- **Pages**:
  - `_pages/about.md` (`/`): Biography, research focus, PhD thesis overview, selected publications, and awards.
  - `_pages/publications.md` (`/publications/`): Full peer-reviewed publications grouped by year.
  - `_pages/experience.md` (`/experience/`): Professional experience, education, skills, and academic/industry references.
  - `_pages/awards.md` (`/awards/`): CIFRE doctoral grant and hackathon prizes.
  - `_pages/404.md`: Custom 404 page with navigation links and publications overview.
- **Academic CV** is located at `cv/Academic_CV.pdf`.
