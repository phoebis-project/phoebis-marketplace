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
| `phoebis-keepalive` | [daystrom-labs/phoebis-keepalive](https://github.com/daystrom-labs/phoebis-keepalive) | Reports session liveness and agent state to the router's keepalive engine |

Install one with `/plugin install phoebis-keepalive@phoebis`.
