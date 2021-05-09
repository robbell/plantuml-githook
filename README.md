# PlantUML generation Git hook

A **Git hook** which spots PlantUML source files and generates diagrams in a structured way.

## How it works

1. Finds any staged `*.puml` during a commit
2. Generates diagrams into `/docs/assets`
3. Includes the generated diagrams in the same commit

## Future additions

* [x] Generate diagrams only for files which have changed
* [ ] Installation of hooks using [GitHooks][githooks]
* [ ] Inline diagrams in Markdown
* [ ] Ad-hoc runs

[githooks]: https://github.com/rycus86/githooks
