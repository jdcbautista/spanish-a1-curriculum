# Spanish A1: First Steps

A four-lesson beginner Spanish course published as a zero-build GitHub Pages site.

- Live site: https://jdcbautista.github.io/spanish-a1-curriculum/
- Made from: [Curriculum Pages Template](https://github.com/jdcbautista/curriculum-pages-template), which documents the full build, run and maintain guide
- Owner: the Curriculum Pipeline (JC Labs), listed in its `repositories.json`

## Run locally

```bash
python3 -m http.server 8000
```

Open http://localhost:8000 and refresh after each edit. There is nothing to build.

## Maintain

- **Add a lesson:** create `lessons/05-topic.md` with Goals, teaching sections, Practice and a collapsible Answer key; list it in `_sidebar.md` and in the outline table in `home.md`.
- **Fix content:** edit the Markdown file and push; Pages republishes in about a minute.
- **Version every change:** bump `VERSION`, add a `CHANGELOG.md` line, and put the version in the commit message.
- **Site settings** (title, repo link, colour) live at the top of `index.html`.

Troubleshooting and docsify upgrades are covered in the template's README.
