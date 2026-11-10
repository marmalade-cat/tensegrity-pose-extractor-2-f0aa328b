Tensegrity Pose Extractor — prototype

A tiny prototype that fetches a page, finds linked CSV/JSON files, downloads them, and otherwise scrapes HTML tables. Produces a small standardized JSON with provenance and simple confidence scores.

Usage: open index.html in a modern browser. This is a client-only demo; CORS may block some fetches when testing with remote sites. Designed as a starting point for a more robust extractor.

Limitations: no crawling, limited schema inference, basic confidence heuristics. See in-file comments.