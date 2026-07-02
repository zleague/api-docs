# MEGA Developer Docs

Source for the public developer documentation at **developers.gomega.ai** — the MEGA public CRM Lead API (pull leads, push leads, and lead webhooks).

- Built with [Mintlify](https://mintlify.com); config in `docs.json`, API reference generated from `openapi.json`.
- Guide pages are the `*.mdx` files; `index.mdx` is the API overview / landing page.

## Local preview

```bash
npm i -g mint
mint dev
```

Pushes to `main` auto-deploy via the Mintlify GitHub app.
