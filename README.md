# GhostSpellWebSite

Landing page for www.ghostspell.com.

## Local preview

From this repo directory:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://127.0.0.1:8080/
```

## Cloudflare Pages

This repo is connected to the Cloudflare Pages project:

- Project name: `ghostspell`
- Preview URL: `https://ghostspell.pages.dev`

Manual deploy from this repo:

```bash
wrangler pages deploy . --project-name ghostspell --branch main --commit-dirty=true
```
