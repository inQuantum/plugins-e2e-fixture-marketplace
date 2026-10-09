# plugins-e2e-fixture-marketplace

Throwaway marketplace fixture for testing git marketplace import and pull.

| Plugin | Purpose |
|---|---|
| `fixture-valid-plugin` | Loads cleanly. Skills return refIds (`FXM-REF-7K2Q-V1`, `FXM-REF2-5P9W-V1`, `FXM-WIKI-3N8D-V1`). MCP: `fixture-stripe` (HTTP, needs `STRIPE_SECRET_KEY`), `fixture-deepwiki` (HTTP, no auth). |
| `fixture-invalid-plugin` | Valid JSON, invalid data: `mcp.json` declares schema `2.0.0` while `plugin.json` declares `1.0.0`; one server has no `url`, one has a non-string `type` and a non-URL `url`; the skill has no frontmatter. |
