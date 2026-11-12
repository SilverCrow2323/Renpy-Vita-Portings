# Wiki source and publishing

The `wiki-source/` directory is the canonical source for this practical Wiki. This repository is an index of Ren'Py Vita candidates and test results; keep the Wiki short and focused on how to propose, track and report a test.

## Page rules

- One topic per page.
- Start with a short explanation and say when the page is useful.
- Keep each bullet to one concept.
- Use **MUST KNOW!!** only for real prerequisites or compatibility limits.
- Use **Optional** only for non-essential enhancements.
- Leave basic items unlabelled.
- Keep candidate, testing, failed-basic-conversion and available-port status distinct.
- Do not upload copyrighted game files or private game assets.

## First-time Wiki activation

1. Open the [GitHub Wiki](https://github.com/SilverCrow2323/Renpy-Vita-Portings/wiki).
2. Create and save a first page titled **Home**.
3. From a clone with Git credentials, run `sh tools/publish_wiki.sh`.

Edit `wiki-source/`, not only the live Wiki. The publisher copies reviewed Markdown pages to the special Wiki repository.
