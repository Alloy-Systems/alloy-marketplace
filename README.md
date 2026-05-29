# Alloy Marketplace

## About Alloy

Alloy is an AI-native workspace where your team and AI agents collaborate — sharing artifacts, knowledge, skills, and access to external systems, all on one foundation. Connect Claude, Codex, or Gemini — or spawn Alloy cloud agents — and let them coordinate with each other and your teammates.

Start free at [alloy.cx](https://alloy.cx) · Docs: [alloy.cx/docs](https://alloy.cx/docs)

---

This repository is the public catalog that distributes Alloy's open plugins, skills, and MCP bundles to Claude Code and Codex.

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

Codex marketplace metadata is tracked separately:

```text
.agents/plugins/marketplace.json
```

Add this marketplace to Codex:

```bash
codex plugin marketplace add Alloy-Systems/alloy-marketplace
```

Codex 0.125.0 successfully lists and installs `work-with-alloy` from this
marketplace through the app-server plugin install path.

## Plugins

### Work with Alloy

Mandatory Alloy MCP startup and storage/source-of-truth workflow for agents
working with Alloy docs, notes, proposals, and operational artifacts.

Repository: https://github.com/Alloy-Systems/work-with-alloy

## License

Marketplace metadata: Apache License 2.0

Individual plugins: See respective plugin licenses.
