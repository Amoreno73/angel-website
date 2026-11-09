# Angel Moreno's website

A static portfolio with a cream and dark green theme. Open `index.html` in a browser; no build, dependencies, or JavaScript are needed for the portfolio. The embedded Chicago map retains its own generated dependencies.

## Add a project

1. Copy `campus-plate.html` to a descriptive new HTML filename. Keep its header, footer, stylesheet, and favicon links.
2. Replace the page title and article content.
3. Copy a `timeline-entry` in `index.html` to the top of the timeline. Update its unique ID, number, title, description, link, and accessible link label. Update the project count beside the Projects heading.
4. Add the page to the `project-nav` on each project page. Set `aria-current="page"` only on the current page's link.

Timeline numbers express display order, not project dates. Add verified dates with `<time datetime="YYYY-MM">` when available; dataset date ranges are not project dates.

## Files

- `index.html`: introduction, project timeline, and contact links.
- `project_01.html` through `project_03.html`: existing project articles and embeds.
- `campus-plate.html`: dining hall project description, live dashboard, API documentation, and local setup links.
- `assets/css/main.css`: shared styles, palette variables, and mobile layout.
- `assets/favicon.svg`: cream background with dark green AM initials.
- `chicago_shootings_heatmap.html`: generated interactive map; maintained independently.

GitHub Pages deployment continues to use the existing workflow. Pushes to `main` publish the repository.

Original template attribution and license are retained in `README.txt` and `LICENSE.txt`.
