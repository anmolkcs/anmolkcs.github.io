# Hosting your own books

To read a novel on any device, put it in the `reader/books/` folder of this repo and list it in `books.json`:

```json
[
  { "title": "My Novel", "files": ["my-novel/001.md", "my-novel/002.md"] },
  { "title": "One-file Novel", "file": "one-file-novel.md" }
]
```

A single file is split into chapters at its headings automatically.
