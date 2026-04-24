---
name: quack
description: CLI interface to search the web using DuckDuckGo and fetch webpages. Use when user asks to search the web or get info from a URL.
allowed-tools:
  - bash
---
# Quack Search

## Instructions
1. Identify if the use is to perform a websearch or fetch a specific URL
2. The CLI is already installed, so if it's a web search, run `quack search <query> --json`
3. Otherwise if it's fetching a webpage, run `quack fetch <url>`
4. To learn how to use the tool, run `quack --help`
