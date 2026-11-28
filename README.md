# Intelligenza Umana marketplace

*Human intelligence. Artificial assistance.*

A single [Claude Code](https://claude.com/claude-code) marketplace for the plugins of [Intelligenza Umana](https://github.com/Intelligenza-Umana/intelligenza-umana). It only lists them: each plugin lives, is versioned and is tested in its own repository.

## Add the marketplace

```sh
claude plugin marketplace add Intelligenza-Umana/iu-marketplace
```

## Plugins

The [marketplace manifest](.claude-plugin/marketplace.json) is the authoritative plugin catalog, so this README does not duplicate its entries. Browse the marketplace in Claude Code after adding it, then use:

```sh
claude plugin install <plugin-name>@intelligenza-umana
```

For the full organization project catalog, [browse GitHub repositories](https://github.com/Intelligenza-Umana?tab=repositories).

Installing a plugin downloads it from its own repository at the default branch. Read a plugin's README and code before using it.

## Maintenance

Run `claude plugin validate . --strict` after editing `.claude-plugin/marketplace.json`; the same check runs in CI on every push and pull request. The marketplace has no version of its own; a plugin's version is the one in its own `plugin.json`.

Distributed under the [MIT license](LICENSE).

## Intelligenza Umana community

**Human intelligence. Artificial assistance.**

[Organization](https://github.com/Intelligenza-Umana) · [Website](https://intelligenza-umana-web.vercel.app/) · [Discord](https://discord.gg/Zt85ZYEXAA) · [Onboarding](https://github.com/Intelligenza-Umana/intelligenza-umana/blob/main/community/ONBOARDING.md) · [Good first issues](https://github.com/search?q=org%3AIntelligenza-Umana+is%3Apublic+is%3Aissue+is%3Aopen+no%3Aassignee+label%3A%22good+first+issue%22&type=issues)

Contributions to public projects are welcome from everyone, regardless of experience. Organization membership and Discord are optional. Discuss scope in an issue before starting work, then submit a focused pull request with verification evidence and limitations. Use English for shared GitHub discussions.

To become an organization member, [submit a membership request](https://github.com/Intelligenza-Umana/intelligenza-umana/issues/new?template=membership_request.md). The Discord numeric user ID is optional; the issue is public, so you may provide it privately instead. A maintainer reviews requests manually and sends an official GitHub invitation if approved. Sentinel is configured to assign the Contributor role on Discord entry; the Member role is assigned manually only after identity and accepted GitHub membership are verified. Neither membership nor a Discord role automatically grants repository write access.

Follow the [code of conduct](https://github.com/Intelligenza-Umana/intelligenza-umana/blob/main/community/CODE_OF_CONDUCT.md) and [private security reporting policy](https://github.com/Intelligenza-Umana/intelligenza-umana/blob/main/SECURITY.md). Each project retains its own license, maturity and verification requirements.
