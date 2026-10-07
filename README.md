# Code Snippets

A home for small, reusable examples from my computer science studies. Snippets belong here when they demonstrate one focused idea without needing a full project.

**Status:** the repository currently contains documentation and a snippet template; no code snippets have been committed yet.

## Layout

```text
snippets/       Add short examples, grouped by language when needed
templates/      A reusable description template for new snippets
```

[Snippet organization](snippets/README.md) explains where new files belong. Use the [snippet template](templates/snippet.md) to document their purpose, requirements, and example output.

## Adding a snippet

1. Create the relevant language directory under `snippets/`, such as `snippets/python/` or `snippets/cpp/`.
2. Choose a descriptive name such as `parse_iso_date.py`, rather than `test2.py` or `misc.py`.
3. Include a runnable example and record any dependencies or limitations. Use a subdirectory with a README when a snippet needs multiple files.

Language directories are created when they contain real examples, rather than pre-filling this repository with empty folders. Keep larger applications in their own project repositories.

## Scope

This is a reference collection, separate from the longer exercises and terminal games in [Python Practice Projects](https://github.com/Snugs44/Python-Practice-Projects-and-Misc-Scripts).
