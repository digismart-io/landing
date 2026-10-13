# Digismart landing pages

Static landing pages served by GitHub Pages.

## Add a new page
1. Create a folder with an unguessable name, e.g. `acme-ai-workshop-9f3k/`
2. Put an `index.html` inside it (self-contained HTML/CSS; images in the same folder).
3. Commit & push:
   git add . && git commit -m "add acme page" && git push
4. Live ~1 min later at:  https://digismart-io.github.io/landing/acme-ai-workshop-9f3k/

Notes:
- Every page keeps `<meta name="robots" content="noindex,nofollow">` so it stays out of Google.
- robots.txt disallows all crawlers.
- NEVER put secrets, API keys, or client data here — this repo is PUBLIC.
