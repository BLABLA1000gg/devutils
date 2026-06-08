# devutils

Developer utilities that run entirely in the browser — no server, no tracking, no dependencies.

**Live:** [blabla1000gg.github.io/devutils](https://blabla1000gg.github.io/devutils/)

## Tools

| Category | Tools |
|---|---|
| **Encode / Decode** | Base64, URL encode, HTML entities |
| **Format** | JSON formatter & validator, YAML → JSON, JSON → YAML |
| **Hash** | SHA-1, SHA-256, SHA-512 (WebCrypto API) |
| **Text** | Case converter (camelCase, snake_case, kebab, ...), Text diff, Lorem ipsum |
| **Other** | UUID v4 generator, Regex tester with highlighting, Unix timestamp converter, JWT decoder |

## Why

Most online dev tools send your data to a server. This runs everything client-side using standard browser APIs (WebCrypto, TextEncoder, etc.) — nothing leaves your machine.

## Stack

- Pure HTML + Vanilla JS
- Tailwind CSS (CDN)
- js-yaml (CDN, for YAML parsing only)
- Hosted on GitHub Pages

## Run locally

```bash
# No build step needed — just open the file
open index.html
```
