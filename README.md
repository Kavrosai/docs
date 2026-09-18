# Kavros Docs

Public customer documentation for Kavros, served at `docs.kavros.ai`.

Static site (plain HTML + Tailwind via CDN), deployable with GitHub Pages.

## Publishing

1. Create a public GitHub repo from this directory (e.g. `Kavrosai/docs`).
2. In repo **Settings → Pages**, set **Source** to `main` branch, `/ (root)`.
3. Add a DNS `CNAME` record for `docs.kavros.ai` → `<org>.github.io`.
4. Push. The `CNAME` file already points at `docs.kavros.ai`.

## Pages

- `index.html` — getting started: the minimum changes to go live.
- `deployment.html` — deploying the stack in the customer's VPC + operations.
- `agent.html` — agent integration (native HTTP, `@kavrosai/cli`, and the optional Python zero-code hook).
