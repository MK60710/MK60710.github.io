# MK60710.github.io

Personal blog. Plain HTML/CSS, no build step, no theme, no framework — served directly by GitHub Pages.

## Adding a post

1. Copy `posts/_template.html` to `posts/your-slug.html` and fill it in.
2. Add a `<li>` to the post list in `index.html` (newest first), replacing the "coming soon" placeholder if it's still there.
3. Commit and push. Pages redeploys automatically.

## Domain

Once `mihirkolakaluri.com` is bought, add a `CNAME` file at the repo root containing just the domain, and point the domain's DNS at GitHub Pages (see GitHub's custom domain docs). Until then this serves at `mk60710.github.io`.
