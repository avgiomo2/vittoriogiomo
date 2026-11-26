# Vittorio Giomo + TESSUTECA

One repository, two independent static websites and shared colour/trend research.

- `sites/vittoriogiomo/` — V09 editorial site with animated six-colour palette.
- `sites/tessuteca/` — experimental archive demonstration with sample filters (CSS placeholders, not real catalogued records).
- `research/COLOUR_TRENDS_REFERENCES.md` — maintained references and benchmarks.

## Netlify configuration
Connect this repository twice, creating two **independent** Netlify projects from `main`:

| Project | Base directory | Build command | Publish directory |
| --- | --- | --- | --- |
| Vittorio Giomo | `sites/vittoriogiomo` | none | `.` |
| TESSUTECA test | `sites/tessuteca` | none | `.` |

If Netlify wants a repository-relative publish directory and no base directory, use `sites/vittoriogiomo` or `sites/tessuteca` respectively. Do not set both the base and the repository-relative publish directory.

Both sites are prototypes. Cross-site links will be enabled after actual deployment URLs are assigned. Do not claim official Pantone matching for RGB palette studies. Biographical details and archive counts require verification before publication.
