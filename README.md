# medialita-digitale

MkDocs Material wiki for **Educazione alla Medialità Digitale** / **Patentino digitale** — parents’ program at the Rudolf Steiner school in Trento (Italy). Site content is in Italian under `docs/`.

## Local preview

```bash
pip install -r requirements.txt
mkdocs serve
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000). Use `mkdocs build --strict` to verify the site before pushing (same check as CI).

## Adding or editing pages

1. Add or edit Markdown files under `docs/`.
2. Register new pages in the `nav:` section of `mkdocs.yml`.
3. Run `mkdocs build --strict` locally.

Module pages live in `docs/moduli/` (`modulo-1.md` … `modulo-5.md`).

## Deployment (primary): Cloudflare Workers

Pushes to `main` run [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml):

1. `mkdocs build --strict`
2. Deploy the `site/` directory with [Wrangler](https://developers.cloudflare.com/workers/wrangler/) via `cloudflare/wrangler-action`

Configuration: [`wrangler.toml`](wrangler.toml) (`name = "medialita-digitale"`, `[assets] directory = "./site"`).

### Repository secrets (one-time)

In **GitHub → Settings → Secrets and variables → Actions**, add:

| Secret | Purpose |
|--------|---------|
| `CLOUDFLARE_API_TOKEN` | API token with permission to deploy Workers (e.g. “Edit Cloudflare Workers”) |
| `CLOUDFLARE_ACCOUNT_ID` | Your Cloudflare account ID |

After a successful deploy, the site is available at the Worker’s **workers.dev** URL (for example `https://medialita-digitale.<subdomain>.workers.dev`). You can attach a **custom domain** later in the Cloudflare dashboard for that Worker.

### Manual deploy

```bash
pip install -r requirements.txt
mkdocs build --strict
npx wrangler deploy
```

Requires Wrangler authentication (`wrangler login` or `CLOUDFLARE_API_TOKEN` in the environment).

## Alternative: GitHub Pages (not enabled)

This repository does **not** ship an active GitHub Pages workflow. If you prefer Pages instead of Workers, you can add a workflow that uploads `site/` with `actions/upload-pages-artifact` and `actions/deploy-pages`, and set **Settings → Pages → Source** to **GitHub Actions**. Only one primary host is recommended to avoid duplicate deployments.
