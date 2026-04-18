# OnePagent Skills Registry

This repository hosts the static registry and inline skill artifacts for `https://skills.onepagent.top`.

## Structure

- `registry.json`: primary marketplace index
- `skills/*.json`: skill package artifacts referenced by URL entries
- `CNAME`: custom GitHub Pages domain

## Contributing

1. Fork this repository or create a branch.
2. Add or update an entry in `registry.json`.
3. If using `source: "url"` and hosting locally in this repo, place the artifact under `skills/`.
4. Open a pull request.

## Supported skill sources

- `inline`: embed full skill object in `registry.json`
- `url`: direct link to `SKILL.md` or JSON skill file
- `repo`: GitHub repository reference with optional branch and path
