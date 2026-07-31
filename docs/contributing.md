# Contributing

FUM-AI-Archive is maintained by teaching assistants of the AI course.
Contributions are welcome from current and former teaching staff, and from
anyone helping to keep the archive accurate and useful.

## Ways to contribute

- Fix outdated or incorrect information on existing pages.
- Add missing content to placeholder sections.
- Archive a new semester once it begins or concludes.
- Improve the site's structure, styling, or build configuration.
- Link newly created repositories from the [Repositories](repositories.md)
  page and the relevant semester page.

## Local development

See the [README](https://github.com/FUM-AI-Archive/fum-ai-archive.github.io#local-development)
in the repository for full setup instructions, including installing
dependencies and running the local development server.

## Adding a new semester

The archive is designed so that adding a new semester is as simple as
copying an existing one:

1. Copy an existing semester directory, e.g.:
   ```bash
   cp -r docs/archive/spring-2026 docs/archive/fall-2026
   ```
2. Update the content of every page in the new directory (team, highlights,
   schedule, repositories, assignments, projects, tutorials, resources).
3. Add a corresponding entry to the `nav` section of `mkdocs.yml`, mirroring
   the structure used for existing semesters.
4. Open a pull request with the changes.

## Style guidelines

- Keep each semester section self-contained — avoid cross-linking content
  between semesters except from the top-level Repositories page.
- Use clear, concise Markdown. Prefer short paragraphs and lists.
- Do not leave new pages empty — every page should have a title, a short
  introduction, and placeholder sections describing expected content until
  it is filled in.
- Do not present this site as the official course website anywhere in its
  content.

## Submitting changes

1. Fork the repository or create a branch.
2. Make your changes and verify the site builds locally (`mkdocs serve`).
3. Open a pull request describing the change.
4. A maintainer will review and merge the pull request. Merging to the
   default branch triggers automatic deployment to GitHub Pages.
