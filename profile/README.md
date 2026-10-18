# Ascribe

Documentation written as code, checked like code, and built into a website, plain Markdown, and JSON.

Ascribe is a markup language and a toolchain: Markdown with `@` directives, a content model in `ascribe.toml`, and one compiler. `ascribe check` finds a broken link, a missing heading, or a name the content model doesn't declare, in the editor as you type and in CI. `ascribe build` writes a site for Astro, a Markdown version of every page, and JSON, with `llms.txt` for agents.

- **Docs:** [ascribed-dev.com](https://ascribed-dev.com/docs/)
- **Source:** [ascribed-dev/ascribe](https://github.com/ascribed-dev/ascribe), under the Mozilla Public License 2.0
- **Editor:** the [Ascribe extension](https://marketplace.visualstudio.com/items?itemName=Ascribe.ascribe-vscode) for VS Code

## Install

```sh
npm install --save-dev @ascribed/cli     # in a project with Node
brew install ascribed-dev/tap/ascribe    # on macOS and Linux, without Node
```

Then [Getting started](https://ascribed-dev.com/docs/getting-started/).

## Repositories

| Repository | What it is |
|---|---|
| [ascribe](https://github.com/ascribed-dev/ascribe) | The language, the `ascribe` command, the VS Code extension, and the npm packages |
| [tested-examples-node](https://github.com/ascribed-dev/tested-examples-node) | A repository to copy for docs whose code examples say what they were tested with, with Node and TypeScript |
| [tested-examples-python](https://github.com/ascribed-dev/tested-examples-python) | The same, with Python |
| [homebrew-tap](https://github.com/ascribed-dev/homebrew-tap) | The formula for `brew install ascribed-dev/tap/ascribe` |

Ascribe is before 1.0, so what it writes and what it accepts can still change between releases.
