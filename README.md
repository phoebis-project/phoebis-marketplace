# Phoebis marketplace

The Claude Code plugin catalog of the Phoebis Router. Each plugin lives in its own repository, and this catalog tells
Claude Code where to fetch it from.

## Add the marketplace

Inside Claude Code:

```text
/plugin marketplace add daystrom-labs/phoebis-marketplace
```

From a shell, `claude plugin marketplace add daystrom-labs/phoebis-marketplace`. The catalog's name is `phoebis`, so an
install line reads `<plugin>@phoebis`.

## Plugins

| Plugin | Repository | What it does |
| --- | --- | --- |
| `phoebis-companion` | [daystrom-labs/phoebis-companion](https://github.com/daystrom-labs/phoebis-companion) | Reports session liveness to the router and gives the model the pool's allowance |

Install one with `/plugin install phoebis-companion@phoebis`.
