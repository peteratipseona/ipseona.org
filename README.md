# IPSEONA website — v0.2.1

Static website for https://ipseona.org.

## Local preview

Run from this directory:

```bash
python3 -m http.server 8080 --bind 127.0.0.1
```

Open http://127.0.0.1:8080.

## Specification

- `/spec.html` points to the current specification, `/spec-v0.2.1.html`.
- No build step is required.

## Publishing

The website repository is `peteratipseona/ipseona.org`, branch `main`.
Pushing `main` triggers Cloudflare automatic deployment.
Canonical domain: `ipseona.org`. Verify the public response after publishing.
