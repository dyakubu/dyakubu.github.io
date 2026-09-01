---
title: "Scout"
date: 2026-08-31
weight: 1
summary: "Local semantic search CLI for text, PDF, and (soon) media files, deployed via Homebrew."
link: "https://github.com/dyakubu/scout"
---

Grep finds text; it doesn't understand what you meant. Scout is a local semantic search CLI written in Go that indexes your files with on-device embeddings and lets you search by meaning instead of exact keywords. No cloud calls, no API keys, nothing leaves your machine. It works on any text-based files, including PDFs. Image and video support is currently in the works, and contributions are welcome! Everything is stored in a local SQLite index, and it ships as a Homebrew formula for a one-command install.

```
brew install dyakubu/scout/scout
```
