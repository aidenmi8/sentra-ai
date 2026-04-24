# Sentra Plugin Registry

Central plugin catalog for Sentra.

This repository is consumed by Sentra's plugin browser at:

```text
https://github.com/aidenmi8/sentra-ai.git
```

## Catalog Shape

Plugin specs live under `plugins/*.json` and must decode as Sentra/Osaurus `PluginSpec` JSON.

Compatibility note: plugin IDs remain `osaurus.*` for this release so installed plugins and stored references continue to work. Visible names, authors, descriptions, and catalog homepage metadata are Sentra-branded.

The initial catalog points at existing signed release artifacts from the upstream plugin repositories. New Sentra-owned source forks and release artifacts can replace those URLs in a later catalog update after the artifacts are built, checksummed, and signed.
