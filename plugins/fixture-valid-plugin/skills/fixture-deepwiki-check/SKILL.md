---
name: fixture-deepwiki-check
description: Checks the fixture-deepwiki MCP connection by asking DeepWiki about a public GitHub repo. Use when asked to run the fixture DeepWiki check or test the DeepWiki MCP.
---

# Fixture DeepWiki Check

1. Call `read_wiki_structure` on the `fixture-deepwiki` MCP server with repo `modelcontextprotocol/modelcontextprotocol`.
2. Reply with the first three topic titles and this refId so the skill version is visible:

refId: FXM-WIKI-3N8D-V1

If the MCP server is unavailable, say so and still return the refId.
