# Fynn's site

A small static homepage built with plain HTML and CSS. It has no build step, JavaScript dependency, or framework.

## Local preview

From the repository root, run:

```powershell
py -m http.server 8000 --directory site
```

Open <http://localhost:8000> in a browser.

## GitHub Pages

1. Push the repository to GitHub.
2. Open `Settings > Pages` and set `Source` to `GitHub Actions`.
3. Push changes to `main` or `master`:

```powershell
git add -A
git commit -m "Build static personal site"
git push
```

The workflow publishes the `site/` directory automatically. For a project repository, the address is:

`https://<username>.github.io/<repository>/`

All local links and assets are relative, so the same files also work for a user Pages repository named `<username>.github.io`.

The old custom-domain file is not included. When a domain is active again, add a `CNAME` file containing the domain to `site/` before deploying.