# dotelove.com

Static host for **Dote**'s deep-link verification files (served via Cloudflare Pages).

- `/.well-known/apple-app-site-association` — iOS Universal Links (`AM8P283P5J.com.o9tech.dote`)
- `/.well-known/assetlinks.json` — Android App Links (`com.o9tech.dote`)
- `_headers` — sets `Content-Type: application/json`

These files are public by design. No secrets here (Apple Team IDs and cert
fingerprints are public identifiers).
