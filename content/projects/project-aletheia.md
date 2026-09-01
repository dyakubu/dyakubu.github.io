---
title: "Project Aletheia"
date: 2026-08-31
weight: 2
summary: "Real-time fact-checking via a Chrome extension backed by a Go + Python microservices stack."
link: "https://github.com/dyakubu/project-aletheia"
---

Most viral misinformation isn't new; it's a claim someone already fact-checked, repackaged. Aletheia is a real-time fact-checking system: highlight any text on a webpage via a Chrome extension and instantly retrieve matching, already-verified claims from a database of fact-checks (e.g. PolitiFact). Under the hood it's a small microservices stack: a Go API gateway, a Python retrieval service doing vector similarity search over OpenAI embeddings (FAISS/Pinecone), and an ingestion pipeline that keeps the claim database current.
