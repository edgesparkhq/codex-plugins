# EdgeSpark Codex Plugins

Official Codex plugin marketplace by EdgeSpark.

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [edgespark](./plugins/edgespark) | Build full-stack apps on EdgeSpark with the current CLI, generated types, and docs MCP access |

## Installation

The supported end-user install flow uses the latest GitHub release asset:

- [`edgespark-codex-plugins.zip`](https://github.com/edgesparkhq/edgespark-codex-plugins/releases/latest/download/edgespark-codex-plugins.zip)

Open `codex`, then paste this:

```text
$plugin-creator Install or update the EdgeSpark Codex plugin
from this exact release zip:
https://github.com/edgesparkhq/edgespark-codex-plugins/releases/latest/download/edgespark-codex-plugins.zip
Extract that zip and use its repository contents directly.
Copy plugins/edgespark/ into ~/.codex/plugins/edgespark/.
If ~/.agents/plugins/marketplace.json does not exist, copy .agents/plugins/marketplace.json into ~/.agents/plugins/marketplace.json.
If ~/.agents/plugins/marketplace.json already exists, merge only the EdgeSpark marketplace entry from the zip without removing unrelated existing entries.
Do not invent a different install layout.
Tell me when the local plugin files are updated.
```

Then inside Codex:

1. Run `/plugins`
2. Install `EdgeSpark`

## Repository Layout

- [`plugins/edgespark`](./plugins/edgespark): Standalone Codex plugin bundle
- [`.agents/plugins/marketplace.json`](./.agents/plugins/marketplace.json): Marketplace metadata for Codex plugin discovery

The repository marketplace file uses the repo-local path `./plugins/edgespark`. The release zip repackages that marketplace entry for home-local installation under `~/.codex/plugins/edgespark`.

## License

MIT. See [LICENSE](./LICENSE).
