# Sentra Plugin Registry

Central plugin catalog for Sentra.

This repository is consumed by Sentra's plugin browser at:

```text
https://github.com/aidenmi8/sentra-ai.git
```

## Catalog Shape

Plugin specs live under `plugins/*.json` and must decode as Sentra plugin-spec-compatible JSON.

Compatibility note: plugin IDs remain `osaurus.*` for this release so installed plugins and stored references continue to work. Visible names, authors, descriptions, and catalog homepage metadata are Sentra-branded.

The current catalog points at existing signed upstream release artifacts so installs have real downloadable ZIPs with matching checksums and minisign signatures. New Sentra-owned source forks and release artifacts can replace those URLs in a later catalog update after the artifacts are built, checksummed, and signed.

## Included Plugins

- Sentra Apple Music
- Sentra Apple Notes
- Sentra Browser
- Sentra Calendar
- Sentra Contacts
- Sentra Emacs
- Sentra Fetch
- Sentra Images
- Sentra Mail
- Sentra Maps
- Sentra Messages
- Sentra PPTX
- Sentra Reminders
- Sentra Resend
- Sentra Search
- Sentra Telegram
- Sentra Time
- Sentra Vision
- Sentra XLSX
- Sentra macOS Use
