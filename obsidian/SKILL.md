---
name: obsidian
description: CLI interface to manage knowledge curation and retrieval in Obsidian or knowledge base (KB). Use when user asks to create/update/retrieve knowledge.
allowed-tools:
  - bash
---
# Knowledge Management using Obsidian as Knowledge Base (KB)

## Instructions
1. Identify if the use is to create/update or retrieval knowledge.
2. The CLI is already installed. Run the command in a shell.

## CLI References

### Read

```sh
# Search your vault
obsidian search query="meeting notes"

# Read the active file
obsidian read

# These are equivalent if "Recipe.md" is the only file with that name
obsidian read file=Recipe
obsidian read path="Templates/Recipe.md"

# Open today's daily note
obsidian daily

# List all tasks from your daily note
obsidian tasks daily

# List all tags in your vault with counts
obsidian tags counts

# Compare two versions of a file
obsidian diff file=README from=1 to=3

```

### Write

```sh
# Create a new note called "Note" with content
obsidian create name=Note content="# Title\n\nBody text"

# Add a task to your daily note
obsidian daily:append content="- [ ] Buy groceries"

```

### Help

```sh
# Run the help command
obsidian help
```
