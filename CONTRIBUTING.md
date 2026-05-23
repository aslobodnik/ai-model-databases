# Contributing

## Adding a database

Open a pull request adding an entry to `databases.json` with:

- `name` — the project's name
- `url` — canonical URL
- `description` — one sentence
- `form` — one of: `web`, `library`, `repo`, `api`
- `language` — primary language, if `form` is `library` (optional)
- `source` — link to source repo, if not already the `url` (optional)

Keep the list alphabetized by `name` after the first entry (Models.dev stays first for historical reasons).

We'll merge it if the project actually catalogs AI models.

## Adding a database of AI model databases

We do not currently maintain a database of AI model database databases.

If you start one, please add an entry here, and then list this database in yours. We'll add yours here in return. Recursion is fine. JSON handles it.
