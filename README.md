# Intelligenza Umana marketplace

*Human intelligence. Artificial assistance.*

A single [Claude Code](https://claude.com/claude-code) marketplace for the plugins of [Intelligenza Umana](https://github.com/fabiozagaria/intelligenza-umana). It only lists them: each plugin lives, is versioned and is tested in its own repository.

## Add the marketplace

```sh
claude plugin marketplace add Intelligenza-Umana/iu-marketplace
```

## Plugins

| Plugin | Install | What it does |
|---|---|---|
| [spring-security-advisor](https://github.com/Intelligenza-Umana/iu-spring-security-advisor) | `claude plugin install spring-security-advisor@intelligenza-umana` | Security audit for Spring Boot with a deterministic 0-100 score. |
| [learning-ledger](https://github.com/Intelligenza-Umana/iu-learning-ledger) | `claude plugin install learning-ledger@intelligenza-umana` | Guided learning and a local ledger that caps mastery by evidence. |
| [iu-model-router](https://github.com/Intelligenza-Umana/iu-model-router) | `claude plugin install iu-model-router@intelligenza-umana` | Task-aware model routing for coding agents. |
| [iu-project-lifecycle](https://github.com/Intelligenza-Umana/iu-project-lifecycle-skill) | `claude plugin install iu-project-lifecycle@intelligenza-umana` | Project context, lifecycle and handoff workflow. |

Installing a plugin downloads it from its own repository at the default branch. Read a plugin's README and code before using it.

## Maintenance

Run `claude plugin validate . --strict` after editing `.claude-plugin/marketplace.json`; the same check runs in CI on every push and pull request. The marketplace has no version of its own; a plugin's version is the one in its own `plugin.json`.

Distributed under the [MIT license](LICENSE).
