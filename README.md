# FUM AI Archive Website

This repository contains the source code for the **FUM AI Archive** website.

The website is built using **MkDocs** with the **Material for MkDocs** theme and is automatically deployed via **GitHub Pages**.

Its purpose is to provide a long-term public archive of educational resources, repositories, and documentation produced by the AI course teaching team.

**Note:**
>
> This website is **not** the official course website. Official course announcements, assignments, submissions, and grading are managed through the university VU.

---

## Development

### Prerequisites

* Python 3
* MkDocs
* Material for MkDocs

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## Running the Website

Start the local development server:

```bash
mkdocs serve
```

The website will be available at:

```
http://127.0.0.1:8000
```

Changes are automatically reloaded while the server is running.

---

## Building

To build the static website:

```bash
mkdocs build
```

The generated website will be placed in the `site/` directory.

---

## Contributing

Contributions from members of the teaching team are welcome.

When contributing:

* Keep pages well-structured and easy to navigate.
* Follow the existing directory structure.
* Prefer Markdown over HTML whenever possible.
* Keep semester-specific content inside its corresponding archive directory.
* Write clear and descriptive commit messages.

---

## Documentation

For more information about MkDocs and the Material theme, refer to the official documentation:

* MkDocs: https://www.mkdocs.org/
* Material for MkDocs: https://squidfunk.github.io/mkdocs-material/
