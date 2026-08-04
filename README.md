# Replayfy Docs

Public documentation for Replayfy, published at **docs.replayfy.app** with [Mintlify](https://mintlify.com).

## Local preview

```sh
npm i -g mint      # Mintlify CLI
mint dev           # serves the docs at http://localhost:3000
```

## Deploy

Deployment is automatic: the Mintlify GitHub App builds and publishes on every
push to `main`, and opens a preview for each pull request. Connect this repo once
at dashboard.mintlify.com → Settings → GitHub App, then set the custom domain to
`docs.replayfy.app`.

## Editing

Pages are MDX under `platforms/` and `guides/`; site config + navigation live in
`docs.json`. SDK reference content mirrors each SDK's README — keep them in sync.
