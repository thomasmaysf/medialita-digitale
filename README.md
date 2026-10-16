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

## Deployment (current): GitHub Pages

Pushes to `main` run [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml):

1. `mkdocs build --strict`
2. Publish `site/` with `actions/configure-pages`, `actions/upload-pages-artifact`, and `actions/deploy-pages`

**One-time setup**

1. **Settings → Pages → Build and deployment → Source:** choose **GitHub Actions** (not “Deploy from a branch”).
2. On GitHub’s **free plan**, the repository must be **public** for GitHub Pages on `github.io` (private repos need a paid plan for Pages).

After deploy, the site is at:

**https://thomasmaysf.github.io/medialita-digitale/**

(`site_url` in `mkdocs.yml` is set to match.)

Pull requests run the same build (strict) without deploying.

## Future migration: Cloudflare Workers

[`wrangler.toml`](wrangler.toml) is kept for a possible move to Cloudflare static assets (`name = "medialita-digitale"`, `[assets] directory = "./site"`). This is **not** deployed automatically.

When you are ready:

1. Add Actions secrets `CLOUDFLARE_API_TOKEN` and `CLOUDFLARE_ACCOUNT_ID`.
2. Run the manual workflow [`.github/workflows/deploy-cloudflare.yml`](.github/workflows/deploy-cloudflare.yml) from the Actions tab, or deploy locally:

```bash
pip install -r requirements.txt
mkdocs build --strict
npx wrangler deploy
```

Update `site_url` in `mkdocs.yml` to the Worker URL (or custom domain), switch off GitHub Pages if you no longer want two hosts, and prefer a single primary deployment.
