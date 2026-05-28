# Alloy Marketplace

Distribution index for Alloy plugins, skills, and MCP bundles.

This repository is intentionally a marketplace/catalog repository, not the
plugin implementation itself. Plugin source lives in the referenced plugin
repositories.

## Claude Code

Add this marketplace to Claude Code:

```bash
/plugin marketplace add Alloy-Systems/alloy-marketplace
```

Install Work with Alloy:

```bash
/plugin install work-with-alloy@alloy-marketplace
```

Claude marketplace metadata lives in:

```text
.claude-plugin/marketplace.json
```

## Codex

Codex marketplace metadata is tracked separately while Codex public marketplace
installation conventions are confirmed.

```text
.agents/plugins/marketplace.json
```

## Plugins

### Work with Alloy

Mandatory Alloy MCP startup and storage/source-of-truth workflow for agents
working with Alloy docs, notes, proposals, and operational artifacts.

Repository: https://github.com/Alloy-Systems/work-with-alloy

## License

Marketplace metadata: Apache License 2.0

Individual plugins: See respective plugin licenses.
