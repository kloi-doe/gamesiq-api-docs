# gamesIq API Docs (Mintlify-style)

This repo is now structured for Mintlify.

## Local preview

```bash
npm i -g mintlify
mintlify dev
```

## Publish on Mintlify

1. Go to https://dashboard.mintlify.com/
2. Connect GitHub repo: `kloi-doe/gamesiq-api-docs`
3. Select this repo and root directory
4. Mintlify will read `docs.json` and publish your docs portal

## Files

- `docs.json` — Mintlify config + navigation
- `*.mdx` — docs pages
- `api/*.mdx` — endpoint categories
- `gamesiq-postman-collection.json` — importable collection
