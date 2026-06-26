# amit-chaudhary

Personal site for **Amit Chaudhary**, Senior Ruby on Rails Engineer & Architect, available for independent contract work with US/UK remote teams.

Standard Jekyll site served by GitHub Pages. All content is data-driven: you edit YAML, not HTML.

## Where the content lives

| What | File |
|------|------|
| Title, tagline, contact, hero text, baseurl | `_config.yml` |
| About paragraphs + "at a glance" facts | `_data/profile.yml` |
| "What I do" service cards | `_data/services.yml` |
| Tech stack columns | `_data/stack.yml` |
| Work history + education | `_data/experience.yml` |
| Résumé download | `resume.pdf` |
| Page structure / layout | `index.html`, `_layouts/default.html` |
| Styles | `assets/css/main.css` |

## Local preview

```bash
bundle exec jekyll serve   # or: jekyll serve
# open http://localhost:4000/amit-chaudhary/
```

## Deploy

Pushed to `main` on `chaudhary/amit-chaudhary`; GitHub Pages builds it automatically.
Live at https://chaudhary.github.io/amit-chaudhary/
