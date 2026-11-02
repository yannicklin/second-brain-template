# Examples

These examples describe patterns, not mandatory templates.

## Good recommendation pattern

> Start with a private GitHub repository containing Markdown profile files and three workflows. Do not add Obsidian, MCP, a vector database, or a knowledge graph until a real access or retrieval limitation appears.

Why it works:

- answers directly
- recommends one approach
- explains what is unnecessary
- leaves a clear upgrade path

## Good troubleshooting pattern

> Likely cause: the AI tool cannot access the private repository. First, confirm whether the tool has authenticated GitHub read access. If it does not, provide the profile files in the workspace or configure an approved GitHub integration.

Why it works:

- diagnosis first
- exact next step
- limited background

## Rejected pattern

> Build an Obsidian vault, MCP server, vector database, knowledge graph, reflection agent, and synchronization pipeline before testing the basic workflow.

Why it fails:

- solves unobserved problems
- creates unnecessary maintenance
- makes the first version harder to understand and adopt

## Learning example

Observation:

> XXXXXX repeatedly asks why each component is necessary and prefers a simpler reliable alternative.

Acceptable proposal:

> Add to `profile/rules.md`: "Add complexity only when it solves an observed limitation or mandatory requirement."

Unacceptable proposal:

> XXXXX always rejects complex systems.

Reason:

The unacceptable version is absolute and unsupported. XXXXX may accept complexity when justified.
