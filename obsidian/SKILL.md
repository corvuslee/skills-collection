---
name: obsidian
description: CLI interface to manage knowledge curation and retrieval in Obsidian or knowledge base (KB). Use when user asks to create/update/retrieve knowledge.
---
# Knowledge Management using Obsidian as Knowledge Base (KB)

## Instructions
1. Identify if the use is to create/update or retrieval knowledge.
2. The CLI is already installed. Always use `obsidian` CLI to interact with the KB.

## CLI References

### Read

```sh
# Search your vault
obsidian search query="meeting notes"

# List all folders
obsidian folders

# Read the active file
obsidian read

# These are equivalent if "Recipe.md" is the only file with that name
obsidian read file=Recipe
obsidian read path="Templates/Recipe.md"
```

### Write

```sh
# Create a new note called "Note" with content
obsidian create path="New Folder/New Note.md" content="# Title\n\nBody text"

# Overwrite notes
obsidian create path="New Folder/New Note.md" content="# Title\n\nBody text" overwrite

# Update notes
> Use your built-in tools instead of Obsidian CLI
```

### Help

```sh
# Run the help command
obsidian help
```
